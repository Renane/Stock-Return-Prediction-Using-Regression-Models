# Stock-Return-Prediction-Using-Regression-Models
Predict daily return on S&amp;P500 Future using Multiple Linear Regression, XGBoost, Random Forest, and Decision Tree. 


Predict daily return on E-Mini S&P 500(Ticker: "ES=F") using regression models.

The response variable is: The daily excess return on ES=F over risk-free rate.

The predicting variables include: 
(1) Rm-Rf: The excess return on the market, value-weight return of all CRSP firms incorporated in the US and listed on the NYSE, AMEX, or NASDAQ.
(2) SMB (Small Minus Big): The average return on the nine small stock portfolios minus the average return on the nine big stock portfolios.
(3) HML (High Minus Low): The average return on the two value portfolios minus the average return on the two growth portfolios.
(4) RMW (Robust Minus Weak): The average return on the two robust operating profitability portfolios minus the average return on the two weak operating profitability portfolios.
(5) CMA (Conservative Minus Aggressive): The average return on the two conservative investment portfolios minus the average return on the two aggressive investment portfolios.
(6) MOM (Momentum): The average return on the two high prior return portfolios minus the average return on the two low prior return portfolios.
(7) ST_Rev (Short-Term Reversal): The average return on the two low prior return portfolios minus the average return on the two high prior return portfolios.
(8) Volume: Trading Volume on a daily basis.

Predicting variables 1-6 are selected based on Fama French 5-Factor Model, which was designed by Eugene Fama and Kenneth French to describe stock returns in 2012. Fama shared the 2013 Nobel Memorial Prize in Economic Sciences. Data source: Kenneth R. French - Data Library.

Implement long strategy based on the prediction, and perform back testing for 1 month period. The regression model achieves 2.32% accumulative return during the testing period, which outperforms the benchmark (1.83%) by approximately 27%.



