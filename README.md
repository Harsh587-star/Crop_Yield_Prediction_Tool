# 🌱 Crop Yield Pro - Advanced Agricultural Intelligence Platform

## 🚀 Overview
Crop Yield Pro is an advanced, data-driven agricultural intelligence platform designed to help farmers, agribusinesses, and researchers make smarter decisions.

It uses machine learning and analytics to predict crop yields, optimize inputs, and improve profitability while promoting sustainable farming practices.

---

## ✨ Key Features (Version 2.0)

### 🤖 Advanced Machine Learning
- Ensemble models:
  - XGBoost  
  - Random Forest  
  - Gradient Boosting  
- High accuracy predictions  
- Scalable ML pipeline  

### 📊 Smart Dashboard
- Multi-page interactive UI  
- Real-time insights  
- Trend analysis  

### 💰 Economic Analysis
- ROI (Return on Investment)  
- Cost-benefit analysis  
- Fertilizer optimization  

### 🌾 Smart Recommendations
- Crop suggestions  
- Soil & climate-based insights  
- Personalized farming strategies  

### ⚠️ Risk & Sustainability
- Risk prediction  
- Sustainability metrics  
- Long-term insights  

### 🎨 UI/UX
- Dark/Light mode  
- Responsive design  
- Interactive charts  

---

## 🛠️ Tech Stack
- **Backend**: Python  
- **Machine Learning**: Scikit-learn, XGBoost  
- **Frontend**: Streamlit  
- **Database**: MySQL  
- **Visualization**: Matplotlib, Plotly  

---

## 📋 Prerequisites
- Python 3.8+  
- MySQL 5.7+  
- Minimum 4GB RAM  
- Internet connection  

---
## ⚙️ Installation

# 1. Clone the Repository
git clone <your-repo-link>
cd crop-yield-pro

# 2. Create Virtual Environment
python -m venv venv

# Activate Virtual Environment
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

# 3. Install Dependencies
pip install --upgrade pip
pip install -r requirements.txt

# 4. Setup MySQL Database
# Open MySQL and run:
# CREATE DATABASE crop_yield_pro;

# Then configure environment variables (create a .env file or config file)
# Example:
# DB_HOST=localhost
# DB_USER=root
# DB_PASSWORD=your_password
# DB_NAME=crop_yield_pro

# 5. Run Migrations (if using Django)
python manage.py migrate

# 6. Train Machine Learning Model (optional)
python train_model.py

# 7. Run the Application
streamlit run app.py

# 8. Open in Browser
# http://localhost:8501

# Optional: Install extra libraries if needed
pip install xgboost plotly mysql-connector-python

# Optional: Run on different port
streamlit run app.py --server.port 8502
