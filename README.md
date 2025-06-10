# Managing-SuppyChain-using-CNN

This project implements a **Convolutional Neural Network (CNN)** based model to forecast supply chain demand using historical sales data. CNNs are typically used for image recognition, but this project demonstrates their effectiveness for time series forecasting tasks as well.

---
##  Objectives

-  **Forecast Future Sales**: Leverage historical data to predict demand across time.
-  **Inventory Optimization**: Avoid stockouts and overstock by maintaining ideal inventory levels.
-  **Replenishment Planning**: Estimate optimal quantities and frequency for reordering goods.
-  **Sales Driver Analysis**: Identify the impact of seasonality, promotions, and other factors.
---
##  Problem Statement

Supply chain systems are data-rich environments where demand forecasting can significantly impact operations. This project addresses the following challenges:

- **Sales Trend Forecasting** – Modeling sales behavior over time.
- **Inventory Balancing** – Reducing waste and meeting customer demand efficiently.
- **Replenishment Optimization** – Reducing transportation and holding costs.
- **Feature Influence Analysis** – Discovering what drives demand (e.g., price cuts, season, etc.).
---
##  Models Used

##  Machine Learning

1.  **Linear Regression** – Simple, interpretable baseline model for linear trends.
2.  **XGBoost** – Gradient Boosted Decision Trees known for high accuracy and speed.

##  Deep Learning

1.  **CNN (Convolutional Neural Network)** – Captures local temporal patterns in sales data.
2.  **LSTM (Long Short-Term Memory)** – Learns long-term dependencies in time-series.
3.  **CNN + LSTM (Hybrid)** – Combines CNN’s feature extraction with LSTM’s temporal memory.
4.  **GRU (Gated Recurrent Unit)** – Lightweight alternative to LSTM with competitive performance.
5.  **Transformer** – Attention-based model designed for long-range time series relationships.

---

##  Key Insights
1. **XGBoost** performs best among classical ML models due to its efficiency and minimal tuning.
2.  The **CNN + LSTM hybrid** model outperforms all others in forecasting accuracy.
3.  Deep Learning models excel when large volumes of sequential data are available.
4.  Feature engineering and time-windowing are critical for all model types.
---

##  Why These Models?

###  XGBoost

1. Excellent default performance  
2. Handles missing data and sparse matrices  
3. Feature importance visualization  
4. Regularization to reduce overfitting  
5. Fast due to parallelization

###  CNN + LSTM

1. Learns both short-term patterns (via CNN) and long-term dependencies (via LSTM)  
2. Efficient modeling of sequences  
3. Delivers high accuracy for complex time series  
4. Can generalize across multiple product types and seasonal patterns

---
