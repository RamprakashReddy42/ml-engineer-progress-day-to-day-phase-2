# 📊 Phase 2 — Exploratory Data Analysis (EDA)

## 🎯 Objective

Analyze the Credit Card Fraud Detection dataset to understand its statistical properties, feature distributions, outliers, correlations, and target-class imbalance before building a Machine Learning model.

**Dataset columns:** `Time`, `V1`–`V28`, `Amount`, `Class`

**Target column:** `Class`
- `0` — Normal transaction
- `1` — Fraudulent transaction

## 📌 Steps Completed

### ✅ Step 8 — Statistical Analysis
- Used `df.describe()` to calculate descriptive statistics.
- Examined mean, standard deviation, minimum, maximum, and quartiles.
- Used statistical summaries to understand numerical features.

### ✅ Step 9 — Distribution Analysis
- Examined feature distributions using histograms.
- Investigated the distributions of `Amount`, `Time`, and selected `V` features.
- Learned about skewness and when transformations may be appropriate.

### ✅ Step 10 — Outlier Analysis
- Applied the Interquartile Range (IQR) method to identify potential outliers in `Amount`.
- Visualized transaction amounts using box plots.
- Investigated outlier values without automatically deleting them.
- Explored an optional `Amount_Outlier` flag.

### ✅ Step 11 — Correlation Analysis
- Calculated a numerical correlation matrix using `df.corr(numeric_only=True)`.
- Visualized correlations using a heatmap.
- Examined correlations between input features and `Class`.
- Ranked the top 10 features by absolute correlation strength.

### ✅ Step 12 — Target Analysis
- Counted normal and fraudulent transactions.
- Calculated class percentages and the imbalance ratio.
- Visualized the distribution of the target classes.
- Learned why accuracy alone can be misleading for imbalanced datasets.

### ✅ Step 13 — Preliminary Feature Analysis
- Identified candidate input features and the target variable.
- Checked for duplicate column names.
- Identified potential constant features.
- Examined feature correlations with `Class`.
- Created a preliminary feature inventory for further investigation.

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization

## 💡 Key Learnings

- Understand the dataset before training a model.
- Identify skewed distributions and potential outliers.
- Interpret positive, negative, and weak linear correlations.
- Understand class imbalance in fraud detection.
- Avoid removing features or outliers without evidence.
- Keep the target variable separate from input features.
- Treat correlation as an exploratory tool, not proof of predictive usefulness.

## 🚀 Next Phase

**Phase 3 — Feature Engineering**

Upcoming steps:

- [ ] Step 14: Create New Features
- [ ] Step 15: Validate New Features
- [ ] Step 16: Check Feature Correlation
- [ ] Step 17: Visualize Features
- [ ] Step 18: Finalize Feature Set

---

**Learning status:** Phase 2 documented. The next phase will focus on creating and validating candidate features before model training.

*Note: This repository documents a step-by-step learning workflow. Model performance and final conclusions will be recorded after the corresponding experiments are completed.*
