# Titanic-dataset

<img src="https://user-images.githubusercontent.com/64269342/167267300-ea9744f9-acb0-4144-9088-bb6ef97a943f.png" width="600" height="350">


Machine Learning Life cycle 
1. **Exploratory Data Analysis (EDA)** is used to analyze the datasets and by this, we summarize their main importance.
3. **Feature Engineering** is the process of extract features from raw data with some domain knowledge.
4. **Feature Selection** where we select those features that will give a high impact on the model.
5. **Model creation** in this we create a machine learning model using suitable algorithms.
6. **Deployment** where we deploy our ML model on the web.

### 1. Data Preprocessing 

  It consists of  Exploratory Data Analysis, Feature Engineering and Feature Selection.

  Standard Scaler, MinMax Scaler, Imputer and PCA is used for Data preprocessing. 

  Here for example if we are using standard scalar, 
  **fit** is used to calculate the mean and standard deviation. 
  **transform** is used to apply the Standard Scaler to the dataset.

  In data preprocessing fit and transform is applied to the training dataset whereas only transform is applied to the test data set.
  This will help to overcome overfitting problem.

### 2. Models 

  It consists of Model creation and Model deployment.

  Logistic regression, Decision Trees, Random Forest Classifier, XGBoost are used for Model training.

  Here,
  **fit** is used to fit the model with our training dataset. 
  **predict** is used predict the output using our test dataset.

  In model training, fit is applied to the training dataset whereas predict is applied to the test data set or any new data.



