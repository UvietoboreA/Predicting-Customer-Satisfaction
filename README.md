# 📈 Predicting Customer Satisfaction with Machine Learning  

Understanding customer satisfaction is vital for enhancing business strategies and creating impactful customer experiences.  

Leveraging the **Customer Feedback and Satisfaction Dataset**, I developed a **predictive model** to forecast satisfaction scores based on demographic and behavioral features of **38,444 customers**.  

---

## 🎯 Project Objectives  

✅ **Predictive Modeling**: Built regression models to forecast customer satisfaction scores.  
✅ **Insight Generation**: Analyzed factors influencing satisfaction, such as gender, loyalty level, and feedback scores.  
✅ **Model Evaluation**: Assessed performance metrics to ensure reliability and accuracy.  

---

## 🔍 Key Steps  

### 1️⃣ Data Preprocessing  
- Cleaned and **encoded categorical features** (e.g., gender, country, loyalty level).  
- **Scaled data** using Min-Max Scaler for normalization.  
- **Applied Principal Component Analysis (PCA)** to reduce dimensionality while preserving **95% variance**.  

### 2️⃣ Exploratory Data Analysis (EDA)  
📊 **Correlation heatmaps and scatter plots** revealed strong relationships between **loyalty level, feedback score, and satisfaction score**.  

### 3️⃣ Model Implementation  
🔧 **Support Vector Regression (SVR) with RBF kernel** was selected for its ability to handle non-linear relationships.  
- **Hyperparameter tuning**:  
  - `C = 10`, `ε = 0.5` for optimal performance.  

### 4️⃣ Performance Evaluation  
📊 **Metrics Achieved**:  
- **R² Score**: 78.59%  
- **Mean Absolute Error (MAE)**: 5.4069  
- **Root Mean Squared Error (RMSE)**: 7.7890  

### 📉 Visual Insights  
- **Line and scatter plots** compared actual vs predicted satisfaction scores, showcasing the model’s alignment with real-world data.  

---

## 🔑 Key Takeaways  

📊 **Regression techniques like SVR provide powerful tools** for predicting and understanding customer satisfaction.  
📈 **Insights from such models enable targeted improvements** in customer experience, loyalty programs, and overall business strategy.  

---

## 🛠 Tech Stack  

- **Programming Language**: Python  
- **Libraries**: pandas, scikit-learn, seaborn, matplotlib  
- **Model Used**: Support Vector Regression (SVR)  

---

## 🏷️ Tags  

**#MachineLearning #CustomerSatisfaction #DataScience #Regression #SVR #BusinessAnalytics**  
