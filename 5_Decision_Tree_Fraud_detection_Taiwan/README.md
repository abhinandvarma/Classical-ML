# Fraud Detection [x]



Data taken from the UCI data repository (Taiwan Dataset)

Decision Tree :
        This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel alpha Smoothing Method to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. 
Therefore, among the six data mining techniques, I have compared various classical algorithms and concluded Decision Tree Model to be best.
Customer default payment prediction using an optimized Decision Tree Model with the top 15 features selected among 22 for best results. F1-Score achieved: 0.5 on test set. Concluded that a Neural Network can learn more complex patterns.

Libraries : Numpy, Pandas, Sklearn, Imblearn
