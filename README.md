# 📞 Wireless Caller ID Display for Bikers Using Bluetooth

## 📌 Project Overview
The Wireless Caller ID Display for Bikers is a smart safety system that allows riders to view incoming call alerts on a TFT display mounted on the bike. This eliminates the need to check a mobile phone while riding, thereby reducing distractions and improving road safety.

---

## 🎯 Objective
To design a wireless system that provides real-time call notifications to bikers using visual, audio, and physical alerts.

---

## ⚙️ Working Principle
When a phone receives an incoming call, the signal is transmitted via the HC-05 Bluetooth module to the microcontroller. The controller processes this data and displays a call alert on the TFT screen. At the same time, a buzzer produces sound and a motor provides additional alert. The LDR sensor adjusts display brightness based on surrounding light conditions.

---

## 🔄 System Flow
1. Incoming call detected on smartphone  
2. Bluetooth (HC-05) sends signal  
3. Microcontroller receives data  
4. TFT display shows alert  
5. Buzzer gives sound notification  
6. Motor provides physical alert  
7. LDR adjusts brightness automatically  

---

## 🚀 Features
- 📞 Incoming call alert display
- 📡 Wireless communication using Bluetooth
- 🔔 Buzzer alert system
- ⚙️ Motor-based alert mechanism
- 🌙 Automatic brightness control using LDR
- 🏍️ Improves rider safety

---

## 🔧 Components Used
- ESP32 / Arduino
- TFT Display
- HC-05 Bluetooth Module
- LDR Sensor
- N20 Gear Motor
- L298N Motor Driver
- Buzzer
- Power Supply

---

## 🔌 Pin Connections

### 📺 TFT Display (SPI)
- VCC → 3.3V / 5V  
- GND → GND  
- CS → GPIO 5  
- RESET → GPIO 4  
- DC → GPIO 2  
- MOSI → GPIO 23  
- SCK → GPIO 18  
- LED → 3.3V  

### 📡 HC-05 Bluetooth
- VCC → 5V  
- GND → GND  
- TX → GPIO 16  
- RX → GPIO 17  

### 🌙 LDR Sensor
- One end → 3.3V  
- Other end → GPIO 34  
- Resistor → GND (Voltage Divider)

### 🔔 Buzzer
- Positive → GPIO 15  
- Negative → GND  

### ⚙️ Motor Driver (L298N)
- IN1 → GPIO 27  
- IN2 → GPIO 26  
- IN3 → GPIO 25  
- IN4 → GPIO 33  
- ENA → GPIO 14  
- ENB → GPIO 12  

### 🔄 Motor
- N20 Gear Motor connected to driver output

---
