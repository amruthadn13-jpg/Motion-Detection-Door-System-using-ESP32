# 🚪 Motion Detection Door System using ESP32

## 📌 Overview

This project is a **basic IoT-based motion detection system** built using **ESP32**, **PIR Sensor**, **Servo Motor**, and a **Buzzer**.

The system automatically detects motion and responds by:

* Opening a door (servo motor)
* Triggering a buzzer alert

---

## ⚙️ Features

* Motion detection using PIR sensor
* Automatic door control using servo motor
* Buzzer alert on motion detection
* Real-time status monitoring via Serial output

---

## 🧠 Project Description

This project demonstrates how embedded systems can respond to real-world events using sensors and actuators.

---

### 🔹 PIR Sensor (Motion Detection)

* The PIR (Passive Infrared) sensor detects movement in its range
* It outputs:

  * **HIGH** → Motion detected
  * **LOW** → No motion

---

### 🔹 Servo Motor Control

* The servo motor acts as a door mechanism

Behavior:

* **No Motion → 0° (Door Closed)**
* **Motion Detected → 90° (Door Open)**

---

### 🔹 Buzzer Alert System

* When motion is detected:

  * Buzzer turns ON
* When no motion:

  * Buzzer turns OFF

This provides an audible alert for detection.

---

### 🔹 Serial Monitoring

The system prints real-time status:

* `"Motion is detected --> The door is open!!"`
* `"No Motion detected --> The door is Closed!!"`

This helps in debugging and monitoring.

---

## 🔄 Working Flow

1. ESP32 reads data from PIR sensor
2. If motion is detected:

   * Buzzer turns ON
   * Servo rotates to open position
3. If no motion:

   * Buzzer turns OFF
   * Servo returns to closed position
4. Status is printed on Serial Monitor

---

## 🧠 Learning Outcomes

* Working with ESP32 GPIO pins
* Interfacing PIR motion sensors
* Controlling servo motors
* Using buzzer for alerts
* Implementing simple automation logic

---

## 🚀 Future Enhancements

* Add IoT connectivity (WiFi / MQTT / Telegram)
* Add camera for surveillance
* Implement mobile notifications
* Add delay or timer-based door control
* Integrate with authentication system

---

## 👩‍💻 Author

**Amrutha D N**
