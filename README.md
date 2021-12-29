# Investment-
Multifactor modeling 
Factor Modeling Proposal

Situation: This project is to predict the price of certain financial assets in the next day given historical information. This is significantly important in investments because accurate predictions will help traders make the best investment decisions.
	
Proposed Solution: A multifactor model is going to be built upon common factors people can find in the market. The multifactor model is an extension of the single-factor capital asset pricing model (CAPM). After building up the multifactor model, we will design a portfolio based on this model. All data are extracted from the Bloomberg terminal, all needed information can be found in the links and references we cited.

Steps Involved:
1.   	Preparation
1)  	Data Cleaning
Picking target factors (classified by style): Value Factor, Growth Factor, Financial Quality Factor, Leverage Factor, Size Factor, Momentum Factor, Volatility Factor, Turnover Factor, Modified Momentum Factor, Sentiment Factor, Shareholder Factor and Technical Factor.
2)  	Depolarization and Standardization
3)  	Significance Test for Single Factor
Regression (t and r t+1), excluding market and industry influence, cross-section regression (rolling monthly), WLS or GLS, t-test for parameters.
Correlations (rolling, lagging), test monotone by stratifying
2.   	Factor Model Construction
1)  	Factors Classification Analysis
	Correlation between factors. If the correlation is high, discard the factor with lower significance, or construct a synthetic factor
2)  	Multicollinearity
	Same as the above
3)  	Heteroscedasticity
	BP test - WLS or GLS
4)  	Predicting Stock Returns by Multi-linear Regression
	Significance of the model
5)  	Calculating Risk Exposure
	Using the predictions to calculate the covariance matrix
3.   	Optimization
1)  	Setting Return and Risk Target
2)  	Constraints of Weights of Component Stocks
	Industries-neutral, components constraints, factor exposure constraints
3)  	Mean-Variance Optimization
4)  	Back-Testing

Goals: Construct a portfolio based on the model built, the return of this portfolio is expected to be higher than the average market returns with limited risks.
