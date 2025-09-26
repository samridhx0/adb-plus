# ADB-Plus — ADB Desktop Toolkit

![logo-adb](https://github.com/user-attachments/assets/b580c8df-0438-45ca-8bb0-e37a7e0727b6)

Streamline everyday Android workflows in a single, clean interface: manage apps, run shell commands, launch screen mirroring (scrcpy), and generate quick forensic-style snapshots for triage and documentation.

> **Experimental project — use with caution.**  
> Always ensure you have permission to interact with any device, and verify outputs independently before relying on them.

---

![Screenshot 2025-09-19 231722](https://github.com/user-attachments/assets/c44302f9-ff0a-4a1c-a39f-206821658ce2)
![Screenshot](https://github.com/user-attachments/assets/ab0ea6fa-b10b-40ce-9682-e59bff9bba29)

## 🚀 Highlights

- **Device and connection helpers**
  - Point the app at your local `adb.exe`
  - Connect over USB or TCP/IP
  - Quick server controls (kill / restart)
- **App management (Apps tab)**
  - Install/Update/Uninstall APKs
  - Enable/Disable packages
  - List system/third‑party packages
  - Extract APKs from a device to your computer
- **Shell runner (Shell tab)**
  - One‑off shell commands with a shortcuts dropdown
  - Run a command across all connected devices concurrently
  - Scrollable, copyable console output with inline error banner
- **Forensic snapshot (Forensics tab)**
  - Gathers common on‑device data (build info, packages, logs, running apps, storage, etc.)
  - Produces an HTML report (templated via Jinja2) for quick review
- **scrcpy launcher**
  - Start scrcpy with your preferred resolution/bitrate presets

---

![Forensics Report](https://github.com/user-attachments/assets/509555f3-9d2d-4a23-8f5e-1f4a2111875e)
![AndroidForensiX](https://github.com/user-attachments/assets/9898c90c-d1a3-490e-98c7-9e3c9a5139e)
