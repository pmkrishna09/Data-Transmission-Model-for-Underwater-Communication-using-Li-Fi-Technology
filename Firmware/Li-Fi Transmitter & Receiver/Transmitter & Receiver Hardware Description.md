# 📡 Li-Fi Transmitter & Receiver

You can check complete detailes on Li-Fi Transceiver on (https://www.scirp.org/journal/paperinformation?paperid=80019)
## Li-Fi Transmitter:
The LiFi Transmitter is a custom-design front-end for visible light communications (VLC). It has a wide bandwith (25 MHz) to support even the most demanding video streaming applications. The transmitter has a powerful 5000K 186 lumen LED with an interchangeable lens mechanism.
-  Function: Converts electrical data into light pulses for transmission.
  
-  *Components:*
-  Microcontroller: Processes and encodes data for transmission. (Often an Arduino Uno in simpler setups)
-  LED or Laser: Acts as the light source for transmitting encoded data. LEDs are common for shorter distances, while lasers offer advantages for longer ranges due to their directionality.
-  Driver Circuit: Controls and modulates the intensity of the light source based on the encoded data.
 
---
## Li-Fi Receiver:
LiFi Receiver is a custom-design front-end for visible light communications (VLC). It has a wide bandwith (20 MHz) to support even the most demanding video streaming applications.
- Function: Detects and converts received light pulses back into electrical data.
- *Components:*
- Photodiode: Converts received light signals into electrical current.
- Signal Processing Circuit: Amplifies and filters the received electrical signal for accurate data recovery.
- Microcontroller: Decodes the received electrical signal back into original data.

 ---
## 🔄 Data Transmission Process:
1.	Data Input: The transmitter receives data through a serial interface (e.g., USB) from a computer or other device.
2.	Data Encoding: The data is converted into a format suitable for transmission using Li-Fi protocols. This often involves encoding the data into variations of light intensity.
3.	Light Pulse Generation: The driver circuit rapidly switches the light source (LED or laser) on and off based on the encoded data.
4.	Light Transmission: The encoded light pulses travel through the air (or water in some applications) towards the receiver.
5.	Light Detection: The photodiode in the receiver detects the incoming light pulses.
6.	Signal Processing: The received electrical signal from the photodiode is amplified and filtered for better clarity.
7.	Data Decoding: The microcontroller decodes the received electrical signal back into its original data format.
8.	Data Output: The recovered data is then sent to a connected device for further processing or use.

--- 

## Additional Notes:
•	Li-Fi requires a clear line of sight between the transmitter and receiver for successful data transfer.
•	The range of Li-Fi communication depends on various factors like light source power, receiver sensitivity, and environmental conditions.


