# 🪟 Windows 10 – Hiren’s Boot CD PE Guide

This guide explains how to use **Hiren’s Boot CD PE x64 (2019)** to troubleshoot, repair, and recover Windows 10 PCs. The toolkit runs in a lightweight Windows 10 Preinstallation Environment (WinPE) and provides a variety of recovery tools.

---

## 🔁 Booting from Hiren’s Boot CD on Windows 10 PCs

1. Prepare a bootable USB or DVD with the Hiren’s Boot CD PE ISO.
2. Insert the USB/DVD into your Windows 10 PC.
3. Restart the PC and enter the **Boot Menu** using the key specific to your manufacturer:
   - HP: `Esc` → `F9`
   - Dell: `F12`
   - Lenovo: `F12` or Novo Button
   - Acer: `F12`
   - Custom PCs: `F8`, `F11`, `F12`, or `Del`
4. Select the USB/DVD drive to boot.
5. If the PC boots directly to Windows or the boot media is not detected, check BIOS settings:
   - Disable **Secure Boot**
   - Enable **Legacy Boot** or **CSM** if available
   - Set USB/DVD as the first boot device

---

## 🛠️ Key Tools Included for Windows 10 Recovery

| Task                   | Tool Example                 | Purpose                                    |
|------------------------|------------------------------|--------------------------------------------|
| Password Reset         | Lazesoft Recovery Suite       | Reset or remove Windows login passwords    |
| Malware Removal        | Malwarebytes Portable         | Scan and remove malware without booting OS |
| Disk Partitioning      | AOMEI Partition Assistant     | Resize, format, or fix partition issues    |
| Disk Imaging           | Macrium Reflect               | Create or restore full disk images          |
| File Recovery          | Recuva, 7-Zip                | Recover deleted files or browse backups    |
| Hardware Diagnostics   | CPU-Z, HWMonitor             | Monitor CPU, temperatures, and hardware info|

---

## 🧰 Useful Tips for Windows 10 Recovery

- Use **Lazesoft Password Recovery** if you forgot your Windows 10 password.
- Run **Malwarebytes** from PE to remove persistent viruses.
- Use **Macrium Reflect** to create a backup image before making system changes.
- **AOMEI Partition Assistant** can fix partition table errors causing boot problems.
- If you have multiple drives, verify which drive contains your Windows installation before repairing.

---

## 🧑‍🔧 Troubleshooting Common Issues

| Issue                             | Solution                                                       |
|----------------------------------|-----------------------------------------------------------------|
| Boot media not detected           | Confirm BIOS boot order and USB boot support; disable Secure Boot |
| USB keyboard/mouse unresponsive   | Try different USB ports or use wired peripherals                |
| PE environment boots but tools fail| Try re-creating bootable media or use another USB drive         |
| System boots straight into Windows| Change boot priority in BIOS and confirm boot device selection  |

---

## 🧼 After Repair or Recovery

1. Safely eject the USB/DVD boot media.
2. Restart your PC.
3. Optionally, re-enable **Secure Boot** and disable Legacy Boot.
4. Verify that your system boots normally.

---

Need help or want to contribute to improving this Windows 10 guide?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---
