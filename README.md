# ML Regression Projects

A collection of machine learning regression projects designed to practice and master various regression techniques and methods.

## Overview

This repository contains beginner to intermediate regression projects, each focusing on different aspects of regression analysis, feature engineering, and model evaluation.

## Learning Objectives

- Master fundamental regression algorithms (Linear, Polynomial, Ridge, Lasso, Elastic Net)
- Learn feature engineering and data preprocessing techniques
- Understand model evaluation metrics (MSE, RMSE, R², MAE)
- Practice train-test split and cross-validation
- Implement regularization techniques to prevent overfitting
- Gain hands-on experience with scikit-learn and pandas

## Repository Structure

```
ml-regression-projects/
├── README.md
├── requirements.txt
├── house-price-prediction/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   └── reports/
├── student-performance-prediction/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   └── reports/
├── car-price-prediction/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   └── reports/
└── [future-projects]/
```

## Projects Included

### 1. House Price Prediction
Predict house prices based on various features like rooms, bathrooms, square footage, location, and age.

**Methods**: Linear Regression, Polynomial Regression, Ridge, Lasso, Elastic Net, Feature Scaling, Cross-Validation

**Status**: In Progress

### 2. Student Performance Prediction
Predict student exam scores based on study hours, attendance, and other factors.

**Methods**: Simple Linear Regression, Correlation Analysis, Feature Engineering

**Status**: Planned

### 3. Car Price Prediction
Predict car prices based on specifications like brand, model, year, mileage, and features.

**Methods**: Multiple Regression, Categorical Encoding, Feature Engineering

**Status**: Planned

### 4. Stock Price Forecasting
Forecast stock prices using historical data and time series techniques.

**Methods**: Time Series Regression, Moving Averages, Trend Analysis

**Status**: Planned

### 5. Salary Prediction
Predict employee salaries based on experience, education, skills, and department.

**Methods**: Multiple Regression, Feature Interactions, Polynomial Regression

**Status**: Planned

## 🛠️ Tech Stack

- **Python** 3.8+
- **Libraries**:
  - pandas (data manipulation)
  - numpy (numerical computing)
  - scikit-learn (machine learning)
  - matplotlib & seaborn (visualization)
  - Jupyter (interactive notebooks)

## 📋 Requirements

See `requirements.txt` for complete dependencies.

```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=0.24.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Johan-ML-AI/ml-regression-projects.git
   cd ml-regression-projects
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Navigate to a project**:
   ```bash
   cd house-price-prediction
   ```

5. **Start exploring**:
   ```bash
   jupyter notebook notebooks/01_exploratory_data_analysis.ipynb
   ```

## Project Status

| Project | Status | Methods Covered |
|---------|--------|-----------------|
| House Price Prediction | In Progress | Linear, Polynomial, Ridge, Lasso, Elastic Net |
| Student Performance | Planned | Simple Linear, Correlation, Feature Engineering |
| Car Price Prediction | Planned | Multiple Regression, Encoding, Features |
| Stock Price Forecasting | Planned | Time Series, Moving Averages, Trends |
| Salary Prediction | Planned | Interactions, Polynomial, Multiple Regression |

## 📈 Evaluation Metrics

For each regression project, we evaluate models using:

- **Mean Squared Error (MSE)**: Average of squared differences
- **Root Mean Squared Error (RMSE)**: Square root of MSE
- **Mean Absolute Error (MAE)**: Average absolute differences
- **R-squared (R²)**: Proportion of variance explained
- **Adjusted R²**: R² adjusted for number of features

## Best Practices

- Always split data into training and testing sets
- Normalize/scale features when necessary
- Use cross-validation for robust model evaluation
- Document your findings and insights
- Compare multiple models before selecting the best one
- Validate assumptions of linear regression
- Each project has its own README with detailed instructions

## 📝 Project Structure Convention

Each project in this repository follows a consistent structure:

```
project-name/
├── README.md                 # Project-specific documentation
├── data/
│   ├── raw/                 # Original dataset
│   └── processed/           # Cleaned and processed data
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_development.ipynb
│   └── 04_model_evaluation.ipynb
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── models.py
│   └── evaluation.py
└── reports/
    └── analysis_report.md
```

## Resources

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [StatQuest with Josh Starmer](https://www.youtube.com/c/joshstarmer) - Great for understanding ML concepts
- [Kaggle Competitions](https://www.kaggle.com/) - Real datasets and competitions

## Contributing

This is a personal learning repository. Feel free to fork and adapt it for your own learning journey!

## Contact

For questions or suggestions, feel free to reach out!

---

**Happy Learning!** 🎉 Keep practicing and building amazing ML models!
