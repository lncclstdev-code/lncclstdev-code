# Hi, I'm Lance Celeste 👋

**Aspiring Embedded Systems Engineer** · Computer Engineering graduate, UP Diliman

Build. Solve. Learn. Grow.

I like the layer where software meets hardware: sensors, microcontrollers, wireless protocols and the firmware that ties them together. I graduated in Computer Engineering from the University of the Philippines Diliman (2026), and my capstone and side projects are all built around ESP32/ESP8266 systems, from sensor fusion to smart home integration. By day I work as a Systems Programmer at the City Government of Antipolo.

📍 Antipolo City, Philippines
🌐 Portfolio: [lncclstdev-code.github.io](https://lncclstdev-code.github.io/)
📫 Email: [lncclst.admin@gmail.com](mailto:lncclst.admin@gmail.com)
💼 LinkedIn: [lance-celeste](https://www.linkedin.com/in/lance-celeste/)

---

## 🔧 Embedded Projects

### 🔔 KLSG: Keyed Long-Lasting Smart Gateway
**ESP32-based smart doorbell with multi-sensor fusion** · Capstone, presented at NEECECON 2026

A tamper-aware doorbell that combines several sensors into one feature vector and uses **Mahalanobis distance** against a calibrated baseline to decide whether an event is normal or an anomaly.

- **Hardware:** ESP32, camera module, PIR sensor, accelerometer, fingerprint module, copper-pad and spring case-tamper contact, RGB LED status indicator
- **Firmware:** sensor acquisition, baseline calibration (mean vector and covariance matrix), on-device Mahalanobis distance computation, chi-square thresholds at 99.75%, 99.95% and 99.99% confidence to grade severity
- **Result:** accounting for variance and correlation between sensors reduced false positives compared with Euclidean distance; a 3-hour calibration baseline was the most stable across day and night
- **Benchmark:** 100% true positive rate in tampering detection against Ring Doorbell Pro, with a near-zero false positive rate on normal pedestrian activity
- **Integration:** live web dashboard (camera feed, sensor and Mahalanobis readouts, user management) and email alerts that identify known or unknown visitors
- **Maturity:** prototype assessed at Technology Readiness Level 6

`ESP32` `Sensor Fusion` `Mahalanobis Distance` `Anomaly Detection` `PIR` `Accelerometer` `Camera` `IoT`

### 🌉 ESP-NOW to ESPHome Bridge for Home Assistant
**Protocol bridge for low-power ESP devices**

Lets battery-friendly ESP devices join a smart home without each one needing a full Wi-Fi connection to the home network.

```
ESP-NOW devices  →  bridge/adapter  →  UART  →  ESPHome  →  Home Assistant
```

- Receives ESP-NOW packets wirelessly on the bridge, then forwards the data over a serial UART link
- Configures an ESPHome node to read the incoming UART data and expose it to Home Assistant dashboards and automations
- Translates between two protocols: wireless reception on one side, serial data exchange on the other

`ESP-NOW` `UART` `ESPHome` `Home Assistant` `ESP32`

---

## 🛠️ Embedded & Hardware Skills

![ESP32](https://img.shields.io/badge/ESP32%20/%20ESP8266-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&logo=platformio&logoColor=white)
![ESPHome](https://img.shields.io/badge/ESPHome-000000?style=for-the-badge&logo=esphome&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-18BCF2?style=for-the-badge&logo=homeassistant&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA%20/%20Vivado-FF8800?style=for-the-badge)
![Verilog](https://img.shields.io/badge/Verilog%20/%20HDL-5C8374?style=for-the-badge)

- Sensor integration, circuit design, prototyping and hardware debugging
- Wireless and serial protocols: ESP-NOW, UART, Wi-Fi, HTTP
- Analog and digital circuit design and simulation (LTSpice, MATLAB and Simulink)
- Digital systems design on FPGA with Verilog (AMD/Xilinx Vivado)

**Languages**
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Software, Networking & Tools**
![Linux](https://img.shields.io/badge/Linux%20/%20Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

TCP/IP, HTTP/HTTPS, DNS and routing fundamentals round out the networking side.

---

## 🎓 Background

- 🎓 **BS Computer Engineering**, University of the Philippines Diliman (UP EEEI), July 2026. Coursework includes Embedded Systems (Microprocessors and Microcontrollers), Digital Systems Design, Electronics Engineering (Analog and Digital Circuits) and Computer Networking
- 💻 **Systems Programmer**, City Government of Antipolo: VB.NET, Python (Django / FastAPI) and MySQL for government information systems
- 📜 Civil Service Eligibility (Professional Level), 2025
- 📜 Cisco: AI Fundamentals, 2026

---

## 🌱 Currently

- Looking for opportunities in embedded systems, firmware and IoT engineering
- Building more ESP32 projects and going deeper on low-power and wireless design

---

## 📫 Let's connect

Always happy to talk about embedded systems, IoT and hardware-software integration.

[![Portfolio](https://img.shields.io/badge/Portfolio-092635?style=for-the-badge&logo=githubpages&logoColor=9EC8B9)](https://lncclstdev-code.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lance-celeste/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lncclst.admin@gmail.com)
