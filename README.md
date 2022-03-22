# Forecasting Daily $JPM Stock Price using Machine Learning

:star2: [Final Hosted Notebook](https://g-andrey.github.io/Forecasting-Daily-JPM-Stock-Price-with-Machine-Learning/) :star2:

## Goal :dart:
The ultimate goal of this project was to take a real-world problem and then attempt to solve it utilizing proper machine learning principles. The specific problem tackled is that of predicting future stock price movement using techincal analysis, framed as a forecasting machine learning problem. *Logistic regression*, *random forest classifier*, and *neural network* models were trained and tested on 7 years of historical $JPM data from 2012 - 2019.

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
- Perfomed data exploration and constructed visualizations with *matplotlib*:
  + 
