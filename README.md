<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:38bdf8&height=220&section=header&text=Bitcoin%20Predictor%20Agent&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI-Powered%20Multi-Model%20Crypto%20Forecasting%20Dashboard&descAlignY=55&descAlign=50" width="100%"/>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![TensorFlow](https://img.shields.io/badge/TensorFlow-LSTM-FF6F00?logo=tensorflow)
![XGBoost](https://img.shields.io/badge/XGBoost-Regressor-EC4E20)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)
![Status](https://img.shields.io/badge/Status-Production_Ready-success)

</p>

---

# 🧠 Overview

**Bitcoin Predictor Agent** is a production-grade AI forecasting dashboard that demonstrates real-world full-stack machine learning system design.

It:

- Trains multiple time-series forecasting models
- Automatically selects the best model using RMSE
- Generates 30-day forward predictions
- Provides interactive visual analytics
- Supports live market data & file uploads
- Runs locally or fully containerized via Docker

This project showcases end-to-end AI architecture — from model orchestration to interactive UI deployment.

---

# 🎬 Live Demo

<p align="center">
  <img src="assets/demo.gif" width="100%" />
</p>

👉 **Watch 20-sec Demo Video:**  
[Click here to view demo](./assets/BitCoinPredictorAgent.mp4)

---

# ✨ Core Capabilities

## 📊 Multi-Model Forecasting
- LSTM (50 / 100 epochs)
- SARIMA (multiple parameter combinations)
- Facebook Prophet
- XGBoost Regressor

## 🏆 Automated Model Selection
- Validation split evaluation
- RMSE-based ranking
- MAE & MAPE performance metrics
- Best-model highlighting in UI

## 📈 Interactive Visualization
- Last 30 days (actual)
- Next 30 days (forecast)
- Toggle models on/off
- Best model emphasis
- Custom legend UI
- Future region visual separator

## 📂 Flexible Data Sources
- Yahoo Finance (BTC-USD)
- CSV Upload
- Excel Upload (.xlsx)

## ⚡ Deployment Options
- `run.sh` (Mac / Linux)
- `run_win.bat` (Windows)
- `docker-compose up --build` (Recommended)

---

# 🏗 System Architecture

```
User (React UI)
       ↓
FastAPI Backend
       ↓
AutoML Orchestrator
       ↓
Model Training Layer
   ├── LSTM (TensorFlow)
   ├── SARIMA (Statsmodels)
   ├── Prophet
   └── XGBoost
       ↓
Evaluation Engine (RMSE, MAE, MAPE)
       ↓
Forecast Response → Interactive Chart.js Visualization
```

This architecture mirrors real-world AI product systems.

---

# 🛠 Technology Stack

## Frontend
- React
- Chart.js
- React-ChartJS-2
- Axios

## Backend
- FastAPI
- Scikit-learn
- TensorFlow / Keras
- Statsmodels
- Prophet
- XGBoost
- Pandas / NumPy
- yfinance

## DevOps
- Docker
- Docker Compose

---

# 🚀 Quick Start

---

## 🐳 Run with Docker (Recommended)

From project root:

```bash
docker-compose up --build
```

This will:

- Build backend container
- Build frontend container
- Install dependencies
- Start both services

### Access:

Frontend:
```
http://localhost:3000
```

Backend API Docs:
```
http://localhost:8000/docs
```

To stop:

```bash
docker-compose down
```

---

## 🖥 Run on macOS / Linux (Without Docker)

```bash
chmod +x run.sh
./run.sh
```

---

## 🪟 Run on Windows

```bash
run_win.bat
```

---

# 📊 Model Evaluation Logic

Primary metric:
- **RMSE**

Secondary metrics:
- MAE
- MAPE

The model with the lowest RMSE on validation data is selected automatically as the best model.

---

# 📁 Project Structure

```
BitcoinPredictorAgent/
│
├── backend/
│   ├── app/
│   ├── requirements.txt
│   └── main.py
│
├── frontend/
│   ├── src/
│   ├── package.json
│
├── assets/
│   ├── demo.gif
│   └── BitCoinPredictorAgent.mp4
│
├── docker-compose.yml
├── run.sh
├── run_win.bat
└── README.md
```

---

# 💼 Professional Context

Built as part of applied AI system design exploration.

**Ketan Swaroop**  
Deloitte Certified Technical Architect | Former Deloitte (8+ Years)  
Executive Program in Data Science & AI — IIM Lucknow Alumni  

---

---

## 🔐 Source Code Access

<p align="center">

The complete implementation is maintained privately to protect intellectual property.  

If you are a recruiter, hiring manager, or potential collaborator and would like access:

</p>

<br>

<p align="center">

<a href="https://www.linkedin.com/in/ketan-swaroop-8bbba515" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Ketan%20Swaroop-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

&nbsp;&nbsp;

<a href="https://github.com/kswar06" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-kswar06-111827?style=for-the-badge&logo=github&logoColor=white"/>
</a>

&nbsp;&nbsp;

<a href="mailto:ketan.swaroop.majestic@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

<br>

<p align="center">
Access available upon request.
</p>


---

# ⭐ Support

If you find this project interesting, consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is intended for educational and demonstration purposes.