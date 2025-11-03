# 🌞 Renewable Energy Forecasting  

*A Machine Learning & Deep Learning approach for accurate renewable energy prediction*

---

## 📘 Overview  
This project focuses on **forecasting renewable energy output** (solar/wind) using both **statistical models** and **deep learning architectures**.  
It compares **ARIMA** and **Facebook Prophet** with an **LSTM neural network**, demonstrating how advanced time-series techniques can improve forecasting accuracy.  

This research was part of an academic project and is supported by a **certificate** and a **research publication**, both included in this repository.

---

## 🧠 Objectives  
- Forecast renewable energy generation using time-series data.  
- Compare classical vs deep learning forecasting approaches.  
- Visualize and evaluate model accuracy using metrics such as MAE, MSE, and RMSE.  

---

## 🗂️ Repository Structure  
```
Renewable-Energy-Forecasting-/
├── ARIMA and F-PROPHET.ipynb      → Time-series forecasting using ARIMA & Prophet
├── LSTM_MODEL_ipynb.ipynb          → Deep learning (LSTM) forecasting implementation
├── filtered_time_series.csv        → Cleaned dataset for model input
├── final_thesis_dataset.csv        → Combined dataset used in analysis
├── docs/
│   ├── certificate.pdf             → Official project completion certificate
│   └── research_paper.pdf          → Published research paper
└── README.md                       → Project documentation
```
---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/sathiyaseelanjr/Renewable-Energy-Forecasting-.git
cd Renewable-Energy-Forecasting-
python3 -m venv venv
source venv/bin/activate          # Windows: venv\Scripts\activate
pip install --upgrade pip
pip install jupyter numpy pandas matplotlib scikit-learn tensorflow statsmodels prophet
```
---
##  🧪 Running the Models

ARIMA & Prophet

Open the notebook:
```bash
jupyter notebook "ARIMA and F-PROPHET.ipynb"
```
Run all cells to see preprocessing, training, forecasting, and evaluation.

LSTM Model
```bash
jupyter notebook LSTM_MODEL_ipynb.ipynb
```
This notebook handles:
- Time window creation
- Normalization and reshaping for LSTM input
- Model training and predictions
- Graphical results (actual vs predicted)
---
##  📈 Evaluation Metrics
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)

Each notebook includes visual comparisons and performance summaries.

---

##  🔍 Future Enhancements
- Incorporate Transformer models for sequence forecasting
- Build a real-time web dashboard for live energy prediction
- Optimize hyperparameters using Bayesian Optimization
- Add requirements.txt and LICENSE for reproducibility and open-source clarity

---
 
##  👨‍💻 Author
Sathiyaseelan J
- GitHub: @sathiyaseelanjr￼
- Project: Renewable Energy Forecasting
- Research Focus: Data-Driven Energy Prediction and Smart Grid Analytics
  
##  💡 Acknowledgement
- This project was completed as part of an academic research initiative.
- Special thanks to the mentors and peers who provided guidance and insights throughout the project.

---
