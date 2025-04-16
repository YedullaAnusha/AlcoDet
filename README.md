#  Alco-Det – Smart Alcohol Detection System

**Alco-Det** is an IoT-based alcohol detection system designed to prevent drunk driving and enhance road safety. Using sensors and real-time monitoring, this system detects alcohol in a driver’s breath and responds with alerts, while also tracking environmental data like temperature and humidity.

---

##  Features

-  Detects alcohol in real-time using MQ-3 sensor.
- 🌡 Monitors temperature and humidity via DHT11.
-  Sends live updates to mobile using Blynk IoT.
-  Alerts user with buzzer and LED indicators.

---

##  Components Used

| Component        | Description                                       |
|------------------|---------------------------------------------------|
| MQ-3 Sensor      | Detects ethanol vapors from breath                |
| DHT11 Sensor     | Measures temperature and humidity                 |
| ESP8266          | Wi-Fi enabled microcontroller                     |
| Buzzer           | Provides sound alerts                             |
| LEDs (Red/Green) | Indicate safe or unsafe alcohol levels            |
| Jumper Wires     | For circuit connections                           |

---
##  How It Works

1. **Alcohol Detection**: The MQ-3 sensor detects ethanol levels from a person’s breath.
2. **Temperature & Humidity Monitoring**: The DHT11 sensor records environmental conditions.
3. **Real-Time Alerts**: If alcohol levels cross a set threshold, a buzzer is triggered, an LED lights up, and a warning is sent to the user via the Blynk IoT platform.
4. **Safety Feedback**:
   - Safe alcohol levels: Green LED ON, Red LED OFF, buzzer beeps briefly.
   - Unsafe levels: Red LED ON, Green LED OFF, continuous alert and IoT notification.
5. **Connectivity**: ESP8266 connects to Wi-Fi to push real-time data to the Blynk dashboard.

---
