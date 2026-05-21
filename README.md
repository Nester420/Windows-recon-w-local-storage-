<img width="1721" height="914" alt="win11" src="https://github.com/user-attachments/assets/6bf1175d-994e-4870-9592-569b6c362c9f" />
# 🦆 Rubber Ducky Payload – Full Windows Recon & Data Dump to USB

## 📋 Description
This payload is designed for **Rubber Ducky 3.0** using the `ATTACKMODE HID STORAGE` feature. It performs a comprehensive reconnaissance of a Windows machine and exfiltrates the data directly to the Ducky's mounted USB storage — no internet required.

> ⚠️ **For educational and authorized lab use only.**

---

## 🔍 What It Collects
- Saved Wi-Fi SSIDs & passwords
- System and OS info
- User and group details
- Installed software
- Running processes (top by CPU)
- Listening ports (via netstat)
- Missing Windows patches
- Privilege escalation indicators:
  - Admin rights
  - UAC config
  - AlwaysInstallElevated
  - Unquoted service paths
  - Writable service binaries
  - Weak scheduled tasks
  - Writable registry keys
- WSUS hijack config
- Antivirus/EDR detection
- Screenshot of desktop
- Clipboard contents

---

## 💾 Output Files (Saved to Ducky USB)
- `recon_report.txt`: All system and privilege info
- `clipboard.txt`: Current contents of clipboard
- `screenshot.jpg`: Screenshot of all monitors

---

## 🚀 Usage Instructions
1. Save the payload as `inject.ducky` in the root directory.
2. Plug the Ducky into a Windows machine.
3. Wait ~30–60 seconds for the script to complete.
