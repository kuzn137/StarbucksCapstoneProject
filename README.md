# StarbucksCapstoneProject

Author Inga Kuznetsova

Data set provided by Starbucks for UDACITY students consists from customer profile, portfolio (offers description) and transcript (how offer was used by customer). 
It is published at https://kuzn137.medium.com/completions-of-starbucks-offers-685c268bacd0
The goal of described model is to predict for bogo and discount types of offers if offer will be completed after it was viewed by customer using customer and offer information 
provided in dataset. In Features Engineering we explore offers and customer predictors to use in the model. As model RandomForest Classifier is used to classify if customer will 
complete offer. ROC Area Under the Curve is used for scoring as very suitable metrics for binary classification. As Model refinement the Light Gradient Boosting is used, it 
slightly improves results. 

Files: Starbucks_Capstone_notebook.ipynb

Data:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)

profile.json - demographic data for each customer

transcript.json - records for transactions, offers received, offers viewed, and offers completed


Python 3.8 libraries:

pandas

numpy

math

json

matplotlib

seaborn

sklearn

lightgbm
