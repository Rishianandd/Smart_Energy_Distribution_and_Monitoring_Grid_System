# ⚡ Smart Energy Distribution and Monitoring Grid System

An **IoT-powered, ML-enhanced smart grid** that enables **real-time energy monitoring**, **solar-powered autonomy**, and **predictive analytics** for efficient and sustainable power distribution.

---

## 🌐 Overview

As global energy demand soars and sustainability becomes critical, traditional power grids struggle with inefficiencies and a lack of real-time insight. This project introduces a **Smart Energy Distribution and Monitoring Grid System**—a modular, scalable platform combining **IoT, machine learning**, and **renewable energy** to optimize power consumption across homes, offices, and small industrial units.

---

## 🎯 Objectives

- 🔍 **Monitor** voltage, current, and power usage in real-time.
- 📡 **Transmit** sensor data wirelessly using ESP32 and Wi-Fi.
- 🔋 **Operate autonomously** using solar energy and battery backup.
- 📊 **Forecast** future power consumption using ML regression models.
- 🖥️ **Visualize** real-time and predicted data via a dashboard.

---

## 🧰 Technologies Used

| Domain              | Tools/Components                                 |
|---------------------|--------------------------------------------------|
| Microcontroller     | ESP32                                            |
| Sensors             | ACS712 (Current), ZMPT101B (Voltage)            |
| Power Supply        | Solar Panel, 18650 Li-ion Battery, BMS, Buck Converter |
| Communication       | WiFi, MQTT/HTTP Protocol                        |
| ML Algorithms       | XGBoost, LightGBM, CatBoost                     |
| Data Visualization  | ThingSpeak, Grafana, Node-RED                   |
| Language & Tools    | Python, Jupyter, Arduino IDE                    |

---

## 📐 System Architecture

The system operates across five interconnected layers:

1. **Sensing Layer**: Real-time voltage and current monitoring using sensors.
2. **Communication Layer**: Wireless data transmission via ESP32 and WiFi.
3. **Processing Layer**: Data cleaning, normalization, and storage.
4. **Prediction Layer**: ML-based forecasting using historical energy data.
5. **Presentation Layer**: Dashboard displaying real-time and predicted data.

---

## 🧪 ML Model Performance

| Model     | R² Score | MSE            | Notes                        |
|-----------|----------|----------------|------------------------------|
| XGBoost   | 0.9965   | Medium         | High accuracy, fast training |
| LightGBM  | 0.9967   | Low            | Lightweight, efficient       |
| CatBoost  | 0.9971   | **Lowest**     | Best performance overall     |

📈 **CatBoost** was selected as the primary model due to its superior forecasting accuracy and generalization.

---

## 💻 Dashboard Preview

The system features a responsive dashboard showing:

- 🔌 Real-time energy usage (voltage, current, power)
- 📈 Predicted consumption trends
- 🚨 Load anomalies and alert notifications
- 🌞 Solar charging and battery status (optional)

> Built with Grafana/Node-RED for live charts and seamless UI.

---

## 🔋 Power System

- ☀️ **Solar Panel**: Harvests daylight energy
- 🔋 **18650 Battery**: Rechargeable backup with BMS
- 🔌 **Buck Converter**: Ensures safe 3.3V for ESP32 and peripherals
- 🧯 **Safety Features**: Fuses, relays, and isolation circuits

---

## 📚 References

> Refer to the [Project Report (PDF)](https://github.com/BSRohit20/Smart-Energy-Distribution-and-Monitoring-Grid-System/blob/main/Smart%20Energy%20Distribution%20and%20Monitoring%20Grid%20System/Smart%20Energy%20Distribution%20and%20Monitoring%20Grid%20System.pdf) for detailed technical documentation, circuit designs, and references to academic sources.

---
