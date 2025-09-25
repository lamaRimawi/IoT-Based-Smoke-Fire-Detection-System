# 🔥 IoT-Based Smoke & Fire Detection System

This project implements a **comprehensive IoT-based fire detection and alarm system** that integrates wireless sensors, edge computing, and cloud services. It enhances building safety through **real-time monitoring, automated threat detection, and emergency response**.

---

## 📖 Overview

- **Smoke Detector**: Detects smoke in the air with a threshold of **40 ppm** (placed in bedrooms, kitchen, dining room).  
- **Carbon Monoxide Detector**: Monitors CO levels with a threshold of **3 ppm** (placed in living rooms, bedrooms, kitchen).  
- **Fire Monitor**: Detects fire with thresholds of **760 ppm (low)** and **1100 ppm (high)** (placed in kitchens and high-risk areas).  
- **Fire Sprinkler**: Activates automatically when fire is detected to suppress flames.  
- **Automatic Windows**: Open automatically when smoke or CO levels exceed thresholds to ventilate the area.  

The system uses **MQTT protocol** for communication:  
- **Sensors** → act as **Publishers**  
- **Actuators** (Alarm, Sprinkler, Windows, Email Alerts) → act as **Subscribers**  
- **Server** → acts as the **MQTT Broker**  

---

## 🏗️ System Architecture

The system is divided into three layers:

1. **Edge Layer**  
   - Wireless sensors (Smoke, CO, Fire)  
   - Actuators (Windows, Sprinklers, Alarms)  

2. **Gateway Layer**  
   - Collects data from sensors  
   - Forwards to server via MQTT  
   - Sends commands to actuators  

3. **Cloud Layer**  
   - MQTT Broker + Server  
   - Real-time monitoring dashboard  
   - Email alerts & notifications  

---

## 📡 Communication Flow

- Sensors publish data to MQTT topics.  
- Gateway forwards data to the server.  
- Server processes data and triggers actuators.  
- Actuators subscribe to topics and perform actions.  

---

## 🖼️ Project Screenshots

### 🔹 System Layout
![System Layout](https://drive.google.com/uc?export=view&id=1ol0owbvyag1IO_99nYTVEP1zGOVMnkxx)

### 🔹 Device Placement
![Device Placement](https://drive.google.com/uc?export=view&id=1L-CsukYoHQtWLSSMnTXaCwilMcV_TFhg)

### 🔥 Fire Detection in Action
![Fire Detection](https://drive.google.com/uc?export=view&id=1A92zpHBF-nmAjtwljNoeOqptBSdlkfGF)

### 🔗 MQTT Communication
![MQTT Communication 1](https://drive.google.com/uc?export=view&id=1D12UuQUPbcvxtqQnPIIKoSWW85kIDHr9)  
![MQTT Communication 2](https://drive.google.com/uc?export=view&id=127AQaXnPI-T6xD9plciDojapf_FQKXTK)

---

## ⚙️ Technologies Used

- **Cisco Packet Tracer** – IoT simulation  
- **Python** – MQTT client scripts for actuators & sensors  
- **MQTT Protocol** – Lightweight publish/subscribe communication  
- **Edge & Cloud Integration** – Real-time monitoring and control  

---

## 🚀 How It Works

1. Sensors detect smoke, CO, or fire.  
2. Data is published to the MQTT broker.  
3. Server processes data and decides actions.  
4. Actuators (windows, sprinklers, alarms) respond automatically.  
5. Alerts are sent to the monitoring dashboard and via email.  

---

## ✅ Conclusion

This IoT-based fire detection system provides **early warning, automated response, and real-time monitoring**. By combining **wireless sensors, MQTT communication, and cloud services**, it ensures a scalable and reliable safety solution for smart buildings.
