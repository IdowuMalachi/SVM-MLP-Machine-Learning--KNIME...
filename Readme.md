# 🤖 SVM vs MLP Classifier – KNIME Machine Learning Project

This project explores the use of **Support Vector Machines (SVM)** and **Multilayer Perceptrons (MLP)** in classifying structured data using the KNIME Analytics Platform. It applies best practices in data cleaning, feature selection, model evaluation, and hyperparameter optimization.

---

## 🧠 Project Overview

- Explored a dataset with 210 samples across 3 classes
- Visualized feature distributions and variance using boxplots, histograms, and PCA
- Performed feature selection using correlation and information gain
- Built and evaluated two classification pipelines:
  - **SVM** with kernel tuning
  - **MLP** with neural architecture optimization
- Applied **k-fold cross-validation** for robust evaluation
- Exported models as **PMML files** for future deployment

---

## 📊 Key Results

- **Accuracy**: 100% for both SVM and MLP
- **Precision, Recall, F1-score**: 1.0 across all classes
- **Cohen’s Kappa**: 1.0 (perfect agreement)
- **Confusion Matrix**: 0 false positives/negatives

> ⚠️ Note: These results are based on a small dataset — performance may vary on larger, real-world data.

---

## 🛠️ Workflow Highlights

- 📁 **Data Preprocessing**: Missing value imputation, one-hot encoding, normalization
- ⚙️ **Modeling**: KNIME SVM and MLP Learner nodes with parameter tuning
- 🧪 **Evaluation**: X-Partitioner for cross-validation, Scorer node for metrics
- 📝 **Deployment**: PMML Writer node used to export final models

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `classification-workflow.knwf` | Full KNIME workflow |
| `data/dataset.csv` | Input dataset used |
| `models/svm_model.pmml` | Exported SVM model |
| `models/mlp_model.pmml` | Exported MLP model |
| `results/accuracy_stats.png` | Confusion matrix screenshot |
| `report/KNIME_Classification_Report.pdf` | Full project write-up/report |

---

## 🔍 Future Improvements

- Validate on a larger and more complex dataset
- Compare with Random Forest or ensemble methods
- Deploy models in real-time using KNIME Server or web integration

---

## ✍️ Author

**Idowu Malachi**  
[GitHub Profile](https://github.com/idowumalachi)  
[LinkedIn](linkedin.com/in/idowu-malachi-2b311a352)

---

_“Machine learning is not magic. It’s modeling, math, and measurement — done right.”_
