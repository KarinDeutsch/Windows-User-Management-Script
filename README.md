# PowerShell User Management Script

This is a PowerShell-based command-line tool for local user account management on Windows systems. It allows administrators to easily **add, edit, delete**, and **list users** using a menu-based interface.

## 🔧 Features

- Create new users with:
  - Secure password input
  - Optional expiration date
  - Group assignment
- Edit existing users:
  - Change password, name, groups, or expiration
- Delete users safely
- List all current local users
- Simple terminal menu navigation

## 📂 Usage

1. Open PowerShell **as administrator**.
2. Run the script:
   ```powershell
   .\UserManager.ps1
3. Follow the on-screen prompts.

Note: This script uses built-in cmdlets like New-LocalUser and Add-LocalGroupMember, so it only works on Windows 10/11/Server with local user access.

🧠 Skills Demonstrated
- PowerShell scripting
- Local user management
- Menu-driven automation
- String and date handling
- Secure password input
- Use of conditionals and loops
- Basic DevOps/sysadmin scripting logic

**🚫 Disclaimer
This is a local-only script for educational and administrative use on test or personal systems. Use responsibly.
