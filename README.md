<h1 align="center">Hi there, I'm Aadhitya G. 👋</h1>
<h3 align="center">Embedded Systems Engineer | Hardware Security Researcher | IoT Developer</h3>

<p align="center">
  <a href="https://linkedin.com/in/aadhitya-g" target="blank"><img align="center" src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## 👨‍🎓 About Me

I am a passionate Electronics & Communication Engineer specializing in bare-metal programming, hardware-software co-design, and hardware security. I thrive on building deterministic, real-time systems and bridging them with modern IoT frameworks. 

* 🎓 **Incoming Graduate Student:** Pursuing an M.Sc. in **Embedded Electronic System Design** at **Chalmers University of Technology** *(Autumn 2026 - Spring 2028)* as an **IPOET Scholar**.
* 🎓 **Undergraduate:** Final-year B.E. ECE student at SRM Easwari Engineering College (CGPA: 9.3/10).
* 🔬 **Research Focus:** Hardware security, specifically side-channel analysis and hardware Trojan detection in cryptographic algorithms (AES-256, DES, ASCON).
* ⚙️ **Current Obsession:** Writing deterministic bare-metal C firmware, RTOS implementation, and designing low-power IoT architectures.

---

## 🛠️ Tech Stack & Tools

**Languages:** ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Verilog](https://img.shields.io/badge/Verilog-000000?style=for-the-badge&logo=fpga&logoColor=white)

**Microcontrollers & Architectures:** ![ARM7](https://img.shields.io/badge/ARM7_(LPC2129)-0091BD?style=for-the-badge&logo=arm&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white) ![ESP32/8266](https://img.shields.io/badge/ESP32%20/%208266-E7352C?style=for-the-badge&logo=espressif&logoColor=white) ![MSP430](https://img.shields.io/badge/TI_MSP430-CC0000?style=for-the-badge&logo=texas-instruments&logoColor=white) ![RP2040](https://img.shields.io/badge/Raspberry_Pi_Pico-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white)

**Software & Toolchains:** ![Keil](https://img.shields.io/badge/Keil_µVision-0055A5?style=for-the-badge) ![Altium](https://img.shields.io/badge/Altium_Designer-A5A5A5?style=for-the-badge&logo=altium&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314CB6?style=for-the-badge&logo=kicad&logoColor=white) ![Vivado](https://img.shields.io/badge/Xilinx_Vivado-000000?style=for-the-badge&logo=xilinx&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

**IoT & Cloud:** ![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white) ![Arduino Cloud](https://img.shields.io/badge/Arduino_IoT_Cloud-00979D?style=for-the-badge&logo=arduino&logoColor=white) ![Blynk](https://img.shields.io/badge/Blynk_IoT-1DB954?style=for-the-badge) 

---

## Featured Projects

### Smartlink: Advanced IoT-Based Smart Device Automation
*Designed a master-slave IoT architecture integrating cloud control with bare-metal hardware execution.*
* **Hardware:** LPC2129 (ARM7 Master), ESP8266 (Network Coprocessor), 4-Channel AC Relay.
* **Tech:** Bare-metal C, Keil µVision, UART (Hardware & SoftwareSerial), MQTT, Arduino IoT Cloud.
* **Highlights:** Achieved deterministic local hardware execution by offloading the TCP/IP stack to the ESP8266, allowing robust remote actuation of 230V AC loads via custom UART callback logic.

### Hardware Trojan Detection in Cryptographic Cores
*Research project analyzing synthesis-masking effects to identify optimal ciphers for Trojan detection.*
* **Tech:** Xilinx Vivado, Verilog HDL, Python (Data Analysis).
* **Highlights:** Implemented a custom AES-256 engine and analyzed 646 Vivado synthesis nets. Achieved a **93% detection accuracy** using power analysis and switching activity profiling (validated via Z-score, SNR, and KL Divergence). 

### ESP32-Based Medical Health Monitoring System (Remedy Generator)
*An end-to-end medical sensor node with remote telemetry and AI integrations.*
* **Tech:** ESP32, MAX30102 (SpO2/HR), DHT22, Python (OpenCV), MQTT.
* **Highlights:** Integrated real-time hardware vitals with laptop-based OpenCV facial mood detection, achieving a 487ms end-to-end cloud latency via an MQTT broker to a Blynk dashboard.

---

## Professional Experience

* **Advanced Embedded System Design Intern | Vector India** *(Dec 2025 - Jun 2026)*
  * Developed ARM7 (LPC2114) and 8051 firmware focusing on UART/SPI/I2C drivers.
  * Implemented RT-Linux RT-PREEMPT patches for deterministic real-time task scheduling.
* **Embedded Systems and Industrial Automation Intern | Taras Systems and Solutions** *(Jun - Dec 2025)*
  * Developed bare-metal MSP430 firmware achieving <1µA idle current (LPM3) and wrote STM32F4 HAL drivers.
  * Redesigned a fire alarm system using SX1278 LoRa (868MHz, 5km+ range) for remote sensor telemetry.
* **CNS Intern | Airports Authority of India (AAI)** *(Dec 2024)*
  * Gained hands-on insight into safety-critical air traffic surveillance, VHF radio communications, ILS, and radar transponder encoding at Chennai Airport.
* **Technical Intern | Integral Coach Factory (Indian Railways)** *(Jul 2024)*
  * Studied Siemens S7-300 PLC ladder logic, SCADA HMI, and PROFIBUS industrial Ethernet communication for automated welding robots.

---

## Publications & Research

* **Scopus-Index Published Paper:** *"Dual-Metric Detection of Synthesis-Masked Hardware Trojans in AES-256: Correlating Power Signatures with Switching Activity"* — Scopus-indexed journal (IROTCSST Journal) (April 2026).
* **Conference Abstract:** *"Detection of Hardware Trojans in AES-256 Cores using Power and Switching Analysis"* — ITDECC-2025 (Sept 2025).
* **Conference Paper:** *"Adapt an RTOS to RISC-V for Safety-Critical Embedded Applications"* — ICMICC'25 (April 2025).
* **Conference Paper:** *"IoT Based Fire Alarm using Raspberry Pi Pico W"* — ICMICC'25 (April 2025).

---

## Honors, Awards & Community

* **NPTEL Honors (IIT Madras & Roorkee):** Top 1% Performer in Entrepreneurship; Top 5% Performer in Leadership & Team Effectiveness.
* **Mentorship:** Organized and conducted the *"Texas Instruments Microcontrollers and Energia IDE Programming"* workshop for 30+ first-year ECE students.
* **Memberships:** Active member of IETE & ISTE; Volunteer for Youth Red Cross (YRC) and Rotaract Club.

---
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Aadhitya-12007&show_icons=true&theme=radical" alt="Aadhitya's GitHub Stats" />
</p>
