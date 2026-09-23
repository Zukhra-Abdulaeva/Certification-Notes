# 🛠️ Development Environment

This project is developed on **Windows** using **WSL2 with Ubuntu** as the Linux development environment.

The following steps show how to prepare the project after cloning the repository.
---

## 1. 🪟 Open Ubuntu through WSL2

Open **PowerShell** on Windows and start Ubuntu:

```powershell
wsl -d Ubuntu
```

You should now be inside the Ubuntu environment.

Check the current location:

```bash
pwd
```

If necessary, move to the Linux home directory:

```bash
cd ~
```

---

## 2. 📁 Create a Project Directory

Create a directory for the GitHub projects:

```bash
mkdir -p ~/GitHub_Projects
```

Move into it:

```bash
cd ~/GitHub_Projects
```

---

## 3. 📥 Clone the Repository

Clone the repository:

```bash
git clone https://github.com/<OWNER>/<REPOSITORY>.git
```

Enter the repository:

```bash
cd <REPOSITORY>
```

Verify the configured remote:

```bash
git remote -v
```

The `origin` remote should point to the project's GitHub repository.

---

## 4. 💻 Open the Project in VS Code

From the repository directory:

```bash
code .
```

VS Code should open the project using the **WSL: Ubuntu** environment.

---

## 5. 🐍 Create the Python Virtual Environment

Inside the repository, create the local Python environment:

```bash
python3 -m venv .venv
```

The environment is created inside:

```text
.venv/
```

The virtual environment is local and must not be committed to Git.

You can verify that the environment was created:

```bash
ls -l .venv/bin/python .venv/bin/activate
```

---

## 6. ▶️ Activate the Virtual Environment

Activate the environment:

```bash
source .venv/bin/activate
```

The terminal should now show:

```text
(.venv)
```

---

## 7. 🔍 Verify Python

Check which Python executable is being used:

```bash
which python
```

The path should point into the project environment:

```text
.../<REPOSITORY>/.venv/bin/python
```

Check the Python version:

```bash
python --version
```

Expected:

```text
Python 3.12.3
```

---

## 8. 📦 Install Dependencies

Install the dependencies defined by the repository:

```bash
python -m pip install -r requirements.txt
```

At the current stage, `requirements.txt` contains no third-party dependencies. The project primarily uses Linux system tools and Python's standard library.

If dependencies are added later, they should be recorded in `requirements.txt`.

---

## 9. ✅ Verify the Environment

After setup, run:

```bash
python --version
which python
python -m pip --version
git status
```

The Python executable should point to:

```text
.venv/bin/python
```

The Python version should be:

```text
Python 3.12.3
```

---

## 🔄 Future Sessions

After opening a new Ubuntu/WSL terminal, navigate to the repository and activate the existing environment:

```bash
cd ~/GitHub_Projects/<REPOSITORY>
source .venv/bin/activate
```

Then verify:

```bash
python --version
which python
```

---

## ♻️ Recreate the Environment

If the `.venv` directory does not exist, recreate it:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

The project environment is intentionally **not version-controlled**. The repository contains the files required to recreate it.

---

## 🔐 Security

Do not commit sensitive information such as:

* passwords
* API keys
* authentication tokens
* private keys or certificates
* production credentials
* other secrets
