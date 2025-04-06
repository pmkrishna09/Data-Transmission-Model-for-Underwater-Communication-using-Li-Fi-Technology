# 📊🚢 Data Transmission Model for Underwater Communication using Li-Fi Technology 👨🏻‍💻🎯
Project on developing a data transmission model using Li-Fi

## 🔎📝 Overview / Project Description 
This project involves designing and implementing a **Li-Fi-based data transmission model** for **text, audio, and image transfer** in underwater environments. It serves as an alternative to RF signals for efficient **high-speed communication**. Underwater communication has traditionally relied on radio frequency (RF), acoustic waves, or sonar-based systems. However, these methods face high attenuation, limited bandwidth, and interference. This project explores an alternative approach using Li-Fi (Light Fidelity) technology for wireless underwater data transmission, enabling efficient transfer of text, audio, and images without relying on RF signals.

By leveraging LED-based light modulation, the system transmits digital information through optical signals, providing high-speed and energy-efficient communication in underwater environments.

### *WHAT is **Li-Fi** ?* 💡
Li-Fi (Light Fidelity) is a bidirectional wireless system that transmits data via LED or infrared light. It was first unveiled in 2011 and, unlike wifi, which uses radio frequency, LiFi technology only needs a light source with a chip to transmit an internet signal through light waves. LiFi technology can reach speeds of up to 224 Gbps. LiFi is a wireless technology that uses light to transmit data.
This is an extraordinary advance over today's wireless networks. LiFi multiplies the speed and bandwidth of wifi, 3G and 4G. The latter have a limited capacity and become saturated when the number of users surfing increases, causing them to crash, reducing speeds and even interrupting the connection.

The motivation behind utilizing Visible Light Communication, “Li-Fi technology can easily communicate through water rather than RF. Visible Light communication can easily penetrate through water. 
This Technology used for easy navigation for underwater exploration.”

---


## 🧩 Features 
✅ Optical Wireless Communication (Li-Fi): Uses LED light pulses to transmit data underwater.

✅ ESP32-CAM Integration: Captures and transmits real-time images.

✅ AUX-Based Audio Transmission: Facilitates underwater voice communication.

✅ Text Transmission & Display: Uses LCD screens and X-CTU software for textual communication.

✅ Alternative to RF & Acoustic Waves: Overcomes the limitations of RF waves in water.

---

## ⚙️ Components Used
#### 1️⃣ *Hardware Components*:
**ESP32-CAM:** For image processing and transmission

**High-power LEDs:** Modulates data as light pulses

**Photodiodes/LDRs:** Detects light signals and converts them back to digital data. Solar panels etc.

**Li-Fi transmitter and Receiver:** Converts electrical data into light pulses for transmission & Detects and converts received light pulses back into electrical data

**Microcontroller (Arduino/ESP32):** Controls the modulation and demodulation of signals

**Audio Transmission Module:** Facilitates voice communication

**LCD Display:** Visual output for transmitted text

#### 2️⃣ *Software & Algorithms*:

**Python (PyCharm)** for Image Processing

**X-CTU Software** for Text Transmission

**Arduino IDE** for Embedded Programming

MATLAB (optional) for signal analysis

---


## Working 👩🏻‍💻📓✍🏻💡
**WORKING OF THE SYSTEM** 

In a Li-Fi system, data takes a unique journey. The system consists of two main units: the transmitter unit, and the receiver unit.
The transmitter acts as a lighthouse, directing a beam of light towards the receiver. This light acts as the invisible carrier for the information being sent. Before embarking on its journey, the data undergoes a transformation at the transmitter. It arrives over a serial interface and is then converted into a format suitable for transmission, often involving specific encoding schemes. This encoded data is then used to modulate the intensity of the light source, typically LEDs.
These rapid variations in light intensity, imperceptible to the human eye, become the encoded information carried by the light beam. Upon reaching the receiver, these light signals are captured and converted back into electrical data, completing the data's voyage.
Li-Fi technology leverages the visible light spectrum to transmit data between devices. This essentially means that images can be transferred wirelessly using LEDs as the transmitter. Li-Fi operates by rapidly switching the intensity of the LED light, which is imperceptible to the human eye, to encode digital information. This encoded light is then received by a photodiode, converting it back into digital data for image reconstruction.
This project showcases a Li-Fi system that leverages light for wireless communication. It utilizes voice commands through a speech recognition algorithm to control machine movements. Text data transmission is also achieved through Li-Fi. Both the transmitter and receiver use LCD displays. 
Additionally, the system transmits images and videos, with the received content being displayed on a PC connected to the Li-Fi module. An Arduino UNO microcontroller acts as the central processing unit, transmitting commands via Li-Fi and processing received data.

**Li-Fi: Sending More Than Just Light Underwater**
Li-Fi isn't just for high-speed data in air! This technology can also be a game-changer for underwater communication. Let's see how it transmits different types of information:

--
**TEXT TRANSMISSION:**

