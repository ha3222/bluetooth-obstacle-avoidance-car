# 🚗 Bluetooth Controlled Robot with Obstacle Detection

This project demonstrates an Arduino-based robot car that responds to serial commands (e.g., from a Bluetooth module), and automatically avoids obstacles using an ultrasonic sensor.

---

## 🧠 Features

- Moves Forward, Backward, Left, Right, and Stops based on serial input.
- Stops automatically if an obstacle is detected closer than 20 cm.
- Controls motor speed using PWM.
- Uses `switch-case` logic for command handling.

---

## 🧰 Hardware Used

- Arduino UNO
- L298N Motor Driver
- HC-SR04 Ultrasonic Sensor
- 2 DC Motors
- (Optional) HC-05 Bluetooth Module
- Power Supply / Battery
- Jumper Wires & Breadboard

---

## 🔤 Serial Commands

| Command | Function       |
|---------|----------------|
| `F`     | Move Forward   |
| `B`     | Move Backward  |
| `L`     | Turn Left      |
| `R`     | Turn Right     |
| `S`     | Stop           |

---

## 📏 Obstacle Avoidance Logic

- The ultrasonic sensor constantly measures the distance in front of the robot.
- If the distance is less than 20 cm, forward motion is disabled to prevent collisions.
- The robot can still turn or move backward to avoid the object.

---

## 🚀 Future Ideas

- Add a rotating servo mount for the ultrasonic sensor.
- Connect to a mobile app for Bluetooth control.
- Add LED or buzzer warnings for obstacles.

---

🛠️ Built with 💛 by **Habiba Ahmed**
