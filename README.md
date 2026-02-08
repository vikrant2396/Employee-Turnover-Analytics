# Employee Turnover Analytics

Machine learning project to predict employee turnover and recommend retention strategies.

## Overview

This project helps HR departments identify employees at risk of leaving and provides actionable retention strategies based on work patterns, satisfaction levels, and performance metrics.

## Dataset

- **Records**: 14,999 employees
- **Features**: 10 (satisfaction, evaluation, projects, hours, salary, etc.)
- **Target**: Employee left (1) or stayed (0)


## Key Features

- Exploratory Data Analysis with visualizations
- K-Means clustering of employees who left
- SMOTE for handling class imbalance
- Multiple ML models with 5-fold cross-validation
- Risk-based employee categorization
- Targeted retention strategies

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn
```

## Usage

```python
# Run the Jupyter notebook
jupyter notebook Employee_Turnover_Analytics_Part1.ipynb
```

## Models Trained

1. **Logistic Regression** - Baseline model
2. **Random Forest** - Ensemble method
3. **Gradient Boosting** - Best performer

## Results

Models evaluated using:
- Accuracy, Precision, Recall, F1-Score
- ROC-AUC curves
- Confusion matrices

**Best Model**: Gradient Boosting (highest ROC-AUC)

**Key Metric**: Recall (minimize missed at-risk employees)

## Retention Strategy Framework

Employees categorized into 4 risk zones based on turnover probability:

| Zone | Risk Level | Probability | Action |
|------|-----------|-------------|---------|
| Green | Safe | < 20% | Maintain engagement |
| Yellow | Low | 20-60% | Proactive monitoring |
| Orange | Medium | 60-90% | Immediate intervention |
| Red | High | > 90% | Emergency retention plan |

## Key Insights

**Top turnover factors**:
- Low satisfaction level
- Extreme workload (too few or too many projects)
- Long working hours (>250/month)
- Low salary
- Time in company (peak at 3-4 years)

## Project Structure

```
├── Employee_Turnover_Analytics_Part1.ipynb
├── hr_comma_sep.xlsx
└── README.md
```

## Technologies

- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)


⭐ Star this repo if you found it helpful!
