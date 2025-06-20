# 💻 Lenovo Laptops & Desktops – Hiren’s Boot CD PE Guide

This guide walks you through booting **Hiren’s Boot CD PE x64 (2019)** on Lenovo laptops and desktops to recover Windows, reset passwords, fix boot issues, and more.

---

## 🔁 Accessing the Boot Menu (Lenovo)

There are two ways to access the boot menu on Lenovo systems:

### Method 1: Using the Novo Button
1. Power off your Lenovo device.
2. Locate the **Novo Button** (a small pinhole on the side or near the power button).
3. Use a paperclip to press it once.
4. From the Novo Menu, select **Boot Menu**.
5. Choose your **USB drive** or **DVD**.

### Method 2: Using Function Keys
1. Turn off your computer completely.
2. Power it on and **press `F12` repeatedly** until the **Boot Menu** appears.
3. Select your **USB** or **DVD** device and press `Enter`.

> 💡 Tip: If the device doesn’t show up, check the BIOS settings below.

---

## ⚙️ BIOS Settings for Boot Compatibility

Lenovo systems may require changing BIOS settings to allow booting from external media.

1. Restart and press `F1` or `F2` to enter **BIOS Setup**.
2. Navigate to:
   - **Security** → Disable **Secure Boot**
   - **Boot** → Set **Boot Mode** to **Legacy Support** or **Both**
3. Make sure the USB/DVD is set high in the boot order.
4. Save and exit (`F10`).

> ⚠️ On newer Lenovo ThinkPads and IdeaPads, UEFI-only mode may block older bootloaders. Try **UEFI + GPT + FAT32** formatting via Rufus.

---

## 🛠️ Common Hiren’s Tools for Lenovo Repairs

| Task                     | Recommended Tool            |
|--------------------------|-----------------------------|
| Password reset           | Lazesoft Recovery Suite     |
| Partition repair         | AOMEI Partition Assistant   |
| Drive backup/cloning     | Macrium Reflect             |
| File recovery            | Recuva, 7-Zip               |
| Virus & malware removal  | Malwarebytes Portable       |
| BIOS/hardware checks     | HWMonitor, CPU-Z            |

---

## ✅ Tested Lenovo Devices

This guide has been successfully tested on:

- **Lenovo ThinkPad T-Series** (e.g. T480, T14)
- **Lenovo IdeaPad 3/5/7**
- **Lenovo Legion Gaming Laptops**
- **Lenovo Yoga Flex Series**
- **Lenovo ThinkCentre Desktops**

---

## 🧑‍🔧 Troubleshooting Tips

| Issue                             | Solution                                                   |
|----------------------------------|-------------------------------------------------------------|
| Boot menu not appearing          | Try `Novo Button`, or ensure **F12 Boot Menu** is enabled   |
| USB not booting                  | Reformat with Rufus using correct mode (UEFI/Legacy)        |
| Mouse/keyboard unresponsive      | Try different USB ports or plug in external peripherals     |
| Boot loops back to Windows       | Change boot order in BIOS and disable **Fast Boot**         |

---

## 🧼 Post-Repair Wrap-Up

After completing your recovery or repair:

1. Remove the Hiren’s USB/DVD.
2. Reboot your system.
3. Optionally return to BIOS to:
   - Re-enable **Secure Boot**
   - Set your main internal drive as top boot device

---

Need help with a specific Lenovo model or BIOS issue?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---
