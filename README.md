# Acdemic-Project
## Quant trading project
### FAMA-FRENCH MODEL EXTENSION BY MACHINE LEARNING   		
•	Initiated a new idea – ‘Fama French model extension’ and compared results with Fama French  
•	Extracted US stock market data from CRSP and Compustat and normalized the original data such as price, return, capital size, book-to-market ratio, operation income etc.  
•	Applied PCA method to minimize the correlations among these factors and decided five leading contributing factors. Applied K-means clustering to construct five new portfolios due to these 5 new factors from PCA.  
•	Constructed 25 small portfolios by taking 20% tail of all the stocks ordered by the five new factors. Conducted 25 linear regressions of the target portfolios against five K-mean portfolios and computed the p-value and GRS of the constructed portfolios.  
•	Back-tested the five factors in Fama-French model for 30 years and compared the results with the constructed portfolio.   
•	The p-value and GSR value implied the factors in our model significantly contribute to this model and limitations are lack of economic meanings and 5 centres in K-means clustering could be arbitrary.  

### STOCHASTIC PROCESS AND PRICING PROJECT
•	Tuned Black Scholes Models with SABR model of stochastic volatility to catch up volatility smile in order to manage the model risk.  
•	Identified different kinds of risks such as market risk, liquidity risk and credit risk.   
•	Valuated prices, VaR, EL, Greeks and other metrics of various financial products such as equities options and FX by using Stochastic models, historical data and Monte Carlo Simulation.   
•	Estimated XVA of IRS and CDS by stochastic methods and Monte Carlo Simulation with specific Copulas, making proper statements on the exposure and strategies.  
  
### MOMENTUM STRATEGY WITH MANAGED RISK	
•	Constructed momentum portfolio by choosing the top and bottom 10% US stocks ordered by returns over the past 120 days.   
•	Forecasted portfolio volatility by using GARCH and RV models to adjust the weights of momentum portfolio and improved limitations of momentum strategy such as high volatility and negative beta in bear markets.  
•	Optimized the weights of stocks in the portfolio based on Sharpe ratio.   
•	Back-tested all the risk-managed momentum strategies to achieve an average excess return of 50% and annual Sharpe ratio of 1.25.  

### EXCHANGE RATE FORECASTING MODEL BY MACHINE LEARNING
•	Extract data of future indices, stock indices, commodity indices and macro metrics from CRSP and quandl. Predicted the move directions of JPY/USD by other factors.   
•	Built up a financial model by applying classification methods: random forest, SVM and logistic regression to forecast Forex trend. Tuned the test windows, optimization methods and C value to achieve an accuracy of 55%.  
•	Back-tested the model by constructing a strategy of buying at positive signals and selling at negative signals. Achieved excess annual return of 8% - 9% and Sharpe ratio of 0.9 -1.0.  
•	Further research: give more labels such as deep positive, deep negative to verify the trade signal in order to make the prediction more precise.  

