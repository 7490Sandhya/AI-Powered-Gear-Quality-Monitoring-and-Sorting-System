# AI-Powered Gear Quality Monitoring and Sorting System

🛠️ AI-Powered Gear Quality Monitoring and Sorting System

An end-to-end automated gear inspection system using **YOLOv8, Python, OpenCV, and Raspberry Pi 4**, capable of detecting defective gears in real time and automatically sorting them using a servo-controlled mechanism.

---

## 📸 Demo

**System Demo**

*(Real-time gear defect detection and automatic sorting demonstration)*

---

## 🚀 Features

🔍 Real-time gear defect detection and classification using **YOLOv8**  
📷 Live image capture using Raspberry Pi Camera / USB Camera  
🤖 Automatic gear sorting using a servo motor  
⚙️ Conveyor belt control using a DC motor and L298N motor driver  
📡 Ultrasonic sensor for gear detection and image capture triggering  
🧠 Edge AI deployment on Raspberry Pi 4  
💡 Cost-effective solution for industrial quality inspection and smart manufacturing

---

## 🧠 How It Works

### Gear Detection

An ultrasonic sensor detects the presence of a gear moving on the conveyor belt.

### Image Capture

A Raspberry Pi Camera captures an image of the detected gear.

### YOLOv8 Analysis

The captured image is processed using **YOLOv8** to classify the gear as **GOOD** or **DEFECTIVE**.

### Automation Logic

- **If GOOD:** The gear continues moving on the conveyor.
- **If DEFECTIVE:** The Raspberry Pi activates the servo motor to remove the defective gear.

### Conveyor Operation

The conveyor resumes operation and repeats the inspection process for the next gear.

---

## 🔧 Hardware Used

| Component | Description |
|----------|-------------|
| Raspberry Pi 4 | Main controller |
| Raspberry Pi Camera / USB Camera | Image acquisition |
| Ultrasonic Sensor (HC-SR04) | Gear detection trigger |
| Servo Motor (MG995/MG996R) | Defective gear sorting |
| L298N Motor Driver | Controls conveyor motor |
| 12V DC Motor | Conveyor belt drive |
| Conveyor Belt | Gear transportation |

---

## 💻 Software Stack

- Python 3.9+
- YOLOv8 (Ultralytics)
- OpenCV
- Raspberry Pi OS
- NumPy
- GPIO Zero / RPi.GPIO
- Label Studio
