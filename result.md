 Machine Learning Results

# Dataset
- 18 samples
- 9 Tumor samples
- 9 Normal samples
- Gene expression data from public RNA-seq data

# Models Used
1. Logistic Regression
2. Random Forest

## Model Performance

| Model | Mean CV Accuracy |
|---|---:|
| Logistic Regression | 1.00 (100%) |
| Random Forest | 1.00 (100%) |

# Random Forest Test Results

Confusion Matrix:

[[2, 0],
 [0, 2]]

Test samples: 4

Accuracy: 100%

Precision:
- Normal: 1.00
- Tumor: 1.00

Recall:
- Normal: 1.00
- Tumor: 1.00

F1-score:
- Normal: 1.00
- Tumor: 1.00

# Conclusion

Both Logistic Regression and Random Forest achieved 100% mean cross-validation accuracy on this dataset. Random Forest also correctly classified all 4 test samples.

These results demonstrate that the gene-expression features can distinguish Normal and Tumor samples in this dataset. Further validation with larger and independent datasets is required before considering these features as potential biomarkers
