# 🌊 Aquaculture Monitoring System

##  Overview:

Fish don't complain. By the time you notice something's wrong — fish gasping at the surface, unusual deaths, stunted growth — the water quality has already been bad for hours, maybe days. This project exists to catch those problems early, automatically, and from your phone.
The Aquaculture Monitoring System is an affordable, ESP32-based IoT solution that continuously watches your pond or tank. It tracks temperature, pH, and turbidity around the clock, pushes live data to the cloud, and alerts you the moment something drifts outside safe limits — so you can act before it costs you.

##  Features:

*  Real-time temperature monitoring using DS18B20
*  pH level measurement for water quality analysis
*  Turbidity detection for water clarity
*  IoT-based remote monitoring via Wi-Fi
*  Live data visualization using Blynk app
*  Alerts for abnormal conditions

---

## Hardware Components:

* ESP32 Microcontroller
* DS18B20 Temperature Sensor
* pH Sensor Module
* Turbidity Sensor
* Jumper Wires
* Breadboard / PCB
* Power Supply

---

## Software & Tools

* Arduino IDE
* Blynk IoT Platform
* Embedded C ,c++ Programming

---

##  System Architecture

The system collects data from sensors and processes it using ESP32. The data is then transmitted over Wi-Fi to the Blynk cloud, where users can monitor it in real time.
##  Components

### pH Sensor
![pH Sensor](component/PH.jpg)

### Turbidity Sensor
![Turbidity](component/TURBIDITY.jpg)

### DS18B20 Temperature Sensor
![DS18B20](component/DS18B20.jpeg)


##  Working Principle

1. Sensors collect water parameters:

   * Temperature (DS18B20)
   * pH level
   * Turbidity
2. ESP32 reads sensor data
3. Data is processed and sent to Blynk via Wi-Fi
4. User monitors values through mobile dashboard
5. Alerts are triggered if values exceed safe limits

---

## Ideal Water Conditions for Aquaculture

| Parameter   | Ideal Range       |
| ----------- | ----------------- |
| Temperature | 20°C – 30°C       |
| pH          | 6.5 – 8.5         |
| Turbidity   | Less than 50-80 NTU|

##  Installation & Setup

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

##  Future Enhancements

* Automatic water filtration system
* AI-based prediction for fish health
* Mobile notifications and alerts
* Solar-powered system
* Cloud data analytics
