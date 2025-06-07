🫀 Heart Disease Prediction using Decision Tree & Random Forest

This project uses **tree-based machine learning models** to predict heart disease from clinical features. Implemented in Python using `scikit-learn`, the project demonstrates model training, evaluation, visualization, and interpretation.

## 📌 Objective

- Train a **Decision Tree Classifier** and visualize the tree.
- Analyze overfitting by adjusting tree depth.
- Train a **Random Forest Classifier** and compare model performance.
- Interpret **feature importances**.
- Evaluate models using **cross-validation**.

## 🛠️ Tools & Libraries

- Python
- Jupyter Notebook
- scikit-learn
- matplotlib
- seaborn
- pandas

## 📁 Dataset

- File: `heart.csv`
- Source: Common UCI Heart Disease dataset (binary classification)
- Target: `target` (0 = No Disease, 1 = Disease)

## 🚀 How to Run

1. Clone the repository or download the code.
2. Place `heart.csv` in the same directory.
3. Open and run `heart_disease_prediction.ipynb` in Jupyter Notebook.
4. All outputs including graphs, tree visualizations, and metrics will be displayed inline.

## 📊 Results

| Model           | Test Accuracy | Cross-Validation Accuracy |
|----------------|----------------|-----------------------------|
| Decision Tree  | ~98.5%         | 100%                        |
| Random Forest  | ~98.5%         | ~99.7%                      |

> 🔍 **Top Features** (from Random Forest): `cp`, `ca`, `thalach`, `oldpeak`, `thal`

## 📈 Visuals

- ✅ Decision Tree Visualization  
- ✅ Feature Importance Bar Plot

## 📌 Folder Structure

```
heart-disease-prediction/
│
├── heart.csv
├── heart_disease_prediction.ipynb
└── README.md
```

## ✍️ Author

**Kaldhendi Srinivas**  
AI & Data Science Student  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

