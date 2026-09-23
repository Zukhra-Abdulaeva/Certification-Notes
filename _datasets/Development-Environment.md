# Development Environment

## 1. Purpose

This document describes the development environment used for the project.

The project is developed on a Windows host with a Linux-based development environment. Ubuntu or Debian may be used as the Linux distribution, depending on the project setup.

The environment is intended for software development, testing and cybersecurity-related work.

This document covers:

* system requirements
* repository setup
* runtime requirements
* project dependencies
* environment configuration
* development and security tools
* verification
* security requirements
* known limitations
* reproducibility

The development environment follows this structure:

```text
Windows Host
     ↓
Linux Environment
     ↓
Ubuntu / Debian
     ↓
Development & Cybersecurity Tooling
     ↓
Project
```

---

## 2. Requirements

The development environment consists of a Windows host and a Linux-based development environment.

| Component          | Requirement         |
| ------------------ | ------------------- |
| Host OS            | Windows             |
| Development OS     | Linux               |
| Linux distribution | Ubuntu or Debian    |
| Architecture       | `<ARCHITECTURE>`    |
| Runtime            | `<RUNTIME>`         |
| Runtime version    | `<VERSION>`         |
| Package manager    | `<PACKAGE_MANAGER>` |
| Git                | `<VERSION>`         |
| Shell              | Bash                |
| Editor / IDE       | `<EDITOR>`          |
| Additional tools   | `<TOOLS>`           |

The Linux environment may run through WSL, a virtual machine or another supported Linux environment.

The project should be developed and tested inside the Linux environment when Linux-specific tools or behavior are required.

### Linux distribution

Check the installed distribution with:

```bash
cat /etc/os-release
```

Check the kernel and architecture with:

```bash
uname -a
uname -m
```

---

## 3. Repository

The repository is used from within the Linux development environment.

The repository root is represented by:

```text
<REPOSITORY_ROOT>
```

A typical project structure may look like:

```text
<REPOSITORY_ROOT>/

├── README.md
├── .gitignore
├── src/
├── tests/
├── docs/
└── scripts/
```

The actual project structure takes precedence over this example.

### Repository location

For a Linux-native environment, a typical location is:

```text
/home/<USER>/<PROJECT>
```

For WSL, the repository may be stored inside the Linux filesystem:

```text
/home/<USER>/<PROJECT>
```

Windows-mounted locations are also possible:

```text
/mnt/c/<PROJECT>
```

For development workloads with frequent file operations, the project should use the repository location recommended by the project's environment setup.

### Git verification

Run:

```bash
git status
git remote -v
git branch --show-current
```

These commands verify the repository state, configured remote and active branch.

---

## 4. Runtime

The project runtime is provided by the Linux development environment.

Record the required runtime and version:

| Runtime     | Required version | Verification |
| ----------- | ---------------- | ------------ |
| `<RUNTIME>` | `<VERSION>`      | `<COMMAND>`  |

For Python projects:

```bash
python3 --version
```

For Node.js projects:

```bash
node --version
```

The required runtime version should match the project configuration.

The installed version can be verified independently with the corresponding runtime command.

### Python

When Python is used, verify the interpreter with:

```bash
python3 --version
which python3
```

The interpreter should resolve to the intended Linux environment.

---

## 5. Dependencies

Project dependencies are managed inside the Linux development environment.

For Python projects, dependencies may be defined through:

```text
requirements.txt
pyproject.toml
poetry.lock
Pipfile
Pipfile.lock
```

Use the dependency mechanism defined by the project.

For example:

```bash
python3 -m pip install -r requirements.txt
```

### Python virtual environment

A local virtual environment isolates project dependencies from the system Python installation.

Create it with:

```bash
python3 -m venv .venv
```

Activate it with:

```bash
source .venv/bin/activate
```

Verify the active interpreter:

```bash
which python
python --version
```

The interpreter should point to the project's `.venv` environment.

---

## 6. Environment Setup

Set up the environment in the following order:

