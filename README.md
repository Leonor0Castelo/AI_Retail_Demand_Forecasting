
# AI-Based Retail Demand Forecasting

## Overview

This project applies Artificial Intelligence and Machine Learning techniques to retail demand forecasting. Using historical store and product-level sales data, the objective is to predict the number of units sold and explore how predictive models can support data-driven business decisions.

A Random Forest Regression model is developed to identify patterns in historical sales and estimate product demand.

## Project Objectives

- Apply supervised machine learning to a real-world retail problem.
- Explore historical sales patterns and relationships between variables.
- Investigate the impact of pricing and promotional activities on product demand.
- Develop and evaluate a predictive regression model.
- Explore the potential of AI-driven analytics in retail and supply chain planning.

## Dataset

The dataset includes:
- Store and product identifiers.
- Total and base prices.
- Promotional indicators (featured and displayed products).
- Day, month and year.
- Units sold (target variable).

## Methodology

### 1. Exploratory Data Analysis
- Data inspection and statistical summaries.
- Analysis of sales distributions.
- Identification and treatment of outliers.
- Visualisation of relationships between features.

### 2. Data Preprocessing
- Removal of irrelevant identifiers.
- Feature engineering.
- Categorical variable encoding.
- Preparation of training and testing datasets.

### 3. Machine Learning
- Random Forest Regression.
- Model training and prediction.
- Hyperparameter optimisation using GridSearchCV.

### 4. Model Evaluation
- R² (coefficient of determination).
- Root Mean Squared Error (RMSE).
- Actual vs. predicted sales comparison.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Business Applications

Demand forecasting is an important component of retail and supply chain management. Accurate demand predictions can help businesses:

- Improve inventory planning.
- Anticipate product demand.
- Support replenishment decisions.
- Reduce potential overstocking and stockouts.
- Make more informed operational decisions.

## Repository Structure

```text
AI-Retail-Demand-Forecasting/
│
├── demand_forecasting.ipynb
├── requirements.txt
├── README.md
└── images/
    ├── sales_distribution.png
    └── actual_vs_predicted.png
```

## How to Run

1. Clone this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download and place the dataset in the project directory.
4. Open the Jupyter Notebook.
5. Run the notebook cells sequentially.

## Learning Outcomes

Practical experience in machine learning, predictive analytics, data preprocessing, feature engineering and regression modelling, with a focus on applying AI techniques to business and supply chain challenges.

## Acknowledgements

Inspired by the NeuralNine tutorial:

[Demand Forecasting For Stores – AI Project in Python](https://www.youtube.com/watch?v=grtQYI4KVpo)
