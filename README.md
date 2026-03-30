# 🌊 Aquaculture Monitoring System

## 📌 Overview

The **Aquaculture Monitoring System** is an IoT-based solution designed to monitor and maintain optimal water quality in fish farming environments. It continuously tracks key parameters such as **temperature, pH, and turbidity** to ensure a healthy aquatic ecosystem.

The system uses sensors connected to a microcontroller and sends real-time data to the cloud, allowing remote monitoring through a mobile application.

## 🚀 Features

* 🌡️ Real-time temperature monitoring using DS18B20
* 💧 pH level measurement for water quality analysis
* 🌫️ Turbidity detection for water clarity
* 📡 IoT-based remote monitoring via Wi-Fi
* 📱 Live data visualization using Blynk app
* ⚠️ Alerts for abnormal conditions

---

## 🛠️ Hardware Components

* ESP32 Microcontroller
* DS18B20 Temperature Sensor
* pH Sensor Module
* Turbidity Sensor
* Jumper Wires
* Breadboard / PCB
* Power Supply

---

## 💻 Software & Tools

* Arduino IDE
* Blynk IoT Platform
* Embedded C ,c++ Programming

---

## 🔌 System Architecture

The system collects data from sensors and processes it using ESP32. The data is then transmitted over Wi-Fi to the Blynk cloud, where users can monitor it in real time.
## 🧩 Components

### pH Sensor
![pH Sensor](components/PH.jpg)

### Turbidity Sensor
![Turbidity](components/TURBIDITY.jpg)

### DS18B20 Temperature Sensor
![DS18B20](components/DS18B20.jpeg)


## 🔧 Working Principle

1. Sensors collect water parameters:

   * Temperature (DS18B20)
   * pH level
   * Turbidity
2. ESP32 reads sensor data
3. Data is processed and sent to Blynk via Wi-Fi
4. User monitors values through mobile dashboard
5. Alerts are triggered if values exceed safe limits

---

## 📊 Ideal Water Conditions for Aquaculture

| Parameter   | Ideal Range       |
| ----------- | ----------------- |
| Temperature | 20°C – 30°C       |
| pH          | 6.5 – 8.5         |
| Turbidity   | Low (Clear Water) |

## ⚙️ Installation & Setup

1. Install Arduino IDE
2. Install required libraries:

   * WiFi
   * Blynk
   * OneWire
   * DallasTemperature
3. Upload code to ESP32
4. Connect sensors as per circuit diagram
5. Configure Blynk credentials in code
6. Run the system

---

## 🔮 Future Enhancements

* Automatic water filtration system
* AI-based prediction for fish health
* Mobile notifications and alerts
* Solar-powered system
* Cloud data analytics

