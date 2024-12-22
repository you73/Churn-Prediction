# Customer Churn Analysis

## Description

This notebook conducts a comprehensive analysis of customer churn using the "d0r1h/customer_churn" dataset. The analysis encompasses data preprocessing, feature engineering, exploratory data analysis, and the development of predictive models to identify factors influencing customer churn. Advanced techniques such as hyperparameter tuning and ensemble learning are employed to enhance model performance. The results are visualized through interactive graphs to facilitate a deeper understanding of the underlying patterns.

## Technologies Used

- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **Altair**: Creating interactive visualizations.
- **Scikit-learn**: Machine learning algorithms and preprocessing.
- **XGBoost**: Gradient boosting framework for predictive modeling.
- **LightGBM**: Gradient boosting framework optimized for speed and performance.
- **Seaborn & Matplotlib**: Data visualization libraries.
- **HuggingFace Datasets**: Accessing and loading datasets.
- **NumPy**: Numerical computing.
- **RandomizedSearchCV**: Hyperparameter tuning with cross-validation.

## Usage
Open the notebook `customer_churn_analysis.ipynb` using Jupyter Notebook or JupyterLab and follow the step-by-step instructions to execute the analysis.

## Results

The analysis reveals key insights into customer churn, highlighting the most influential factors and the performance of various predictive models. The following graph illustrates the performance metrics of the developed models:

![Model Performance](https://i.imgur.com/vygQETi.png)

**Key Findings:**

- **Feature Importance:** "membership_category" emerged as the most significant feature influencing churn.
- **Model Performance:** Tree-based models like XGBoost, Random Forest, and Gradient Boosting demonstrated superior accuracy.
- **Threshold Adjustment:** Optimizing the classification threshold improved the recall for the "Churn" class, ensuring fewer customers are missed.
- **Ensemble Learning:** Combining multiple models enhanced overall predictive performance.

These results provide actionable insights for businesses to implement strategies aimed at reducing customer churn and improving customer retention.

