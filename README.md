# Titanic-dataset


Machine Learning Life cycle 
- Exploratory Data Analysis
- Feature Engineering
- Feature Selection
- Model Training
- Model Evaluation

### 1. Data Preprocessing 

  It consists of  Exploratory Data Analysis, Feature Engineering and Feature Selection.

  Standard Scaler, MinMax Scaler, Imputer and PCA is used for Data preprocessing. 

  Here for example if we are using standard scalar, 
  **fit** is used to calculate the mean and standard deviation. 
  **transform** is used to apply the Standard Scaler to the dataset.

  In data preprocessing fit and transform is applied to the training dataset whereas only transform is applied to the test data set.
  This will help to overcome overfitting problem.

### 2. Models 

  It consists of Model Training and Model Evaluation.

  Logistic regression, Decision Trees, Random Forest Classifier, XGBoost are used for Model training.

  Here,
  **fit** is used to fit the model with our training dataset. 
  **predict** is used predict the output using our test dataset.

  In model training, fit is applied to the training dataset whereas predict is applied to the test data set or any new data.



