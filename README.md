# ML Regression Projects

A collection of machine learning regression projects designed to practice and master various regression techniques and methods.

## 📚 Overview

This repository contains beginner to intermediate regression projects, each focusing on different aspects of regression analysis, feature engineering, and model evaluation.

## 🎯 Learning Objectives

- Master fundamental regression algorithms (Linear, Polynomial, Ridge, Lasso, Elastic Net)
- Learn feature engineering and data preprocessing techniques
- Understand model evaluation metrics (MSE, RMSE, R², MAE)
- Practice train-test split and cross-validation
- Implement regularization techniques to prevent overfitting
- Gain hands-on experience with scikit-learn and pandas

## 📁 Project Structure

```
ml-regression-projects/
├── README.md
├── requirements.txt
├── house-price-prediction/
│   ├── README.md
│   ├── data/
│   │   ├── raw/
│   │   └── processed/
│   ├── notebooks/
│   │   ├── 01_exploratory_data_analysis.ipynb
│   │   ├── 02_data_preprocessing.ipynb
│   │   ├── 03_model_development.ipynb
│   │   └── 04_model_evaluation.ipynb
│   ├── src/
│   │   ├── __init__.py
│   │   ├── data_loader.py
│   │   ├── preprocessing.py
│   │   ├── models.py
│   │   └── evaluation.py
│   └── reports/
│       └── analysis_report.md
└── [future-regression-projects]/
```

## 🏠 Project 1: House Price Prediction

**Status**: 🚀 In Progress

A classic regression project predicting house prices based on various features such as:
- Number of rooms, bathrooms
- Square footage
- Location/neighborhood
- Age of property
- And more...

**Methods Covered**:
- ✅ Linear Regression
- ✅ Multiple Linear Regression
- ✅ Polynomial Regression
- ✅ Ridge Regression (L2 Regularization)
- ✅ Lasso Regression (L1 Regularization)
- ✅ Elastic Net
- ✅ Feature Scaling & Normalization
- ✅ Train-Test Split & Cross-Validation
- ✅ Model Evaluation Metrics

**Dataset**: Boston Housing / Kaggle House Prices / California Housing

**Key Learnings**:
- Data exploration and visualization
- Handling missing values
- Feature engineering and selection
- Hyperparameter tuning
- Model comparison and selection

## 🛠️ Tech Stack

- **Python** 3.8+
- **Libraries**:
  - pandas (data manipulation)
  - numpy (numerical computing)
  - scikit-learn (machine learning)
  - matplotlib & seaborn (visualization)
  - jupyter (interactive notebooks)

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

## 🚀 Getting Started

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

## 📊 Project Roadmap

- [ ] **House Price Prediction** (Current)
  - [ ] Phase 1: Data Exploration & Analysis
  - [ ] Phase 2: Data Preprocessing & Feature Engineering
  - [ ] Phase 3: Model Development & Training
  - [ ] Phase 4: Model Evaluation & Comparison
  - [ ] Phase 5: Hyperparameter Tuning & Optimization

- [ ] **Future Projects**:
  - Stock Price Forecasting
  - Student Performance Prediction
  - Car Price Prediction
  - Salary Prediction
  - And more...

## 📈 Evaluation Metrics

For each regression project, we'll evaluate models using:

- **Mean Squared Error (MSE)**: Average of squared differences
- **Root Mean Squared Error (RMSE)**: Square root of MSE
- **Mean Absolute Error (MAE)**: Average absolute differences
- **R-squared (R²)**: Proportion of variance explained
- **Adjusted R²**: R² adjusted for number of features

## 💡 Best Practices

- Always split data into training and testing sets
- Normalize/scale features when necessary
- Use cross-validation for robust model evaluation
- Document your findings and insights
- Compare multiple models before selecting the best one
- Validate assumptions of linear regression

## 📝 Notes

- This is a learning-focused repository
- All projects follow a consistent structure for easy navigation
- Each project includes detailed notebooks and comments
- Feel free to experiment and modify approaches

## 🤝 Contributing

This is a personal learning repository, but feel free to fork and adapt it for your own learning journey!

## 📚 Resources

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [StatQuest with Josh Starmer](https://www.youtube.com/c/joshstarmer) - Great for understanding ML concepts
- [Kaggle Competitions](https://www.kaggle.com/) - Real datasets and competitions

## 📧 Contact

For questions or suggestions, feel free to reach out!

---

**Happy Learning!** 🎉 Keep practicing and building amazing ML models!
