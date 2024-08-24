# Stock Market Prediction using Technical Indicators and Machine Learning

This project focuses on analyzing and predicting stock market trends for major tech companies using a combination of technical indicators, statistical analysis, and machine learning models (like LSTM). The companies analyzed include AAPL, AMZN, GOOG, META, MSFT, NVDA, TSLA, and INTC.

## Data Collection & Preparation
- **Data Source**: Historical stock price data is collected from CSV files for the selected companies.
- **Data Preprocessing**: The data is processed to extract key features such as `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, and adjusted close prices. Additionally, a new column for the stock label is added for easier identification.

## Technical Indicators
The project computes various technical indicators for each stock, which are crucial for understanding stock market dynamics. These include:

- **RSI (Relative Strength Index)**: Used to measure the magnitude of recent price changes to evaluate overbought or oversold conditions.
- **Bollinger Bands**: Indicates the volatility of a stock by plotting a band (upper, middle, lower) around the stock price.
- **Aroon Oscillator**: Helps identify whether a stock is trending and measures the strength of that trend.
- **Price Volume Trend (PVT)**: Combines price and volume to assess the direction of a stock’s price trend.
- **Stochastic Oscillator**: Used to detect overbought and oversold conditions by comparing the stock's closing price to its price range over a given period.
- **Chaikin Money Flow (CMF)**: Measures the accumulation/distribution of money flow over time to identify buying and selling pressure.
- **VWAP (Volume Weighted Average Price)**: Tracks the average price a stock has traded throughout the day, adjusted for volume.
- **ATR (Average True Range)**: Measures market volatility by decomposing the range of stock prices over a set period.
- **DMI (Directional Movement Index)**: Quantifies trend strength by comparing positive and negative price movement.

## Statistical Analysis and Calculations
- The project also implements custom functions to compute key indicators, such as the **Rate of Change (ROC)** and **Parabolic Stop and Reverse (PSAR)**, which help in identifying momentum and potential trend reversals.
- **Quantum Analysis**: Price shifts over time are calculated to understand short-term price movements.

## Visualizations
- The project includes comprehensive visualizations to illustrate the stock trends and behaviors. These visualizations include:
  - **RSI and Volume** plotted over time for each stock.
  - **Bollinger Bands** surrounding the stock's closing prices to indicate volatility.
  - **Aroon Oscillator** alongside the stock's closing prices to show trend strength.
  - **Price Volume Trend (PVT)** to depict price movement influenced by volume.
  - **Stochastic Oscillators** showing overbought/oversold conditions.
  - **Chaikin Money Flow** and other indicators visualized over time for better trend analysis.

## Future Work
The project can be expanded by incorporating:
- **Machine Learning Models** (like LSTM or other time-series models) to predict future stock prices based on the calculated indicators.
- **Feature Engineering** to enhance the predictive power of the models.
- **Backtesting** strategies using the technical indicators to assess historical performance.
