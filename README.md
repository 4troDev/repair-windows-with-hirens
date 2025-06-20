# 🛠️ Hiren’s Boot CD PE x64 (2019) – Full Windows Repair Guide

This repository provides a **step-by-step tutorial** on how to use **Hiren’s Boot CD PE x64 (2019)** — a powerful, bootable Windows 10-based recovery toolkit — to repair, recover, and troubleshoot **Windows PCs** across all major brands including HP, Dell, Lenovo, Acer, and more.

Whether you're locked out of your system, recovering lost data, or fixing startup issues, this guide will help you navigate the process using the tools included in Hiren’s Boot CD PE.

---

## 📋 Table of Contents

- [What is Hiren’s Boot CD PE?](#what-is-hirens-boot-cd-pe)
- [What You Need](#what-you-need)
- [Step 1: Create Bootable Media](#step-1-create-bootable-media)
- [Step 2: Boot from Hiren’s Boot CD (DVD/USB)](#step-2-boot-from-hirens-boot-cd-dvdusb)
- [Step 3: Explore the Recovery Environment](#step-3-explore-the-recovery-environment)
- [Step 4: Use Key Tools (Examples)](#step-4-use-key-tools-examples)
- [Step 5: Exit and Reboot](#step-5-exit-and-reboot)
- [Device-Specific Guides](#device-specific-guides)
- [OS-Specific Guides](#os-specific-guides)
- [FAQ](#faq)
- [Contributing](#contributing)
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

- ✅ A PC or laptop running Windows (any brand)
- ✅ The **Hiren’s Boot CD PE x64 (2019) ISO** file
- ✅ A **USB flash drive (4GB+)** or a **blank DVD**
- ✅ [Rufus](https://rufus.ie/) (recommended for USB creation)
- ✅ Optional: External drive for backups and recovered data

---

## Step 1: Create Bootable Media

### Using Rufus to create a bootable USB:

1. Download and launch [Rufus](https://rufus.ie/).
2. Insert your USB flash drive (all data will be erased).
3. Select the USB drive in Rufus.
4. Click **SELECT** and choose the Hiren’s Boot CD PE ISO.
5. Choose partition scheme:
   - GPT for UEFI systems
   - MBR for Legacy BIOS systems
6. Select **FAT32** for file system (preferred for UEFI), or **NTFS** for Legacy BIOS.
7. Click **START** and wait for completion.

### Creating a bootable DVD:

1. Insert a blank DVD into your burner.
2. Right-click the ISO file and choose **Burn disc image** (Windows built-in) or use ImgBurn.
3. Follow prompts to complete burning.

---

## Step 2: Boot from Hiren’s Boot CD (DVD/USB)

- Insert your bootable USB or DVD.
- Power on your PC.
- Enter the **Boot Menu** (keys vary by brand):
  - HP: `Esc` then `F9`
  - Dell: `F12`
  - Lenovo: `F12` or **Novo button**
  - Acer: `F12`
  - Custom PCs: `F8`, `F11`, `F12`, or `Del`
- Select your USB or DVD device.
- If it doesn’t appear:
  - Enter BIOS/UEFI setup.
  - Disable **Secure Boot**.
  - Enable **Legacy Boot** or **CSM**.
  - Adjust boot priority.

---

## Step 3: Explore the Recovery Environment

Booting loads a Windows 10 PE desktop with included recovery tools:

- Macrium Reflect (imaging)
- AOMEI Partition Assistant (partitioning)
- Lazesoft Recovery Suite (password reset)
- Malwarebytes (malware removal)
- Recuva (file recovery)
- 7-Zip (file management)
- CPU-Z & HWMonitor (hardware diagnostics)

---

## Step 4: Use Key Tools (Examples)

### Reset a Forgotten Password

- Open **Lazesoft Password Recovery**.
- Select your Windows installation.
- Reset or remove user passwords.
- Reboot to log in.

### Recover Deleted Files

- Launch **Recuva**.
- Scan desired drives.
- Recover files to external storage.

---

## Step 5: Exit and Reboot

- Save all data and close tools.
- Remove the USB or DVD.
- Restart your PC.
- Optionally, re-enable **Secure Boot** in BIOS for security.

---

## Device-Specific Guides

- [HP Laptops & Desktops](devices/hp.md)
- [Dell Systems](devices/dell.md)
- [Lenovo Devices](devices/lenovo.md)
- [Acer Systems](devices/acer.md)
- [Custom / Whitebox PCs](devices/custom.md)

---

## OS-Specific Guides

- [Windows 7 & 8](os/windows7-8.md)
- [Windows 10](os/windows10.md)
- [Windows 11 (Beta)](os/windows11.md)

---

## FAQ

**Q: Can I use this with Windows 11?**  
Yes, most tools are compatible but some newer hardware may have limited support.

**Q: Is it safe?**  
Yes, tools are reputable and non-destructive unless you choose to modify system files.

**Q: Do I need admin access?**  
No, since you boot outside your installed OS.

---

## Contributing

Contributions welcome! Please:

- Open issues for bugs or questions.
- Submit pull requests for new device or OS guides.
- Suggest improvements to existing docs.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## License

This repository’s content is licensed under the MIT License. See [LICENSE](LICENSE).

---

## Additional Resources

- [Creating Bootable Media Guide](bootable-media.md)
- Images and screenshots in `/images/`
- Issue templates for easier bug reports

---

Made with 💻 by [4troDev](https://github.com/4troDev)  
Feel free to fork, contribute, or report issues!
