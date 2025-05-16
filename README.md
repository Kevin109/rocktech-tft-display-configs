# Rocktech TFT Display Configuration Examples for Linux & Android Kernel

This repository provides Linux & Android device tree and configuration files for integrating **Rocktech TFT LCD modules** into embedded systems such as industrial panels, handheld devices, and smart terminals.

---

## 📋 Supported Displays

| Model       | Size  | Resolution | Interface | Notes |
|-------------|-------|------------|-----------|-------|
| [RK070CU01](https://www.rocktech.com.hk/lcd-product/rk070cu01/) | 7.0"  | 1024x600   | LVDS      | Standard 7" IPS panel |
| [RK050HR18](https://www.rocktech.com.hk/lcd-product/rk050hr18-ctg/) | 5.0"  | 800x480   | RGB      | High-resolution IPS with capacitive touch |

> 🔗 **Click model names above to view official product pages **

---

## 📁 Display Configuration Index

- **RK070CU01**
  - 📄 [`RK070CU01.dtsi`](RK070CU01/RK070CU01.dtsi)
  - 📘 [`README.md`](RK070CU01/README.md)
  - 🔧 Optional: `notes.txt` for kernel-specific notes (if needed)

- **RK050HR18**
  - 📄 [`RK050HR18.dtsi`](RK050HR18/RK050HR18.dtsi)
  - 📘 [`README.md`](RK050HR18/README.md)

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
