# real-time-iot-anomaly
End-to-end real-time anomaly detection pipeline for streaming IoT sensor data using Kafka, ML models, and Streamlit
# Real-Time IoT Sensor Anomaly Detection

[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

A full‐stack solution for streaming IoT sensor data, real‐time anomaly detection using machine learning (Isolation Forest, Autoencoders, LSTM), and live visualization with Streamlit. Ideal for predictive maintenance in smart manufacturing environments.

## 🚀 Features
- **Data Simulation**: Synthetic temperature, pressure, vibration, humidity and RPM streams.  
- **Streaming**: Kafka producer/consumer setup for real‐time data pipelines.  
- **Anomaly Models**:  
  - Isolation Forest  
  - Autoencoder neural network  
  - LSTM‐based sequence model  
- **Dashboard**: Interactive Streamlit app displaying live metrics & anomalies.  
- **Automation**: n8n workflow for data ingestion, storage, alerting, and maintenance scheduling :contentReference[oaicite:2]{index=2}  
- **Alerts**: Email, Slack, and Grafana annotations on anomaly detection.  

## 📐 Architecture
See [docs/architecture.md](docs/architecture.md) for an overview diagram, component descriptions, and data flow.

## ⚙️ Prerequisites
- Docker & Docker Compose  
- Python 3.8+  
- Apache Kafka  
- PostgreSQL (or your preferred SQL DB)  
- InfluxDB & Grafana (optional, for metrics dashboard)  
- Telegram Bot token & Chat ID (for demo alerts)  

## 🛠️ Installation

1. **Clone**  
   ```bash
   git clone https://github.com/yourusername/iot-anomaly-detection.git
   cd iot-anomaly-detection
