# Hands-Free Voice-Controlled Robot 🤖🎙️

This project demonstrates a Bluetooth voice-controlled 4-wheel robot using Arduino Uno, motor driver shield, and an HC-05 module. It accepts voice commands such as **move forward**, **turn left**, **turn right**, and **stop**. The robot can be controlled hands-free using a smartphone with a voice command app.

## 🧠 Features
- Voice command input via smartphone using Bluetooth
- Four DC motor control using `Adafruit Motor Shield`
- Servo-assisted turning (for steering or gesture indication)
- Simple Arduino-based design and easy integration

## 🧰 Components Used
- Arduino Uno
- Adafruit Motor Driver Shield (AFMotor library)
- HC-05 Bluetooth module
- 4 x DC Motors
- 1 x Servo motor
- 12V Battery Supply
- Android smartphone with voice command app (e.g., Bluetooth Voice Control)

## 🎤 Voice Commands Supported

| Command           | Action         |
|------------------|----------------|
| `*move forward#` | Moves forward  |
| `*move backward#`| Moves backward |
| `*turn left#`    | Turns left     |
| `*turn right#`   | Turns right    |
| `*stop#`         | Stops movement |

> Make sure your voice command app sends commands exactly as listed (with `*` prefix and `#` suffix).

## 🛠️ Libraries Required
- `AFMotor` – For motor shield control
- `Servo` – For controlling servo motor

Install via Arduino IDE Library Manager.

## 📝 How to Use
1. Connect your Android phone with HC-05 (Default PIN: `1234`).
2. Open a Bluetooth voice control app.
3. Speak commands like **"move forward"**, **"turn left"**.
4. Watch your robot respond hands-free!
