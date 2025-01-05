# Big Mart Sales Prediction

Predicting sales is crucial for optimizing inventory, managing supply chains, and driving business growth in retail. This project focuses on using machine learning techniques to predict the sales of products across various Big Mart outlets. By leveraging a rich dataset of product and outlet characteristics, this project aims to provide actionable insights for decision-making.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Data Analysis and Preprocessing](#data-analysis-and-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

---

## Overview

Big Mart is a retail company, and this project focuses on building a machine learning model to predict product sales based on various factors such as product weight, visibility, outlet type, and more. Gradient Boosting Regressor was chosen as the machine learning model for this task.

---

## Dataset

The dataset contains the following columns:

| Column Name                 | Description                                          |
| --------------------------- | ---------------------------------------------------- |
| `Item_Identifier`           | Unique product identifier                            |
| `Item_Weight`               | Weight of the product                                |
| `Item_Fat_Content`          | Fat content of the product (e.g., Low Fat, Regular)  |
| `Item_Visibility`           | Visibility of the product in the store               |
| `Item_Type`                 | Type/category of the product                         |
| `Item_MRP`                  | Maximum Retail Price (MRP) of the product            |
| `Outlet_Identifier`         | Unique outlet identifier                             |
| `Outlet_Establishment_Year` | Year the outlet was established                      |
| `Outlet_Size`               | Size of the outlet (e.g., Small, Medium, High)       |
| `Outlet_Location_Type`      | Type of city the outlet is located in                |
| `Outlet_Type`               | Type of outlet (e.g., Grocery Store, Supermarket)    |
| `Item_Outlet_Sales`         | Sales of the product in the outlet (Target variable) |

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/iDharitri-Raj/Big_Mart_Sales_Prediction
   ```
2. Navigate to the project directory and install the required dependencies.

---

## Dependencies
The project requires the following Python libraries:
`sklearn`
`numpy`
`pandas`
`matplotlib`
`seaborn`
`gradient_boosting_regressor`

---

## Data Analysis and Preprocessing

- Handled Missing Values
- Encoded categorical data into numerical.
- Feature Distribution Visualization
- Splitted the data into training and test sets.

---

## Model Training and Evaluation
- Model Used: Gradient Boosting Regressor

Hyperparameters:
- `n_estimators`: 100
- `learning_rate`: 0.1
- `random_state`: 42

Performance Metrics
- Training Data R² Score: 0.6348
- Test Data R² Score: 0.5805

---

## Results
The Gradient Boosting Regressor performed well on the given dataset, achieving an R² score of approximately 0.58 on the test data, indicating a moderate predictive power for product sales.

---

## Usage

1. Load the dataset and preprocess it.
2. Train the Gradient Boosting Regressor or any other model of choice.
3. Evaluate the model using the R² score or other metrics.
4. Use the trained model to predict sales for new data.

---

## License
This project is licensed under the [**MIT License**](LICENSE) 
