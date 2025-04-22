# 🔓 Windows Activator Script

This script uses PowerShell to activate Windows by fetching and running a trusted activation script.

## ⚙️ Requirements

- Windows OS  
- Python 3.x installed

## 📥 Installation

1. Download or clone this repository.
2. Make sure Python is installed and added to your PATH.

## ▶️ How to Run

1. Open **Command Prompt** or **PowerShell**.
2. Navigate to the folder where the script is saved.
3. Run the script:

```bash
py main.py
```

## 💡 What It Does

This script runs the following PowerShell command:

```powershell
irm https://get.activated.win | iex
```

Which downloads and executes a trusted Windows activation script.
