# Rainfall Prediction Web Application

A machine learning web application that predicts rainfall probability based on weather parameters using Random Forest algorithm.

## 🌟 Features
- 🌦️ Real-time rainfall prediction
- 🎯 7 weather parameter inputs
- 📱 Fully responsive web interface
- 📊 Confidence score display
- 🚀 Fast and accurate predictions

## 🛠️ Technologies Used
- **Backend:** Python, Flask, Scikit-learn, Pandas, NumPy
- **Frontend:** HTML5, CSS3, JavaScript
- **Machine Learning:** Random Forest Classifier
- **Version Control:** Git, GitHub

## 📋 Input Parameters
1. **Pressure** (hPa) - Atmospheric pressure
2. **Dew Point** (°C) - Temperature at which condensation occurs
3. **Humidity** (%) - Relative humidity
4. **Cloud Cover** (%) - Percentage of cloud coverage
5. **Sunshine** (hours) - Duration of sunshine
6. **Wind Direction** (degrees) - Wind direction in degrees
7. **Wind Speed** (km/h) - Wind speed

## 🚀 Installation & Setup

### Prerequisites
- Python 3.7+
- Git

### Step-by-Step Installation
```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/rainfall-prediction-app.git

# 2. Navigate to project directory
cd rainfall-prediction-app

# 3. Install required packages
pip install flask pandas scikit-learn numpy

# 4. Run the application
python app.py

# 5. Open your browser and visit
# http://127.0.0.1:5000


rainfall-prediction-app/
├── app.py                         # Main Flask application
├── rainfall_prediction_model.pkl  # Trained ML model
├── templates/
│   └── index.html                 # Web interface
└── README.md                      # Project documentation
