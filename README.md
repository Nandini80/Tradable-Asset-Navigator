# Trade-Asset-Navigator

This project aims to assist cryptocurrency investors in making informed decisions in the volatile Bitcoin market. It combines advanced forecasting technologies with actionable investment recommendations, offering insights on whether to hold or sell assets. The project integrates **Long Short-Term Memory (LSTM)** and **ARIMA** models for short-term and long-term Bitcoin price predictions, respectively, ensuring both accuracy and real-world applicability.

## Key Features:

### Motivation
- Bridging the gap between advanced forecasting tools and practical decision-making for cryptocurrency trading.

### Development
- **LSTM**: Captures short-term, volatile price movements.
- **ARIMA**: Models stable, long-term trends.
- **Hybrid Model**: Combines the strengths of both.

### Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Pandas, NumPy (data preprocessing and numerical computations)
  - TensorFlow/Keras (LSTM implementation)
  - Statsmodels (ARIMA implementation)
  - YFinance (data collection for Bitcoin historical prices)
  - Matplotlib, Plotly (data visualization and interactive dashboards)
- **Tools**:
  - Jupyter Notebook
  - Git/GitHub

## Methodology:

1. **Data Collection**: Historical Bitcoin data spanning 6-7 years using YFinance.
2. **Data Preprocessing**: Cleaning, addressing missing values and outliers, and normalizing the data.
3. **Exploratory Data Analysis (EDA)**: Visualizing historical trends and market fluctuations using interactive plots.
4. **Model Development**:
   - LSTM for short-term predictions (daily/weekly trends).
   - ARIMA for long-term predictions (monthly trends).
   - Hybrid model combining outputs from LSTM and ARIMA.
5. **Model Training**: Splitting data into training and testing sets (80:20) and evaluating performance using metrics like MSE and MAE.
6. **Decision-Making Logic**: Providing actionable recommendations (hold/sell) based on predicted trends.
7. **Result Visualization**: Trend graphs with actionable insights for easy decision-making.

## Outcomes:

- **Long-term Trends**: ARIMA provided stable predictions.
- **Short-term Trends**: LSTM captured rapid fluctuations effectively.
- **Hybrid Model**: Balanced approach ensured reliable recommendations tailored to market conditions.

## Conclusion:

The project successfully demonstrated the feasibility of combining statistical and machine learning models to forecast cryptocurrency prices and guide investment decisions. It highlighted the potential of hybrid models in managing volatility and providing actionable insights in financial markets.
