# 🌱 Crop Yield Pro - Advanced Agricultural Intelligence Platform

## 🎯 What's New in Version 2.0
- **Advanced ML Models**: Ensemble methods with XGBoost, Random Forest, and Gradient Boosting
- **Beautiful UI/UX**: Dark/Light mode, responsive design, interactive charts
- **Economic Analysis**: ROI calculations, cost-benefit analysis, fertilizer optimization
- **Smart Recommendations**: Personalized farming recommendations
- **Advanced Analytics**: Risk assessment, sustainability metrics, trend analysis
- **Multi-page Dashboard**: Comprehensive farmer dashboard with insights

## 📋 Prerequisites
- Python 3.8+
- MySQL 5.7+
- 4GB RAM minimum
- Internet connection (for weather data)

## 🚀 Quick Setup & Run

### 1. Environment Setup
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

#Train the moddel
#for train.py file
python train.py
This will train the crop yield prediction model and save something like:
models/yield_model.pkl
models/scaler.pkl

#for train_risk_model.py
python train_risk_model.py
This will train the crop yield prediction model and save something like:
models/yield_model.pkl
models/scaler.pkl

#Run the Project
streamlit run file_name(the main file).py
