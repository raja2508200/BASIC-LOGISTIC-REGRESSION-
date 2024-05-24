# BASIC-LOGISTIC-REGRESSION-

Importing Libraries:

The code imports essential libraries including pandas for data manipulation, train_test_split from sklearn.model_selection for splitting the dataset, LogisticRegression from sklearn.linear_model for building the logistic regression model, and LabelEncoder from sklearn.preprocessing for encoding categorical variables.
Loading the Dataset:

The dataset is loaded from a CSV file named 'Book1.csv' into a DataFrame df.
Encoding Categorical Variables:

The LabelEncoder is used to convert categorical variables (gender, smoking, and cancer) into numerical values. This transformation is necessary for the logistic regression model to process these features.
Preparing Features and Target Variable:

The target variable cancer is separated from the features. X contains all the feature columns except cancer, and y contains the cancer column.
Splitting the Data:

The dataset is split into training and testing sets using an 80-20 split. X_train and y_train are used for training the model, while X_test and y_test are reserved for evaluating the model’s performance.
Training the Logistic Regression Model:

A logistic regression model is instantiated and trained using the training data (X_train, y_train).
Making a Prediction:

The trained model is used to make a prediction for a new data point with features [1, 23, 1], representing a specific combination of encoded gender, age, and smoking status.