1. Prepare the Windows host.
2. Start the Linux development environment.
3. Verify the Linux distribution.
4. Obtain the repository.
5. Enter the repository root.
6. Install the required runtime.
7. Create the project environment.
8. Install project dependencies.
9. Configure required environment variables.
10. Install the required development and security tools.
11. Run the verification commands.
12. Run the project's tests or validation procedure.

### Linux environment verification

Start with:

```bash
cat /etc/os-release
uname -a
pwd
```

Verify Git:

```bash
git --version
```

Verify the project runtime:

```bash
< RUNTIME_COMMAND >
```

Replace the placeholder with the actual runtime command.

### Example Python setup

```bash
git clone <REPOSITORY_URL>
cd <REPOSITORY_DIRECTORY>

python3 -m venv .venv
source .venv/bin/activate

python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Use the project's actual dependency configuration when it differs from this example.

---

## 7. Configuration

Environment-specific configuration is provided through local configuration files or environment variables.

Typical configuration includes:

* API endpoints
* API keys
* local service settings
* database connections
* tool configuration
* development paths

Document variable names and their purpose:

| Variable          | Purpose     | Required   | Secret     |
| ----------------- | ----------- | ---------- | ---------- |
| `<VARIABLE_NAME>` | `<PURPOSE>` | `<YES/NO>` | `<YES/NO>` |

Secret values remain in the local environment.

Example:

```text
API_KEY=<LOCAL_SECRET>
TARGET_HOST=<LOCAL_TARGET>
DATABASE_URL=<LOCAL_DATABASE>
```

### Local configuration

Machine-specific settings may include:

```text
.env
.local/
local configuration files
developer-specific tool settings
temporary files
```

The project should define which local configuration files belong in `.gitignore`.

### `.gitignore`

A Python-based project may use:

```gitignore
.venv/
__pycache__/
*.py[cod]
.pytest_cache/
.env
```

Additional entries depend on the tools used by the project.

---

## 8. Development Tools

Development and cybersecurity tools are installed inside the Linux environment when they are required by the project.

| Tool              | Purpose                       | Version     |
| ----------------- | ----------------------------- | ----------- |
| Git               | Version control               | `<VERSION>` |
| Bash              | Shell environment             | `<VERSION>` |
| Python            | Development runtime           | `<VERSION>` |
| Package manager   | Dependency management         | `<VERSION>` |
| Editor / IDE      | Development                   | `<VERSION>` |
| Security tooling  | Security testing and analysis | `<VERSION>` |
| Container runtime | Containerized development     | `<VERSION>` |

Only project-relevant tools should be documented.

### Security tooling

Cybersecurity tools may be used for:

* network analysis
* vulnerability testing
* web security testing
* source-code analysis
* authentication testing
* system analysis
* traffic inspection
* security automation

The exact tools depend on the project.

Examples include:

```text
Nmap
Wireshark
Burp Suite
OWASP ZAP
Nuclei
Docker
Git
Python
```

Tools should be documented together with their purpose when they form part of the project workflow.

### Visual Studio Code

Visual Studio Code may run on Windows while working with the Linux development environment through WSL or another supported integration.

Open the repository through the configured Linux environment:

```bash
code .
```

The selected interpreter, terminal and project path should point to the Linux environment used by the project.

---

## 9. Verification

Verification confirms that the Linux environment matches the project requirements.

### System

```bash
cat /etc/os-release
uname -a
uname -m
```

### Repository

```bash
pwd
git status
git remote -v
git branch --show-current
```

### Runtime

For Python:

```bash
python --version
which python
```

For Node.js:

```bash
node --version
npm --version
```

### Dependencies

Verify the project's dependency environment using its configured package manager.

For Python:

```bash
python -m pip --version
python -m pip list
```

### Security tools

Verify required tools individually:

```bash
<TOOL> --version
```

Some security tools use different version commands. Use the command provided by the installed tool.

### Project validation

Run the project's tests or validation procedure:

```bash
<VALIDATION_COMMAND>
```

Record observed results when the environment state needs to be documented.

### Verification matrix

| Requirement     | Expected        | Observed     | Status     |
| --------------- | --------------- | ------------ | ---------- |
| Host OS         | Windows         | `<OBSERVED>` | `<STATUS>` |
| Development OS  | Linux           | `<OBSERVED>` | `<STATUS>` |
| Distribution    | Ubuntu / Debian | `<OBSERVED>` | `<STATUS>` |
| Architecture    | `<EXPECTED>`    | `<OBSERVED>` | `<STATUS>` |
| Runtime         | `<EXPECTED>`    | `<OBSERVED>` | `<STATUS>` |
| Runtime version | `<EXPECTED>`    | `<OBSERVED>` | `<STATUS>` |
| Dependencies    | `<EXPECTED>`    | `<OBSERVED>` | `<STATUS>` |
| Security tools  | `<EXPECTED>`    | `<OBSERVED>` | `<STATUS>` |

Useful status values are:

```text
Planned
Configured
Verified
Not applicable
Not yet verified
```

---

## 10. Security

The development environment is used for cybersecurity-related development and testing.

Security-sensitive information remains outside source code and documentation.

Protect:

* passwords
* API keys
* access tokens
* SSH keys
* private keys
* database credentials
* cloud credentials
* test-system credentials

Use dedicated development or test credentials where available.

### Repository security

Before committing changes, review:

```bash
git status
git diff
```

After staging:

```bash
git diff --cached
```

Check the staged content for:

* credentials
* tokens
* private keys
* sensitive configuration
* unintended files
* generated security reports containing sensitive information

### Security testing

Security tools should be used only against systems and environments that are authorized for testing.

Project-specific testing targets and authorization requirements should be documented separately when required.

---

## 11. Known Limitations

The Windows host and Linux development environment may introduce platform-specific differences.

Potential limitations include:

* differences between Windows and Linux filesystem behavior
* differences in file permissions
* differences in shell commands
* WSL-specific behavior
* network configuration differences
* hardware-dependent security tools
* virtualization limitations
* tools that require native Linux functionality

Document the practical impact of a limitation when it affects development, testing or reproducibility.

| Limitation     | Impact     |
| -------------- | ---------- |
| `<LIMITATION>` | `<IMPACT>` |
| `<LIMITATION>` | `<IMPACT>` |

---

## 12. Reproducibility

The development environment should be reproducible from the documented project requirements.

The environment consists of:

```text
Windows Host
     ↓
