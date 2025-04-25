# CHUCK

the CHUCK package manager  
**Codified Hybrid Universal Command Kernel**  
🪵💻 A sovereign boot orchestration interface for building and deploying operating systems — like JaymiOS, OpenCore/macOS, or any multi-platform live image — from a single modular command-line experience.

---

### 🏢 About CHUCK Industries

CHUCK Industries is the umbrella company behind the CHUCK package manager and related technologies. Founded by Charles E. Drain, CHUCK Industries specializes in sovereign boot orchestration, hybrid OS deployment, and modular command-line tooling for multi-platform environments.

---

### ✍️ Digital Signature

CHUCK is the digital fingerprint and signature of Charles E. Drain. It represents his authorship, creativity, and intellectual property in the realm of software engineering and boot orchestration technologies.

---

### 📜 Legal Notice

CHUCK and all associated technologies are © 2025 by Charles E. Drain and CHUCK Industries. All rights reserved.  
Unauthorized reproduction, distribution, or modification of this software is strictly prohibited without explicit permission from the author or CHUCK Industries.  
This software is intended for commercial use, and any derived works must comply with the terms of the MIT License.

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