Text Chat Under the Waves: Text messages can travel underwater with Li-Fi. First, the text is converted into a digital format, like a series of ones and zeros. Then, these digital bits are encoded by rapidly changing the intensity of light pulses from LEDs. Special sensors called photodiodes pick up these light variations at the receiving end, converting them back into digital information, allowing divers or underwater devices to exchange clear text messages.

--
**AUDIO TRANSMISSION:**

Underwater Conversations: Li-Fi can even transmit voices! Similar to text, the sound is first converted into a digital signal. Then, this digital information is used to control how bright the transmitted light beam becomes. By decoding these variations in light intensity, Li-Fi allows for clear voice communication between divers or underwater equipment.

--
**IMAGE TRANSMISSION:**

Seeing the Underwater World with Li-Fi: Imagine sending images and videos underwater! Li-Fi makes it possible. An image is divided into tiny squares called pixels, and each pixel's color information is used to create unique light pulses. Videos are simply a collection of images shown very quickly, so Li-Fi transmits them by breaking them down into individual frames and sending them one after another. At the receiving end, the information is reassembled, allowing for the reconstruction of clear images and videos. 

---
 
## ⚡📈For real-time industrial Marine Applications ⚓
Industrial marine applications require data transfer over long distances (several meters to kilometers).
Regular LEDs may work for small-scale lab models, but high-power LEDs or lasers are required for real-world deployment.
Collimated laser beams (focused light) reduce scattering and increase transmission range.
Marine industries need real-time video feeds, telemetry data, and remote operation capabilities.
Higher intensity LEDs can modulate at faster speeds, supporting high-bandwidth applications like HD video streaming.
Photodiodes & Avalanche Photodetectors (APDs) with high sensitivity are used for fast signal reception and decoding.
Underwater environments are dynamic, with waves, particles, and temperature variations affecting signal quality.
Adaptive beamforming & signal processing techniques are needed to correct distortions in real-time.
AI-based algorithms can optimize transmission angles and compensate for signal loss.
Industrial systems require continuous operation, often in deep-sea or offshore environments.
High-power LEDs & laser diodes are designed for efficiency, durability, and long operational life.
Energy-efficient power supplies & battery backup systems ensure uninterrupted operation.

### 🔹 Essential Equipment for Industrial Marine Li-Fi Systems

#### 1️⃣ *Transmission (Sender) Equipment*

✅ **High-Power Blue/Green LEDs or Laser Diodes (450-495 nm)** – For maximum underwater penetration

✅ **Modulation Circuit** – Converts digital data into light pulses

✅ **Embedded Controller (ESP32, Raspberry Pi, FPGA)** – Manages high-speed data transmission

✅ **Underwater Optical Lens System** – Focuses and directs the light beam efficiently

✅ **Power Management System** – Provides a stable energy source for deep-sea use

✅ **Data Source:** Can be a camera, microphone (for audio), or a sensor module

#### 2️⃣ *Reception (Receiver) Equipment*

✅ High-Sensitivity Photodiodes / Avalanche Photodetectors (APDs) – Converts light signals into electrical signals

✅ Optical Filters & Amplifiers – Enhances signal detection and minimizes noise

✅ Real-Time Signal Processing Unit (FPGA/AI-based Algorithm) – Improves data accuracy

✅ Display & Data Storage System – Outputs received text, images, and video



### **📡 Communication & Networking** 

- 📡 **Li-Fi Base Stations →** Placed strategically to ensure signal continuity

- 🗼 **Hybrid RF + Li-Fi System →** For seamless transition between air-water communication

- 📊 **Multiple Wavelength Transmission →** Improves range and reliability

- 🌐 **IoT Integration →** Sends collected data to cloud-based marine research platforms

---

## 🚀🚢 Applications & Use Cases

**🌊 Underwater Wireless Communication:** Enables data transmission without RF interference.

**🏗️ Industrial & Military Applications:** Can be used in defense, naval operations, and underwater robotics.

**🐠 Marine Research:** Supports data collection and monitoring of aquatic environments.

**🚢 Diver-to-Diver Communication:** Facilitates efficient information sharing for deep-sea divers.

🔹 **Autonomous Underwater Vehicles (AUVs) & Remotely Operated Vehicles (ROVs)**

Supports real-time video transmission and remote control for deep-sea exploration.
Enhances search and rescue missions by enabling high-speed underwater data exchange.

🔹 **Underwater Surveillance & Defense**

Offers secure and encrypted communication for naval operations and maritime defense.
Assists in monitoring and tracking underwater threats, such as unauthorized submarines and robotic drones.

---

<details>
<summary>📐Block Diagram</summary>

![Transmission Module Block Diagram](https://github.com/pmkrishna09/Data-Transmission-Model-for-Underwater-Communication-using-Li-Fi-Technology/blob/a668866a01e57694cf2d6d052a70049c0d89b591/Circuit%20Designs%20%26%20Data%20Flow/Transmission%20Module.jpg) 

![Receiving Module Block Diagram](https://github.com/pmkrishna09/Data-Transmission-Model-for-Underwater-Communication-using-Li-Fi-Technology/blob/a668866a01e57694cf2d6d052a70049c0d89b591/Circuit%20Designs%20%26%20Data%20Flow/Receiving%20Module.jpg) 


</details>