Linux Environment
     ↓
Ubuntu / Debian
     ↓
Runtime
     ↓
Project Environment
     ↓
Dependencies
     ↓
Configuration
     ↓
Development & Security Tools
     ↓
Verification
```

Keep the following information synchronized with the project:

* Linux distribution
* runtime version
* dependency definitions
* virtual environment configuration
* security tool requirements
* environment variables
* project setup commands
* validation commands

### Recreation procedure

1. Prepare the Windows host.
2. Start the supported Linux environment.
3. Verify Ubuntu or Debian.
4. Obtain the repository.
5. Install the required runtime.
6. Create the project environment.
7. Install the declared dependencies.
8. Configure required environment variables.
9. Install required development and security tools.
10. Run the verification commands.
11. Run the project's tests or validation procedure.

A recreated environment should provide the same required runtime, dependencies and project functionality as the documented development environment.

---

## Environment Maintenance

Update this document when changes affect the development environment, including:

* Windows host requirements
* Linux distribution
* runtime versions
* project dependencies
* security tools
* development tools
* configuration requirements
* repository structure
* verification procedures

Keep this document aligned with the actual project configuration.
id on another.

When the project uses path-sensitive tooling, document the expected path format and platform requirements.

---

## 17. 🐧 WSL Environment

This section applies only when Windows Subsystem for Linux is used.

WSL provides a Linux environment hosted within Windows.

Document:

| Property            | Value            |
| ------------------- | ---------------- |
| WSL version         | `<VERSION>`      |
| Distribution        | `<DISTRIBUTION>` |
| Linux version       | `<VERSION>`      |
| Repository location | `<PATH>`         |

The repository location should be documented according to the actual project setup.

Windows-mounted paths and Linux-native paths should not be treated as interchangeable without verification.

---

## 18. 📦 Containers and Virtual Machines

If the project uses containers or virtual machines, document them separately from the host operating system.

Example:

```text
Host
  ↓
