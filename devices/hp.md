# 🖥️ HP Laptops & Desktops – Hiren’s Boot CD PE Guide

This guide explains how to boot and use **Hiren’s Boot CD PE x64 (2019)** on HP laptops and desktop PCs for system repair, recovery, and troubleshooting.

---

## 🔁 Accessing the Boot Menu (HP)

To boot from your Hiren’s Boot CD (DVD or USB):

1. **Shut down** your HP device completely.
2. Power it back on and **immediately press `Esc` repeatedly** until the **Startup Menu** appears.
3. Press `F9` to open the **Boot Device Options** menu.
4. Use the arrow keys to select your **USB drive** or **DVD drive**.
5. Press `Enter` to boot into Hiren’s Boot CD.

> 💡 If nothing shows up, double-check that the DVD/USB is bootable and properly inserted.

---

## 🧰 Recommended BIOS Settings (HP)

If your system doesn't detect the boot media, change these settings in BIOS:

1. Restart the computer and press `Esc`, then press `F10` for **BIOS Setup**.
2. Go to the **System Configuration** tab.
3. Set:
   - **Legacy Support** → **Enabled**
   - **Secure Boot** → **Disabled**
4. Press `F10` to **save and exit**.

> 📌 Some newer HP devices require you to confirm a PIN when disabling Secure Boot.

---

## 🛠️ Common Hiren’s Tools for HP Systems

Once booted into the PE environment, you’ll have access to these tools:

| Category           | Tool Example                | Use Case                              |
|--------------------|-----------------------------|----------------------------------------|
| Password Reset     | Lazesoft Password Recovery  | Reset forgotten Windows login password |
| Malware Removal    | Malwarebytes Portable       | Remove viruses and malware             |
| System Backup      | Macrium Reflect             | Create full drive image backups        |
| Partition Fixing   | AOMEI Partition Assistant   | Resize or repair broken partitions     |
| File Recovery      | Recuva / 7-Zip              | Recover or browse user files           |
| Hardware Check     | HWMonitor / CPU-Z           | Check temps, CPU info, health          |

---

## ✅ Tested HP Devices

- HP Pavilion x360 (Convertible)
- HP EliteBook G5 Series
- HP Envy Laptop
- HP Omen Gaming Desktop
- HP ProDesk Business Tower

---

## 🧑‍🔧 Troubleshooting

| Issue                                   | Solution                                                   |
|----------------------------------------|-------------------------------------------------------------|
| USB/DVD not showing in boot menu       | Reformat using Rufus and recheck BIOS boot settings         |
| PC boots straight to Windows           | Re-enter BIOS and reorder boot priority                     |
| Mouse/Keyboard not working in PE       | Try USB 2.0 ports or external devices (some drivers may be missing) |

---

## 🧼 After You're Done

1. Remove the Hiren’s DVD or USB.
2. Reboot your PC normally.
3. Optionally, re-enable **Secure Boot** and disable **Legacy Support** for security.

---

Have an issue or suggestion for HP-specific steps? [Open an issue](https://github.com/4troDev/repair-windows-with-hirens/issues) or contribute to this guide!
