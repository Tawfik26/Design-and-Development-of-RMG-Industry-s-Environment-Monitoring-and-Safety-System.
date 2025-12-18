# Design-and-Development-of-RMG-Industry-s-Environment-Monitoring-and-Safety-System.
To create a professional and comprehensive GitHub `README.md` for your RMG Industry project, use the following structure. It is designed to highlight the technical depth and real-world application of your work.

---

# Design and Development of RMG Industry's Environment Monitoring and Safety System

## 📌 Project Overview

The Ready-Made Garment (RMG) industry is a vital sector that often faces significant safety challenges due to environmental hazards. This project presents an automated **IoT-based safety system** designed to monitor critical environmental parameters in real-time to prevent accidents and ensure worker safety.

The system detects fire, gas leaks, and unsafe temperature/humidity levels, triggering immediate alerts to mitigate risks such as short circuits or industrial fires.

## 🚀 Key Features

* 
**Multi-Sensor Monitoring:** Real-time tracking of temperature, humidity, smoke, and hazardous gas levels.


* 
**Dual Alert System:** Features both local alerts (Buzzer/LCD) and remote notifications via IoT.


* 
**Automated Fire Suppression:** Integrated water pump system that activates automatically upon fire detection.


* 
**Cloud Connectivity:** Data is transmitted to the **Blynk IoT platform** for remote monitoring by factory supervisors.


* 
**Reliable Hardware:** Built using the **NodeMCU (ESP8266)** for efficient Wi-Fi-based data processing.



## 🛠️ Hardware Stack

| Component | Function |
| --- | --- |
| **NodeMCU (ESP8266)** | Central processing unit and Wi-Fi gateway.

 |
| **DHT11 Sensor** | Monitors temperature and humidity levels.

 |
| **MQ-2 Sensor** | Detects smoke and flammable gas leakages.

 |
| **Flame Sensor** | Provides high-speed detection of fire/flames.

 |
| **L298N Driver** | Controls the 5V DC water pump for fire extinguishing.

 |
| **LCD (16x2)** | Displays real-time status and sensor readings locally.

 |

## 📊 System Architecture

The system operates in a continuous loop to ensure zero downtime:

1. 
**Data Acquisition:** Sensors collect environmental data from the factory floor.


2. 
**Logic Processing:** NodeMCU compares values against safety thresholds (e.g., High Temp or Gas detected).


3. 
**Local Response:** If a hazard is detected, the buzzer sounds and the water pump activates.


4. 
**Cloud Sync:** All data is pushed to the Blynk app for real-time visualization and emergency logging.



## 📈 Significance

* 
**Prevents Disasters:** Early detection of smoke and heat prevents catastrophic fires common in garment factories.


* 
**Worker Health:** Maintains optimal humidity and temperature to prevent heat exhaustion.


* 
**Compliance:** Helps factories meet international safety standards and audits.
