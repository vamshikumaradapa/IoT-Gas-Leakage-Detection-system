# 🔥 IoT Gas Leakage Detection System

## 📌 Overview
An IoT-based safety system that detects gas leakage and provides real-time alerts.  
It also monitors temperature and humidity and uploads data to the cloud for remote access.

---

## 🚀 Features
- Gas leakage detection using MQ-2 sensor  
- Instant buzzer alert for safety  
- Temperature & humidity monitoring (DHT11)  
- Real-time cloud data monitoring  
- WiFi-enabled using ESP8266  

---

## 🛠️ Tech Stack
- ESP8266 (NodeMCU)  
- Embedded C  
- ThingSpeak Cloud Platform  

---

## 🔧 Components Required
- ESP8266 (NodeMCU)  
- MQ-2 Gas Sensor  
- DHT11 Sensor  
- Buzzer  
- Jumper Wires  

---

## ⚙️ Working Principle
- MQ-2 sensor continuously detects gas levels  
- If gas exceeds threshold, buzzer is activated  
- DHT11 measures temperature & humidity  
- ESP8266 sends all data to cloud (ThingSpeak)  
- User monitors data remotely  

---

## 🔌 Pin Configuration

| Component   | Pin |
|------------|-----|
| MQ-2 Sensor | A0  |
| Buzzer      | D2  |
| DHT11       | D5  |

---

## 🧰 Setup Instructions
1. Connect all components as per circuit  
2. Configure WiFi credentials in code  
3. Set ThingSpeak API key  
4. Upload code to ESP8266  
5. Power ON the system  
6. Monitor data on ThingSpeak  

---

## 📷 Images
![Circuit Diagram](https://github.com/vamshikumaradapa/IoT-Gas-Leakage-Detection-system/blob/2aae022d5ca9d0be305c32735056dd1be1ed27db/Circuit%20Daigram.png)
![Project Output](https://github.com/vamshikumaradapa/IoT-Gas-Leakage-Detection-system/blob/e583b05040fd948011861183afeb0070d6b83181/Output%20Of%20the%20Project.png)
![Cloud Data](https://github.com/vamshikumaradapa/IoT-Gas-Leakage-Detection-system/blob/0c8fd7b4eeb7fd66eb51dd3a994af93f6ff3286d/Data%20Uploaded%20to%20the%20System.png)

---

## 📌 Output
- Detects gas leakage and triggers buzzer alert  
- Displays temperature and humidity values  
- Sends real-time data to ThingSpeak cloud  
- Enables remote monitoring  

---

## 🎯 Applications
- Home safety systems  
- Industrial gas monitoring  
- Smart IoT alert systems  
