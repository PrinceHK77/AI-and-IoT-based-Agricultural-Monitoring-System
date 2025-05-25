# 🌾 Smart Agriculture Suite

This repository contains two AI + IoT-based agricultural solutions designed to help farmers and agronomists manage plant health and field conditions efficiently:

1. **Plant Leaf Disease Detection Web App** – an ML-based image classifier for identifying plant diseases.
2. **Agricultural Monitoring System** – a real-time IoT system for monitoring and automating field parameters like watering, fire alerts, and more.

---
![Screenshot 2024-04-20 171729](https://github.com/user-attachments/assets/0d231655-e94a-4486-9ebc-778bce7bed4d)
![Screenshot 2024-04-20 172019](https://github.com/user-attachments/assets/f89f364d-58bd-453b-935c-49dceca45f6e)

![Screenshot 2024-04-20 174524](https://github.com/user-attachments/assets/60f0a424-284d-42c6-9e94-2835d1566183)
![Screenshot 2024-04-20 174651](https://github.com/user-attachments/assets/c9a6a89a-2433-4c48-9ddb-e987c317e057)

## 🌿 1. Plant Leaf Disease Detection Web App in Multilingual languages

A user-friendly web application where farmers can upload images of diseased plant leaves and receive:

- ✅ Disease name
- ❗ Reason for infection
- 💊 Recommended remedies

### 🔧 Technologies

- Python
- Machine Learning (Image Classification)
- Streamlit
- OpenCV
- HTML, CSS

### 📌 Features

- Upload and classify diseased leaf images
- Pre-trained ML model identifies disease
- Detailed remedy and cause explanations
- Fast, mobile-friendly UI built using Streamlit

![Uploading Screenshot 2024-04-20 174524.png…]()
## 🌾 2. Agricultural Monitoring System (IoT)

A sensor-driven smart farming system that automates irrigation, detects fire/gas presence, and adapts watering logic based on weather models.

### 🔧 Technologies

- Arduino (for hardware logic)
- Python (for ML/weather logic)
- IoT Sensors:
  - DHT11 (Temperature & Humidity)
  - Soil Moisture Sensor
  - Gas Sensor
  - Watering Motor (Pump)

### 🔌 Features

- 🌱 Soil moisture-based auto irrigation
- 🌡️ Temperature & humidity live tracking
- 🔥 Fire alarm based on gas/temp threshold
- ⛈️ ML-enhanced watering system using weather data
- 📈 Optional dashboard (web/serial-based)

### 🧠 System Workflow

1. Sensors collect environmental data.
2. If thresholds crossed (e.g., soil is dry), motor activates watering system.
3. Gas levels above safety trigger fire alarm.
4. External weather data improves irrigation efficiency using a lightweight ML model.


---

## 🧑‍🌾 Benefits to Farmers

| Feature                        | Value Delivered                                 |
|-------------------------------|--------------------------------------------------|
| 🚑 Disease Identification      | Reduces crop loss through timely treatment       |
| 💧 Auto Irrigation             | Conserves water and labor                        |
| 🔥 Fire Detection              | Protects farmland from hazardous events          |
| 📊 Data-Driven Decisions       | Encourages smart, tech-assisted agriculture      |

---

## 🛠 Future Enhancements

- Mobile app for field use
- Cloud storage for sensor logs
- AI-based pest prediction (Vision + Climate)
- Multilingual remedy guides
- SMS alert integration for fire/irrigation triggers

---

> “Technology meets tradition — building smarter farms, safer crops, and sustainable futures.”
