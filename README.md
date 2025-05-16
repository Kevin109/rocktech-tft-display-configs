# Rocktech TFT Display Configuration Examples

This repository provides Linux & Android device tree and configuration files for integrating Rocktech TFT LCD modules into embedded systems.

Currently supported displays:

| Model       | Size  | Resolution | Interface | Notes |
|-------------|-------|------------|-----------|-------|
| [RK070CU01](https://www.rocktech.com.hk/lcd-product/rk070cu01/) | 7.0"  | 1024x600   | LVDS      | Standard 7" IPS panel |
| [RK050HR18](https://www.rocktech.com.hk/lcd-product/rk050hr18-ctg/) | 5.0"  | 800x480   | RGB      | High-resolution IPS with capacitive touch |


## Quick Access

- **RK070CU01**
  - 📄 [`RK070CU01.dtsi`](RK070CU01/RK070CU01.dtsi)

- **RK050HR18**
  - 📄 [`RK050HR18.dtsi`](RK050HR18/RK050HR18.dtsi)

---

## 📁 Folder Structure

Each folder contains:

- `README.md` – Basic specs and connection info  
- `*.dts` / `*.dtsi` – Linux/Android device tree snippet  
- `notes.txt` – Optional usage notes or kernel version requirements
