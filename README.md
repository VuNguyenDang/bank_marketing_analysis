# bank_marketing_analysis
This dataset is about marketing activities of a commercial bank, contains data about various features which can contribute to dicision of customer
that whether they subcribe the term deposit of the bank or not.

# This notebook is a data analysis project, 
which analyzes data from marketing activities of the commercial bank, 
then detect important features which contributes to decision of customer.

# The project has 3 main parts: 
preprocessing and cleaning data, exploratory data analysis and build machine learning model. 
      1. In preprocessing and cleaning data, I remove columns with high null rate, fill missing values by method like MAR, MNAR, MCAR. 
      Besides, I don't remove outliers as I use random forest classification in building model.
      2. In EDA part, I analyze features, consider if it's good for model or not, then remove features that are not necessary and handle outliers values.
      3. In building machine learning model, as output is imbalanced, I use SMOTE (Oversampling) and Random Forest Classification to build model.
      After tuning and evaluating, model is not overfitting, I find some features that strongly affects to customer decision, this features can help marketing teams 
      in targeting potential customer.
