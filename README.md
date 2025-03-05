# **Time Series Forecasting in Python**

_A repository containing an advanced time series forecasting project with LSTM, XGBoost, and Ensemble Learning._

## 🔹 **Overview**
This project focuses on **predicting time series data** using a combination of **machine learning and deep learning** techniques. It incorporates **feature engineering, hyperparameter tuning, and ensemble learning** for robust forecasting.

✅ **Key Features:**
- Time Series Forecasting using **XGBoost, LSTM, and GRU** 📈
- **Feature Engineering** (Lag Features, EWMA, Seasonal Features) 🛠️
- **Hyperparameter Optimization** with **Optuna** 🔍
- **Walk-Forward Validation** to prevent data leakage 🏆
- **Stacking Ensemble Model** for better accuracy 🔗
- **Model Interpretability** with **SHAP & Permutation Importance** 📊
- **Interactive Visualizations** using **Plotly** 📌

## 🔹 **Tech Stack**
- 🟢 **Python** (Pandas, NumPy, Sci-kit Learn, TensorFlow, Optuna, SHAP, Plotly)
- 🟢 **Jupyter Notebook / Google Colab**
- 🟢 **Libraries**: XGBoost, LightGBM, Ridge Regression, MinMaxScaler, StandardScaler

## 🔹 **Feature Engineering**
✅ **Lag Features** (1-day, 7-day, 30-day)  
✅ **Exponential Weighted Moving Averages (EWMA)**  
✅ **Seasonality Features** (Sine & Cosine Transform)  
✅ **Day of the Week, Quarter, and Weekend Indicators**  

## 🔹 **Installation & Setup**
```bash
# Clone the repository
git clone https://github.com/your-username/time_series_forecasting.git

# Navigate to the project folder
cd time_series_forecasting

# Install dependencies
pip install -r requirements.txt
```

## 🔹 **How to Use?**
1. Load the dataset (`gold_monthly_csv.csv`)
2. Preprocess and scale data
3. Train XGBoost and LSTM models
4. Generate predictions using **stacked ensemble learning**
5. Evaluate models using **RMSE, MAE, R², MAPE**
6. Visualize results with **Plotly**

## 🔹 **Model Performance & Evaluation**
📌 **Metrics Used:** MAE, RMSE, R², MAPE  
📌 **Validation Strategy:** Walk-Forward Cross-Validation  
📌 **Hyperparameter Tuning:** Optuna for XGBoost & LSTM  

## 🔹 **Example Code: LSTM Training**
```python
lstm_model = Sequential([
    Bidirectional(LSTM(100, return_sequences=True, input_shape=(sequence_length, X_train.shape[1]))),
    Dropout(0.2),
    GRU(100, return_sequences=False),
    Dropout(0.2),
    Dense(1)
])

lstm_model.compile(optimizer='adam', loss='mse')
lstm_model.fit(generator, epochs=20, verbose=1)
```

## 🔹 **Future Improvements**
✅ **Optimize LSTM with GRU for better efficiency**  
✅ **Try Attention Mechanism for time series forecasting**  
✅ **Improve hyperparameter tuning using Bayesian Optimization**  
✅ **Deploy model using Flask / FastAPI**  

## 🔹 **Contributing**
Want to contribute? Follow these steps:  
1. Fork the repository  
2. Create a new branch (`feature-xyz`)  
3. Commit changes  
4. Push to the branch  
5. Open a Pull Request  

## 🔹 **Contact** 
🔗 [LinkedIn](# **Time Series Forecasting in Python**

_A repository containing an advanced time series forecasting project with LSTM, XGBoost, and Ensemble Learning._

## 🔹 **Overview**
This project focuses on **predicting time series data** using a combination of **machine learning and deep learning** techniques. It incorporates **feature engineering, hyperparameter tuning, and ensemble learning** for robust forecasting.

✅ **Key Features:**
- Time Series Forecasting using **XGBoost, LSTM, and GRU** 📈
- **Feature Engineering** (Lag Features, EWMA, Seasonal Features) 🛠️
- **Hyperparameter Optimization** with **Optuna** 🔍
- **Walk-Forward Validation** to prevent data leakage 🏆
- **Stacking Ensemble Model** for better accuracy 🔗
- **Model Interpretability** with **SHAP & Permutation Importance** 📊
- **Interactive Visualizations** using **Plotly** 📌

## 🔹 **Tech Stack**
- 🟢 **Python** (Pandas, NumPy, Sci-kit Learn, TensorFlow, Optuna, SHAP, Plotly)
- 🟢 **Jupyter Notebook / Google Colab**
- 🟢 **Libraries**: XGBoost, LightGBM, Ridge Regression, MinMaxScaler, StandardScaler

## 🔹 **Feature Engineering**
✅ **Lag Features** (1-day, 7-day, 30-day)  
✅ **Exponential Weighted Moving Averages (EWMA)**  
✅ **Seasonality Features** (Sine & Cosine Transform)  
✅ **Day of the Week, Quarter, and Weekend Indicators**  

## 🔹 **Installation & Setup**
```bash
# Clone the repository
git clone https://github.com/your-username/time_series_forecasting.git

# Navigate to the project folder
cd time_series_forecasting

# Install dependencies
pip install -r requirements.txt
```

## 🔹 **How to Use?**
1. Load the dataset (`gold_monthly_csv.csv`)
2. Preprocess and scale data
3. Train XGBoost and LSTM models
4. Generate predictions using **stacked ensemble learning**
5. Evaluate models using **RMSE, MAE, R², MAPE**
6. Visualize results with **Plotly**

## 🔹 **Model Performance & Evaluation**
📌 **Metrics Used:** MAE, RMSE, R², MAPE  
📌 **Validation Strategy:** Walk-Forward Cross-Validation  
📌 **Hyperparameter Tuning:** Optuna for XGBoost & LSTM  

## 🔹 **Example Code: LSTM Training**
```python
lstm_model = Sequential([
    Bidirectional(LSTM(100, return_sequences=True, input_shape=(sequence_length, X_train.shape[1]))),
    Dropout(0.2),
    GRU(100, return_sequences=False),
    Dropout(0.2),
    Dense(1)
])

lstm_model.compile(optimizer='adam', loss='mse')
lstm_model.fit(generator, epochs=20, verbose=1)
```

## 🔹 **Future Improvements**
✅ **Optimize LSTM with GRU for better efficiency**  
✅ **Try Attention Mechanism for time series forecasting**  
✅ **Improve hyperparameter tuning using Bayesian Optimization**  
✅ **Deploy model using Flask / FastAPI**  

## 🔹 **Contributing**
Want to contribute? Follow these steps:  
1. Fork the repository  
2. Create a new branch (`feature-xyz`)  
3. Commit changes  
4. Push to the branch  
5. Open a Pull Request  

## 🔹 **Contact**
📩 Email: your-email@example.com  
🔗 [Linkedin](https://www.linkedin.com/in/rishita-makkar-256851291/)
