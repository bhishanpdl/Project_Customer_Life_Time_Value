# Description
- Data source: [Online Retail Datset from UCI](https://archive.ics.uci.edu/ml/datasets/online+retail)

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Here, I took only the data of UK for the data analysis.

# Modelling

```bash
# NOTE: For a given seed, result is same for xgboost but not for keras.

          XGBoost         Keras
MAE     : 923.95          769.21
MSE     : 12,439,437      13,356,743
R2-score: 0.45            0.41
```

# References
- [A Definitive Guide for predicting Customer Lifetime Value (CLV)](https://www.analyticsvidhya.com/blog/2020/10/a-definitive-guide-for-predicting-customer-lifetime-value-clv/)
- [Deep Neural Networks for Customer Lifetime Value](https://antonsruberts.github.io/DNN-for-CLV/)
- [ML vs Statistical Approach for CLV](https://github.com/AntonsRuberts/datascience_marketing/blob/master/DNN%20vs%20BG_NBD%20for%20CLV.ipynb)
- [Predicting Customer Lifetime Value with AI Platform: training the models](https://cloud.google.com/architecture/clv-prediction-with-offline-training-train)