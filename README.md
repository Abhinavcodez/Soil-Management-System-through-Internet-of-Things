# 🌱 Soil Management System using IoT

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![IoT](https://img.shields.io/badge/IoT-Enabled-orange?style=flat-square)

> **Smart Environmental Monitoring for Precision Agriculture & Sustainable Resource Management**  
> An IoT-based real-time system to monitor temperature, humidity, soil moisture, rainfall, and light intensity, enabling **data-driven agriculture** and **climate-smart decision making**.

---

## 📌 Overview
The **Soil Management System** is a low-cost, cloud-connected **IoT solution** that leverages **ESP8266**, environmental sensors, and **Firebase Realtime Database** to deliver live environmental data.  
It is ideal for **precision agriculture**, **greenhouse automation**, and **smart city environmental monitoring**.

---

## ✨ Key Features
- 🌡 **Real-time Sensor Monitoring** – Temperature, humidity, soil moisture, rainfall, and light levels.
- ☁ **Cloud Integration** – Stores and syncs readings instantly to Firebase.
- 📊 **Live Dashboard** – Django-based web app for real-time visualization.
- 💰 **Low-Cost & Scalable** – Uses widely available components for easy expansion.
- 🤖 **Automation Ready** – Can integrate irrigation control and AI-driven predictions.

---

## 🛠 Tech Stack

| Category            | Technology |
|--------------------|------------|
| **Microcontroller** | ESP8266 (NodeMCU) |
| **Sensors**         | DHT11, Soil Moisture Sensor, Raindrop Sensor, Light Sensor |
| **Cloud**           | Firebase Realtime Database |
| **Web Framework**   | Django (Python) |
| **Programming**     | Arduino IDE |
| **Libraries**       | ESP8266WiFi, Adafruit DHT, Adafruit BME280, ESPAsyncWebServer, FirebaseESP8266 |

---



## 🧩 System Architecture

[ Sensors ]
   ├── DHT11 (Temp & Humidity)
   ├── Soil Moisture Sensor
   ├── Raindrop Sensor
   └── Light Sensor
       │
[ ESP8266 Microcontroller ]
       │  Wi-Fi
       ▼
[ Firebase Realtime Database ]
       │
       ▼
[ Django Web App ]
   └── Real-time Visualization

---


## ⚙ Installation & Setup



1️⃣ Clone the Repository

git clone https://github.com/AbhinavCodez/Soil-Management-System-through-Internet-of-Things.git

cd Soil-Management-System-through-Internet-of-Things



2️⃣ Install Arduino Libraries (via Arduino IDE Library Manager)

ESP8266 Board Package

Adafruit Unified Sensor

DHT Sensor Library

ESPAsyncWebServer

FirebaseESP8266



3️⃣ Configure & Upload Code

Edit config.h with your Wi-Fi credentials.

Select NodeMCU 1.0 (ESP-12E) in Arduino IDE.

Upload .ino to ESP8266.



4️⃣ Run Django Web App

pip install -r requirements.txt

python manage.py runserver



📊 Results
| Metric                  | Result        |
| ----------------------- | ------------- |
| Temp Accuracy           | ±2°C          |
| Humidity Accuracy       | ±5% RH        |
| Real-time Update Delay  | < 2 sec       |
| Minimum Detectable Rain | Light drizzle |



🎯 Applications

🌾 Precision agriculture & irrigation scheduling

🌱 Greenhouse climate control

🌦 Weather-responsive farming

🏙 Smart city environmental tracking



📜 License

This project is licensed under the MIT License – free to use and modify.
