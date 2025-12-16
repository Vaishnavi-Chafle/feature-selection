# Filter-Based Feature Selection

Filter-based feature selection methods choose important features using
statistical techniques. These methods evaluate the relationship between
each feature and the target variable without using any machine learning model.

They are usually applied as a **preprocessing step** before model training.

---

## Techniques Covered

The following filter-based techniques are implemented in this folder:

- Variance Threshold
- Correlation Analysis
- Chi-Square Test
- ANOVA (Analysis of Variance)

---

## Why Use Filter-Based Methods?

- Fast and computationally efficient
- Independent of machine learning models
- Suitable for high-dimensional datasets
- Helps remove irrelevant and redundant features

---

## Limitations

- Does not consider interaction between features
- Selected features may not always give the best model performance

---

## Notebook

The complete implementation and examples are available in:

📓 **`based-feature-selection.ipynb`**

The notebook includes:
- Data loading
- Feature selection techniques
- Feature ranking
- Comparison before and after feature selection

---

## Datasets used
df1 = **`/kaggle/input/human-activity-recognition-with-smartphones/train.csv`**
df2 = **`/kaggle/input/titanic/train.csv`**

## Summary

Filter-based feature selection helps reduce the number of features while
keeping the most relevant ones. Although it may slightly reduce accuracy,
it improves model simplicity, interpretability, and training speed.
