# Forecasting-and-Analysis-of-Stock-Prices
This is a project where I discover through trial and error which machine learning methods are best suited for analyzing and predicting a market as uncertain as equities

This study investigates the application of advanced machine learning techniques to forecast and analyse 
stock prices, focusing on methods such as Multilayered Bidirectional Long Short-Term Memory 
(BiLSTM), Support Vector Machine (SVM), XGBoost, and Vector Autoregression (VAR). Stock price 
forecasting is a highly complex task due to the multitude of influencing factors such as market volatility, 
economic indicators, and temporal dependencies. This project aims to develop models capable of 
predicting stock prices for upcoming periods (for example, days or weeks), leveraging historical data 
and machine learning algorithms. 
The methodology consists of multiple stages, beginning with data preprocessing. Historical stock price 
data is scaled and transformed, with a particular emphasis on time-series analysis to capture temporal 
dependencies. Techniques such as sequence splitting and moving averages are employed to prepare 
the dataset. Feature extraction methods, including the creation of relevant time-series data, improve the 
predictive accuracies of the models like BiLSTM, which is adept at handling temporal patterns in data. 
XGBoost, on the hand, is employed for its strong capability in handling structured datasets and providing 
interpretable results. Meanwhile, SVM is employed to capture non-linear relationships in stock price 
movements. 
The implementation focuses on several models trained and tested on real-world stock data assessing 
performance using a key evaluation metric, Mean Squared Error (MSE). Results of this study 
demonstrate the efficacy of each model in predicting stock prices, with each method offering strengths 
in their specialized different contexts. 
Visualizations of predicted versus actual stock prices are provided for each model and feature, alongside 
detailed performance comparisons. The analysis reveals both the potential and the challenges of using 
machine learning in stock price forecasting, emphasizing the importance of feature selection, 
hyperparameter tuning, and the handling of stationarity of time-series data. Finally, limitations such as 
overfitting and data dependency are discussed, with future directions highlighted to improve model 
robustness and scalability. 
This project thus serves as a comprehensive analysis of various machine learning approaches to stock 
price forecasting, offering insights into their practical application, accuracy, and future improvements.
