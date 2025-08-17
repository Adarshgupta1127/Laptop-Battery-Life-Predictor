# Laptop-Battery-Life-Predictor
# 🔋 Laptop Battery Life Predictor

## 📖 Overview
The **Laptop Battery Life Predictor** is a machine learning project designed to estimate the remaining battery hours of a laptop in real-time. By analyzing system-level features such as **RAM usage, CPU load, screen brightness, and running applications**, the predictor achieves **R² of 0.87** using optimized regression models.

This project helps users **anticipate battery life more accurately** compared to default OS-level predictions, making it useful for developers, students, and professionals working in mobile environments.

---

## ✨ Features
- ✅ Real-time system metric collection (RAM, CPU load, brightness, app usage)
- ✅ Automated dataset generation pipeline (10K+ labeled records)
- ✅ ML model training with **Random Forest** & **XGBoost**
- ✅ Hyperparameter tuning & cross-validation
- ✅ 25% reduction in prediction error compared to baseline models
- ✅ Predicts remaining battery hours in **minutes** or **hours**

---

## ⚙️ Tech Stack
- **Programming Language**: Python 3.x  
- **Libraries**: 
  - `scikit-learn`
  - `xgboost`
  - `pandas`, `numpy`
  - `psutil` (for system metrics logging)
  - `matplotlib`, `seaborn` (for visualization)  

---

## 📂 Project Structure
Laptop-Battery-Life-Predictor/
│── data/ # Collected datasets
│── models/ # Trained ML models
│── notebooks/ # Jupyter notebooks for experimentation
│── src/ # Python source code
│ ├── data_logger.py # Logs system metrics in real-time
│ ├── train_model.py # Trains ML models with hyperparameter tuning
│ ├── predictor.py # Battery life prediction script
│── results/ # Model evaluation reports & plots
│── requirements.txt # Required Python packages
│── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Laptop-Battery-Life-Predictor.git
   cd Laptop-Battery-Life-Predictor
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Start system metrics logging:

bash
Copy
Edit
python src/data_logger.py
Train models:

bash
Copy
Edit
python src/train_model.py
Predict battery life:

bash
Copy
Edit
python src/predictor.py
📊 Results
R² Score: 0.87

Prediction Error Reduction: 25% compared to baseline

Dataset Size: 10,000+ labeled records

Best Models: Random Forest, XGBoost

