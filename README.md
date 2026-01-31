# Employee Turnover Prediction - Project Deliverables

##  Project Structure

This folder contains all deliverables for the Portobello Tech Employee Turnover Prediction project.

### Main Files

1. **PROJECT_REPORT.md** - Comprehensive 15-section project report covering:
   - Executive summary with key achievements
   - Data quality assessment
   - Exploratory data analysis findings
   - Clustering analysis results
   - Model performance evaluation
   - 7 targeted retention strategies
   - Implementation roadmap
   - ROI projections ($16-29M annual savings)

2. **employee_turnover_analysis.py** - Complete Python script with:
   - Data loading and quality checks
   - Full exploratory data analysis
   - K-Means clustering implementation
   - Manual SMOTE implementation for class balancing
   - 6 ML models with 5-fold cross-validation
   - Model evaluation and comparison
   - Automated visualization generation
   - Retention strategy identification

### Visualizations Folder (11 charts)

**Data Exploration:**
1. `01_turnover_distribution.png` - Employee turnover distribution
2. `02_correlation_matrix.png` - Feature correlation heatmap
3. `03_feature_distributions.png` - Feature distributions by turnover status
4. `04_satisfaction_vs_evaluation.png` - Satisfaction vs evaluation scatter plot
5. `05_dept_salary_analysis.png` - Turnover rates by department and salary

**Clustering Analysis:**
6. `06_clustering_metrics.png` - Elbow method and silhouette scores
7. `07_clustering_visualization.png` - K-Means cluster visualization

**Model Performance:**
8. `08_cv_performance.png` - Cross-validation comparison
9. `09_model_comparison.png` - Model metrics comparison (4 metrics)
10. `10_best_model_evaluation.png` - Confusion matrix and ROC curve
11. `11_feature_importance.png` - Feature importance rankings

##  Key Results

- **Best Model:** Random Forest
- **Accuracy:** 98.33%
- **F1-Score:** 96.42%
- **ROC-AUC:** 99.23%

##  Top Findings

1. **Satisfaction level** is the strongest predictor (-0.388 correlation)
2. Employees with **>5 projects** have 63.7% turnover rate
3. **3-5 year tenure** employees are at highest risk
4. **Low satisfaction employees** (<0.4) have 53.7% turnover rate
5. Three distinct employee clusters identified requiring different interventions

##  Business Impact

**Projected Annual Savings:**
- Conservative (25% reduction): $16.1M
- Moderate (35% reduction): $22.5M
- Optimistic (45% reduction): $28.9M

**ROI:** 400-1000% after implementation costs

##  Quick Start

### To Run the Analysis:
```bash
python employee_turnover_analysis.py
```

This will:
- Load and analyze the HR data
- Generate all 11 visualizations
- Train and evaluate 6 ML models
- Output comprehensive results to console

### Requirements:
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- openpyxl (for Excel file reading)

##  Project Tasks Completed

 **Task 1:** Data quality check - Zero missing values detected  
 **Task 2:** Exploratory data analysis - 11 visualizations created  
 **Task 3:** Clustering analysis - K-Means with k=3 optimal clusters  
 **Task 4:** Class imbalance handling - SMOTE implementation (manual)  
 **Task 5:** K-fold cross-validation - 5-fold stratified CV on 6 models  
 **Task 6:** Best model identification - Random Forest with F1-Score justification  
 **Task 7:** Retention strategies - 7 comprehensive strategies developed  

##  Implementation Roadmap

**Immediate (0-3 months):**
- Deploy predictive model
- Identify top 500 at-risk employees
- Begin workload rebalancing

**Short-term (3-6 months):**
- Launch satisfaction surveys
- Implement project management improvements
- Start leadership development programs

**Long-term (6-12 months):**
- Build comprehensive engagement programs
- Create predictive analytics dashboard
- Establish sustainable retention culture

##  Technical Details

**Data:**
- 14,999 employee records
- 10 features (8 numerical, 2 categorical)
- 23.81% turnover rate

**Models Evaluated:**
- Logistic Regression
- Decision Tree
- Random Forest  (Selected)
- Gradient Boosting
- K-Nearest Neighbors
- Support Vector Machine

**Validation:**
- 80/20 train-test split
- 5-fold stratified cross-validation
- SMOTE for class balancing

##  Contact

For questions about this analysis, please contact the HR Analytics team.

-
