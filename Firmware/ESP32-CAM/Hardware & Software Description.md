# 🧠 Role of ESP32

**You can check the complete details of ESP32 (Credits: https://www.waveshare.com/wiki/ESP32-CAM)**

**ESP32-CAM**
ESP32-CAM is a low-cost ESP32-based development board with onboard camera, small in size. It is an ideal solution for IoT application, prototypes constructions and DIY projects.
The board integrates WiFi, traditional Bluetooth and low power BLE , with 2 high- performance 32-bit LX6 CPUs. It adopts 7-stage pipeline architecture, on-chip sensor, Hall sensor, temperature sensor and so on, and its main frequency adjustment ranges from 80MHz to 240MHz.
Fully compliant with WiFi 802.11b/g/n/e/i and Bluetooth 4.2 standards, it can be used as a master mode to build an independent network controller, or as a slave to other host MCUs to add networking capabilities to existing devices.
ESP32-CAM can be widely used in various IoT applications. It is suitable for home smart devices, industrial wireless control, wireless monitoring, QR wireless identification, wireless positioning system signals and other IoT applications. It is an ideal solution for IoT applications.

---
The **ESP32-CAM** is a compact and powerful development board that combines **Wi-Fi**, **Bluetooth**, and a **camera module**, making it ideal for projects that require **wireless image/video transmission, real-time monitoring**, and **IoT functionality**.  

In your **Data Transmission Model for Underwater Communication using Li-Fi**, the **ESP32-CAM** plays a crucial role in **image processing, encoding, and wireless data transfer**.

## 📸 **Role of ESP32-CAM in the Project**

| **Functionality** | **Explanation** |
|-------------------|-----------------|
| 🎥 **Image Capture** | Captures real-time visuals using the **OV2640 camera module** integrated with the board. |
| 📡 **Wi-Fi Communication** | Supports **wireless transmission** of captured images to servers or other devices over a **Wi-Fi network**. |
| 🔄 **Data Encoding** | Converts images into a suitable format (JPEG/BMP) and prepares them for **optical transmission via LEDs**. |
| 🔌 **System Integration** | Acts as a bridge between the **camera sensor**, **Arduino**, and **Li-Fi transmission module** for seamless image transfer. |
| 🧠 **Local Processing** | Processes camera frames locally and performs pre-processing tasks (compression, formatting). |
| ⚙️ **Embedded RTOS Support** | Supports **FreeRTOS**, enabling multitasking for efficient operation in real-time environments. |
| 🔧 **IoT-Ready** | Its built-in Wi-Fi and low power consumption make it suitable for **marine IoT** applications like **remote monitoring** or **autonomous vehicles**. |
| 🔍 **Future Potential** | Can be used to implement **computer vision**, **motion detection**, or **ML models** (tinyML) for smart decision-making in underwater environments. |

---

### 🌊 In Underwater Communication Context

- **Above Water**: Captures and sends visuals to the Arduino for **optical transmission**.
- **Underwater Simulation**: Images can be transmitted using **LED-based Li-Fi** and received using a photodiode/LDR + microcontroller at the other end.

---


## ✨ **ESP32-CAM Features**

| **Feature**                                | **Details**                                                  |
|--------------------------------------------|--------------------------------------------------------------|
| Clock Speed                                | Up to 160 MHz                                                |
| Processing Power                           | Up to 600 DMIPS                                              |
| Built-in RAM                               | 520 KB SRAM                                                  |
| External RAM                               | 4 MB PSRAM                                                   |
| Interfaces Supported                       | UART, SPI, I2C, PWM, ADC, DAC                                |
| Camera Support                             | OV2640 and OV7670                                            |
| Built-in Components                        | Flash lamp                                                   |
| Connectivity                               | Wi-Fi upload, Bluetooth 4.2 (BR/EDR, BLE)                    |
| TF Card Support                            | Yes (up to 4GB)                                              |
| Sleep Modes                                | Multiple (Deep, Modem, Light)                                |
| Embedded Software Support                  | LwIP stack, FreeRTOS                                         |
| Wi-Fi Modes                                | STA / AP / STA+AP                                            |
| Smart Config Support                       | Yes (AirKiss supported)                                      |
| Firmware Upgrade Support                   | FOTA (local and remote upgrades)                             |

---

### ⚙️ **ESP32-CAM Specifications**

| **Specification**                    | **Details**                                                   |
|--------------------------------------|---------------------------------------------------------------|
| SPI Flash                            | 32 Mbit                                                       |
| RAM                                  | 520 KB (internal) + 4 MB PSRAM (external)                     |
| Dimensions                           | 27 × 40.5 × 4.5 mm (±0.2 mm)                                  |
| Bluetooth                            | Bluetooth 4.2 BR/EDR and BLE                                  |
| Wi-Fi Standard                       | IEEE 802.11 b/g/n/e/i                                         |
| Interface Support                    | UART, SPI, I2C, PWM                                           |
| TF Card Support                      | Up to 4 GB                                                    |
| I/O Ports                            | 9                                                             |
| Serial Baud Rate                     | 115200 bps (default)                                          |
| Image Output Format                  | JPEG (OV2640), BMP, Grayscale                                 |
| Frequency Range                      | 2412–2484 MHz                                                 |
| Antenna                              | PCB onboard, 2 dBi gain                                       |
| Transmit Power                       | b: 17±2 dBm, g: 14±2 dBm, n: 13±2 dBm                         |
| Receive Sensitivity                  | CCK 1 Mbps: -90 dBm, MCS7: -67 dBm                            |
| Power Consumption                    | Flash off: 180mA, Flash max: 310mA, Sleep: 6–20mA             |
| Security                             | WPA/WPA2/WPA2-Enterprise/WPS                                  |
| Power Supply                         | 5V                                                            |
| Operating Temp                       | -20°C to +85°C                                                |
| Storage Conditions                   | -40°C to +90°C, < 90% RH                                      |
| Weight                               | 10g                                                           |

---

### 💻 **Software & Programming**

| **Component**          | **Description**                                                       |
|------------------------|-----------------------------------------------------------------------|
| Programming Language   | C / C++                                                               |
| Arduino IDE            | Most common environment for coding ESP32-CAM                          |
| ESP-IDF                | Official development framework by Espressif                           |
| Libraries              | ESP32 Board Package + Camera & Wi-Fi Libraries                        |
| Sample Examples        | Includes sketches for camera streaming, web server, motion detection |
| Platform Support       | Arduino IDE (Windows, macOS, Linux)                                   |
| Open Source            | Fully open-source hardware and software                               |

---

