# 🔥 IoT-Based Smoke & Fire Detection System

A smart fire safety solution integrating wireless sensors, edge computing, and cloud services for real-time monitoring, automated threat detection, and emergency response.

---

## 📖 Overview

- **Smoke Detector**: Threshold 40 ppm — placed in bedrooms, kitchen, dining room.  
- **CO Detector**: Threshold 3 ppm — placed in living rooms, bedrooms, kitchen.  
- **Fire Monitor**: Thresholds 760 ppm (low), 1100 ppm (high) — placed in kitchens and high-risk areas.  
- **Fire Sprinkler**: Activates automatically to suppress flames.  
- **Automatic Windows**: Open when smoke or CO exceeds thresholds to ventilate.

**MQTT Protocol** powers communication:  
- Sensors → **Publishers**  
- Actuators → **Subscribers**  
- Server → **MQTT Broker**

---

## 🏗️ Architecture

- **Edge Layer**: Sensors + Actuators  
- **Gateway Layer**: Data collection + forwarding  
- **Cloud Layer**: MQTT Broker + Monitoring + Alerts

---

## 📡 Communication Flow

1. Sensors publish data  
2. Gateway forwards to server  
3. Server processes and triggers actuators  
4. Actuators respond via MQTT subscriptions

---

## 🖼️ Visuals

### 🔹 Layout  
![System Layout](https://drive.google.com/uc?export=view&id=1ol0owbvyag1IO_99nYTVEP1zGOVMnkxx)

### 🔹 Device Placement  
![Device Placement](https://drive.google.com/uc?export=view&id=1L-CsukYoHQtWLSSMnTXaCwilMcV_TFhg)

### 🔥 Fire Detection  
![Fire Detection](https://drive.google.com/uc?export=view&id=1A92zpHBF-nmAjtwljNoeOqptBSdlkfGF)

### 🔗 MQTT Logs  
![MQTT 1](https://drive.google.com/uc?export=view&id=1D12UuQUPbcvxtqQnPIIKoSWW85kIDHr9)  
![MQTT 2](https://drive.google.com/uc?export=view&id=127AQaXnPI-T6xD9plciDojapf_FQKXTK)

### 🎥 Demo Video  
[▶ Watch Demo](https://drive.google.com/file/d/1nJuw_vwiHw14hh6zp53dTlPQwzC_z8Kh/view?usp=sharing)

---

## ⚙️ Technologies

- **Cisco Packet Tracer** – IoT simulation  
- **Python** – MQTT scripts  
- **MQTT** – Lightweight publish/subscribe protocol  
- **Cloud Integration** – Monitoring + Alerts

---

## 🚀 How It Works

- Sensors detect smoke, CO, or fire  
- Data sent via MQTT to server  
- Server triggers actuators  
- System responds automatically  
- Alerts sent to dashboard and email

---

## ✅ Conclusion

A scalable, real-time IoT system for fire safety — combining smart sensors, MQTT communication, and automated emergency response to protect indoor environments.
