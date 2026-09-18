# ESP32 Worm

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-Embedded- E7352C?style=for-the-badge&logo=espressif" alt="ESP32" />
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-Arduino%20%2F%20ESP--IDF-00599C?style=for-the-badge&logo=cplusplus" alt="C/C++" />
  <img src="https://img.shields.io/badge/Wi--Fi-802.11-2CA5E0?style=for-the-badge&logo=wifi" alt="Wi-Fi" />
  <img src="https://img.shields.io/badge/Bluetooth-BLE-0082FC?style=for-the-badge&logo=bluetooth" alt="Bluetooth" />
  <img src="https://img.shields.io/badge/Hardware-3D%20Printed%20Case-555555?style=for-the-badge&logo=3dprinting" alt="3D printed case" />
</p>

An ESP32-based portable wireless security research and experimentation platform. The project explores Wi-Fi and Bluetooth capabilities, raw packet transmission, sanity-check functions, embedded firmware, and a custom 3D-printed enclosure in a compact, Flipper Zero-inspired form factor.



## ✨ What's it does

- Provides a portable ESP32 platform for wireless security research
- Experiments with Wi-Fi and Bluetooth/BLE features supported by the selected ESP32 board
- Sends controlled raw packets for protocol development and laboratory testing
- Includes packet and input sanity checks to prevent malformed or unsafe test data
- Provides an extensible embedded firmware foundation for future tools
- Uses a compact, handheld design inspired by portable electronics test devices
- Includes a custom 3D-modelled casing for assembly and protection

## 🧩 Tech stack

### Hardware

- ESP32 development board
- Optional display, buttons, LEDs, buzzer, battery,
- Custom 3D-printed enclosure

### Firmware

- C and C++
- Reverse engineered Espressif ESP32 Wi-Fi sanity-check function using Ghidra
- ESP32 Wi-Fi and Bluetooth APIs
- Serial logging for control and debugging 
- Packet validation and sanity-check routines

### Design

- 3D enclosure design and modeling using Blender
- Modular internal mounting points
- Openings for the display, buttons, USB port, antenna, and status indicators


## 🔬 Research capabilities

The project can be used to study:

- Wi-Fi scanning and channel information in an authorized lab
- Bluetooth/BLE discovery and advertisement behavior
- Packet structure and protocol fields
- Raw packet construction and transmission in controlled environments
- Embedded input validation and fault handling
- Wireless troubleshooting and signal behavior
- Portable embedded-device interface design


## 📁 Project structure

```text
.
├── firmware/              # ESP32 application source and build configuration
├── wifi/                  # Authorized Wi-Fi research modules
├── bluetooth/             # Bluetooth/BLE research modules
├── common/                # Shared validation, logging, and utility code
├── hardware/              # Wiring diagrams, component notes, and BOM
├── 3d-model/              # Enclosure CAD files and exported 3D-print files
├── examples/              # Small, isolated example sketches
├── README.md              # Project documentation
└── LICENSE                # License information, when provided
```


## ⚠️ Limitations

- ESP32 radio features differ between ESP32 variants.
- Raw packet support is subject to chipset, firmware, driver, and regulatory limitations.
- Bluetooth Classic is not available on every ESP32 family member.
- Wireless experiments may affect nearby devices even when unintentionally configured.
<img width="960" height="1280" alt="WhatsApp Image 2026-02-12 at 11 21 17 PM(1)" src="https://github.com/user-attachments/assets/3f640052-8bb8-4e9f-acc0-7425a49471d7" />
<img width="960" height="1280" alt="WhatsApp Image 2026-02-12 at 11 21 20 PM" src="https://github.com/user-attachments/assets/8f7b48df-1b56-4ada-a7ca-c42c50c4d53b" />
<img width="1040" height="780" alt="WhatsApp Image 2025-12-11 at 9 56 44 PM" src="https://github.com/user-attachments/assets/c53abf92-7740-4584-9997-6be1adc7f630" />



## Authors

Built by [senuka hansira](https://github.com/senukahansira) , [paboda dasanayike](https://github.com/Paboda113)
