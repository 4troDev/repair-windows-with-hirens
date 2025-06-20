# Creating Bootable USB or DVD for Hiren’s Boot CD PE (2019)

This guide explains how to create a bootable USB flash drive or DVD from the Hiren’s Boot CD PE ISO file.

---

## Using Rufus (Windows)

1. Download and launch [Rufus](https://rufus.ie/).
2. Insert a USB flash drive (at least 4 GB). **Warning: This will erase all data on the drive.**
3. In Rufus, select your USB device.
4. Click **SELECT** and choose the Hiren’s Boot CD PE ISO file.
5. Choose partition scheme based on your PC’s firmware:
   - For modern UEFI systems:  
     - Partition scheme: **GPT**  
     - Target system: **UEFI (non-CSM)**
   - For older BIOS/Legacy systems:  
     - Partition scheme: **MBR**  
     - Target system: **BIOS (or UEFI-CSM)**
6. Select the file system:
   - **FAT32** for UEFI (recommended)  
   - **NTFS** for Legacy BIOS
7. Click **START** to create the bootable USB.
8. Accept any prompts and wait until complete.

---

## Creating a Bootable DVD (Windows)

1. Insert a blank DVD into your DVD burner.
2. Right-click the Hiren’s Boot CD PE ISO file and select **Burn disc image**.
3. Choose your DVD drive and click **Burn**.
4. Wait for the burning process to finish.

---

## Booting from USB/DVD

- Insert the bootable media into your target PC.
- Power on and enter the **Boot Menu** (keys vary by manufacturer, e.g., `F12`, `F9`, `Esc`).
- Select the USB or DVD device to boot.
- If booting fails, check BIOS/UEFI settings:
  - Disable **Secure Boot**
  - Enable **Legacy Boot** or **CSM** if needed
  - Adjust boot priority to prioritize USB/DVD

---

If you encounter issues creating or booting from media, feel free to open an issue in this repository.
