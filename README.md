#  AI-Assisted Wi-Fi Occupancy Sensing System

## Overview

This project is a privacy-preserving indoor occupancy sensing system using ESP32-S3 Wi-Fi CSI/RSSI signal analysis and Machine Learning.

The system detects human occupancy and motion activity without using cameras or wearable devices by analyzing RF disturbances in Wi-Fi signal propagation.

---

## Features

- Real-time Wi-Fi occupancy sensing
- ESP32-S3 based RF sensing pipeline
- Random Forest ML occupancy classifier
- Hybrid ML + signal processing architecture
- Live Streamlit dashboard
- Motion/activity estimation
- RF pulse visualization
- Environment stability analysis

---

## Achieved Results

- ~90% binary occupancy classification accuracy
- Real-time inference using live RF data
- Privacy-preserving occupancy sensing

---

## Hardware Used

- ESP32-S3 (Transmitter)
- ESP32-S3 (Receiver)
- Laptop/Desktop

---

## Software Stack

- Python
- Streamlit
- Scikit-learn
- NumPy
- Pandas
- PySerial

---

## Dashboard Preview

![Dashboard](screenshots/dashboard.png)