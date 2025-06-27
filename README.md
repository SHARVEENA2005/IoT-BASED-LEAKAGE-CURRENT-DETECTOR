# ⚡ IoT-Based Leakage Current Detector

## 📘 Project Overview
The **IoT-Based Leakage Current Detector** is a smart safety system designed to detect electrical leakage currents and notify users in real time via IoT. It enhances electrical safety in residential and public environments, especially in areas where people may come in contact with electrically conductive surfaces.

---

## 🧠 Key Features
- 🔍 Detects leakage current using current sensors
- 🌐 Real-time alerts 
- 📲 Cloud integration for remote monitoring (e.g., Blynk, Thingspeak, or Firebase)
- 💡 LED indicators and buzzer alerts for local notification
- 🔌 Helps prevent electric shocks and fire hazards

---

## ⚙️ Working Principle
1. The current sensor continuously monitors leakage current on a line.
2. If current exceeds a predefined threshold, it triggers a **local alert** (buzzer + LED).
3. The ESP32/NodeMCU sends data to a cloud platform.
4. The user receives notifications on their phone or dashboard in real time.

---

