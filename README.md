# Project Setup & Useful Commands

Reusable base library for my Python projects.  
It contains common functionality for fitting, smoothing and model-related utilities that can be shared across multiple applications.

---

## 1. Virtual Environment

### 1.1 Create / check / activate environment

Use the provided PowerShell script:

```powershell
. .\setup_env.ps1
````

This script will:

* Create the `.venv` virtual environment if it does not exist
* Activate the virtual environment
* Install / update the required packages
* Install / update the recommended extensions

### 1.2 Manually activate existing venv (if needed)

If you need to activate the environment manually:

```powershell
.\.venv\Scripts\Activate.ps1
```

## 2. Running the Applications

All applications are started via Python’s module syntax from the repository root.
