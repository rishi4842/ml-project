# 🚀 Smart IoT Data Compression Dashboard

An interactive web-based dashboard demonstrating optimization-based data compression for IoT sensor data.

## 📌 Overview
This project models IoT data transmission as an optimization problem.  
The goal is to minimize transmission cost by reducing redundancy.

We use **Delta Encoding**, where only differences between consecutive values are transmitted instead of full data.

## ⚙️ Features
- Real-time visualization (Original vs Reconstructed)
- Step-by-step encoding process
- Optimization metrics (Cost reduction, bits saved)
- Prediction-based compression (ML-style approach)

## 🧠 Concept
Cost Function:
J = total bits transmitted

We minimize J using predictive encoding:
delta = current - previous

## 🌐 Live Demo
https://rishi4842.github.io/ml-project/

## 🛠️ Tech Used
- HTML
- CSS
- JavaScript (Chart.js)

## 🎯 Use Case
Efficient IoT data transmission, edge computing, and bandwidth optimization.
