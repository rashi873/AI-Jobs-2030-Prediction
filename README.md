# 🚀 AI-Jobs-2030 — Predictive Modeling (Python+Power BI)
Predicting Job Growth Rate in the AI-driven Future Workforce

This project uses **Machine Learning + Data Analytics** to predict **Tech Job Growth Rate by 2030** using the Kaggle **AI Jobs 2030** dataset.  
It includes EDA, feature engineering, model training, model comparison, XGBoost modeling, and an interactive **Power BI insights dashboard**.

---

## 🧠 Project Objectives

✔ Analyze how AI impacts future jobs  
✔ Predict **Average Salary / Job Growth Rate**  
✔ Identify high-risk & high-opportunity job sectors  
✔ Build ML models (Linear Regression, Random Forest, XGBoost)  
✔ Visualize insights using **Power BI**  
✔ Produce a complete, deployable **ML pipeline**

---

## 📊 Tech Stack

| Category | Tools |
|---------|-------|
| **Programming** | Python |
| **Libraries** | Pandas, NumPy, Scikit-Learn, XGBoost, Seaborn, Matplotlib |
| **Visualization** | Power BI |
| **Version Control** | Git + GitHub |

---

## 📂 Repository Structure


AI-Jobs-2030-Prediction/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── 01_EDA.ipynb
│ ├── 02_Feature_Engineering.ipynb
│ └── 03_Model_Training.ipynb
│
├── ML/
│ ├── feature_engineered_data.csv
│ ├── linear_regression_model.pkl
│ ├── random_forest_model.pkl
│ ├── xgboost_model.pkl
│ └── model_comparison.csv
│
├── dashboard/
│ └── PowerBI.pbix
│
├── src/
│ ├── data_preprocessing.py
│ ├── feature_engineering.py
│ ├── train_model.py
│ └── evaluate_model.py
│
├── results/
│ ├── plots/
│ └── predictions.csv
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore



---

## 📘 Project Workflow

### **1️⃣ Data Collection & Preprocessing**
- Load Kaggle dataset  
- Handle missing values  
- Encode categorical variables  
- Scale numeric features  
- Export cleaned dataset to `data/processed/`

---

### **2️⃣ Exploratory Data Analysis (EDA)**
- Job category distribution  
- Salary trends  
- AI Exposure vs Job Growth  
- Correlation heatmaps  
- Outlier detection  

---

### **3️⃣ Feature Engineering**
- Target variable: **Average Salary / Job Growth Rate**  
- Label Encoding for job titles & categories  
- Standard Scaling for numeric columns  
- New engineered features (ratios / interactions)  
- Save final dataset → `ML/feature_engineered_data.csv`

---

### **4️⃣ Model Training**

Models used:
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

Each model:
- Trained using `train_test_split`
- Evaluated using **MSE, RMSE, R²**
- Saved into `ML/` folder for reuse

---

### **5️⃣ Model Comparison**

| Model             | RMSE      | R² Score |
|------------------|-----------|----------|
| Linear Regression | 1.011451  | -0.005046 |
| Random Forest     | 0.443290  | 0.806949 |
| XGBoost           | 0.361838  | 0.871375 |

📌 **XGBoost is the best-performing model.**

---

### **6️⃣ Power BI Dashboard**

## 📊 Dashboard Preview
🔗 [Click here to view the dashboard screenshot 1](https://github.com/rashi873/AI-Jobs-2030-Prediction/blob/main/01_dashboard_screenshot.png)
🔗 [Click here to view the dashboard screenshot 2](https://github.com/rashi873/AI-Jobs-2030-Prediction/blob/main/02_dashbooard_screenshot.png)
🔗 [Click here to view the dashboard screenshot 3](https://github.com/rashi873/AI-Jobs-2030-Prediction/blob/main/03_dashboard_screenshot.png)


Insights include:
- Fastest growing job sectors  
- AI risk vs opportunity for each job role  
- Salary distribution visualization  
- Predictions vs actuals comparison  
- Top 10 future-proof careers  

File is included in `dashboard/PowerBI.pbix`.

---

## 🧾 Credits & Contact

**👩‍💻 Author:** Rashi Bali  

💼 **Role:** Data Analyst  
📧 **Email:** rashibali77@gmail.com  
🔗 **LinkedIn:** [Rashi Bali](https://www.linkedin.com/in/rashibali873/)  
💻 **GitHub:** [github.com/rashi873](https://github.com/rashi873)

---
⭐ Support

If you like this project, please give it a star ⭐ on GitHub!
It helps more people discover the repo and supports my work.
cd AI-Jobs-2030-Prediction


