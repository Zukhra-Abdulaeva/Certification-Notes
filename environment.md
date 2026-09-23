# Development Environment

## Purpose

This document defines the reproducible development environment for the
`Certification-Notes` repository.

The repository is developed primarily in an Ubuntu environment running
through WSL2 on Windows.

The goal is to ensure that the Python environment can be recreated after
cloning the repository without committing the local virtual environment.

---

## Environment Architecture

```text
Windows
  │
  └── WSL2
       │
       └── Ubuntu
            │
            └── /home/zukhra/GitHub_Certification-Notes/Certification-Notes
                 │
                 ├── .venv/              # local only
                 ├── requirements.txt
                 ├── .python-version
                 └── project files
```

---

## Base Environment

| Component           | Requirement           |
| ------------------- | --------------------- |
| Operating system    | Ubuntu on WSL2        |
| Python              | 3.12.3                |
| Virtual environment | Python `venv`         |
| Editor              | Visual Studio Code    |
| Git                 | Git                   |
| Repository          | `Certification-Notes` |

The Python version is documented in `.python-version`.

---

## Repository Location

Linux/WSL working copy:

```text
/home/zukhra/GitHub_Certification-Notes/Certification-Notes
```

The repository should preferably be located inside the Linux filesystem
rather than under `/mnt/c/` for Linux-focused development work.

---

# Environment Setup After Clone

## 1. Clone the repository

```bash
git clone https://github.com/Zukhra-Abdulaeva/Certification-Notes.git
cd Certification-Notes
```

---

## 2. Verify Python

```bash
python3 --version
```

Expected version:

```text
Python 3.12.3
```

If the required Python version is not available, do not continue with the
project environment until the Python installation has been reviewed.

---

## 3. Create the virtual environment

```bash
python3 -m venv .venv
```

This creates a local Python virtual environment.

The `.venv/` directory must not be committed to Git.

---

## 4. Activate the virtual environment

```bash
source .venv/bin/activate
```

After activation, the shell should show:

```text
(.venv)
```

---

## 5. Verify the Python executable

```bash
which python
```

Expected pattern:

```text
.../Certification-Notes/.venv/bin/python
```

The exact username and absolute path may differ on another machine.

---

## 6. Verify Python version

```bash
python --version
```

Expected:

```text
Python 3.12.3
```

---

## 7. Upgrade pip

Only perform this when package installation is required:

```bash
python -m pip install --upgrade pip
```

---

## 8. Install project dependencies

Install the dependencies defined by the repository:

```bash
python -m pip install -r requirements.txt
```

At the current stage, `requirements.txt` intentionally contains no
third-party dependencies because the Linux system analysis primarily uses
standard Linux diagnostic tools and Python's standard library.

If project dependencies are added later, they must be documented in
`requirements.txt`.

---

# Environment Verification

After setup, run:

```bash
python --version
which python
python -m pip --version
git status
```

The expected state is:

```text
Python 3.12.3
```

and the Python executable should point into:

```text
.venv/bin/python
```

The Git working tree should remain clean unless the setup process created
intentional local changes.

---

# VS Code / WSL

The project should be opened from the Ubuntu environment:

```bash
code .
```

VS Code should indicate:

```text
WSL: Ubuntu
```

The integrated terminal should show the activated environment:

```text
(.venv)
```

---

# Activation for Future Sessions

After opening a new Ubuntu terminal, activate the existing environment:

```bash
cd ~/GitHub_Certification-Notes/Certification-Notes
source .venv/bin/activate
```

Verify:

```bash
which python
python --version
```

---

# Deactivation

When the virtual environment is no longer required:

```bash
deactivate
```

This does not delete the environment.

---

# Recreating the Environment

If the local `.venv` does not exist after cloning:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

Then verify:

```bash
which python
python --version
python -m pip --version
```

---

# Dependency Management

Python dependencies must be added to:

```text
requirements.txt
```

Do not commit the `.venv/` directory.

When a new dependency is intentionally introduced, document the reason
and update `requirements.txt`.

---

# Security Considerations

The virtual environment is local and must not contain:

* passwords
* API keys
* private certificates
* SSH private keys
* authentication tokens
* production credentials
* other secrets

Secrets must never be committed to the repository.

---

# Reproducibility Status

| Item                      | Status     |
| ------------------------- | ---------- |
| Ubuntu/WSL environment    | Configured |
| Repository cloned         | Configured |
| Python 3.12.3             | Verified   |
| `.venv`                   | Created    |
| `.venv` activation        | Verified   |
| `.gitignore`              | Configured |
| `requirements.txt`        | Created    |
| Environment documentation | Documented |

---

# Notes

The virtual environment itself is intentionally not version-controlled.

The repository stores the information required to recreate the environment,
rather than the environment itself.
