# 🛡️ Hamilton SafeHouse — Web & IoT Dashboard

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-ESP32%20%7C%20Web%20BLE-purple)

An Intelligent Residential Safety & Monitoring System built by the **3°MSI-02** class at **João XXIII High School** (2026)[cite: 2]. Inspired by the software reliability principles of **Margaret Hamilton**.

---

## 📸 Screenshots

| Mobile View | Desktop View |
| :---: | :---: |
| <img src="img/WhatsApp Image 2026-08-05 at 18.59.09 (1).jpeg" width="260"> | <img src="img/WhatsApp Image 2026-08-05 at 18.59.09.jpeg" width="480"> |

---

## ⚙️ Key Features

- 🌡️ **Environmental Telemetry:** Real-time temperature and humidity tracking[cite: 2, 6].
- ⚡ **Electrical Monitoring:** Voltage, current, active power, and energy consumption metering via PZEM-004T[cite: 2, 6, 8].
- 💧 **Water Management:** Real-time water flow rate (L/min) and session usage tracking[cite: 2, 6].
- 🔥 **Emergency Alerts:** Flame detection triggering hardware actuators (LED indicators and Buzzer)[cite: 2, 6].
- 📶 **Wireless Connectivity:** Native Web Bluetooth API (BLE) integration[cite: 6, 7, 8].
- 📊 **Dynamic Analytics:** Live data visualization powered by Chart.js[cite: 2, 6].

---

## 🛠️ Tech Stack

### **Hardware & Embedded**
- ESP32 WROOM-32[cite: 2, 5]
- Sensors: DHT11/DHT22, Flame Sensor, PZEM-004T Power Meter, Water Flow Sensor[cite: 2, 8].
- Actuators: RGB Signal LEDs & 5V Active Buzzer[cite: 2, 6].

### **Frontend & Interface**
- Semantic HTML5 (Mobile & PWA-ready)[cite: 2, 4]
- CSS3 (Variables, Flexbox, Grid, Media Queries for Desktop/Mobile UI)[cite: 4]
- Vanilla JavaScript (ES6+)[cite: 6]
- Chart.js[cite: 2, 6]

---

## 🚀 Local Setup

The **Web Bluetooth API** requires a secure origin (`HTTPS` or `localhost`)[cite: 5, 7].

```bash
# 1. Clone the repository
git clone [https://github.com/Davy466/site-3msi02mobile.git](https://github.com/Davy466/site-3msi02mobile.git)

# 2. Navigate to project directory
cd site-3msi02mobile

# 3. Start a local server (e.g. via Python)
python -m http.server 8000
