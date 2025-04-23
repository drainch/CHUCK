# CHUCK

the CHUCK package manager
**Codified Hybrid Universal Command Kernel**  
🪵💻 A sovereign boot orchestration interface for building and deploying operating systems — like JaymiOS, OpenCore/macOS, or any multi-platform live image — from a single modular command-line experience.

---

### 📦 Commands

- `CHUCK mac on --usb`  
  Flash macOS to USB using OpenCore, custom specs, and Jaymi’s boot preparation logic.

- `CHUCK mac on --net`  
  PXE-boot JaymiOS/macOS over the network.

- `CHUCK jaymi on --usb`  
  Flash JaymiOS hybrid OS to a USB device.

- `CHUCK fetch --mac`  
  Only fetch BaseSystem.dmg + Install.app from Apple.

- `CHUCK spec --auto`  
  Auto-detect system specs and save for future scripting.

- `CHUCK boot --now`  
  Reboot into the prepared USB or disk device if bootable.

---

### 🛠 Structure

```
chuck/
├── chuck.sh               # main CLI controller
├── packages/
│   ├── mac.sh             # handles CHUCK mac logic (flashing, OpenCore, fetchOS)
│   ├── jaymi.sh           # handles JaymiOS hybrid flashing
│   └── win.sh             # (optional) future Windows ISO flasher
├── profiles/
│   └── default.chuckrc    # saved environment defaults
└── README.md              # this file
```

---

### ⏱️ Timestamp: 2025-04-23 19:47:00

> Created by Charlie Drain. Rendered by GPT. Forged in Crostini.  
> Designed to boot gods from USB.
