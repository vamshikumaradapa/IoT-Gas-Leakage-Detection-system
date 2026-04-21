# 🔥 IoT Gas Leakage Detection System

## 📌 Overview

This project is a smart home safety system that detects gas leakage using a gas sensor and sends real-time alerts. It also monitors temperature and humidity and uploads data to the cloud for remote monitoring.


## 🚀 Features

* Detects gas leakage using MQ-2 sensor
* Real-time buzzer alert for safety
* Monitors temperature and humidity using DHT11
* Sends data to ThingSpeak cloud platform
* WiFi-enabled using ESP8266


## 🛠️ Components Used

* ESP8266 (NodeMCU)
* MQ-2 Gas Sensor
* DHT11 Temperature & Humidity Sensor
* Buzzer
* Jumper Wires

## ⚙️ Working Principle

1. MQ-2 sensor continuously monitors gas concentration
2. If gas value exceeds threshold, buzzer is activated
3. DHT11 reads temperature and humidity
4. ESP8266 sends all data to ThingSpeak cloud
5. User can monitor data remotely


## 📊 Cloud Platform

Data is sent to **ThingSpeak** for real-time monitoring and analysis.

## 🔌 Pin Configuration

| Component   | Pin |
| ----------- | --- |
| MQ-2 Sensor | A0  |
| Buzzer      | D2  |
| DHT11       | D5  |

## 📷 Images
![image alt]()
![image alt]()
![image alt]()

## 🎯 Applications

* Home safety systems
* Industrial gas monitoring
* Smart IoT-based alert systems


## 🧠 Future Improvements

* Mobile app notification (Blynk/Telegram)
* Automatic gas valve shutdown
* SMS alerts using GSM module


## 👨‍💻 Author

Vamshi Kumar

