# Project: Smart Information System - Customer Spending Predictions 

---

## Overview

This project focuses on understanding and preparing customer data. By analyzing consumer behavior, demographics, and spending patterns, the goal is to identify distinct customer groupings that can inform targeted marketing strategies.

The core of this project involves:

* **Data Exploration:** Examining the dataset to understand its structure, features, and potential insights related to customer behavior.
* **Data Preparation:** Cleaning, transforming, and preparing the data to be suitable for machine learning models. This includes feature engineering, scaling, and splitting the data for training and evaluation.

## Case Study: Customer Spending Predictions

This project uses a customer marketing campaign dataset to explore and prepare data specifically for customer segmentation.

## Key Findings (Data Understanding)

The analysis of the dataset led to the following key insights:

* A new `Spending` feature was engineered by aggregating individual purchase categories to represent overall customer value.
* Important customer characteristics such as `Income`, `Age`, and `Education_Years` provide valuable context regarding purchasing power and life stage.
* This integrated perspective on spending behavior and demographics allows for a better understanding of client groupings, paving the way for effective segmentation or predictive models.

## Data Preparation Steps

The data preparation phase involved several crucial steps to ensure the dataset is ready for analysis and modeling:

* **Data Cleaning and Merging:** Corresponding data was cleaned and merged to create a unified dataset for analysis.
* **Feature Engineering:** The `Spending` feature was created to capture the total spending of each customer.
* **Feature Scaling:** Numerical features (`Income`, `Recency`, `Age`, `Education_Years`) were scaled using `StandardScaler` to ensure they contribute equally to subsequent models.
* **Feature Selection:** Important binary and numerical variables were selected for further analysis.
* **Train-Test Split:** The dataset was divided into training and testing sets with an 80:20 ratio.
* **Stratification:** The `stratify` parameter was used during the train-test split to maintain the original class distribution in both sets.
* **Final Data Structure:** The resulting train and test datasets contain six evenly distributed and clean features, making them suitable for modeling.

## Reflection and Challenges

During the project, several challenges were encountered and addressed:

* **Identifying Unnecessary Features and Preventing Data Leakage:** Careful examination of feature significance and removal of redundant features were crucial to avoid information leakage into the model.
* **Selecting the Appropriate Scaling Method:** The choice of `StandardScaler` was justified by its compatibility with planned algorithms and its robustness to outliers.
* **Ensuring Proper Train-Test Separation:** Careful consideration of the `stratify` parameter ensured an appropriate split without distorting the desired class proportions.

Despite these challenges, the data preparation steps successfully laid a strong foundation for insightful segmentation or predictive modeling.

## Author

* **Name:** Teresa Kaena Dharmanyoto
* **Student ID:** 202304560014
* **Course:** Smart Information System Project
* **Lecturer:** Denny Sihombing

## Usage

This repository contains the code and potentially the prepared data used for this analysis. To use this project:

1.  Clone the repository to your local machine.
2.  Ensure you have the necessary Python libraries installed (e.g., pandas, scikit-learn). You can install them using `pip install pandas scikit-learn`.
3.  Run the provided notebooks or scripts to reproduce the data exploration and preparation steps.

## Next Steps (Potential)

* Implement and evaluate various customer segmentation models (e.g., K-Means clustering).
* Explore different feature engineering techniques.
* Analyze the characteristics of the identified customer segments.
* Develop targeted marketing strategies based on the segmentation results.

---
