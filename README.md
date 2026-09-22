# smart waste management system
An Arduino-based smart waste segregation system that detects wet and dry waste using a moisture sensor and automatically sorts it using a servo motor.
# Smart Waste Segregation System

This project is an Arduino-based **Smart Waste Segregation System** designed to identify wet and dry waste using a moisture sensor and automatically direct the waste using a servo motor.

## 🚀 Project Overview

The system uses a **moisture sensor** to detect the moisture level of the waste. Based on the detected moisture value, the Arduino classifies the waste as either **wet waste** or **dry waste**.

A servo motor then moves to different positions to direct the waste into the appropriate compartment.

The project also provides:
- 📟 LCD display messages
- 🔊 Voice announcements using DFPlayer Mini
- ⚙️ Automatic waste sorting using a servo motor
- 💧 Moisture-based waste detection

## 🛠️ Components Used

- Arduino Uno
- Moisture Sensor
- Servo Motor
- 16×2 LCD Display
- DFPlayer Mini
- Speaker
- SoftwareSerial Module/Communication
- Jumper Wires
- Power Supply

## 💻 Software & Libraries

- Arduino IDE
- Servo Library
- LiquidCrystal Library
- SoftwareSerial Library
- DFRobotDFPlayerMini Library

## ⚙️ Working Principle

1. The system starts and displays **"Smart Waste"** on the LCD.
2. A voice message is played through the DFPlayer Mini.
3. The system waits for waste to be placed.
4. The moisture sensor detects the moisture level.
5. If the moisture value is above the defined threshold, the waste is classified as **dry waste**.
6. Otherwise, it is classified as **wet waste**.
7. The servo motor rotates to the required position to direct the waste.
8. After sorting, the servo returns to its initial position.
9. The system waits for the next waste item.

## 🔌 Basic Connections

| Component | Arduino |
|-----------|---------|
| Servo Signal | D9 |
| Moisture Sensor | Analog Input |
| LCD | D7, D6, D5, D4, D3, D2 |
| DFPlayer Mini | A1, A2 |
| Waste Detection Sensor | D8 |

