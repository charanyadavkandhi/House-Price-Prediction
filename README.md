# HOUSE PRICE PREDICTION USING MACHINE LEARNING

### Submitted By

**Kandhi Charan Yadav**
B.Tech-Computer Science and Engineering

SR University

---

# Abstract

House price prediction is an important application of Machine Learning that helps estimate property values based on various housing characteristics. In this project, a Random Forest Regressor model was developed to predict house prices using the California Housing Dataset. The model was trained on historical housing data and evaluated using regression metrics such as Mean Squared Error (MSE) and R² Score. The model achieved an R² Score of 80.62%, demonstrating strong predictive performance.

---

# Introduction

House prices depend on several factors such as location, income levels, number of rooms, population density, and geographical coordinates. Predicting house prices accurately helps buyers, sellers, and real estate agencies make informed decisions.

Machine Learning regression algorithms can analyze historical housing data and learn patterns to estimate future house prices. In this project, a Random Forest Regressor was used to perform house price prediction.

---

# Objective

The objectives of this project are:

* To predict house prices using Machine Learning.
* To analyze housing data and identify important features.
* To train a regression model for price estimation.
* To evaluate model performance using MSE and R² Score.

---

# Dataset Description

The California Housing Dataset from Scikit-learn was used for this project.

### Dataset Information

* Total Records: 20,640
* Total Features: 8
* Target Variable: House Price

### Features

* MedInc (Median Income)
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

Target Variable:

* Price

---

# Methodology

The project was completed using the following steps:

### Step 1: Data Collection

The California Housing Dataset was loaded using Scikit-learn.

### Step 2: Data Exploration

The dataset structure and feature information were analyzed.

### Step 3: Data Preprocessing

* Checked dataset quality.
* Selected input features and target variable.
* Prepared data for training.

### Step 4: Train-Test Split

The dataset was divided into:

* Training Data: 80%
* Testing Data: 20%

### Step 5: Model Training

A Random Forest Regressor model was trained using the training dataset.

### Step 6: Prediction

The trained model was used to predict house prices for unseen data.

### Step 7: Model Evaluation

Performance was evaluated using:

* Mean Squared Error (MSE)
* R² Score

---

# Tools and Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Random Forest Regressor
* VS Code

---

# Implementation

The implementation involved:

1. Loading the California Housing Dataset.
2. Creating a DataFrame.
3. Splitting the dataset into training and testing sets.
4. Training a Random Forest Regressor model.
5. Generating predictions.
6. Evaluating model performance.
7. Visualizing Actual vs Predicted House Prices.

---

# Results

### Model Performance

* Mean Squared Error (MSE): 0.254
* R² Score: 0.8062

The Random Forest Regressor achieved an R² score of 80.62%, indicating that the model successfully explained a large portion of the variance in house prices.

### Sample Prediction

Predicted House Price:

* 4.246

### Visualizations

1. Terminal Output Screenshot
   (Insert Output.png Here)

2. Actual vs Predicted House Prices Graph
   (Insert actual_vs_predicted_prices.png Here)

---

# Advantages

* High prediction accuracy.
* Handles large datasets effectively.
* Captures complex relationships between features.
* Useful for real estate analysis and forecasting.

---

# Applications

* Real Estate Price Estimation
* Property Valuation Systems
* Investment Decision Support
* Housing Market Analysis
* Smart Real Estate Platforms

---

# Conclusion

The House Price Prediction project successfully utilized Machine Learning techniques to estimate house prices using the California Housing Dataset. A Random Forest Regressor was implemented and achieved an R² Score of 80.62% with a low Mean Squared Error of 0.254. The project demonstrates how Machine Learning can be applied to solve real-world regression problems and provide accurate predictions.

---

# References

1. California Housing Dataset – Scikit-learn.
2. Scikit-learn Documentation.
3. Python Documentation.
4. Pandas Documentation.
5. Machine Learning with Python Resources.
