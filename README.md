# 🎓 Student Performance Prediction (UCI Dataset)

This machine learning project predicts student performance based on various academic, demographic, and behavioral factors. The goal is to classify whether a student is likely to pass or fail using supervised classification techniques.

## 📂 Dataset

- Source: [UCI Machine Learning Repository – Student Performance](https://archive.ics.uci.edu/ml/datasets/student+performance)
- Files used: `student-mat.csv` (Mathematics performance data)

## 📊 Features

The dataset includes:
- Demographic info (e.g., `sex`, `age`, `address`)
- Family and social info (e.g., `famsize`, `Pstatus`, `schoolsup`)
- Academic info (e.g., `studytime`, `failures`, `absences`, grades `G1`, `G2`, `G3`)

Target variable:
- `pass` → Created as 1 if `G3 >= 10`, otherwise 0

## ✅ Project Steps

- Data Loading and Preprocessing
- Feature Engineering
- Encoding categorical variables
- Train/Test Split
- Model training (Random Forest Classifier)
- Model evaluation (Accuracy, Classification Report)
- Visualizations:
  - Grade distribution
  - Correlation heatmap
  - Study time vs Pass
  - Feature importance

## 🧠 ML Model Used

- **RandomForestClassifier** (from `sklearn.ensemble`)
- Accuracy achieved: _XX%_ (fill with your model score)

## 📈 Visualizations

- Histogram of grades
- Heatmap of feature correlations
- Boxplots of study time vs pass/fail
- Barplot of feature importances

## 🧪 Requirements

Install required packages:

```bash
pip install -r requirements.txt
