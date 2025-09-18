# 🎓 Student Performance Factors

This project analyzes the **factors that influence student academic performance** using data exploration, preprocessing, and machine learning models.  
The goal is to build predictive models that can estimate student outcomes based on various personal, academic, and social factors.

---

## 📊 Dataset
- **Source**: [Kaggle – Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)  
- **Features**: Includes factors such as hours studied, attendance, parental involvement, access to resources, extracurricular activities, and more.  
- **Target Variable**: Student performance scores.

---

## ⚙️ Workflow
1. **Data Import & Cleaning**
   - Handled missing values  
   - Encoded categorical variables (OneHotEncoder, OrdinalEncoder)  
   - Scaled numerical features  

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of categorical and numerical variables  
   - Examined correlations between features and target  

3. **Modeling**
   - Applied **Linear Regression**  
   - Applied **Polynomial Regression (degree 2)**  
   - Evaluated models using MSE, MAE, and R²  

---

## 📈 Results
- **Linear Regression Model**  
  - MSE: **0.095**  
  - MAE: **0.259**  
  - R²: **0.99**

- **Polynomial Regression Model (degree 2)**  
  - MSE: **0.100**  
  - MAE: **0.264**  
  - R²: **0.99**

✅ Both models achieved high accuracy, but **Linear Regression performed slightly better**, suggesting the relationship between features and student performance is primarily **linear**.

---

## 🏆 Conclusion
The analysis shows that **student performance is strongly influenced by multiple academic and social factors**, and a **Linear Regression model** provides a simple yet highly accurate way to predict outcomes.  
Polynomial complexity did not provide significant improvements, highlighting that simpler models can often be more effective.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-factors.git
   cd student-performance-factors
