# Stock-Market-Anomaly-Detection-Strategies-for-Profitable-Trading

## Objective
1. To develop robust machine learning models capable of detecting anomalies in stock market data, sourced from Yahoo finance.
2. Starting with basic models like Isolation Forest and One-Class SVM, and evaluating their effectiveness in anomaly detection.
3. Investigating the limitations of initial approaches and exploring advanced models, such as Autoencoders with LSTM (Long Short-Term Memory) networks, for improved anomaly detection.
4. Utilizing the detected anomalies to devise a trading strategy, generating actionable buy and sell signals to capitalize on market inefficiencies.
5. Analyzing the performance of trading strategy and providing the average risk-return and effectiveness of the Startegy.

## Anomaly Detection
Any data point/observation that deviates significantly from the other observations is called an Anomaly/Outlier. Anomaly detection is important and finds its application in various domains like Stock market deviations, detection of fraudulent bank transactions, network intrusion detection, sudden rise/drop in sales, change in customer behavior, etc.

* Various methods are employed for detecting such anomalies, ranging from statistical tests and time-series analysis to advanced machine learning techniques like Isolation Forests, One-Class SVMs, and neural network-based autoencoders. 

* Each method has its strengths and is chosen based on the specific characteristics of the data, including volume, volatility, and the presence of seasonal patterns. 

* Effective anomaly detection in stock markets not only aids in risk management by alerting investors to potential market manipulations or financial distress but also identifies opportunities for arbitrage. 

* Given the complex and dynamic nature of financial markets, continuously refining and adapting these detection strategies is crucial for maintaining their effectiveness over time.

## Trading Strategy:

The strategy function analyzes market momentum around key indices, identified as potential trading opportunities, to generate actionable trading signals. It calculates the slopes of closing prices before and after each index within a 3-day window to determine price trends. If the trend shifts from downward to upward, it signals a "Buy" opportunity, indicating rising momentum. Conversely, a shift from upward to downward trend signals a "Sell" opportunity, suggesting declining momentum. This method systematically identifies precise moments to enter or exit trades, based on short-term price movements, optimizing decision-making in trading strategies.
