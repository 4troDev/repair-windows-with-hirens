# 💼 Dell Laptops & Desktops – Hiren’s Boot CD PE Guide

This guide walks you through using **Hiren’s Boot CD PE x64 (2019)** to repair Dell laptops and desktops. Whether you're resetting a password, recovering files, or fixing boot issues, Hiren's PE gives you everything you need — no installation required.

---

## 🔁 Boot Menu Access on Dell Systems

1. Completely shut down your Dell device.
2. Power it on and **immediately press `F12` repeatedly** until the **Boot Menu** appears.
3. From the list, select your **USB** or **DVD** containing Hiren’s Boot CD.
4. Press `Enter` to boot into the PE environment.

> 💡 On newer models, the boot device may show up as “UEFI: [USB NAME]” or “Legacy: [USB/DVD]”.

---

## ⚙️ BIOS Settings for Compatibility

If your USB or DVD doesn’t show up in the boot menu:

1. Reboot and press `F2` to enter **BIOS Setup**.
2. Navigate to:
   - **Boot Configuration**
   - **Secure Boot** → Set to **Disabled**
   - **Load Legacy Option ROMs** → **Enabled**
3. In the Boot Sequence menu:
   - Set Boot List Option to **Legacy** or **Both**
4. Press `F10` to **Save and Exit**.

> 🔐 Secure Boot must be disabled for non-signed tools like Hiren’s Boot CD to load properly.

---

## 🛠️ Key Tools for Dell Repairs

Once you’re in the Hiren’s PE desktop, here are some tools to help:

| Function               | Recommended Tool            |
|------------------------|-----------------------------|
| Password reset         | Lazesoft Recovery Suite     |
| File recovery          | Recuva, 7-Zip               |
| Partition management   | AOMEI Partition Assistant   |
| System image restore   | Macrium Reflect             |
| Malware cleanup        | Malwarebytes Portable       |
| System info/hardware   | CPU-Z, HWMonitor            |

---

## ✅ Tested Dell Systems

These Dell models are confirmed to work with this process:

- **Dell Inspiron Series** (13, 15, 17)
- **Dell Latitude Series**
- **Dell OptiPlex Desktops**
- **Dell XPS Laptops and Desktops**
- **Dell Vostro Business Laptops**

---

## 🧑‍🔧 Troubleshooting Dell Boot Issues

| Problem                            | Solution                                                  |
|-----------------------------------|------------------------------------------------------------|
| USB/DVD not appearing in F12 menu | Reformat USB using Rufus (MBR + NTFS or GPT + FAT32)       |
| System boots into Windows         | Check boot order in BIOS; disable Fast Boot                |
| Keyboard/mouse unresponsive       | Try USB 2.0 ports; plug into rear ports on desktops        |
| UEFI USB won’t boot               | Recreate boot drive using Rufus with UEFI settings         |

---

## 🧼 After Using Hiren’s Boot CD

1. Save any recovered data or complete your repair tasks.
2. Remove the USB or DVD.
3. Reboot your PC.
4. Re-enable **Secure Boot** in BIOS if desired (for extra protection).
5. Make sure your system drive is listed first in the boot sequence.

---

Having trouble with a Dell-specific issue or model?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---
