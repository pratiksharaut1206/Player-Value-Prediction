# ⚽ Player Value Prediction using Machine Learning

## 📌 Objective
Build a machine learning model to predict the market value of football players using player attributes.  
Also evaluate:
- Impact of PCA (Dimensionality Reduction)
- Impact of Hyperparameter Tuning

---

## 📊 Dataset
The dataset includes:
- Player Info: Name, Country, Club
- Physical Attributes: Height, Weight, Age
- Technical Skills: Passing, Dribbling, Finishing, etc.
- Goalkeeping Skills
- Target: Player Market Value

---

## 🛠️ Project Workflow

### 1. Data Preprocessing
- Removed irrelevant columns
- Handled missing values
- Encoded categorical variables
- Removed duplicates
- Treated outliers using IQR

### 2. Exploratory Data Analysis
- Univariate analysis
- Bivariate analysis
- Correlation heatmap

### 3. Feature Engineering
- Scaling using StandardScaler

---

## 🤖 Models Used

| Model | Type |
|------|------|
| Linear Regression | Baseline |
| Random Forest | Advanced |

---

## 📉 PCA (Dimensionality Reduction)
- Applied PCA to reduce feature space
- Selected components explaining 95% variance
- Compared performance before & after PCA

---

## ⚙️ Hyperparameter Tuning
- Used GridSearchCV
- Optimized:
  - n_estimators
  - max_depth
  - min_samples_split

---

## 📏 Evaluation Metrics
- RMSE (Root Mean Squared Error)
- R² Score

---

## 📊 Results Summary

| Model | Performance |
|------|------------|
| Linear Regression | Moderate |
| Random Forest | High |
| RF + PCA | Slight drop |
| Tuned RF | Best |

---

## 🔍 Key Insights
- Player skills like finishing, reactions, and sprint speed impact value the most
- PCA reduces complexity but may slightly reduce accuracy
- Hyperparameter tuning significantly improves model performance

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
