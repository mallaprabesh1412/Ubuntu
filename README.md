# Ubuntu


# Ubuntu 22 on Termux (Proot + XFCE VNC)

This project provides a one-click script to set up **Ubuntu 22 (Jammy)** inside [Termux](https://github.com/termux/termux-app) using **proot**.  
It also installs the **XFCE4 desktop environment** with **VNC support**.

---

## 🚀 Features
- Installs Ubuntu 22 rootfs on Termux
- Auto-configures fake `/proc` entries for compatibility
- Includes `start-ubuntu22.sh` launch script
- Sets up XFCE4 desktop + VNC server
- Supports ARM64 devices (`aarch64`)

---

## 📋 Requirements
- Android with Termux installed
- Minimum **3 GB free storage**
- Stable internet connection

---

## ⚙️ Installation

Open Termux and run:

```bash
pkg update && pkg upgrade -y
pkg install git wget proot tar -y
git clone https://github.com/mallapesh1412/ubuntu.git
cd ubuntu-termux-setup
bash setup.sh
