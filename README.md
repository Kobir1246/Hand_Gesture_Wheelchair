# Hand Gesture Controlled Wheelchair

An Arduino-based smart wheelchair prototype that enables wireless navigation using hand gestures. The system utilizes an MPU6050 motion sensor mounted on a wearable glove to detect hand movements and transmits movement commands wirelessly through nRF24L01 RF modules. The receiver interprets these commands and controls the wheelchair's motors in real time.

> **Academic Project**
> Department of Computer Science & Engineering
> Daffodil International University

---

## 📌 Overview

This project was developed to demonstrate an affordable and intuitive mobility assistance system using embedded electronics and wireless communication. Instead of using traditional joysticks, the wheelchair can be controlled by simply tilting the user's hand.

The system consists of two Arduino-based modules:

- **Transmitter Unit (Hand Glove)**
- **Receiver Unit (Wheelchair)**

The transmitter continuously measures the orientation of the user's hand using an MPU6050 accelerometer and gyroscope. Based on the detected gesture, movement commands are transmitted wirelessly to the receiver using nRF24L01 RF modules.

The receiver processes the incoming commands and controls the wheelchair motors accordingly.

---

# ✨ Features

- Wireless hand gesture control
- Real-time gesture detection
- MPU6050 motion sensing
- nRF24L01 wireless communication
- Arduino-based embedded system
- Forward movement
- Backward movement
- Left turn
- Right turn
- Stop functionality
- Simple and low-cost implementation

---

# 🛠 Hardware Components

- Arduino Nano (Transmitter)
- Arduino Uno (Receiver)
- MPU6050 Accelerometer & Gyroscope
- 2 × nRF24L01 RF Modules
- L298N Motor Driver
- DC Motors
- Chassis / Wheelchair Prototype
- Battery Supply
- Connecting Wires

---

# 💻 Software

- Arduino IDE
- Embedded C / Arduino C++

---

# ⚙️ Working Principle

1. The MPU6050 continuously measures the orientation of the user's hand.

2. The Arduino Nano processes the sensor readings and determines the intended movement direction.

3. A wireless data packet containing the movement command is transmitted through the nRF24L01 RF module.

4. The receiver Arduino listens for incoming packets.

5. Upon receiving a valid command, the receiver controls the motor driver to move the wheelchair in the corresponding direction.

---

# 📡 Wireless Communication

The project uses the nRF24L01 2.4 GHz transceiver module for communication between the transmitter and receiver.

Each transmitted packet contains:

- Movement Direction
- Speed Value (reserved for future implementation)

---

# 📂 Project Structure

```
Hand-Gesture-Controlled-Wheelchair
│
├── transmitter/
│   └── Project_nano.ino
│
├── receiver/
│   └── Project.ino
│
├── images/
│
├── demo/
│
├── docs/
│
└── README.md
```

---

# 📷 Project Images

Images of the hardware prototype are available in the **images** directory.

---

# 🎥 Demonstration

Project demonstration videos can be found here:

**Google Drive**
(Add your Google Drive link)

or

**YouTube**
(Add YouTube link)

---

# 🚀 Future Improvements

- Variable motor speed control using PWM
- Obstacle detection using ultrasonic sensors
- Emergency stop button
- Bluetooth/Wi-Fi connectivity
- Voice command support
- Android application integration
- Gesture calibration mode
- Battery monitoring system

---

# 📚 Technologies Used

- Arduino
- Embedded C
- MPU6050
- nRF24L01
- RF Communication
- Motor Control
- Embedded Systems
- Internet of Things (IoT)

---

# 👨‍💻 Author

**Md. Shahriar Kobir Sabbir**

B.Sc. in Computer Science & Engineering

GitHub: https://github.com/kobir1246

LinkedIn: *(Add your LinkedIn profile)*

Email: *(Add your email)*

---

# 📄 License

This project is released for educational and academic purposes.
