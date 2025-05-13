# Elderly Monitoring System using IoT

A health-focused IoT prototype designed to monitor elderly individuals at home. The system detects critical events like falls, triggers alerts, and reminds users of medication schedules. Built using **Arduino Nano**, **NodeMCU**, and various sensors.

---

## 🧓 Problem Statement
Many elderly people live alone or with limited supervision. This system aims to:
- Detect accidental falls and send immediate alerts
- Remind users to take scheduled medications
- Notify caretakers via SMS during critical events

---

## 🛠️ Tech Stack
- **Microcontrollers**: Arduino Nano, NodeMCU (ESP8266)
- **Sensors Used**:
  - **Accelerometer (e.g., MPU6050)** – Fall detection
  - **Buzzer/LED** – Local alerts and reminders
- **Communication**:
  - **GSM Module** – SMS alerting to caregivers
  - **Wi-Fi (NodeMCU)** – Optional online dashboard or logging
- **Software**: Arduino IDE, Serial Monitor, GSM AT Commands

---

## ⚙️ Features
- Detects sudden falls via accelerometer motion thresholds
- Sends SMS alerts using GSM module with location/alert text
- Medication reminders triggered on a timer (with buzzer/LED)
- Low-power and portable design for home or elderly-care use

---

## 🔒 Safety & Design
- Non-intrusive wearable form factor possible (belt, necklace)
- Alert system activates only when impact and orientation change match
- Time-based scheduling logic ensures regular medication reminders

---

## 🧠 What I Learned
- Real-time sensor calibration and fall detection logic
- Interfacing GSM modules with Arduino for SMS delivery
- Time-based hardware control using millis() (for reminders)
- Thinking through real-world healthcare scenarios in IoT

---

## 🚀 Future Additions
- Integrate heartbeat or pulse sensor (e.g., MAX30100)
- Send data to Firebase or cloud for caregiver dashboard
- Add voice assistant integration for reminders

---

## ✍️ Author
Pratham Govalkar — Embedded Systems mini project
