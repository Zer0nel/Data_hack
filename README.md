# Car Price Prediction Project
This project aims to predict the prices of cars based on their features using machine learning techniques. The project uses structured data such as car features and unstructured data such as car images to make accurate predictions.

## Data
The data used for this project is obtained from the Kaggle dataset: "Car details from car dekho". The dataset contains information about used cars, including features such as the car's name, mileage, engine, power, fuel type, transmission, owner type, and price. In addition, the dataset includes images of the cars.

## Libraries
The project uses various libraries to preprocess the data and create a predictive model. Some of the libraries used include:

# Tidyverse:
For data manipulation and visualization
# Caret: 
For machine learning and predictive modeling
# e1071: 
For support vector machines (SVM) algorithms
# ROSE: 
For oversampling of minority classes
# Random Forest: 
For creating a random forest model
# XGBoost: 
For creating a gradient boosting model
# MLtools: 
For feature engineering
# Imager: 
For image processing
# Preprocessing
The preprocessing step involves cleaning the data and feature engineering. The cleaning involves removing unwanted columns, replacing missing values with NA, and converting data types. Feature engineering involves creating new features such as mileage per engine and engine per power.

## Integration
The structured and unstructured data are integrated by joining the two datasets based on car names. The images are processed and converted into pixels, which are added to the structured data.

## Model
The project uses the *XGBoost algorithm* to create a predictive model. The model is trained using the training data and evaluated using the testing data. The evaluation metrics used are root mean square error (RMSE), mean absolute error (MAE), and R-squared.

## Usage
The project includes a function preprocess_data that can be used to preprocess new data for predictions. The function takes a data frame as input and returns a preprocessed data frame. The function can be used to preprocess new data before feeding it into the model for predictions.

## Conclusion
This project demonstrates how machine learning techniques can be used to predict car prices. The project shows that integrating structured and unstructured data can improve prediction accuracy. The XGBoost algorithm is used to create a predictive model that achieves good performance on the test data.
