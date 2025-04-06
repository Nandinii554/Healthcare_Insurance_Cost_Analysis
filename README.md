# 🏥 Medical Insurance Cost Prediction

A Python-based data analysis and machine learning project that explores how various factors such as age, BMI, smoking habits, and region impact medical insurance charges. The project involves **exploratory data analysis (EDA)**, **data preprocessing**, and building a **Linear Regression model** to predict insurance costs.

---

## 📦 Dataset

- **Source:** `insurance.csv`
- **Features:**
  - `age`: Age of the individual
  - `sex`: Gender
  - `bmi`: Body Mass Index
  - `children`: Number of dependents
  - `smoker`: Smoking status
  - `region`: US region of residence
  - `charges`: Medical insurance cost (Target variable)

---

## 🧹 Data Cleaning & Preprocessing

- Removed missing values (none found)
- One-hot encoded categorical variables (`sex`, `smoker`, `region`)
- Created BMI categories: `underweight`, `normal`, `overweight`, `obese`

---

## 📊 Exploratory Data Analysis (EDA)

- Generated summary statistics
- Plotted heatmaps for correlation
- Created scatter and box plots for visual insights

### 🔍 Key Observations:

- **Smokers** pay significantly higher charges
- **Age** and **BMI** show a strong positive correlation with charges
- **Region** also influences insurance costs

---

## 🤖 Predictive Modeling

- Model: **Linear Regression**
- Libraries: `scikit-learn`, `pandas`, `matplotlib`, `seaborn`
- Train-test split: 80/20

### 🧪 Evaluation Metrics:

- ✅ **R-squared:** 0.78  
- ✅ **Root Mean Squared Error (RMSE):** 5805.65  
- ✅ **Mean Absolute Error (MAE):** 4282.94

---

## 💡 Key Findings

- Smoking has the largest impact on insurance costs  
- Age and BMI are important cost drivers  
- Certain regions report higher average charges

---

## 📌 Recommendations

- Use personalized pricing based on customer attributes  
- Promote healthier lifestyles to reduce insurance costs  
- Consider regional variations in pricing models

---

## 🛠 Tech Stack

- **Language:** Python  
- **Libraries:** pandas, seaborn, matplotlib, scikit-learn  
- **Tool:** Jupyter Notebook or Python script

---

