# Customer Subscription Prediction

## Overview
This project was completed for my **Intro to Data Science** course. The goal of the project was to use customer shopping behavior data to predict whether a customer would subscribe to a service.

This project focuses on a real-world business problem: helping companies better understand customer behavior so they can improve targeting, promotions, and retention.

## Problem
Businesses want to know which customers are more likely to subscribe so they can:
- reduce marketing costs
- personalize promotions
- better understand customer behavior
- improve customer retention and lifetime value

## Machine Learning Task
This project is a **binary classification** problem.

- **Target variable:** `Subscription Status`
- **Classes:** `Yes` or `No`

The goal is to predict whether a customer will subscribe based on demographic and purchasing features.

## Dataset
The project uses the file `shopping_behavior.csv`.

The dataset includes customer information such as:
- age
- gender
- item purchased
- category
- purchase amount
- location
- size
- color
- season
- review rating
- shipping type
- discount applied
- promo code used
- previous purchases
- payment method
- frequency of purchases

The dataset contains about **3,900 rows** of customer shopping behavior data.

## Methods
In this project, I:
- loaded and explored the dataset
- checked data types and missing values
- performed exploratory data analysis (EDA)
- visualized important patterns in the data
- prepared the data using preprocessing
- split the data into training, validation, and test sets
- trained and compared multiple machine learning models

## Models Used
The following models were tested:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gaussian Naive Bayes

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

## Results
On the validation set, the strongest models were:
- **Random Forest**
- **Naive Bayes**
- **SVM**

### Test Set Results
| Model | Accuracy | Precision | Recall | F1 Score |
|------|---------:|----------:|-------:|---------:|
| Random Forest | 0.8530 | 0.6500 | 0.9873 | 0.7839 |
| Naive Bayes | 0.8513 | 0.6449 | 1.0000 | 0.7841 |
| SVM | 0.8239 | 0.6279 | 0.8544 | 0.7239 |

These results show that **Random Forest** and **Naive Bayes** performed the best overall, with very strong recall and solid F1 scores. This suggests that tree-based and probabilistic models were effective at identifying likely subscribers from shopping behavior patterns.

## Key Takeaways
Through this project, I practiced:
- data cleaning and exploration
- data visualization
- feature preparation
- machine learning model training
- model comparison and evaluation
- interpreting classification results

This project helped me build a stronger understanding of how data science can be used to solve business problems with predictive modeling.

## Files in This Repository
- `project_implementation.ipynb` — main notebook with analysis, visualizations, and modeling
- `shopping_behavior.csv` — dataset used in the project
- `project_description.pdf` — assignment description

## Tools Used
- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Author
**Justen Hilliard**  
Intro to Data Science Final Project
