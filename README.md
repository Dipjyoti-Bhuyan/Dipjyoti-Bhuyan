# Hi, I'm Dipjyoti Bhuyan 👋
**Electronics & Telecommunication Engineering Undergraduate @ Assam Engineering College (2023–2027)**  
*Embedded Firmware Developer | Digital System Design & RTL Enthusiast | IoT Hardware*

Guwahati, Assam, India  
**Get in touch:** [Email](dipjyotibhuyan600@gmail.com) • [LinkedIn](https://linkedin.com/in/dipjyotibhuyan)

---

### Engineering & Technical Skillset
* **Core Languages:** Embedded C, C++, Verilog HDL, Python (pyserial, pygame, SQLite3)
* **Hardware Platforms:** ESP32 DevKit, Arty S7 (Xilinx Spartan-7 FPGA), Arduino, 8051 Architecture
* **Protocols & Interfaces:** UART, SPI, I2C, 1-Wire, GSM/GPRS (SIM800L AT Commands), MQTT
* **EDA & Design Tools:** Xilinx Vivado, NI Multisim, Git, Arduino IDE
* **Lab Instrumentation:** Digital Storage Oscilloscopes (DSO), RF Spectrum Analyzers, SWR Meters, Insulation Testers (Megger), Earth Grounding Testers

---

### Collaborative Engineering Projects & Field Training

*Most of my engineering builds are developed in multidisciplinary academic teams. I value clear communication, modular hardware-software separation, and end-to-end system reliability.*

#### [FPGA-Based Ultrasonic Radar System](https://github.com/Dipjyoti-Bhuyan/fpga-ultrasonic-radar)
* **Academic Mini-Project (Team of 6) | Guided by Prof. Niranjan Jyoti Borah**
* **The System:** Designed an autonomous active radar scanning system using an Arty S7 FPGA and an HC-SR04 ultrasonic sensor mounted on an SG90 servo motor.
* **My Contribution:** Synthesized synthesizable RTL modules in Verilog HDL for 50Hz PWM servo sweep; designed fixed-point shift arithmetic `((timer * 141) >> 13)` to compute distance without DSP divider blocks; implemented the 115,200-baud UART transmitter streaming 3-byte synchronization packets to a real-time Python/Pygame radar GUI.

#### [Fault-Tolerant Electronic Voting Machine (EVM)](https://github.com/Dipjyoti-Bhuyan/esp32-secure-evm)
* **Academic Hardware Project (Team of 6) | Guided by Prof. Swapna Bharali**
* **The System:** Built a dual-tier secure voting architecture physically isolating authorization (Host PC via SQLite) from anonymous ballot casting (ESP32).
* **My Contribution:** Programmed the 7-state finite state machine firmware with 50ms software debouncing and 500ms confirmation lock; implemented cryptographic SHA-256 hash chaining via mbedTLS on MicroSD storage with mirrored state backup to ESP32 Non-Volatile Storage (NVS) to ensure zero data loss during power outages.

#### [Solar-Powered Off-Grid IoT Data Logger](https://github.com/Dipjyoti-Bhuyan/solar-iot-telemetry-logger)
* **Summer Research Internship @ IIT Guwahati (Team of 4) | Supervised by Prof. Prabir Barooah**
* **The System:** Engineered an autonomous environmental telemetry station for subterranean cold storage monitoring in rural areas.
* **My Contribution:** Built the hardware telemetry node using ESP32, an 18V solar panel with MPPT charging, and 18650 Li-ion battery arrays; integrated two DS18B20 1-Wire sensors and DHT22 modules; programmed the SIM800L GPRS module using AT commands to upload batched JSON packets every 60 seconds to ThingSpeak cloud.

#### Northeast Frontier Railway (NFR) Field Engineering Training
* **Industrial Internship (Team of 6) | Signal & Telecommunication Department, Maligaon**
* Completed comprehensive field studies on mission-critical public infrastructure: line-of-sight (LOS) microwave link alignment (1.4–7 GHz), -48V DC digital telephone switching exchanges (FlexiCom series) on KRONE distribution frames, and online double-conversion UPS battery banks with grounding pit resistance testing (< 1.0 Ω).

### What I’m Working on Now
* Final Year Capstone: **ML-Assisted Condition Monitoring System** — Deploying TinyML (TensorFlow Lite Micro) on ESP32 to detect mechanical unbalance and bearing wear from 3-axis vibration and current signatures.
