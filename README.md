# Forecasting Daily $JPM Stock Price using Machine Learning

:star2: [Final Hosted Notebook](https://g-andrey.github.io/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/) :star2:

## Goal :dart:
The ultimate goal of this project was to take a real-world problem and then attempt to solve it utilizing proper machine learning principles. The specific problem tackled is that of predicting future stock price movement using technical analysis, framed as a forecasting machine learning problem. *Logistic regression*, *random forest classifier*, and *neural network* models were trained and tested on 7 years of historical $JPM data from 2012 - 2019.

## Tasks Performed 

- Conducted research in existing literature regarding the use of machine learning in stock price predicting
- Performed feature engineering by implementing various technical indicators using *numpy* and *pandas*:
  + Day to day close price difference ($ and %)
  + 7-Day moving average (MA)
  + 7-Day price momentum
  + 26-Day and 12-Day exponential moving average (EMA)
  + Moving Average Convergence Divergence (MACD)
  + Stochastic Oscillator
- Implemented Machine Learning preprocessing techniques with *scikit-learn*:
  + Removed missing/broken values
  + Standardized input features
  + Constructed training and testing splits
- Performed data exploration and constructed visualizations with *matplotlib*:
  + Stock price w/ MA and EMA 
  + Stock price w/ volume
  + Total return by year
  + Stock price w/ momentum trend indicator
  ![momentum](https://github.com/G-Andrey/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/blob/main/Figures/Stock%20Price%20and%20Momentum%20Indicator.png)
  + Stock price w/ MACD indicator
  ![macd](https://github.com/G-Andrey/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/blob/main/Figures/Stock%20Price%20and%20MACD%20Indicator.png)
  + Stock price w/ stochastic oscillator
  ![stochastic](https://github.com/G-Andrey/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/blob/main/Figures/Stock%20Price%20and%20Stochastic%20Oscillator.png)
- Trained 3 models:
  + Logistic regression with hyperparameter optimization using gridsearch
  + Random forest classifier with hyperparameter optimization using gridsearch
  + Dense neural network using *tensorflow*
- Measured and visualized performance of all 3 models:
  + Accuracy
  + ROC curves and AUC scores
  ![roc](https://github.com/G-Andrey/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/blob/main/Figures/ROC%20Curves%20for%20All%203%20Models.png)
  + Confusion matrices
  ![confusion](https://github.com/G-Andrey/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/blob/main/Figures/Confusion%20Matricies.png)
- Assessed and visualized interpretability of all 3 models:
  + Logistic regression model's coefficients
  + Random forest model's feature importances
  + Shapley plot for best performing model
  
  ![shapley](https://github.com/G-Andrey/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/blob/main/Figures/Shapley%20Plot%20of%20Best%20Performing%20Model.png)
