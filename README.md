# PowerShell User Management Script

This is a PowerShell-based command-line tool for local user account management on Windows systems. It allows administrators to easily **add, edit, delete**, and **list users** using a menu-based interface.

## 🔧 Features

- 🔐 Add new users with:
  - Secure password prompt
  - Optional expiration date
  - Optional group assignment
- ✏️ Edit users:
  - Change password, full name, expiration date, groups
- ❌ Delete existing users
- 📋 Show all local users
- 🧭 Simple interactive terminal menu

## 📂 Usage

1. Open PowerShell **as administrator**.
2. Run the script:
   ```powershell
   .\UserManager.ps1
3. Follow the on-screen prompts.

Note: This script uses built-in cmdlets like New-LocalUser and Add-LocalGroupMember, so it only works on Windows 10/11/Server with local user access.

## 🧠 Skills Demonstrated
- PowerShell scripting
- Local user management
- Menu-driven automation
- SecureString and date handling
- Secure password input
- Menu-based CLI logic
- Use of conditionals and loops
- Automation for IT/admin tasks
- Basic DevOps/sysadmin scripting logic

## ⚙️ Requirements
- Windows 10/11 or Server
- PowerShell 5+
- Local admin permissions

## 🚫 Disclaimer
This is a local-only script for educational and administrative use on test or personal systems. Use responsibly.
