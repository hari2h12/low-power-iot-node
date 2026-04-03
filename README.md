# 🌱 Minimization of Power Consumption in IoT Node

## 📌 Overview  
This project focuses on designing and implementing a **low-power IoT node** for efficient environmental monitoring. The system is developed using the **Raspberry Pi Pico W** and integrates multiple sensors to collect real-time data such as temperature, humidity, soil moisture, voltage, and current.

The main objective is to **reduce energy consumption** in IoT devices by optimizing sensing, communication, and processing techniques. This makes the system ideal for battery-powered and remote applications.

---

## 🎯 Objectives  
- Minimize power consumption in IoT nodes  
- Compare system performance with and without optimization  
- Implement sleep scheduling for energy efficiency  
- Optimize data transmission using HTTP and MQTT  
- Extend battery life of IoT devices  

---

## ⚙️ Features  
- 🌡️ Temperature & Humidity Monitoring  
- 🌱 Soil Moisture Detection  
- 🔋 Voltage & Current Measurement  
- 📡 Wi-Fi Connectivity  
- ☁️ Cloud Data Upload (ThingSpeak)  
- 😴 Deep Sleep Mode for Power Saving  
- 📊 Power Consumption Analysis  

---

## 🧠 Methodology  

### 🔴 Without Power Optimization  
- Continuous sensor data reading  
- Frequent data transmission  
- Higher power consumption  

### 🟢 With Power Optimization  
- Scheduled sensor activation  
- Microcontroller deep sleep mode  
- Reduced transmission frequency  
- Efficient communication protocols  

---

## 🔌 Hardware Components  
- Raspberry Pi Pico W  
- DHT Sensor (Temperature & Humidity)  
- Soil Moisture Sensor  
- Voltage Sensor  
- Current Sensor  
- Relay / Motor Driver (Actuator)  
- RTC Module (DS3231) *(optional)*  

---

## 💻 Software & Technologies  
- MicroPython  
- Wi-Fi Networking  
- HTTP Protocol  
- MQTT Protocol  
- ThingSpeak Cloud Platform  

---

## 📊 Results  
- Significant reduction in power consumption  
- Improved battery life  
- Efficient data transmission  
- Better performance in optimized mode  

---

## 🚀 Applications  
- Smart Irrigation Systems  
- Environmental Monitoring  
- Remote Agriculture  
- Battery-powered IoT Systems  

---

## 📁 Project Structure  
/code       → MicroPython scripts  
/docs       → Project report  
/images     → Diagrams and graphs  
/results    → Power analysis data  

---

## 🔮 Future Improvements  
- Solar-powered IoT node  
- AI-based smart scheduling  
- Edge data processing  
- Integration with LoRa communication  

---

## 📜 Conclusion  
This project demonstrates an effective approach to reducing power consumption in IoT systems using sleep scheduling and optimized communication. It provides a practical solution for building sustainable and energy-efficient IoT applications.
