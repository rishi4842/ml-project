# 🚀 Smart IoT Data Compression Dashboard

An interactive web-based dashboard that demonstrates efficient compression techniques for IoT sensor data.

## 📌 Overview
This project focuses on reducing redundancy in sensor data using **Delta Encoding**, a lossless compression technique. Instead of transmitting full sensor values, only the difference between consecutive readings is sent.

This approach is highly effective for IoT systems where sensor values change gradually over time.

---

## ⚙️ Features

- 📊 Real-time data visualization (Original vs Reconstructed)
- 🔄 Step-by-step encoding process
- 📉 Compression output display
- 📈 Efficiency metrics (Compression ratio, Space saved)
- ⚡ Smooth UI with interactive charts
- 🎯 "Try Sample Data" for quick demo

---

## 🧠 Algorithms Used

### 1. Delta Encoding (Main Algorithm)
- Stores difference between consecutive values
- Lossless compression
- Best for gradually changing sensor data

### 2. Run-Length Encoding (RLE)
- Compresses repeated values
- Useful for constant sensor readings

### 3. Min-Max Normalization
- Scales values between 0 and 1
- Helps in efficient data transmission

---

## 📊 Example

### Input:
100, 101, 102, 103, 104

### Delta Encoded Output:
100, +1, +1, +1, +1

### Reconstruction:
100, 101, 102, 103, 104

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript
- Chart.js (for visualization)

---

## 🎯 Use Cases

- IoT sensor data transmission
- Time-series data optimization
- Smart devices and monitoring systems

---

## 📌 Key Concept

> Instead of sending full sensor values, transmit only the change (difference) between readings to reduce redundancy.

---

## 🚀 How to Run

1. Download or clone the repository
2. Open `index.html` in your browser
3. Enter sensor values (e.g., `100,101,102,103,104`)
4. Click **Compress**

---

## 📈 Output

- Encoded data stream
- Reconstructed values
- Graph comparison
- Compression efficiency metrics

---

## 👨‍💻 Author

Developed as a B.Tech project to demonstrate IoT data compression techniques.

---

## ⭐ Note

This project is a simulation of compression techniques and is intended for educational and demonstration purposes.
