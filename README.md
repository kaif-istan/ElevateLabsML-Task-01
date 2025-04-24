# 🧹 Task 1: Data Cleaning & Preprocessing – AI & ML Internship

This repository contains my submission for Task 1 of the AI & ML Internship program. The objective was to clean and preprocess the **Titanic dataset** for machine learning.

---

## 📂 Dataset

- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `titanic.csv`

---

## ✅ Steps Performed

### 1. **Data Exploration**
- Used `pandas` to check data types, shape, null values, and statistical summary.

### 2. **Handling Missing Values**
- Imputed missing values in `Age` with median.
- Filled missing `Embarked` values with mode.
- Dropped the `Cabin` column due to excessive nulls.

### 3. **Encoding Categorical Variables**
- Applied one-hot encoding on `Sex` and `Embarked` columns using `pd.get_dummies()`.

### 4. **Feature Scaling**
- Normalized `Age` and `Fare` using `StandardScaler` from `sklearn`.

### 5. **Outlier Removal**
- Visualized outliers using `boxplots`.
- Removed extreme outliers in `Fare` above the 99th percentile.

---

## 📊 Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn

---

## 📁 Files in This Repo

- `titanic.csv` – Original dataset (if allowed)
- `cleaned_titanic.csv` – Final cleaned dataset
- `task1_preprocessing.ipynb` – Jupyter notebook with full code
- `README.md` – This documentation

---

## 🚀 How to Run

1. Clone this repository.
2. Open `task1_preprocessing.ipynb` in Jupyter Notebook.
3. Run all cells to see preprocessing in action.

---

## 📝 Submission

[🔗 Internship Submission Form](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## 💡 Key Learnings

- Identified types of missing data and handled them appropriately.
- Understood the difference between normalization and standardization.
- Practiced encoding, outlier detection, and the impact of preprocessing on model performance.

---

Feel free to fork or star this repo if it helped you! ⭐
