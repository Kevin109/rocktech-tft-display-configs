# Linux Device Tree Configs for Rockchip SBCs with Rocktech TFT Displays

This repository is intended for embedded developers working with Rockchip-based SBCs such as RK3566, RK3568, PX30, and others. It provides ready-to-use Device Tree Source (DTS) configurations to support Rocktech TFT LCD modules in Linux and Android environments.

---

## 📋 Supported Displays

| Model       | Size  | Resolution | Interface | Notes |
|-------------|-------|------------|-----------|-------|
| [RK070CU01](https://www.rocktech.com.hk/lcd-product/rk070cu01/) | 7.0"  | 1024x600   | LVDS      | Standard 7" IPS panel |
| [RK050HR18](https://www.rocktech.com.hk/lcd-product/rk050hr18-ctg/) | 5.0"  | 800x480   | RGB      | High-resolution IPS with capacitive touch |
| [RK101HI34E](https://www.rocktech.com.hk/lcd-product/rk101hi34e-ct/) | 10.1"  | 1280x800   | LVDS      | High-Brightness IPS with capacitive touch |

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
