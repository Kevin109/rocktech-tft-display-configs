# Linux Device Tree Configs for Rockchip SBCs with Rocktech TFT Displays

This repository provides pre-tested Device Tree Source (DTS) configurations for integrating Rocktech TFT LCD display modules with popular Rockchip-based Single Board Computers (SBCs), including RK3566, RK3568, PX30, and others. It aims to help embedded Linux and Android developers quickly bring up display interfaces in custom or commercial projects.

## ✨ Features

- 📌 Ready-to-use `.dts` and `.dtsi` configuration files
- 🧩 Supports Rocktech TFT LCD modules like RK050HR18, RK070CU01
- 🛠️ Compatible with Android and Linux kernel (4.19/5.10/5.15)
- ✅ Validated on PX30, RK3566 SBC platforms
- 🔧 Easily adaptable to custom SBC designs

---

## 📚 Use Case: Rapid Prototyping

When developing a new product with a Rockchip SoC and TFT LCD, our team typically:
1. Selects a matching Rocktech TFT panel
2. Creates a breakout board for quick bring-up
3. Uses these DTS configs to verify display output before finalizing the SBC design

---

## 📋 Supported Displays

| Model       | Size  | Resolution | Interface |
|-------------|-------|------------|-----------|
| [RK070CU01](RK070CU01/) | 7.0"  | 1024x600   | LVDS      | 
| [RK050HR18](RK050HR18/) | 5.0"  | 800x480   | RGB      | 
| [RK101HI34E](RK101HI34E/) | 10.1"  | 1280x800   | LVDS      |
| [RK050BHD335](RK050BHD335/) | 5.0"  | 720x1280   | MIPI      |
| [RK035SHV235](RK035SHV235/) | 3.5"  | 320x480   | MIPI      |

> 🔗 **Click model names above to view official product pages **

---

## 📁 Display Configuration Index

### 📺 Supported Display Configuration Index

- **RK070CU01**  
  A standard 7” IPS TFT display suitable for HMI panels and industrial user interfaces. Widely used in embedded projects that require a balance between resolution, visibility, and affordability.  
  - 📄 [`RK070CU01.dtsi`](RK070CU01/RK070CU01.dtsi)  
  - 📘 [`README.md`](RK070CU01/README.md)

- **RK050HR18**  
  A high-resolution 5.0” IPS panel with capacitive touch, commonly used in compact handheld or wall-mounted smart terminals.  
  - 📄 [`RK050HR18.dtsi`](RK050HR18/RK050HR18.dtsi)  
  - 📘 [`README.md`](RK050HR18/README.md)

- **RK101HI34E**  
  A 10.1” high-brightness IPS TFT display, ideal for applications needing excellent sunlight readability and a wide viewing angle. Suitable for industrial HMIs and automotive use.  
  - 📄 [`RK101HI34E.dtsi`](RK101HI34E/RK101HI34E.dtsi)  
  - 📘 [`README.md`](RK101HI34E/README.md)


- **RK050HR18**  
  A high-resolution 5.0” IPS panel with capacitive touch, commonly used in compact handheld or wall-mounted smart terminals.  
  - 📄 [`RK050BHD335.dtsi`](RK050BHD335/RK050BHD335.dts)  
  - 📘 [`README.md`](RK050BHD335/README.md)


- **RK035SHV235**  
  A 3.5” TFT panel with capacitive touch, commonly used in compact handheld or wall-mounted smart terminals.  
  - 📄 [`RK035SHV235_mipi_320x480.dtsi](RK035SHV235/RK035SHV235_mipi_320x480.dtsi)  

---

## 📂 Folder Structure

Each display folder typically includes:

- `README.md` – Basic electrical/mechanical info and usage notes
- `*.dts` / `*.dtsi` – Linux/Android device tree include files
- `notes.txt` – (Optional) Setup tips, BSP quirks, or kernel compatibility notes

---

## 🌐 About Rocktech
---

We provide complete custom embedded solutions and industrial display products:

- 🧩 [Custom Embedded Systems](https://www.rocktech.com.hk/custom-embedded-system/)
- 💡 [Industrial TFT Display Modules](https://www.rocktech.com.hk/industrial-tft-displays/)
- 🌞 [High Brightness Displays for Outdoor Use](https://www.rocktech.com.hk/high-brightness-displays/)
- 🖥️ [Android/Linux Embedded SBCs](https://www.rocktech.com.hk/embedded-single-board-computers/)

For more details, visit 👉 [rocktech.com.hk](https://www.rocktech.com.hk/)

📂 View more configs and documentation on  
👉 [GitHub @Kevin109](https://github.com/Kevin109)  
👉 [Kevin's GitHub Pages](https://kevin109.github.io)
