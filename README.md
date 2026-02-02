# ASUS Vivobook X441U Hackintosh (OpenCore)

![Platform](https://img.shields.io/badge/Platform-macOS-lightgrey.svg)
![OpenCore](https://img.shields.io/badge/OpenCore-1.0.1-blue.svg)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)

A highly optimized and stable OpenCore EFI for the **ASUS X441U** series. This configuration has been battle-tested for daily productivity.

## 💻 System Specifications
| Component | Details |
| :--- | :--- |
| **Model** | ASUS Vivobook X441UB |
| **Processor** | Intel® Core™ i3 6006u|
| **Graphics** | Intel® HD Graphics 520 / 620 |
| **dGPU** | NVIDIA GeForce (Disabled via SSDT for power efficiency) |
| **Network** | Intel® Dual Band Wireless-AC 7260 |
| **RAM** | 12GB |
| **Audio** | Realtek ALC255 (Layout-ID: 21) |
| **Bootloader** | OpenCore |
| **Current OS** | Sonoma |

---

## ✅ What's Working
- [x] **Graphics Acceleration (QE/CI)** - Full smooth transparency.
- [x] **CPU Power Management** - Optimized for mobile efficiency.
- [x] **Battery Indicator** - Accurate percentage and charging status.
- [x] **WiFi & Bluetooth** - Native feel with Intel AC 7260 (AirportItlwm).
- [x] **Audio & Microphone** - Internal speakers, headphones, and mic working.
- [x] **Sleep & Wake** - Fixed (No instant wake or black screen).
- [x] **Trackpad & Keyboard** - Multi-touch gestures and brightness/volume keys.
- [x] **USB Ports** - Fully mapped (USB 3.0 & Type-C).

## ❌ What's Not Working
- **NVIDIA dGPU** - macOS does not support Optimus technology. Disabled to save battery and reduce heat.

## ⚠️ Disclaimer
This project is for educational purposes. I am not responsible for any damage to your hardware. Always back up your data before modifying your EFI partition.

---
