# ML-Data-Cleaning-Pipeline

## 📌 Project Overview  
This project is part of my **AI & ML Internship**. The goal of Task 1 is to learn and apply **data cleaning & preprocessing** techniques on a real dataset. I used the **Titanic dataset** (from Seaborn) since it contains missing values, categorical features, and numerical features — making it perfect for this task.  

---

## 🎯 Objectives  
- Explore raw dataset and understand its structure  
- Handle missing values (imputation with median/mode, special category for missing)  
- Encode categorical features into numerical format  
- Apply normalization and standardization to numerical features  
- Detect and handle outliers using **boxplots** and **IQR method**  
- Save the cleaned dataset for further ML tasks  

---

## 🛠 Tools & Libraries  
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn** (for encoding & scaling)  

---

## 📂 Files in this Repository  
- `Task1_Data_Preprocessing.ipynb` → Google Colab notebook with all code & outputs  
- `titanic_cleaned.csv` → Cleaned dataset with preprocessing applied  
- `titanic_final_for_model.csv` → Final dataset ready for ML model training  
- `README.md` → Project documentation (this file)  

---

## 📊 Steps Performed  
1. **Data Exploration (EDA)** → checked shape, info, null values, and summary stats  
2. **Handling Missing Values**  
   - `age` → filled with median  
   - `embarked` → filled with mode  
   - `deck` → filled with a new category `"Missing"`  
3. **Encoding Categorical Variables** → one-hot encoding using `pd.get_dummies`  
4. **Feature Scaling** → applied both normalization and standardization for numeric columns  
5. **Outlier Detection** → used IQR method & boxplots for `age` and `fare`  
6. **Dataset Export** → saved cleaned datasets as CSV for reuse  
7. **Bonus** → trained a simple Logistic Regression model as a sanity check  

---

## 📖 Key Learnings  
- Different types of missing data (MCAR, MAR, MNAR)  
- Encoding strategies: Label Encoding vs One-Hot Encoding  
- Normalization vs Standardization  
- Outlier detection using IQR and visualization  
- Importance of preprocessing in improving ML model performance  

---

## 📸 Sample Visuals  
- Distribution plots (Age, Fare)  
- Count plots (Class vs Survival)  
- Boxplots for Outliers  
- Correlation heatmap  

---

## 🚀 How to Run  
1. Open the notebook in **Google Colab** or Jupyter  
2. Run all cells sequentially  
3. Cleaned datasets will be saved in `/content/` (if Colab)  
4. You can download them or directly use for ML model training  

---

## 📌 Submission Note  
This project is prepared as part of my **AI & ML Internship (Task 1: Data Cleaning & Preprocessing)**.  
