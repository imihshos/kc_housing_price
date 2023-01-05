# King County (USA) Housing Price Prediction

In this project, we built a model to predict the housing prices in King County.

The following machine learning models were used: 
* Linear Regression
* Ridge Regression 
* Random Forest 
* XGBoost
* LightGBM 


| Model                 | Accuracy    | RSME       | 
|:--------------------: |:-----------:| :---------:| 
| Linear Regression     | 0.7535364   |0.7535364   |
| Ridge Regression      | 0.7529079   |0.7535364   | 
| Random Forest         | 0.7484488   |0.7535364   | 
| XGBoost               | 0.6919283   |0.7535364   |
| LightGBM              | 0.7202357   |0.7535364   |



Ensemble Stacking was then used to build the final model for prediction. 
| Model                 | Accuracy    | RSME       | 
|:--------------------: |:-----------:| :---------:| 
| Linear Regression     | 0.7535364   |0.7535364   |
| Ridge Regression      | 0.7529079   |0.7535364   | 
| Random Forest         | 0.7484488   |0.7535364   | 

Data Source: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction
