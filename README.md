# Advertising Sales Prediction

## 📊 Project Results

| Metric | Result |
|---|---:|
| **MAE** | **1.2748** |
| **RMSE** | **1.7052** |
| **R² Score** | **90.59%** |
| **Predicted Sales (TV=150, Radio=20, Newspaper=30)** | **15.04** |
| **Strongest Feature** | **Radio** |
| **Weakest Feature** | **Newspaper** |

### 🔍 Key Finding

The Linear Regression model achieved an **R² score of 90.59%**, meaning the model explains most of the variation in sales using the advertising spending data.

For an advertising budget of:

- **TV = 150**
- **Radio = 20**
- **Newspaper = 30**

the model predicts approximately **15.04 units of Sales**.

Among the three advertising channels, **Radio has the strongest relationship with Sales**, while **Newspaper has the weakest contribution** in the model.

### 💼 Business Recommendation

The company should give more attention to **Radio advertising**, as it shows the strongest relationship with sales in this dataset.

However, decisions should not be based only on the model coefficients. The company should also consider advertising cost, customer reach, and return on investment.

### 🛠️ Technical Improvement

A useful improvement would be to compare Linear Regression with other models and use cross-validation to check whether the model performs consistently on different subsets of the data.
