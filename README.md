# IoT-Based SpO2 and Pulse Oximeter with MAX30102


![GitHub License](https://img.shields.io/github/license/ItzzInfinity/IoT-Based-SpO2-and-Pulse-Oximeter-with-MAX30102)
![Arduino](https://img.shields.io/badge/Platform-Arduino-blue)
![MAX30102](https://img.shields.io/badge/Sensor-MAX30102-red)![Platform](https://img.shields.io/badge/MCU-ESP8266-blue.svg) 
![Language](https://img.shields.io/badge/language-C%2B%2B-yellow.svg)
![I2C Protocol](https://img.shields.io/badge/protocol-I2C-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-success.svg)
![OLED Display](https://img.shields.io/badge/display-SSD1306-orange.svg)
![Sensor](https://img.shields.io/badge/sensor-MAX30102-red.svg)
![Difficulty](https://img.shields.io/badge/difficulty-Intermediate-lightgrey.svg)
![Project Type](https://img.shields.io/badge/project-IoT-blueviolet.svg)
![Made with Love](https://img.shields.io/badge/made%20with-%E2%9D%A4-red.svg)


## Overview
This project demonstrates a compact **IoT-Based SpO2 and Pulse Oximeter** built using the **MAX30102 pulse oximeter sensor**, **ESP8266 microcontroller**, and an **OLED display**. It measures blood oxygen saturation (SpO2) and heart rate, displaying the values in real-time on an OLED screen. The ESP8266’s wireless capabilities open the door for IoT integration, making it suitable for remote monitoring systems.

### Features:
- Accurate measurement of **SpO2** and **heart rate**.
- Real-time display of results on an **SSD1306 OLED**.
- Designed for **DIY enthusiasts** and **health monitoring systems**.
- Compact, affordable, and extendable for wireless IoT applications.

---

## Hardware Requirements
- **ESP8266** Microcontroller
- **MAX30102** Pulse Oximeter Sensor
- **SSD1306 OLED** Display (128x64 pixels)
- Jumper Wires and Breadboard
---
## Circuit Diagram:  
![Circuit Diagram](https://github.com/ItzzInfinity/IoT-Based-SpO2-and-Pulse-Oximeter-with-MAX30102/blob/main/Images/pulse_oximeter_bb_1.png)

---

## Software Requirements
- **Arduino IDE**
- Required Libraries:
  - [DFRobot_MAX30102](https://github.com/DFRobot/DFRobot_MAX30102)
  - `Wire (Arduino’s built-in library)`
  - `Adafruit_GFX`
  - `Adafruit_SSD1306`

---

## Code Description
The program configures the MAX30102 sensor to measure SpO2 and heart rate. The data is displayed on an SSD1306 OLED screen. Key features include:
- Sensor initialization and configuration for optimal accuracy.
- Real-time validity checks for SpO2 and heart rate data.
- OLED display messages prompting user interaction.

Refer to the full code in the repository: [IoT-Based SpO2 and Pulse Oximeter](https://github.com/ItzzInfinity/IoT-Based-SpO2-and-Pulse-Oximeter-with-MAX30102/blob/main/Src/SPo2_OLED.ino).

---

## Working Images
![Working Demo](https://github.com/ItzzInfinity/IoT-Based-SpO2-and-Pulse-Oximeter-with-MAX30102/blob/main/Images/Working_1.jpeg)

![Finger_out](https://github.com/ItzzInfinity/IoT-Based-SpO2-and-Pulse-Oximeter-with-MAX30102/blob/main/Images/Working_2.jpeg)

---

## How to Use
1. **Set up the circuit** as per the circuit diagram.
2. Install the required libraries in the Arduino IDE.
3. Upload the provided code to the ESP8266 board.
4. Power the system and place your finger on the MAX30102 sensor to measure SpO2 and heart rate.
5. View the results on the OLED display.

---

## License
This project is licensed under the [MIT License](https://github.com/ItzzInfinity/IoT-Based-SpO2-and-Pulse-Oximeter-with-MAX30102/blob/main/LICENSE).

---

## Contributions
Contributions are welcome! Please fork the repository and create a pull request for any enhancements or bug fixes.

For any issues, feel free to open an issue in the repository.

