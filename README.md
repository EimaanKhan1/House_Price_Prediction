# 🏡 House Price Prediction

## 📌 Project Overview

This project focuses on predicting residential property prices using the Ames Housing Dataset. The objective was to build a reliable regression model capable of estimating house prices while identifying the most influential features affecting property value.

The project follows a complete Machine Learning pipeline from data exploration to model evaluation and interpretation.

---

## 🎯 Objectives

- Predict house sale prices accurately.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Handle missing values and outliers.
- Engineer meaningful features.
- Select the most relevant predictors.
- Compare multiple regression models.
- Interpret model predictions through visualization.

---

## 📊 Dataset

The Ames Housing Dataset contains detailed information about residential properties, including:

- Lot Area
- Overall Quality
- Year Built
- Living Area
- Garage Information
- Basement Features
- Neighborhood
- Sale Price

Dataset Size:
- 79 Features
- 1460 Records

---

## 🛠️ Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Data distribution analysis
- Missing value assessment
- Correlation analysis
- Outlier detection
- Feature relationship exploration

### 2. Data Preprocessing

- Missing value imputation
- Outlier treatment using IQR capping
- Categorical encoding
- Feature scaling

### 3. Feature Engineering

Created additional features including:

- HouseAge
- TotalSF
- TotalBathrooms
- AgeSinceRemodel

### 4. Feature Selection

Applied:

- Mutual Information Analysis
- Correlation Analysis
- Random Forest Feature Importance

Top predictors included:

- OverallQual
- GrLivArea
- TotalSF
- GarageCars
- YearBuilt

### 5. Model Development

The following regression models were evaluated:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### 6. Hyperparameter Tuning

- Cross Validation
- Grid Search Optimization

---

## 📈 Results

### Best Performing Model
**Linear Regression**

### Performance Metrics

| Metric | Value |
|----------|----------|
| RMSE | \$24,510 |
| Evaluation | Strong Predictive Performance |

---

## 🔍 Key Insights

Important factors affecting house prices:

- Overall Quality
- Above-Ground Living Area
- Total Square Footage
- Garage Capacity
- Property Age

Notable findings:

- House quality strongly influences sale price.
- Larger living areas significantly increase value.
- Newer homes generally command higher prices.
- Combined engineered features improved model performance.

---

## 📊 Visualizations

The project includes:

- Price Distribution Analysis
- Correlation Heatmaps
- Actual vs Predicted Plots
- Residual Analysis
- Feature Importance Charts
- Outlier Detection Visualizations

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📚 Key Learnings

- Importance of feature engineering in regression tasks.
- Effective handling of missing data and outliers.
- Feature selection techniques for structured datasets.
- Model evaluation using regression metrics.

---

## 🚀 Future Improvements

- Ensemble Regression Models
- XGBoost Optimization
- Automated Feature Engineering
- Model Deployment with FastAPI or Streamlit

---

## 👨‍💻 Author

Eimaan Khan  
BS Computer Science | AI Engineer
