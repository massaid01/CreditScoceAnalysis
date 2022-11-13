# About Credit Scoring Analysis
This is the first project I created commonly used in financial industry. In addition to making a model with Logistic Regression, I also made a scorecard to filter whether the borrower is good or bad. There are actually 3 models used in financial industry, but at this time I have only cretead one that is sufficient toscreen good borrowers. The other two will updated laters to completed the models.

# Model
This project uses Logistic Regression and gets an AUC ROC score of 0.76 which is accepted as a machine learning model.
The method used is to group features into several categories (discretized) with the weight of evidence (Woe) score parameter and filtered by Information Value (IV) as a feature that is feasible to be modeled.
