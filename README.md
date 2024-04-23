# Stock-Market-Anomaly-Detection

## Objective
1. To develop robust machine learning models capable of detecting anomalies in stock market data, sourced from Yahoo finance.
2. Starting with basic models like Isolation Forest and One-Class SVM, and evaluating their effectiveness in anomaly detection.
3. Investigating the limitations of initial approaches and exploring advanced models, such as Autoencoders with LSTM (Long Short-Term Memory) networks, for improved anomaly detection.
4. Utilizing the detected anomalies to devise a trading strategy, generating actionable buy and sell signals to capitalize on market inefficiencies.
5. Analyzing the performance of trading strategy and providing the average risk-return and effectiveness of the Startegy.

## Data
**Data Source:**
Utilizing Yahoo Finance - yfinance as the primary data source, ensuring access to historical stock market data of Google.


## Anomaly Detection
Any data point/observation that deviates significantly from the other observations is called an Anomaly/Outlier. Anomaly detection is important and finds its application in various domains like Stock market deviations, detection of fraudulent bank transactions, network intrusion detection, sudden rise/drop in sales, change in customer behavior, etc.

* Various methods are employed for detecting such anomalies, ranging from statistical tests and time-series analysis to advanced machine learning techniques like Isolation Forests, One-Class SVMs, and neural network-based autoencoders. 

* Each method has its strengths and is chosen based on the specific characteristics of the data, including volume, volatility, and the presence of seasonal patterns. 

* Effective anomaly detection in stock markets not only aids in risk management by alerting investors to potential market manipulations or financial distress but also identifies opportunities for arbitrage. 

* Given the complex and dynamic nature of financial markets, continuously refining and adapting these detection strategies is crucial for maintaining their effectiveness over time.

![image](https://github.com/vedb1211/Stock-Market-Anomaly-Detection-Strategies-for-Profitable-Trading/assets/106091820/d5473764-d47f-41a9-8a49-58035a68c079)


## Trading Strategy:

The strategy function analyzes market momentum around key indices, identified as potential trading opportunities, to generate actionable trading signals. It calculates the slopes of closing prices before and after each index within a 3-day window to determine price trends. If the trend shifts from downward to upward, it signals a "Buy" opportunity, indicating rising momentum. Conversely, a shift from upward to downward trend signals a "Sell" opportunity, suggesting declining momentum. This method systematically identifies precise moments to enter or exit trades, based on short-term price movements, optimizing decision-making in trading strategies.

![image](https://github.com/vedb1211/Stock-Market-Anomaly-Detection-Strategies-for-Profitable-Trading/assets/106091820/dff76b72-d759-4540-91ac-34e090d4d327)

## Results from Anomaly-Based Trading Strategy:

1. **Profitability**: The strategy demonstrates clear profitability with an average return of **9.64%**, indicating its effectiveness in leveraging market anomalies for gains.

2. **Risk Management**: A volatility of **5.28%** suggests a moderate risk level, pointing towards a balanced approach in pursuit of profitable trades while maintaining risk within a manageable range.

3. **Efficient Use of Capital**: With a Sharpe ratio of **1.64**, the strategy shows strong risk-adjusted performance, implying that investors are adequately compensated for the risks taken.

In essence, the promising average return, managed volatility, and robust Sharpe ratio collectively signal a well-devised and executed trading strategy based on anomaly detection.

## Conclusion:

The analysis of stock market anomalies using machine learning techniques like LSTM autoencoders has demonstrated a compelling approach to identifying and capitalizing on market inefficiencies. With an average return of 9.64% and a Sharpe ratio of 1.64, the strategy not only promises profitability but also maintains a balanced risk profile. This underscores the effectiveness of leveraging machine learning for financial analysis, offering a potent blend of risk management and return optimization.