Virtualization / Container Layer
  ↓
Development Environment
  ↓
Project
```

Document:

| Component                             | Value     |
| ------------------------------------- | --------- |
| Host OS                               | `<VALUE>` |
| Virtualization / Container technology | `<VALUE>` |
| Image / VM                            | `<VALUE>` |
| Runtime version                       | `<VALUE>` |

Only include this section when applicable.

---

## 19. 🔍 Environment Verification

Environment verification confirms that the configured environment corresponds to the documented requirements.

A generic verification sequence may include:

```bash
pwd
git status
git remote -v
```

For Python:

```bash
python --version
python -m pip --version
```

For Node.js:

```bash
node --version
npm --version
```

The exact commands depend on the project.

Record actual results only after execution.

A command documented in this file is not evidence that the command was executed.

---

## 20. 📊 Environment Verification Matrix

Separate requirements from observed values.

| Requirement       | Expected     | Observed     | Status     |
| ----------------- | ------------ | ------------ | ---------- |
| Operating system  | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |
| Architecture      | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |
| Repository        | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |
| Runtime           | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |
| Runtime version   | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |
| Dependencies      | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |
| Development tools | `<EXPECTED>` | `<OBSERVED>` | `<STATUS>` |

Recommended status values:

```text
Planned
Configured
Verified
Documented
Not applicable
Not yet verified
```

---

## 21. 🧭 Reproducibility

A reproducible environment should allow another developer to reconstruct the required setup.

Generic sequence:

```text
Repository
    ↓
Operating System
    ↓
Runtime
    ↓
Environment Isolation
    ↓
Dependencies
    ↓
Configuration
    ↓
Verification
```

The exact reconstruction procedure depends on the project.

Document the required steps in the order in which they must be performed.

---

## 22. 🚀 Environment Setup

Project-specific setup instructions should follow a logical sequence:

```text
1. Prepare the required operating-system environment.
2. Obtain the repository.
3. Enter the repository root.
4. Install or select the required runtime.
5. Create the project environment if required.
6. Install project dependencies.
7. Configure required non-secret environment variables.
8. Verify the runtime and dependencies.
9. Run the project's validation procedure.
```

Replace generic steps with project-specific commands when the actual project is known.

---

## 23. ♻️ Environment Recreation

When an environment needs to be recreated, use the project's documented setup procedure.

Generic sequence:

```text
Existing Environment
        ↓
Recreate project-local environment
        ↓
Install declared dependencies
        ↓
Apply required configuration
        ↓
Run verification
```

Avoid destructive system-level operations in generic environment documentation.

Environment recreation should remain within the scope necessary for the project.

---

## 24. 🔐 Security

The development environment should follow basic security principles:

* keep credentials outside source control
* use least-privilege access where appropriate
* avoid storing production credentials locally unless required
* keep development tools reasonably maintained
* review repository changes before committing
* avoid exposing private configuration
* separate development and production credentials
* document security-sensitive configuration without exposing secret values

Before committing changes:

```bash
git status
git diff
```

After staging:

```bash
git diff --cached
```

Secrets should not be stored in source files, documentation, or Git history.

---

## 25. 🧪 Evidence

Environment claims should be supported by evidence where verification matters.

Possible evidence includes:

```text
Command output
Configuration files
Version information
Git status
Dependency definitions
Environment variable names
Tool configuration
Test results
```

Evidence should be:

```text
Actual
Relevant
Traceable
Reproducible
```

Do not fabricate command output or replace observed values with example values.

Example values must remain clearly identifiable as examples.

---

## 26. 📋 Environment Status

Use factual status reporting:

| Area                   | Status     | Evidence     |
| ---------------------- | ---------- | ------------ |
| Operating system       | `<STATUS>` | `<EVIDENCE>` |
| Repository             | `<STATUS>` | `<EVIDENCE>` |
| Runtime                | `<STATUS>` | `<EVIDENCE>` |
| Dependencies           | `<STATUS>` | `<EVIDENCE>` |
| Development tools      | `<STATUS>` | `<EVIDENCE>` |
| Configuration          | `<STATUS>` | `<EVIDENCE>` |
| Security configuration | `<STATUS>` | `<EVIDENCE>` |
| Reproducibility        | `<STATUS>` | `<EVIDENCE>` |

The status must reflect the actual project state.

---

## 27. ⚠️ Known Limitations

Document environment-specific limitations when they affect development or reproducibility.

Examples include:

```text
Platform-specific commands
Platform-specific paths
Optional tools
Unverified platforms
Hardware-dependent functionality
Network-dependent setup
Development-only configuration
```

A limitation should describe its practical impact where relevant.

Do not use limitations to make unsupported assumptions about the environment.

---

## 28. 🔄 Change Management

Changes to the development environment should be reflected in the documentation when they affect reproducibility.

Typical sequence:

```text
Environment Change
        ↓
