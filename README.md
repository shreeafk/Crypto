# Time series Analysis with cryptocurrency

 Time Series Analysis with Cryptocurrency Data leverages advanced data analytics techniques to explore and analyze historical cryptocurrency trends. This project focuses on price forecasting, volatility measurement, and identifying market patterns using algorithms like ARIMA and LSTM. By visualizing data through interactive charts and graphs, it provides actionable insights for traders and investors. Additionally, the project detects anomalies in trading activities and examines correlations between cryptocurrencies and external factors,aiding in informed decision-making and strategic portfolio management.

## heatmaps for data exploration

![image](https://github.com/user-attachments/assets/616f77e1-92fa-4aca-a043-7021c00788c2)


##  Flags potential market manipulations or unusual trends in data.

![image](https://github.com/user-attachments/assets/50164cac-920f-44d6-8ecc-2fc4d8e9aa73)


#### **1. Summary/Overview**
This project focuses on analyzing historical cryptocurrency data, identifying trends, and providing short-term and long-term price forecasts. The analysis leverages statistical and machine learning models to assist in investment decision-making. The dataset includes key metrics such as high, low, open, close prices, volume, and market capitalization.

---

#### **2. Objectives**
- Analyze historical price trends and correlations between cryptocurrencies.
- Identify bullish and bearish market periods.
- Highlight periods of high and low market stability.
- Provide short-term (ARIMA) and long-term (LSTM) price forecasts for investment decisions.

---

#### **3. Activities and Tasks**
1. **Data Preprocessing**:
   - Cleaned the dataset by handling missing and infinite values.
   - Converted relevant columns to numeric and calculated percentage changes for daily returns.

2. **Exploratory Data Analysis**:
   - Visualized historical price trends of top cryptocurrencies using Matplotlib.
   - Generated a correlation heatmap of daily returns to understand relationships between cryptocurrencies.

3. **Market Insights**:
   - Identified bullish and bearish periods using a 30-day moving average.
   - Highlighted high and low stability periods based on price volatility.

4. **Forecasting**:
   - Implemented ARIMA for short-term forecasting (15 days).
   - Built an LSTM model for long-term forecasting (30 days).

5. **Anomaly Detection**:
   - Used Z-scores to detect anomalies in Bitcoin's closing prices.

---

#### **4. Challenges and Solutions**
- **Challenge**: Handling missing and infinite values in the dataset.
  - **Solution**: Replaced invalid values with `NaN` and dropped rows with missing data.
  
- **Challenge**: Computational complexity of LSTM training.
  - **Solution**: Reduced sequence length and used GPU acceleration for faster training.

- **Challenge**: Visualizing multiple trends and insights effectively.
  - **Solution**: Used Matplotlib and Plotly for clear and interactive visualizations.

---

#### **5. Conclusion**
This project successfully analyzed cryptocurrency data, identified key market trends, and provided actionable insights through forecasting models. The ARIMA model offers reliable short-term predictions, while the LSTM model captures long-term trends. These tools can aid investors in making informed decisions in the volatile cryptocurrency market.
