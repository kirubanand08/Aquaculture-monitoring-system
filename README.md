🌊 Aquaculture Monitoring System
📌 Overview

Maintaining the right water quality is crucial for healthy fish growth in aquaculture. This project presents an IoT-based Aquaculture Monitoring System that continuously tracks key water parameters such as temperature, pH, and turbidity.

Using an ESP32 microcontroller, the system collects real-time sensor data and sends it to the cloud. With the help of the Blynk mobile app, users can monitor water conditions anytime, from anywhere, and take action before problems occur.

🚀 Key Features
🌡️ Real-time Temperature Monitoring using DS18B20
💧 pH Level Tracking for water quality balance
🌫️ Turbidity Measurement to monitor water clarity
📡 Wi-Fi Enabled IoT System for remote access
📱 Live Dashboard using Blynk app
⚠️ Smart Alerts when parameters exceed safe limits
🛠️ Hardware Used
ESP32 Microcontroller
DS18B20 Temperature Sensor
pH Sensor Module
Turbidity Sensor
Jumper Wires
Breadboard / PCB
Power Supply
💻 Software & Tools
Arduino IDE
Blynk IoT Platform
Embedded C / C++
🔌 System Architecture

The system works in a simple but powerful way:

Sensors measure water parameters (temperature, pH, turbidity)
ESP32 processes the sensor data
Data is transmitted via Wi-Fi to the Blynk cloud
Users view real-time data on a mobile dashboard
Alerts are triggered if values go beyond safe limits
🧩 Components
🌡️ Temperature Sensor (DS18B20)

💧 pH Sensor

🌫️ Turbidity Sensor

🔧 Working Principle
The sensors continuously collect environmental data from the water
ESP32 reads and processes this data
The processed data is sent to the cloud using Wi-Fi
Users can monitor everything through the Blynk app
Alerts notify users if water conditions become unsafe
📊 Ideal Water Conditions for Aquaculture
Parameter	Recommended Range
Temperature	20°C – 30°C
pH	6.5 – 8.5
Turbidity	< 50–80 NTU
⚙️ Installation & Setup
Install Arduino IDE
Add required libraries:
WiFi
Blynk
OneWire
DallasTemperature
Connect sensors to ESP32 as per circuit diagram
Update your Wi-Fi and Blynk credentials in the code
Upload the code to ESP32
Power on the system and start monitoring
🔮 Future Enhancements
🤖 Automatic water filtration system
🧠 AI-based fish health prediction
🔔 Advanced mobile notifications
☀️ Solar-powered operation
📊 Cloud-based data analytics
