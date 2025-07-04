# Linux Device Tree Configs for Rockchip SBCs with Rocktech TFT Displays

This repository is intended for embedded developers working with Rockchip-based SBCs such as RK3566, RK3568, PX30, and others. It provides ready-to-use Device Tree Source (DTS) configurations to support Rocktech TFT LCD modules in Linux and Android environments.

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
For more display products and custom embedded solutions, visit 👉 [rocktech.com.hk](https://www.rocktech.com.hk/)
