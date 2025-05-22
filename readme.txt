# 🌾 Crop Recommendation System

**Using Machine Learning and Sensors to Boost Sustainable Farming**

This project is a full-stack Crop Recommendation System designed to help farmers make informed decisions about which crop to cultivate based on soil and environmental conditions. It combines a Flask-based backend that uses a machine learning model with a responsive React frontend.

---

## 📌 Features

- 🔍 Predicts the most suitable crop based on user input (N, P, K, temperature, humidity, pH, rainfall)
- 🤖 Machine learning model (Random Forest) trained on agricultural datasets
- 🌐 Flask API for backend prediction
- 💻 Responsive and modern React frontend with routing and chart visualizations
- 🌦️ Weather forecasting component

---

## 🛠 Tech Stack

### Frontend
"@headlessui/react": "^2.2.0",
    "@heroicons/react": "^2.2.0",
    "@reduxjs/toolkit": "^2.8.2",
    "axios": "^1.7.9",
    "chart.js": "^4.4.9",
    "lucide-react": "^0.511.0",
    "moment": "^2.30.1",
    "react": "^18.3.1",
    "react-chartjs-2": "^5.3.0",
    "react-dom": "^18.3.1",
    "react-icons": "^5.5.0",
    "react-redux": "^9.2.0",
    "react-router-dom": "^7.0.2"

### Backend
- Python 3.12
- Flask
- scikit-learn
- numpy, pandas
- CORS



---

Frontend Setup-
 cd frontend
 npm install
 npm run dev

📍 App runs on: http://localhost:5173

API Endpoint-
 POST /predict