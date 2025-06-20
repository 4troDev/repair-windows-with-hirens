# 🪟 Windows 7 & 8 – Hiren’s Boot CD PE Guide

This guide covers how to use **Hiren’s Boot CD PE x64 (2019)** to repair and recover Windows 7 and Windows 8 systems. Many of the included tools support legacy BIOS and older hardware.

---

## 🔁 Booting from Hiren’s Boot CD on Windows 7/8 PCs

1. Create a bootable USB or DVD with Hiren’s Boot CD ISO.
2. Insert the USB/DVD into your Windows 7/8 PC.
3. Restart and press the appropriate **boot menu key**:
   - Most common keys: `F12`, `F9`, `Esc`, or `Del`
4. Select your USB/DVD from the boot menu and press `Enter`.
5. The Hiren’s PE environment will load, based on Windows 10 but compatible with older systems.

> ⚠️ If booting fails, disable **Secure Boot** in BIOS and enable **Legacy Boot** or **CSM**.

---

## 🧰 Key Tools for Windows 7 & 8 Repairs

| Repair Task           | Recommended Tool              |
|----------------------|------------------------------|
| Password Reset       | Lazesoft Recovery Suite       |
| Malware Removal      | Malwarebytes Portable         |
| Partition Management | AOMEI Partition Assistant     |
| File Recovery        | Recuva, TestDisk              |
| Disk Imaging         | Macrium Reflect               |
| System Info/Hardware | CPU-Z, HWMonitor              |

---

## 🧩 Special Notes for Older Systems

- Many Windows 7/8 PCs use BIOS with Legacy Boot by default, making USB/DVD boot easier.
- Some older hardware may not be fully supported in the Windows 10 PE environment — try to use USB 2.0 ports for better compatibility.
- Data recovery tools can help if your system disk has become corrupted or accidentally formatted.
- Hiren’s Boot CD PE can also be used to migrate files from an old system to a new one.

---

## 🧑‍🔧 Troubleshooting Tips

| Problem                             | Solution                                                   |
|-----------------------------------|------------------------------------------------------------|
| Boot media not detected            | Check BIOS boot order and enable Legacy Boot/CSM          |
| USB keyboard/mouse not working     | Use USB 2.0 ports or wired devices                         |
| System boots directly to Windows   | Double-check boot device selection and reboot             |
| Compatibility issues with PE tools | Try running tools on a secondary PC or use standalone versions |

---

## 🧼 After Repair

1. Remove the bootable media.
2. Restart your computer normally.
3. Return to BIOS and restore settings if you disabled Secure Boot or Legacy mode.

---

Need help or want to share tips for Windows 7/8 recovery?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---
