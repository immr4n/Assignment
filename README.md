# Breast Cancer Classification — Machine Learning

> A machine learning project built as part of my MSc AI coursework, exploring different classification algorithms on a real medical dataset.

---

## What this project does

This notebook applies and compares multiple supervised learning algorithms to classify breast cancer tumors as malignant or benign, using the Wisconsin Breast Cancer dataset. The goal was to understand how different models behave on the same problem and what evaluation metrics actually matter in a medical context (where false negatives are costly).

---

## Algorithms compared

| Model | Notes |
|-------|-------|
| Support Vector Machine (SVM) | Best overall accuracy |
| Logistic Regression | Fast, interpretable baseline |
| K-Nearest Neighbors (KNN) | Tested multiple k values |

---

## Key steps

1. **Data loading & exploration** — understanding feature distributions, missing values
2. **Preprocessing** — normalization, train/test split
3. **Model training** — fitting SVM, LR, KNN on training data
4. **Evaluation** — accuracy, precision, recall, F1-score, confusion matrix
5. **Comparison** — which model performs best and why

---

## Dataset

- **Source:** Wisconsin Breast Cancer Dataset (included as `breast_cancer_dataset.csv`)
- **Features:** 30 numerical features (radius, texture, perimeter, area, etc.)
- **Target:** Malignant (1) or Benign (0)

---

## How to run

```bash
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Open the notebook
jupyter notebook Assignment_code.ipynb
```

---

## What I learned

- How to properly evaluate a classifier beyond just accuracy
- Why recall matters more than precision in medical classification
- How SVM decision boundaries work in high-dimensional feature spaces
- The importance of feature scaling for distance-based algorithms like KNN

---

## Author

**Mohammed Imran Ibrahim**  
MSc Artificial Intelligence — Berlin School of Business and Innovation  
[LinkedIn](https://www.linkedin.com/in/imm4n)
