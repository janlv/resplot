# resplot
Using pyvista to plot reservoir data

# Project Installation Guide

This project includes installation scripts that create a virtual environment and install all necessary dependencies.

---

## Installation (Linux/macOS)

1. Make the script executable:
```bash
chmod +x install.sh
```

2. Run the installer:
```bash
./install.sh
```

---

## Installation (Windows)

1. Open a terminal (e.g., Command Prompt or PowerShell)

2. Run:
```bat
install.bat
```

---

## Activating and deactivating the environment

### Linux/macOS:

To **activate** the environment:
```bash
source .venv_<project_name>/bin/activate
```

To **deactivate**, run:
```bash
deactivate
```

---

### Windows:

To **activate** the environment:
```bat
call .venv_<project_name>\Scripts\activate.bat
```

To **deactivate**, run:
```bat
deactivate
```

---

## Notes

- The virtual environment will be named `.venv_<project_name>`, where `<project_name>` is read from your `pyproject.toml`.
- If `requirements.txt` is present, it will be used to install additional dependencies (e.g., GitHub packages).
