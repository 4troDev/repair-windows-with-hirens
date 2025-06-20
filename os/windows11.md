# 🪟 Windows 11 – Hiren’s Boot CD PE Guide (Beta)

This guide helps you use **Hiren’s Boot CD PE x64 (2019)** to troubleshoot and repair Windows 11 PCs. Although the environment is based on Windows 10 PE, most tools work on Windows 11 systems.

---

## 🔁 Booting Hiren’s Boot CD on Windows 11 PCs

1. Create a bootable USB or DVD with the Hiren’s Boot CD PE ISO.
2. Insert it into your Windows 11 PC.
3. Restart and enter the **Boot Menu** using your manufacturer’s key:
   - HP: `Esc` → `F9`
   - Dell: `F12`
   - Lenovo: `F12` or Novo button
   - Acer: `F12`
   - Custom PCs: `F8`, `F11`, `F12`, or `Del`
4. Select the USB/DVD device to boot.
5. If the system boots directly into Windows or the device doesn’t appear:
   - Enter BIOS (`F2`, `Del`, or manufacturer-specific key).
   - Disable **Secure Boot**.
   - If available, enable **Legacy Boot** or **CSM**.
   - Adjust boot priority to prioritize USB/DVD.

> ⚠️ Windows 11 PCs often use strict UEFI and Secure Boot settings that may prevent booting unsigned boot media.

---

## 🛠️ Recommended Tools for Windows 11 Recovery

| Task                     | Tool Example                  | Purpose                                   |
|--------------------------|-------------------------------|-------------------------------------------|
| Password Reset           | Lazesoft Recovery Suite        | Reset forgotten Windows login passwords   |
| Malware Removal          | Malwarebytes Portable          | Scan and remove malware                    |
| Disk Partitioning        | AOMEI Partition Assistant      | Manage and repair disk partitions          |
| Disk Imaging             | Macrium Reflect                | Backup and restore system images           |
| File Recovery            | Recuva, 7-Zip                 | Recover deleted files or browse backups   |
| Hardware Diagnostics     | CPU-Z, HWMonitor              | Check CPU, temperatures, and hardware info|

---

## 💡 Windows 11 Compatibility Notes

- Some hardware drivers may not be available in this WinPE environment.
- Touchscreen or certain newer peripherals may not work; use wired mouse/keyboard if possible.
- Newer NVMe drives and RAID configurations may require additional drivers not included.
- Some features may be limited due to Windows 10-based PE environment.

---

## 🧑‍🔧 Troubleshooting Windows 11 Boot Issues

| Problem                        | Solution                                                   |
|-------------------------------|------------------------------------------------------------|
| Boot media doesn’t appear      | Disable Secure Boot and enable Legacy Boot or CSM in BIOS  |
| Unable to boot from USB/DVD    | Try recreating boot media with Rufus (GPT + FAT32 for UEFI)|
| USB keyboard/mouse unresponsive| Use wired peripherals or different USB ports               |
| System boots directly to Windows| Confirm boot priority and boot device selection in BIOS   |

---

## 🧼 After Recovery

1. Remove the boot media.
2. Reboot your PC.
3. Optionally re-enable Secure Boot for security.
4. Confirm your system boots normally.

---

Need help or want to improve this Windows 11 guide?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---
