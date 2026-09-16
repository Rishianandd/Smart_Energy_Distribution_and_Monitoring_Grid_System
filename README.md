# ⚡ Smart Energy Distribution and Monitoring Grid System

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-IoT-blue?style=flat&logo=espressif" />
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-orange?style=flat&logo=scikit-learn" />
  <img src="https://img.shields.io/badge/XGBoost-ML-green?style=flat" />
  <img src="https://img.shields.io/badge/LightGBM-ML-green?style=flat" />
  <img src="https://img.shields.io/badge/CatBoost-ML-red?style=flat" />
  <img src="https://img.shields.io/badge/IoT-ThingSpeak-purple?style=flat" />
  <img src="https://img.shields.io/badge/Dashboard-Grafana-orange?style=flat" />
</p>

---

## 🚀 Project Overview

This project implements an **IoT-powered, Machine Learning-enhanced Smart Energy Distribution and Monitoring Grid System** designed for real-time energy monitoring, renewable energy integration, predictive analytics, and intelligent energy management.

The system combines **ESP32, voltage and current sensors, solar energy, battery storage, IoT communication, Machine Learning, and real-time dashboards** to monitor and analyze electrical energy consumption.

The ESP32 collects real-time electrical parameters such as **voltage and current**, calculates power consumption, and transmits the data wirelessly using **Wi-Fi, MQTT, or HTTP**.

Historical energy data is then processed and used to train Machine Learning regression models including **XGBoost, LightGBM, and CatBoost** for energy consumption forecasting.

The system also integrates a **solar panel, 18650 Li-ion battery, Battery Management System (BMS), and buck converter** to support renewable-energy-powered and battery-backed operation.

### 🔄 Overall Pipeline

```text
☀️ Solar Energy
      ↓
🔋 Battery + BMS
      ↓
⚡ Voltage & Current Sensing
      ↓
💻 ESP32 Data Acquisition
      ↓
📡 Wi-Fi / MQTT / HTTP
      ↓
☁️ IoT Data Collection
      ↓
🧹 Data Preprocessing
      ↓
⚙️ Feature Engineering
      ↓
🤖 Machine Learning
      ↓
XGBoost / LightGBM / CatBoost
      ↓
📊 Model Evaluation
      ↓
📈 Energy Consumption Forecasting
      ↓
🚨 Anomaly Detection
      ↓
🖥️ Dashboard Visualization
