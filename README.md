# Hands-Free Voice-Controlled Robot

## Project Overview
A Bluetooth-controlled 4-wheel robot built with Arduino Uno, motor driver shield, and HC-05 module. It responds to voice commands—such as *move forward*, *turn left*, *turn right*, and *stop*—sent from a smartphone app, enabling hands-free robotic control.

---

## Key Features
- **Voice Command Control** via smartphone and HC-05 Bluetooth module  
- **Command Set:** *move forward*, *move backward*, *turn left*, *turn right*, *stop*  
- **Motor Control:** Four DC motors managed through Adafruit Motor Shield (AFMotor library)  
- **Servo Integration:** Optional servo handling for steering or visual feedback  
- **Friendly Design:** Simple setup with Arduino for smooth integration and deployment

---

## Components Used
- **Microcontroller:** Arduino Uno  
- **Motor Control:** Adafruit Motor Driver Shield (AFMotor library)  
- **Communication:** HC-05 Bluetooth module  
- **Actuators:** 4 × DC motors; 1 × Servo motor  
- **Power Supply:** 12 V battery  
- **Interface:** Android smartphone app (e.g., Bluetooth Voice Control)

---

## Voice Commands Supported
| Command          | Action       |
|------------------|--------------|
| `*move forward#` | Moves forward |
| `*move backward#`| Moves backward |
| `*turn left#`    | Turns left   |
| `*turn right#`   | Turns right  |
| `*stop#`         | Stop motion  |

> Ensure the voice app sends commands exactly as listed—including `*` and `#`.

---

## Setup & Usage
1. Install the required Arduino libraries (`AFMotor`, `Servo`) via the IDE.  
2. Connect the Android phone to HC-05 (default PIN: `1234`).  
3. Launch a Bluetooth voice control app on your phone.  
4. Speak any listed command to control the robot hands-free.

---

## Results
A responsive, hands-free robot prototype that reacts accurately to voice commands—demonstrating seamless integration of Bluetooth communication with motor control in a simple Arduino environment.

---

## Folder Structure
- `Arduino code/Arduino_Voice_Control_robot` — Core Arduino sketch and logic  
- `Media/` — Images or video demos of the running robot (if available)

---

## Future Enhancements
- **Add SLAM integration** with embedded microcontrollers for environmental mapping  
- **Wireless Range Extension** via LoRa modules for outdoor or long-range control  
- **Advanced Command Parsing** using speech recognition libraries  
- **Mobile Companion App** for richer controls and UI feedback

---

