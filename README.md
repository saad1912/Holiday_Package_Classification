# Holiday_Package_Classification

## Life cycle of Machine learning Project

### Understanding the Problem Statement
  * "Trips & Travel.Com" company wants to enable and establish a viable business model to expand the customer base.
  * One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering * Basic, Standard, Deluxe, 
    Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers
    were contacted at random without looking at the available information.
  * The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a 
    healthy lifestyle, and support or increase one's sense of well-being.
  * However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

### Collecting Data
  * The Dataset is collected from https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction
  * The data consists of 20 column and 4888 rows.

### Exploratory Data Analysis
  * Extracted Numerical and Categorical features, performed Univariate and Multivariate Analysis.
  * Further extracted Continuous and Discrete features from Numerical features, and plotted their relation with target variable.
### Data Cleaning
  * Handled Null values, Misspellings and Duplicates.
### Data Pre-Processing
  * Removed redundant columns
  * Multicollinearity check using Variance Inflation Factor
  * Capped Outliers using Boxplot formula for upper limit and lower limit
### Model Training
  * Encoded and Standardized Categorical and Numerical features.
  * Handled imabalanced data using SMOTE
  * Trained the model on 9 regression models, namely, Logisitc Regression, SVC, Gradient Boosting Classifier, K-Neighbours Classifier, Decision Tree Classifier, Random Forest Classifier,
    XGBClassifier, CatBoosting Classifier, AdaBoost Classifier.
### Choosing optimal model
  * Performed Hyperparameter Tuning on the 4 best models based on Accuracy score, namely, CatBoosting Classifier, XGBClassifier, Random Forest Classifier,K-Neighbours Classifier.
  * Final best model : CatBoosting Classifier with Accuracy score of 0.9895.
  * Save the best trained model as a pickle file.

  
