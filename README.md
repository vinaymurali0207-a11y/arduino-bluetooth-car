🚗 Bluetooth Controlled RC Car
📌 Overview

This project is a Bluetooth-controlled robot car built using an Arduino Uno, HC-05 module, and L298N motor driver. It enables real-time wireless control of a 4-wheel drive vehicle using a mobile device.

The system receives commands via Bluetooth and translates them into motor actions for directional movement.

⚙️ Components Used
Arduino Uno
HC-05 Bluetooth Module
L298N Motor Driver
4 × DC Gear Motors
12V Battery
Chassis + Wheels
Connecting Wires

🔧 How It Works
The mobile app sends commands via Bluetooth (HC-05)
Arduino reads incoming serial data
Based on the command, Arduino controls the motor driver
The motor driver powers the motors to move the car
Control Commands
F → Forward
B → Backward
L → Left
R → Right
S → Stop

🔌 Circuit Connections (Basic)
HC-05 TX → Arduino RX
HC-05 RX → Arduino TX (use voltage divider if needed)
L298N IN1–IN4 → Arduino digital pins
ENA, ENB → PWM pins
Motors → Motor driver outputs
Battery → Motor driver power input

🚀 Features
Wireless control using Bluetooth
Real-time response to commands
4-wheel drive movement
Simple and reliable motor control system

🧠 Learning Outcomes
Basics of embedded systems
Bluetooth communication using HC-05
Motor control using L298N
Arduino programming and serial communication

📂 Project Structure
bluetooth-rc-car/
│── bluetooth_controlled_rc_car.ino
│── README.md

⚠️ Limitations
No obstacle avoidance
No autonomous functionality
Depends on manual control

🔥 Future Improvements
Add obstacle avoidance (ultrasonic sensor)
Implement speed control
Integrate camera for vision-based control
Build mobile app UI instead of generic controller
