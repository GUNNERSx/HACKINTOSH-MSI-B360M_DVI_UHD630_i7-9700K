# 🍎 HACKINTOSH — MSI B360M PRO-VD + Intel i7-9700K  
🎯 [MSI B360M PRO-VD Motherboard Specs](https://www.msi.com/Motherboard/B360M-PRO-VD/Specification)  
💻 Mac Model: iMac19,1 (2019 Edition)  

![Hackintosh Build](https://github.com/GUNNERSx/HACKINTOSH-MSI-B360M_DVI_UHD630_i7-9700K/blob/main/Pic.jpg)  

---

## 🛠️ System Configuration  

| 💻 **Model**     | 🖥️ iMac19,1 (2019)         | 🧩 **macOS Version** | Ventura 13.7           |
|------------------|-----------------------------|----------------------|-------------------------|
| 🧠 Processor      | Intel Core i7-9700K          | 🎨 Graphics           | Sapphire RX580 8GB   |
| 🧵 RAM            | G.Skill DDR4 2667MHz 8GB x2  | 💾 Storage            | WD Black SN770       |
| 🖥️ Motherboard    | MSI B360M PRO-VD             | 🧬 BIOS Revision       | AMI BIOS 7B53v1C    |
| 🌐 Network        | Realtek RTL8111H Gigabit     | 🔊 Audio              | Realtek ALC887       |
| 📶 Wifi           | Fenvi wifi intel 6E AX210    | 🖼️ Monitor            | Zowie XL2411P 144Hz  |


![Specs](https://github.com/GUNNERSx/HACKINTOSH-MSI-B360M_DVI_UHD630_i7-9700K/blob/main/specs.jpg)  

---

## ⚙️ OpenCore + reFind Bootloader  

🔧 **Version**: [OpenCore 1.0.5](https://github.com/acidanthera/OpenCorePkg/releases)  
🚀 **Bootloader**: [reFind](https://www.rodsbooks.com/refind/)  
![reFind Boot Manager](https://github.com/GUNNERSx/HACKINTOSH-MSI-B360M_DVI_UHD630_i7-9700K/blob/main/reFind.jpg)  

💡 **TRIPLE BOOT**  
- 🍏 macOS Sequoia 15.xx  
- 🪟 Windows 11  
- 🐧 Linux Mint 22  

---

## ✅ Working Components  

| 🔧 **Component**       | 📝 **Status & Notes**                                                                |
|------------------------|--------------------------------------------------------------------------------------|
| 🎮 GPU                | [Sapphire RX580 Nitro+ Special Edition](https://www.techpowerup.com/gpu-specs/sapphire-nitro-rx-580-special-edition.b4912) ✅ |
| 📶 Wi-Fi              | Intel AX210 using AirportItlwm — Fully supported ✅                                   |
| 📡 Bluetooth          | IntelBluetoothFirmware — Stable ✅                                                   |
| 🌐 Ethernet           | Realtek RTL8111H — Works with [driver](https://github.com/Mieze/RTL8111_driver_for_OS_X) ✅ |
| 🔊 Audio              | Speaker & Mic — Functional ✅                                                        |
| 🖱️ Input Devices      | Keyboard & Mouse — Fully responsive ✅                                                |
| 🔌 USB Ports          | Mapped & working ✅ ([USBToolBox](https://github.com/USBToolBox/tool))               |
| 🌙 Sleep/Wake         | Working ✅ *(Requires manual display reactivation)*                                  |

---

## 🧱 Post Installation  

🛠️ Platform ID was generated randomly — use:  
- 🔧 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)  
- 🧰 [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases)  

🧬 ACPI Tables:  
- Built using [Corpnewt SSDTTime](https://github.com/corpnewt/SSDTTime) on Windows 11  
- Default tables from [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#acpi) included in `EFI/OC/ACPI/Back`

---

## 🙌 Credits  

- Huge shout-out to [Matcha-xiaobin](https://github.com/Matcha-xiaobin/EFI-B360m_d2v_OpenCore_dvi_uhd630) for the DVI patch!  
- Thanks to all developers & maintainers contributing to the Hackintosh community 🎉  

---

🖋️ _Built for performance, crafted with care. This guide is meant to help others replicate a stable Hackintosh on MSI's B360M platform. Feel free to share, fork, or suggest improvements!_
