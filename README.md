# 🧼 Windows Icon Cache Reset Tool

A lightweight batch script to reset the Windows icon cache.  
Fixes broken or missing icons by deleting cache files and restarting File Explorer.

---

## 📦 What It Does

This script performs the following steps:

1. Prompts the user to confirm the operation  
2. Closes Windows File Explorer  
3. Deletes icon cache files  
4. Restarts File Explorer  
5. Displays a success message

---

## 🚀 How to Use

1. **Download or clone** this repository.
2. **Right-click** on `ResetIconCache.bat` and choose  
   `Run as administrator`.
3. **Confirm** when prompted.
4. Wait for the process to complete — icons will reload shortly.

---

## ⚠️ Requirements

- Windows 10 or later  
- Administrator privileges  
- File Explorer must be allowed to restart

---

## 📁 Files

| File Name            | Description                          |
|---------------------|--------------------------------------|
| `ResetIconCache.bat`| Main batch script to reset icon cache|

---

## 🛠 Example Output

```text
============================================
      ICON CACHE RESET TOOL (Windows)
============================================

This tool will reset the Windows icon cache.
Do you want to proceed? (Y/N): Y

Closing File Explorer...
Deleting icon cache files...
Restarting File Explorer...

✅ Icon cache has been successfully reset.
