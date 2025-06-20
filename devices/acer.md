# 🧳 Acer Laptops & Desktops – Hiren’s Boot CD PE Guide

This guide walks you through using **Hiren’s Boot CD PE x64 (2019)** to repair and recover Acer laptops and desktops by booting from a USB or DVD.

---

## 🔁 Accessing the Boot Menu (Acer)

To boot from Hiren’s Boot CD on an Acer device:

1. **Power off** your Acer system.
2. Power it back on and **press `F12` repeatedly** until the **Boot Menu** appears.
3. Select the **USB** or **DVD drive** from the list.
4. Press `Enter` to begin booting into Hiren’s PE.

> 💡 If pressing `F12` does nothing, follow the steps below to enable the boot menu in BIOS.

---

## 🧰 Required BIOS Settings for Booting

If the USB or DVD isn't detected, update the following settings in BIOS:

1. Power on the device and press `F2` to enter **BIOS Setup**.
2. Under the **Main** tab:
   - Set **F12 Boot Menu** to **Enabled**
3. Under the **Boot** or **Security** tab:
   - Set **Secure Boot** to **Disabled**
   - Enable **Legacy Boot** (if supported)

> 📌 Some newer Acer systems only support UEFI mode. If Hiren's doesn't boot, try reformatting the USB with Rufus using **GPT + FAT32**.

---

## 🛠️ Useful Hiren’s Tools for Acer Devices

Once inside the Hiren’s PE desktop, you’ll have access to powerful recovery tools:

| Tool Category      | Example Tool                | Purpose                                 |
|--------------------|-----------------------------|------------------------------------------|
| Password Reset     | Lazesoft / NTPWEdit          | Clear forgotten login passwords          |
| Disk Repair        | AOMEI Partition Assistant    | Resize/fix partitions or boot records    |
| Virus Removal      | Malwarebytes                 | Remove infections without logging in     |
| Data Recovery      | Recuva / TestDisk            | Recover files from formatted or lost drives |
| System Imaging     | Macrium Reflect              | Backup or restore full system image      |
| Diagnostics        | HWMonitor / CPU-Z            | Check temps, CPU info, fan speed         |

---

## ✅ Tested Acer Devices

- Acer Aspire 5 & 7 Series
- Acer Nitro Gaming Laptops
- Acer Spin (Convertible Series)
- Acer Predator Orion Desktops
- Acer Swift Ultrabooks

---

## 🧑‍🔧 Troubleshooting Tips

| Problem                                 | Suggested Fix                                             |
|----------------------------------------|-----------------------------------------------------------|
| USB/DVD not showing in boot menu       | Enable F12 Boot Menu in BIOS                              |
| PC skips to Windows                    | Reorder boot priority or press F12 faster on startup      |
| UEFI-only systems fail to boot         | Reformat USB as GPT + FAT32 using Rufus                   |
| Touchpad or Wi-Fi not working in PE    | Use external mouse/keyboard or wired connection           |

---

## 🧼 After You’re Done

1. Save any recovered data or apply the fixes needed.
2. Remove the USB/DVD.
3. Reboot your system normally.
4. Optionally go back into BIOS to:
   - Re-enable **Secure Boot**
   - Disable **Legacy Boot**

---

Need help or want to suggest improvements to this guide?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---