<div align="center">

# Decision Trees vs Gradient Boosting

</div>

A comparative analysis demonstrating the performance improvement achieved through gradient boosting over a single decision tree classifier using the breast cancer dataset.

This notebook compares two machine learning approaches for binary classification:
- **Single Decision Tree**: A standalone classifier with max depth of 3
- **Gradient Boosting**: An ensemble of 6 decision trees combined through boosting

The project uses scikit-learn's **Breast Cancer Wisconsin dataset**, which contains 569 samples with 30 features each, used to classify tumors as malignant or benign.

<div align="center">

| Model | Accuracy |
|-------|----------|
| Single Decision Tree | 94.74% |
| Gradient Boosting | 95.61% |

</div>

The gradient boosting ensemble demonstrates improved performance by combining multiple weak learners to create a stronger predictive model, achieving nearly 1% higher accuracy on the test set.

