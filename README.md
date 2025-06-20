# 🛠️ Hiren’s Boot CD PE x64 (2019) – Full Windows Repair Guide

This repository provides a **step-by-step tutorial** on how to use **Hiren’s Boot CD PE x64 (2019)** — a powerful, bootable Windows 10-based recovery toolkit — to repair, recover, and troubleshoot **Windows PCs** across all major brands including HP, Dell, Lenovo, Acer, and more.

Whether you're locked out of your system, recovering lost data, or fixing startup issues, this guide will help you navigate the process using the tools included in Hiren’s Boot CD PE.

---

## 📋 Table of Contents

- [What is Hiren’s Boot CD PE?](#what-is-hirens-boot-cd-pe)
- [What You Need](#what-you-need)
- [Step 1: Boot from Hiren’s Boot CD (DVD/USB)](#step-1-boot-from-hirens-boot-cd-dvdusb)
- [Step 2: Explore the Recovery Environment](#step-2-explore-the-recovery-environment)
- [Step 3: Use Key Tools (Examples)](#step-3-use-key-tools-examples)
- [Step 4: Exit and Reboot](#step-4-exit-and-reboot)
- [Device-Specific Guides](#device-specific-guides)
- [FAQ](#faq)
- [License](#license)

---

## 📦 What is Hiren’s Boot CD PE?

**Hiren’s Boot CD PE x64 (2019)** is a modern Windows 10-based Preinstallation Environment (WinPE) packed with free tools for:

- Password recovery
- System repair
- Partition management
- Malware removal
- Disk imaging
- Data recovery
- Hardware diagnostics

> 🖥️ No installation required — boot from USB or DVD directly into a repair-ready environment.

---

## 🧰 What You Need

- ✅ A PC or laptop running **Windows 10** (any brand)
- ✅ The **Hiren’s Boot CD PE x64 (2019) ISO**
- ✅ A **USB drive (4GB+)** or a **blank DVD**
- ✅ [Rufus](https://rufus.ie/) (if using USB)
- ✅ Optional: An external drive for backups

---

## 🔁 Step 1: Boot from Hiren’s Boot CD (DVD/USB)

### For USB Boot:
1. Use **Rufus** to create a bootable USB using the Hiren’s ISO.
2. Insert the USB into the PC.
3. Power on the PC and enter the **boot menu**:
   - HP: `Esc` → `F9`
   - Dell: `F12`
   - Lenovo: `F12` or `Novo button`
   - Acer: `F12`
4. Select the USB drive to boot.

### For DVD Boot:
1. Burn the ISO to DVD using **Windows Disc Image Burner** or **ImgBurn**.
2. Insert the DVD and restart the PC.
3. Enter the **boot menu** and choose the DVD drive.

> ⚠️ If booting fails, disable **Secure Boot** and enable **Legacy Support** in BIOS.

---

## 🪟 Step 2: Explore the Recovery Environment

Once booted, Hiren’s loads a **Windows 10 PE desktop**. No installation is needed.

### Included Tools:
- **Macrium Reflect** – System imaging and backups
- **AOMEI Partition Assistant** – Disk partitioning
- **Lazesoft Recovery Suite** – Password reset, registry recovery
- **Malwarebytes** – Virus and malware removal
- **Recuva** – File recovery
- **7-Zip** – File browsing and extraction
- **CPU-Z, HWMonitor** – Hardware diagnostics

---

## 🛠️ Step 3: Use Key Tools (Examples)

### 🔑 Reset a Forgotten Password:
1. Open `Lazesoft Password Recovery`.
2. Select your Windows installation and user account.
3. Reset the password to blank or a new one.
4. Reboot and log in.

### 💾 Recover Deleted Files:
1. Launch `Recuva`.
2. Select the drive to scan.
3. Recover files to an external backup drive.

---

## 🔚 Step 4: Exit and Reboot

- Save any recovered data or changes.
- Remove the USB/DVD.
- Reboot your computer.
- Optionally, re-enable **Secure Boot** in BIOS if you disabled it earlier.

---

## 📁 Device-Specific Guides

Looking for a guide specific to your laptop or OS version? Check these:

### 🏷️ By Manufacturer:
- [🖥 HP Laptops & Desktops](devices/hp.md)
- [💼 Dell Systems](devices/dell.md)
- [💻 Lenovo Devices](devices/lenovo.md)
- [🧳 Acer Systems](devices/acer.md)
- [🧰 Custom/Whitebox PCs](devices/custom.md)

### 🪟 By Operating System:
- [🪟 Windows 10](os/windows10.md)
- [🪟 Windows 11 (Beta)](os/windows11.md)
- [📀 Legacy Systems (Windows 7/8)](os/windows7-8.md)

> 💡 Don’t see your device? Feel free to contribute a guide or open an issue!

---

## ❓ FAQ

**Q: Can I use this on Windows 11?**  
Yes, most tools work with Windows 11 as well, though the environment is based on Windows 10.

**Q: Is this safe?**  
Yes, Hiren’s Boot CD PE uses reputable, free tools and does not modify your system unless you choose to.

**Q: Do I need admin access to use it?**  
No, since it runs outside of your OS, you can reset admin passwords or access data without logging in.

---

## 📄 License

All tools included in Hiren’s Boot CD are free for personal and educational use. This tutorial is licensed under the [MIT License](LICENSE).

---

> Made with 💻 by [4troDev](https://github.com/4troDev) – feel free to contribute or open an issue if you need help!
