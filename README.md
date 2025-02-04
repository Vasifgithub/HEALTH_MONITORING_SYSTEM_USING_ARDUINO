# HEALTH_MONITORING_SYSTEM_USING_ARDUINO

## Health Monitoring System Using Arduino 🚑🔬
### Project Overview
This project is an IoT-based health monitoring system that tracks vital signs such as heart rate, oxygen levels (SpO₂), ECG, and body temperature. The system uses an Arduino Uno along with multiple sensors and transmits real-time data to the cloud for remote monitoring.


<br> 

### 📌 Features
✅ Monitors ECG, temperature, heart rate, and SpO₂ <br>
✅ Real-time data visualization on the serial monitor or web interface <br>
✅ Cloud integration for remote health tracking <br>
✅ Low-cost, efficient, and portable IoT-based health monitoring system <br>
✅ Alerts for abnormal readings

<br>

## 🛠️ Components Used

| Component                    | Description                               |
|------------------------------|-------------------------------------------|
| **Arduino Uno**              | Microcontroller board for processing sensor data |
| **ESP8266 Wi-Fi Module**      | Transmits data to the cloud               |
| **DS18B20 Temperature Sensor**| Measures body temperature                |
| **MAX30102 Pulse Oximeter**   | Detects heart rate and SpO₂ (oxygen level) |
| **AD8232 ECG Module**         | Captures ECG signals                     |
| **Jumper Wires**              | Connects components                      |
| **Breadboard**                | Prototyping connections                   |

<br>

###  🖥️ System Workflow
1️⃣ Sensors collect vital health data. <br>
2️⃣ Arduino processes and filters the data. <br>
3️⃣ The ESP8266 Wi-Fi module transmits data to the cloud. <br>
4️⃣ Users can monitor real-time health metrics on a web dashboard or serial monitor. <br>
5️⃣ System triggers alerts for abnormal readings. <br>

<br>

###  🔬 Methodology
The Health Monitoring System follows a structured approach to sensor data collection, processing, transmission, and visualization:

1️⃣ Data Acquisition: <br>
Various biometric sensors (ECG, temperature, SpO₂, heart rate) continuously collect data.
These sensors are interfaced with the Arduino Uno microcontroller. <br> 

2️⃣ Data Processing: <br>
The Arduino reads sensor values and performs filtering or preprocessing to improve accuracy.
Analog signals (ECG, pulse) are converted to digital values for further analysis. <br>

3️⃣ Wireless Transmission: <br>
The ESP8266 Wi-Fi module sends processed sensor data to the cloud for remote access.
Data is stored in a cloud-based database or visualized on a real-time web dashboard. <br>

4️⃣ Real-time Monitoring & Alerts: <br>
The serial monitor (for local monitoring) or web-based interface (for remote access) displays live data.
Abnormal readings trigger alerts to notify users or medical professionals. <br>

### 📌 System Architecture:

<img width="370" alt="image" src="https://github.com/user-attachments/assets/cf370dfa-59df-4b8f-aa24-d55d47fa8316" />


<br>

### 🚀 Installation & Setup

1️⃣ Hardware Setup <br> 
Connect sensors to the Arduino as per the circuit diagram.
Ensure the ESP8266 module is connected properly for Wi-Fi transmission.

2️⃣ Software Setup <br> 

🔹 Required Libraries <br>

Make sure you have these libraries installed in Arduino IDE: <br>
#include <Wire.h> <br>
#include <OneWire.h> <br>
#include <DallasTemperature.h> <br>
#include "MAX30105.h" <br>
#include "spo2_algorithm.h" <br>

### To install them:
Open Arduino IDE <br> 
Go to Sketch → Include Library → Manage Libraries <br>
Search for and install DallasTemperature, OneWire, MAX30105, and spo2_algorithm.

<br>

### 3️⃣ Uploading the Code

Open codes/ folder and select the appropriate .ino file. <br>
Connect the Arduino board via USB. <br>
Select the correct COM port in Arduino IDE. <br>
Click Upload and open the Serial Monitor to check sensor readings. <br>
<br>


### 📊 Results <br>

Here are some sample outputs from our system: <br>

📌 Temperature Readings: <br>
<br> 

<img width="307" alt="image" src="https://github.com/user-attachments/assets/b15d4663-ce94-4aa0-bcc3-c8aff4e0e6e0" /> <br> 

<br>

📌 ECG Signal: <br>
<img width="288" alt="image" src="https://github.com/user-attachments/assets/bb9b4452-6a0c-4fec-85bf-8a62e5191a8c" />

<br>

### 🎯 Future Improvements
🔹 Mobile App Integration – Build an Android/iOS app for real-time monitoring. <br>
🔹 AI-based Predictions – Use machine learning to predict potential health issues. <br>
🔹 Wearable Integration – Make the system compact and portable. <br>
🔹 Cloud Storage & Analytics – Store historical data for analysis. <br>

<br>

### 💡 Guided by Dr. Nandha Kumar R (VIT-AP University)

<br> 

### 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

<br>

### ✅ Badges
![Arduino](https://img.shields.io/badge/Arduino-Uno-blue.svg) <br>
![IoT](https://img.shields.io/badge/IoT-Project-green.svg) <br>
![Deep Learning](https://img.shields.io/badge/Deep_Learning-Project-blue.svg) <br>
![AI](https://img.shields.io/badge/AI-Project-green.svg)

