# Day 1 — PowerShell Basics

**Date:** 28 September 2026  
**Repository:** daily-powershell-practice

## 🎯 Goal

Learn the basic PowerShell commands used to inspect the PowerShell environment, navigate directories, view files and folders, and check the current date and time.

## 1. Check PowerShell Version

### Command

``powershell
$PSVersionTable.PSVersion
``

### Purpose

Displays the installed PowerShell version.

### Output

PowerShell 5.1 was used for this practice.

---

## 2. Check Current Location

### Command

``powershell
Get-Location
``

### Purpose

Shows the current working directory.

### Output

``text
C:\Users\sneha\daily-powershell-practice
``

---

## 3. List Files and Folders

### Command

``powershell
Get-ChildItem
``

### Purpose

Lists files and folders in the current directory.

### Output

The repository contained Day-01.md.

---

## 4. Check Current Date and Time

### Command

``powershell
Get-Date
``

### Output

``text
28 September 2026 19:45:37
``

---

## 5. Commands Learned

| Command | Purpose |
|---|---|
| $PSVersionTable.PSVersion | Check PowerShell version |
| Get-Location | Show current directory |
| Get-ChildItem | List files and folders |
| Get-Date | Display date and time |

---

## 6. Practical Practice

``powershell
$PSVersionTable.PSVersion
Get-Location
Get-ChildItem
Get-Date
``

## 7. What I Learned

- Checked the installed PowerShell version.
- Checked the current working directory.
- Listed files and folders.
- Checked the current date and time.
- Practiced basic PowerShell commands.

## ✅ Day 1 Checklist

- [x] Checked PowerShell version
- [x] Checked current location
- [x] Listed files and folders
- [x] Checked current date and time
- [x] Created Day-01.md
- [x] Committed the practice
- [x] Pushed the practice to GitHub

## 🚀 Key Takeaway

Today I learned the fundamental PowerShell commands needed to understand my terminal environment and work with files and directories.

## 📌 Day 1 Status

**Completed successfully ✅**

**Learning Track:** Daily PowerShell Practice  
**Day:** 1 / 30
