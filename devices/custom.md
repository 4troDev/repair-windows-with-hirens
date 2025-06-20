# 🧰 Custom / Whitebox PCs – Hiren’s Boot CD PE Guide

If you're working with a **custom-built desktop** or white-label PC, this guide shows how to boot into **Hiren’s Boot CD PE x64 (2019)** from a USB or DVD and use it for system recovery, password reset, or data repair.

---

## 🔁 Common Boot Menu Keys by Motherboard Brand

Custom-built PCs often use motherboards from popular brands. Below are the common **boot menu** and **BIOS keys**:

| Motherboard Brand | Boot Menu Key | BIOS Key     |
|-------------------|---------------|--------------|
| ASUS              | `F8`          | `Del` or `F2`|
| MSI               | `F11`         | `Del`        |
| Gigabyte          | `F12`         | `Del`        |
| ASRock            | `F11`         | `Del`        |
| Biostar           | `F9`          | `Del` or `F2`|

> ⚠️ Make sure the USB or DVD is connected before powering on. Press the key as soon as you see the brand logo.

---

## ⚙️ BIOS Settings to Check

Sometimes custom PCs require a few BIOS changes to allow booting from Hiren’s:

1. Power on your PC and enter the BIOS using the key for your board (see above).
2. Look for these settings:
   - **Secure Boot** → **Disable**
   - **CSM (Compatibility Support Module)** → **Enable**
   - **Legacy USB Boot** or **Boot Mode** → Set to **Legacy** or **Both**
3. Save and exit (`F10` on most BIOS).

If you're using **UEFI only** mode (common on newer builds), use **GPT + FAT32** when creating your USB with [Rufus](https://rufus.ie).

---

## 🛠️ Recommended Hiren’s Tools for DIY PCs

Once inside the Windows PE environment, use these tools depending on your build issue:

| Purpose               | Tool Name                   |
|-----------------------|-----------------------------|
| Fix boot/MBR issues   | AOMEI Partition Assistant   |
| Recover deleted data  | Recuva, TestDisk            |
| Clone or image disk   | Macrium Reflect             |
| Remove malware        | Malwarebytes, ESET Online   |
| Reset passwords       | Lazesoft Recovery Suite     |
| Monitor temps/fan     | HWMonitor, CPU-Z            |

---

## ✅ Tested Configurations

- Ryzen 5 / 7 + ASUS B550/X570 boards
- Intel i5/i7 + MSI Z390/Z490 boards
- Gigabyte mini ITX & custom gaming towers
- Budget systems with Biostar or ASRock boards

---

## 🧑‍🔧 Troubleshooting for Custom Rigs

| Issue                                  | Solution                                                   |
|---------------------------------------|------------------------------------------------------------|
| USB/DVD not detected                  | Use another port (prefer USB 2.0), check BIOS boot options |
| Black screen after selecting device   | Try switching from UEFI to Legacy, or reformat the USB     |
| No keyboard/mouse in PE               | Try different USB ports; use wired peripherals             |
| "No OS found" message                 | Check boot order and verify drive formatting               |

---

## 🧼 Wrap-Up

After using Hiren’s Boot CD PE:

1. Remove the boot media.
2. Restart your PC.
3. Re-enter BIOS if needed to:
   - Re-enable **Secure Boot**
   - Set your main drive back as the primary boot device

---

Need help getting Hiren’s working on your custom build?  
👉 [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues)

---
