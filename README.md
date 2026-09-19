# California House Price Prediction

# Project Overview

This mini-project focuses on predicting **median house values in California** using Machine Learning.

The project uses the **California Houses dataset** and applies **Linear Regression** to understand the relationship between different housing and demographic features and the median house value.

The complete project covers data preprocessing, exploratory data analysis, correlation analysis, model building, evaluation, and interpretation of results.


# Objectives

* Analyze the California housing dataset.
* Understand the relationship between different housing features and house prices.
* Perform data preprocessing and cleaning.
* Visualize important patterns and relationships in the data.
* Build a Linear Regression model.
* Evaluate the model using standard regression metrics.
* Interpret the model's performance and limitations.


# Dataset

The dataset contains information about houses and their surrounding areas in California.

# Target Variable

`Median_House_Value`

This is the variable that the machine learning model attempts to predict.

# Features

The dataset contains **14 columns**, including:

* `MedInc` – Median income of households
* `HouseAge` – Median age of houses
* `AveRooms` – Average number of rooms
* `AveBedrms` – Average number of bedrooms
* `Population` – Population of the area
* `AveOccup` – Average number of household members
* `Latitude` – Geographic latitude
* `Longitude` – Geographic longitude
* Distance-related features such as distance to the coast and major cities
* Other housing-related attributes

---

#  Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Git & GitHub**

---

# Project Workflow

The project follows these major steps:

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Linear Regression Model
   ↓
Model Prediction
   ↓
Model Evaluation
   ↓
Result Interpretation
```

---

# Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to understand the dataset and identify important relationships between the features and the target variable.

The analysis includes:

* Checking the dataset structure
* Checking missing values
* Checking duplicate records
* Statistical summary
* Distribution of numerical features
* Relationship between features and house prices
* Correlation analysis
* Data visualization

---

# Machine Learning Model

# Linear Regression

Linear Regression is used to predict the median house value based on the available features.

The dataset is divided into:

* **Training data** – Used to train the model.
* **Testing data** – Used to evaluate the model on unseen data.

The model learns the relationship between the input features and `Median_House_Value`.

---

# Model Evaluation

The Linear Regression model is evaluated using the following metrics:

# Mean Absolute Error (MAE)

Measures the average absolute difference between the actual and predicted values.

```text
MAE = Average(|Actual - Predicted|)
```

Lower MAE indicates smaller prediction errors.

# Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction error.

```text
RMSE = √Average((Actual - Predicted)²)
```

Lower RMSE indicates better prediction performance.

# R² Score

The R² score indicates how much of the variation in the target variable is explained by the model.

A value closer to **1** generally indicates that the model explains more of the variation in the target.

---

# Project Structure

```text
California-House-Price-Prediction/
│
├── README.md
├── Project_Report.md
├── California_Houses.csv
│
└── work.ipynb
```

### File Description

| File                                      | Description                        |
| ----------------------------------------- | ---------------------------------- |
| `README.md`                               | Project overview and documentation |
| `Project_Report.md`                       | Detailed project report            |
| `California_Houses.csv`                   | Dataset used for analysis          |
| `work.ipynb`                              | Complete Python implementation    |


# Results

The Linear Regression model is evaluated using **MAE, RMSE, and R² score**.

The evaluation results are discussed in detail in the project notebook and report.

The analysis also helps identify which housing and demographic features have stronger relationships with median house values.

