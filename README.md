# Airline_passengers_prediction
This project applies **Recurrent Neural Networks (RNN)** to forecast the **monthly number of international airline passengers** using the classic **Air Passengers dataset**. The dataset contains monthly totals of international airline passengers from **1949 to 1960**.  

---

## Dataset  
- Source: [AirPassengers dataset](https://datamarket.com/data/set/22u3/international-airline-passengers-monthly-totals-in-thousands-jan-49-dec-60)  
- Contains **monthly passenger counts** (in thousands) from **1949 to 1960**.  
- A widely used dataset for **time series forecasting**.  

---

## Summary  
The project demonstrates:  
1. Loading and visualizing the Air Passengers dataset.  
2. Applying preprocessing: scaling and sequence generation.  
3. Building a **Recurrent Neural Network (RNN)** for time series forecasting.  
4. Training and validating the model on past data.  
5. Forecasting future passenger numbers and comparing predictions with actual values.  

---

## Results  
- The RNN successfully captured the **seasonality and trend** in the passenger data.  
- Predictions closely followed the actual values, with slight under/over estimations during peak months.  
- The model outperformed simple statistical baselines (moving average, linear regression).  

---

## Analysis and Insights  
- The dataset shows **strong seasonality**: peaks every year during travel seasons.  
- There is a **clear upward trend** in the number of passengers across years.  
- RNN handled sequential dependencies better than standard regression models.  
- Further improvements can be made using **LSTM/GRU** architectures.  

---

## Recommendations  
- Use **LSTM (Long Short-Term Memory)** or **GRU** networks for better handling of long-term dependencies.  
- Apply **hyperparameter tuning** (batch size, learning rate, epochs).  
- Test with **advanced forecasting models** like ARIMA, SARIMA, or Prophet for comparison.  
- Extend forecasting beyond 1960 to evaluate generalization.  

---
