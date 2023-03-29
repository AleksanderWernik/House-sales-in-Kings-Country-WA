# House-sales-in-Kings-Country-WA  :houses:

### Objective 🎯
Prediction of the house price in Kings Country, Washington, USA. 

### Description Of Dataset 📊 
The dataset contains attributes of 21613 houses sold between May 2014 and May 2015. 
The data has 18 attributes such as: date of transaction, number of bedrooms and bathrooms, square footage of the apartments interior living space and square footage of the land space, condition and age of the building.

### Methodology ⚙️
To predict prices, I performed a train-test split of 80:20 model and cross-validation. I trained LGBM Regressor, Random Forest Regressor, XGBoost Regressor, CatBoost Regressor, GradientBoosting Regressor, from the Sklearn library. After spliting the data Grid Search CV was used to find optimal hyper-parameters for the models. 
Cross-validation gives about 89% mean r2 score for CatBoost. Spliting the data gives about 87% r2 score on test set for CatBoost and XGBoost.
Appropriate graphs and metrics were generated for the analysis and performance of the different models were compared.
