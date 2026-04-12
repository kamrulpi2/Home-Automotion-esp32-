# 🏠 ESP32 Smart Home IoT System (Firebase + Servo + Sensors)

An advanced IoT-based Smart Home automation system using ESP32, Firebase Realtime Database, and multiple sensors including IR, DHT22, and Gas sensor with real-time control for door, fan, LED, and alerts.

---
          +----------------------+
          |      5V INPUT        |
          | (USB / Adapter 12V)  |
          +----------+-----------+
                     |
              [Buck Converter 5V]
                     |
         +-----------+------------+
         |                        |
     ESP32 (3.3V)          Servo Power 5V
         |
------------------------------------------------
| Sensors + Modules                             |
| DHT22   -> GPIO 4                            |
| IR      -> GPIO 15                           |
| MQ-5    -> GPIO 34 (ADC)                     |
| Button  -> GPIO 23                           |
| LED     -> GPIO 14                           |
| Fan PWM -> GPIO 12                           |
| Buzzer  -> GPIO 13                           |
| Servo   -> GPIO 26                           |
------------------------------------------------
         |
     Firebase WiFi Cloud
ESP32
│
├── Sensors (DHT22, IR, MQ Gas)
├── Actuators (Servo, Buzzer, LED, Fan)
│
├── WiFi Connection
│
└── Firebase Realtime Database
└── Web / Mobile Dashboard

     
## 🚀 Features

### 🔐 Smart Door System
- Firebase controlled door lock/unlock
- Physical button support
- Auto close after 5 seconds
- Servo motor based door control

### 🌡️ Sensor Monitoring
- DHT22 (Temperature & Humidity)
- IR Sensor (motion/obstacle detection)
- MQ Gas Sensor (danger detection)

### ⚡ Automation
- Gas leak alarm system
- IR-based buzzer sound alert
- Real-time Firebase updates

### 💡 Home Control
- LED ON/OFF control via Firebase
- Fan speed control (PWM)
- Door control from web/mobile app

---

## 🧠 System Architecture
<img width="1107" height="882" alt="image" src="https://github.com/user-attachments/assets/0445b1ce-f5a1-4dff-b63c-bbc1f7a34ec1" />
<img width="1536" height="1024" alt="SmartGuard IoT home PCB design" src="https://github.com/user-attachments/assets/301c537d-4df2-4d05-8166-7bf5f164aed1" />

