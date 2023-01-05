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

| Model                 | Accuracy    | RSME       | 
|:--------------------: |:-----------:| :---------:| 
| Model 1               | 0.89809     |0.16982     |
| Model 2               | 0.89835     |0.16960     |
| Model 3               | 0.89858     |0.16960     |
| Model 4               | 0.87931     |0.18480     |


Ensemble Stacking was also used in an attempt to improve the predictive performance of the model but ultimately, the XGBoost model still had the best performance and is hence the chosen model.


<br/>
Data Source: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction
