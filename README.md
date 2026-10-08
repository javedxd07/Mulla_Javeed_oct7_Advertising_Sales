# Advertising Dataset – Sales Prediction

## 📌 Project Overview

This project analyzes how different advertising channels influence product sales.

A consumer goods company spends money on:

- TV advertising
- Radio advertising
- Newspaper advertising

The company wants to understand which advertising channel has the strongest relationship with sales and predict future sales based on a planned advertising budget.

This project uses **Multiple Linear Regression** to analyze the data and make predictions.

---

## 🎯 Objectives

The main objectives of this project are:

1. Load and examine the Advertising dataset.
2. Use TV, Radio, and Newspaper advertising spending as input features.
3. Use Sales as the target variable.
4. Train a Multiple Linear Regression model.
5. Predict sales for unseen/test data.
6. Predict sales for the following advertising budget:
   - TV = 150
   - Radio = 20
   - Newspaper = 30
7. Evaluate the model's prediction error.
8. Interpret the model coefficients.
9. Visualize actual sales vs predicted sales.
10. Provide business and technical recommendations.

---

## 📊 Dataset

The project uses the **Advertising Dataset** from Kaggle.

The dataset contains the following columns:

| Column | Description |
|--------|-------------|
| TV | Amount spent on TV advertising |
| Radio | Amount spent on Radio advertising |
| Newspaper | Amount spent on Newspaper advertising |
| Sales | Product sales |

### Features

- `TV`
- `Radio`
- `Newspaper`

### Target

- `Sales`

---

## 🤖 Machine Learning Approach

### Multiple Linear Regression

Multiple Linear Regression is used because we have multiple input variables and one continuous target variable.

The model learns the relationship:

```text
Sales = Intercept
      + TV × TV coefficient
      + Radio × Radio coefficient
      + Newspaper × Newspaper coefficient
