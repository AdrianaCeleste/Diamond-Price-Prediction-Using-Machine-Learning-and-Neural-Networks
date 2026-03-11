# 💎 Diamond Price Prediction Using Machine Learning and Neural Networks

## Description
This project develops predictive models to estimate **diamond sales prices** using machine learning techniques. The analysis includes **data cleaning, exploratory data analysis, feature selection, and model development** using both **Multiple Linear Regression** and a **Neural Network**. The objective is to identify the key factors influencing diamond prices and evaluate the performance of different predictive approaches.

---

# Executive Summary

This project analyzes a large diamond dataset to build models capable of **predicting total sales price based on physical and quality characteristics of diamonds**.

Two predictive approaches were developed:

- **Multiple Linear Regression**
- **Neural Network (Deep Learning)**

After preprocessing the data and selecting relevant features, both models were trained and evaluated.

**Key results:**

- Linear Regression **R²: 66.19%**
- Neural Network **R²: 70.51%**

The neural network achieved **higher predictive accuracy**, demonstrating that **non-linear relationships exist between diamond characteristics and their market prices**.

These findings suggest that machine learning models can help **improve pricing strategies, automate price estimation, and support decision-making in the diamond industry**.

---

# Business Problem

Diamond pricing is influenced by multiple factors including:

- Carat weight  
- Diamond dimensions  
- Depth percentage  
- Table percentage  
- Quality attributes

Determining the correct price can be complex due to the **large number of variables and nonlinear relationships** between them.

Businesses such as **jewelry retailers, wholesalers, and marketplaces** need reliable pricing models to:

- Improve **pricing consistency**
- Reduce **manual estimation errors**
- Support **inventory valuation**
- Provide **real-time pricing recommendations**

The goal of this project is to **develop predictive models that estimate diamond prices based on measurable attributes**.

---

# Methodology

### 1. Data Cleaning
- Removed redundant columns
- Handled categorical variables using **Label Encoding**
- Removed rows containing **invalid zero measurements**

### 2. Exploratory Data Analysis
- Scatter plots to identify **outliers and feature distributions**
- Correlation heatmap to explore **relationships between variables**

### 3. Feature Selection
Used **F-Regression (SelectKBest)** to evaluate the predictive importance of features.

### 4. Data Preparation
- Split dataset into **training (80%) and testing (20%)**
- Prepared feature matrix **X** and target variable **y**

### 5. Model Development

#### Model 1: Multiple Linear Regression
A baseline model used to measure linear relationships between features and price.

#### Model 2: Neural Network
A feed-forward neural network with:
- 2 hidden layers
- ReLU activation
- Adam optimizer
- Mean Squared Error loss

### 6. Model Evaluation
Performance evaluated using:

- **R² Score**
- **Mean Absolute Error (MAE)**

---

# Skills Demonstrated

### Data Science
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection
- Model Evaluation

### Machine Learning
- Linear Regression
- Neural Networks
- Model Validation

### Python Libraries
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **TensorFlow / Keras**
- **Matplotlib**
- **Seaborn**

### Data Processing
- Data cleaning
- Label encoding
- Dataset splitting
- Model performance analysis

---

# Results

| Model | R² Score |
|------|------|
| Multiple Linear Regression | **66.19%** |
| Neural Network | **70.51%** |

Key findings:

- The neural network achieved **better predictive performance** than linear regression.
- Diamond price prediction benefits from **nonlinear modeling approaches**.
- Physical diamond characteristics explain a **large portion of price variability**.

---

# Business Recommendations

Based on the results of the analysis:

### 1. Implement Predictive Pricing Models
Businesses can deploy machine learning models to **automatically estimate diamond prices** based on measurable characteristics.

### 2. Improve Pricing Consistency
Using a model-driven approach helps reduce **human bias and pricing inconsistencies**.

### 3. Support Inventory Valuation
Accurate predictions allow companies to **estimate the value of their diamond inventory more efficiently**.

### 4. Enhance Decision Making
Data-driven pricing models can support:

- Sales strategies
- Dynamic pricing
- Market competitiveness

---

# Next Steps

To further improve the model:

### Model Improvements
- Hyperparameter tuning
- Cross-validation
- Regularization techniques

### Advanced Algorithms
Test additional models such as:

- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

### Feature Engineering
- Include **diamond quality grades**
- Add **market demand indicators**
- Explore **interaction features**

### Model Deployment
- Build an **API for real-time price predictions**
- Integrate the model into **pricing tools or dashboards**

---

# Conclusion

This project demonstrates how **machine learning and neural networks can be used to predict diamond prices with reasonable accuracy**.

By leveraging data-driven techniques, businesses can **improve pricing strategies, automate valuation processes, and gain deeper insights into the factors driving diamond prices**.
