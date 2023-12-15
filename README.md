# Quant-Research-Project---Harsh-Desai
<h1>Z-Score Based Trading System</h1>
<p>This project focuses on developing a Z-score based trading system. The approach is rooted in statistical arbitrage and involves analyzing the volatilities of two financial indices, Nifty and Bank Nifty.</p>

<h2>Project Overview</h2>
<ul>
  <li><strong>Data Collection:</strong> Historical minute-level implied volatilities of Nifty and Bank Nifty were collected.</li>
  <li><strong>Data Preprocessing:</strong> Handled missing values, corrected anomalies, and ensured consistent time intervals in the data.</li>
  <li><strong>Z-Score Calculation:</strong> Implemented a Z-score computation for the spread between the two indices. This helped in identifying when the volatility diverged significantly from the historical mean.</li>
  <li><strong>Trading Signals:</strong> Developed a system to generate trading signals based on the Z-score. Trades were initiated when the Z-score crossed predefined thresholds.</li>
  <li><strong>Backtesting:</strong> The strategy was backtested using historical data to assess its performance, focusing on metrics like P&L, Sharpe Ratio, and Drawdown.</li>
  <li><strong>Risk Management:</strong> Applied risk management strategies, including stop-loss orders and position sizing, to mitigate potential losses.</li>
</ul>

<h2>Key Findings</h2>
<p>The system demonstrated potential in capturing profitable opportunities in the market while managing risk effectively. The backtesting phase provided insights into the strategy's performance under various market conditions.</p>

<h2>Conclusion</h2>
<p>This project served as an exploration into medium-frequency pairs trading using statistical methods. It highlighted the importance of rigorous backtesting and risk management in developing trading strategies.</p>





<h1>ML-Based Trading Setup</h1>
<p>This project involves creating a trading system based on machine learning, specifically using the XGBoost algorithm. The focus was on predicting future returns based on historical data of Nifty and Bank Nifty volatilities.</p>

<h2>Project Overview</h2>
<ul>
  <li><strong>Data Preparation:</strong> Utilized historical data of Nifty and Bank Nifty to calculate relevant features such as moving averages, volatility, and momentum.</li>
  <li><strong>Feature Engineering:</strong> Engineered features were used to create a dataset suitable for machine learning applications.</li>
  <li><strong>Model Training:</strong> An XGBoost model was trained to predict future returns. The model was evaluated using metrics like Mean Squared Error (MSE).</li>
  <li><strong>Signal Generation:</strong> Based on the model’s predictions, trading signals were generated to indicate buy or sell positions.</li>
  <li><strong>Portfolio Simulation:</strong> A simulation was run to apply these signals to a trading strategy, with calculations made for P&L, Sharpe Ratio, and Maximum Drawdown.</li>
  <li><strong>Hyperparameter Tuning:</strong> Performed GridSearchCV to find the optimal hyperparameters for the XGBoost model.</li>
  <li><strong>Time Series Cross-Validation:</strong> Implemented Time Series Split for model validation to ensure the temporal integrity of financial data.</li>
</ul>

<h2>Key Findings</h2>
<p>The ML-based system showed promise in its ability to predict market movements. However, it also highlighted the challenges in achieving consistent performance across different market conditions.</p>

<h2>Conclusion</h2>
<p>This ML-based trading setup showcased the potential of machine learning in financial strategies. It underscored the need for continuous model refinement, comprehensive backtesting, and robust risk management to build effective trading systems.</p>
