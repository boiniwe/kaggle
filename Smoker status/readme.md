Binary Prediction of Smoker Status using Bio-Signals https://www.kaggle.com/competitions/playground-series-s3e24

Quick description on my actions in the Smoker_Status.ipynb:
1. Check for nulls and bad data, found and fixed 'age', 'height', 'weight' bucket features 
2. Create some new features that indicates deviations from nominal/healthy numbers    
3. Tried CatBoost model with and without PolynomialFeatures 
4. Tried stacking SVClassifier, CatBoost and RF, got slightly better results
