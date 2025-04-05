# 🧠 Role of Arduino UNO in this project

In the **Data Transmission Model for Underwater Communication using Li-Fi**, the **Arduino UNO** plays a vital role in handling **signal processing, hardware control, and communication interfacing**.

The **Arduino UNO** acts as the **controller and communicator** in this project. It interfaces between hardware components like **LEDs, photodiodes, LCDs**, and potentially the **audio and text transmission modules**.

---

The Arduino Uno is a popular, open-source microcontroller board based on the ATmega328P, featuring 14 digital and 6 analog pins, a USB connection, and a power jack, all controlled by the Arduino IDE software. 

### 💻 **Hardware Features**

| **Component**            | **Specification**                  |
|--------------------------|------------------------------------|
| Microcontroller          | ATmega328P                         |
| Digital I/O Pins         | 14 (6 can be used as PWM outputs)  |
| Analog Input Pins        | 6                                  |
| Operating Voltage        | 5V                                 |
| Input Voltage (Recommended) | 7–12V                          |
| Input Voltage (Limits)   | 6–20V                              |
| DC Current per I/O Pin   | 20 mA                              |
| Flash Memory             | 32 KB                              |
| SRAM                     | 2 KB                               |
| EEPROM                   | 1 KB                               |
| Clock Speed              | 16 MHz                             |
| USB Connection           | For programming and power          |
| Power Jack               | For external power supply          |
| Reset Button             | To restart the board               |
| ICSP Header              | For in-circuit programming         |


### 💻 **Software Features**

| **Component**          | **Description**                                       |
|------------------------|-------------------------------------------------------|
| Arduino IDE            | IDE for writing, compiling, and uploading code       |
| Programming Language   | Based on C and C++                                    |
| Sketch                 | The term for Arduino programs                         |
| Sketchbook             | Directory where sketches (programs) are saved         |
| Libraries              | Add-on code packages to extend functionality          |
| Serial Monitor         | Tool to view and debug serial data from the board     |
| Cross-Platform         | Compatible with Windows, macOS, and Linux             |
| Open Source            | Hardware and software are modifiable and community-driven |

---

### 🔌 **Key Responsibilities:**

| **Function**                     | **Description**                                                                 |
|----------------------------------|---------------------------------------------------------------------------------|
| 📤 **Data Encoding & Modulation**   | Controls the **LED intensity or blinking** to encode data (text/audio/image).  |
| 📥 **Signal Reception**            | Reads signals from the **photodiode or light sensor** and decodes them.        |
| 📟 **Text Display Control**        | Manages output to the **LCD screen**, displaying received text data.           |
| 🔁 **I/O Coordination**            | Handles **digital and analog inputs/outputs** to synchronize hardware modules. |
| 🧪 **Testing & Calibration**       | Helps test signal quality, **adjust thresholds**, and optimize range.          |
| 🔄 **Real-Time Processing**        | Works in loop to **send and receive continuously**, ensuring smooth communication. |
| 🛠️ **System Integration**          | Bridges communication between **ESP32-CAM**, audio devices, and text modules. |

---

### 🧪 In Practical Use:

- When sending data:
  - Arduino drives **LEDs** (visible light) to represent data in **on/off patterns**.
- When receiving:
  - It reads input from **LDR or photodiode** to interpret signal changes.
- When processing:
  - It can **filter noise**, buffer data, and display it on an **LCD** or forward it to a serial monitor.

---

### 🔭 **Optional Enhancements with Arduino UNO:**
- Add **adaptive brightness control** for varying underwater light conditions.
- Integrate **Real-Time Clock (RTC)** for time-stamping data.
- Add **EEPROM logging** for offline data storage.