Configuration Update
        ↓
Documentation Update
        ↓
Verification
        ↓
Git Review
        ↓
Commit
```

Review changes with:

```bash
git status
git diff
```

After staging:

```bash
git diff --cached
```

Only commit changes that have been reviewed.

---

## 29. 📌 Reproducibility Checklist

Before considering the environment sufficiently documented:

```text
[ ] Operating system documented
[ ] Platform requirements documented
[ ] Repository location documented
[ ] Runtime documented
[ ] Runtime version documented
[ ] Environment isolation documented
[ ] Dependencies documented
[ ] Required tools documented
[ ] Environment variables documented without secret values
[ ] .gitignore reviewed
[ ] Security requirements documented
[ ] Verification procedure documented
[ ] Observed environment values recorded where required
[ ] Known limitations documented
[ ] Recreation procedure documented
```

---

## 30. 📈 Environment Documentation Status

Use this section to summarize the current documentation state.

| Category               | Status     |
| ---------------------- | ---------- |
| Environment definition | `<STATUS>` |
| Runtime definition     | `<STATUS>` |
| Dependency definition  | `<STATUS>` |
| Tool definition        | `<STATUS>` |
| Security documentation | `<STATUS>` |
| Verification           | `<STATUS>` |
| Reproducibility        | `<STATUS>` |

The status must reflect the actual project state.

---

## 31. 🛠️ Maintenance

Update this document when changes affect the development environment, including:

* runtime version changes
* dependency changes
* supported-platform changes
* development-tool changes
* repository layout changes
* environment-management changes
* new configuration requirements
* changes to the verification procedure

Do not update the document for changes that have no effect on the documented environment.

---

## 32. 🧠 Environment Reproducibility Model

The complete environment can be represented as:

```text
Project Requirements
        ↓
Host Platform
        ↓
Operating System
        ↓
Runtime
        ↓
Environment Isolation
        ↓
Dependencies
        ↓
Configuration
        ↓
Development Tools
        ↓
Verification
        ↓
Reproducible Development Environment
```

The purpose of this model is to make each relevant layer identifiable and reproducible.

---

## 33. 🏁 Completion Criteria

The environment documentation is complete when:

* required platforms are identified
* required runtimes are documented
* required versions are documented
* repository location is defined
* dependencies are defined
* environment isolation is documented where applicable
* required tools are identified
* configuration requirements are documented
* sensitive information is protected
* verification procedures are available
* observed results are recorded where required
* known limitations are documented
* environment recreation is understandable

Completion should be based on **evidence**, not assumptions.

---

## 34. 📎 Adaptation Rule

This document is a **template**, not a fixed project specification.

Before using it for another repository:

```text
1. Inspect the existing repository.
2. Identify the actual environment requirements.
3. Replace placeholders.
4. Remove irrelevant sections.
5. Add project-specific requirements.
6. Execute the verification procedures.
7. Record only observed results.
8. Update the documentation when the environment changes.
```

The final environment documentation should describe the **actual development environment**, not an idealized environment.

---

## 🧾 Final Principle

> **Keep the environment simple, reproducible, secure, and verifiable.**
>
> **Document requirements separately from observations.**
>
> **Use placeholders for user-specific information.**
>
> **Keep secrets outside documentation and source control.**
>
> **Record evidence for verified environment states.**
>
> **Update the documentation when environment changes affect reproducibility.**
