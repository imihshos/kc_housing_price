# King County (USA) Housing Price Prediction

In this project, we built a model to predict the housing prices in King County.

The following machine learning models were used: 
* Linear Regression
* Ridge Regression 
* Random Forest 
* XGBoost
* LightGBM 

### Results 

| Model                 | Accuracy    | RSME       | 
|:--------------------: |:-----------:|:----------:| 
| Linear Regression     | 0.78856     |0.24461     |
| Ridge Regression      | 0.78856     |0.24461     | 
| Random Forest         | 0.84998     |0.20604     | 
| XGBoost               | 0.90151     |0.16695     |
| LightGBM              | 0.87806     |0.18576     |


Ensemble Stacking was then used to build the final model for prediction. 

| Model                 | Accuracy    | RSME       | 
|:--------------------: |:-----------:| :---------:| 
| Linear Regression     | 0.7535364   |0.7535364   |
| Ridge Regression      | 0.7529079   |0.7535364   | 
| Random Forest         | 0.7484488   |0.7535364   | 

<br/>
Data Source: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction
