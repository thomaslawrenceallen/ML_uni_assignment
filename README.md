## Game Data Predictions Assignment ##
Game data supplied was loaded into the script, containing 470 features and 398 instances. 
The goal was to train and develop 5 different models to create 5 predictions; Category, OriginYear, Region, BestAgent and UCT.
This method contains feature engineering techniques such as merging lower respresented regions, clipping predictions
to a certain range due to a large spread but low frequency in that spread.
Models that were trained and developed included Logistic/Linear Regression, K-Nearest Neighbours, XGBoost, AdaBoost,
RandomForest and Decision Trees. These models were included into a stacking ensemble aswell to test the strength of
combining the models.
Hyperparameter tuning was key in this project to achieving better results.
