# HousePricesRegression

## Kaggle House Price Prediction Competition

### **Author:** Ishaan Bhandari

### **Project Overview**
This project is part of the Kaggle competition aimed at predicting residential house prices based on a comprehensive set of features provided in the House Prices Dataset. Utilizing advanced machine learning techniques, the goal is to build models that can accurately predict the sales prices of houses.

### **Dataset**
The dataset includes 1460 observations, each with various features detailing aspects of residential homes. These features include both physical attributes (like square footage and number of rooms) and locational advantages (like proximity to various amenities). The dataset is split into:

Training data: 1168 observations used for training the models.
Validation data: 292 observations used for validating the models.
Test data: 1460 observations used for the competition's final evaluation.

### **Models Used:**

**Random Forest Regressor:** An ensemble learning method known for its robustness and efficacy in handling regression tasks.  
**Gradient Boosting Regressor:** A machine learning technique that produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees.  
**Support Vector Regression (SVR):** A type of Support Vector Machine used for regression challenges.  

### **Objective**
The primary objective is to predict the sale price for each house in the test set. Predictions are expected to be highly accurate, as the competition evaluates submissions based on the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted values and the logarithm of the observed sales prices.

### **Evaluation**
Submissions are evaluated using RMSE, which provides a measure of the differences between the predicted and actual values, with a logarithmic transformation applied to both predicted and actual values. This transformation ensures that underestimations and overestimations are penalized equivalently across the entire range of house prices.

### **Results**
![image](https://github.com/ishaan-bhandari/HousePricesRegression/assets/66647978/1464ca35-9af4-45b1-b975-bb9830ad7643)
![image](https://github.com/ishaan-bhandari/HousePricesRegression/assets/66647978/cdccbe37-9a16-4ee8-a678-faafb9e4b9c1)
![image](https://github.com/ishaan-bhandari/HousePricesRegression/assets/66647978/0429a618-4332-4bd3-a694-d2529fbb100f)  

The Gradient Boosting model achieved the lowest RMSE score of 0.16789 among the three models.


