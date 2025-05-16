# Rocktech TFT Display Configuration Examples

This repository provides Linux & Android device tree and configuration files for integrating Rocktech TFT LCD modules into embedded systems.

Currently supported displays:

| Model       | Size  | Resolution | Interface | Notes |
|-------------|-------|------------|-----------|-------|
| [RK070CU01](./RK070CU01) | 7.0"  | 1024x600   | LVDS      | Standard 7" IPS panel |
| [RK050HR18](./RK050HR18) | 5.0"  | 720x1280   | MIPI      | High-resolution IPS with capacitive touch |

---

## 📁 Folder Structure

Each folder contains:

- `README.md` – Basic specs and connection info  
- `*.dts` / `*.dtsi` – Linux/Android device tree snippet  
- `notes.txt` – Optional usage notes or kernel version requirements
