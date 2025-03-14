# **Adult Census Income Prediction Using Machine Learning**  

## **Overview**  
This project aims to develop a predictive model that classifies an individual's income level based on demographic and socioeconomic characteristics. Using machine learning techniques, the model determines whether an individual's income is **above or below $50,000** per year.  

GitHub Repository: [Adult Income Prediction](https://github.com/akindream/adult_income_prediction)  

---

## **Project Objective**  
The goal of this project is to analyze **census income data** and develop a machine learning model that can accurately predict whether an individual's income is above or below **$50,000** based on multiple socioeconomic factors.  

### **Key Steps:**  
✔ **Data Preprocessing** – Cleaning and encoding categorical variables.  
✔ **Feature Selection** – Identifying the most impactful factors.  
✔ **Model Training** – Testing different machine learning algorithms.  
✔ **Evaluation** – Comparing models based on accuracy and robustness.  

---

## **Dataset**  
The dataset was obtained from the **UCI Machine Learning Repository** ([link](http://archive.ics.uci.edu/dataset/2/adult)). It contains **48,842 instances** with **14 attributes** plus the target variable (`salary`).  

### **Most Influential Features** 🔥  
From **feature selection techniques**, the most important features influencing income prediction were:  
- **age**  
- **education_rank** (numerical representation of education level)  
- **sex**  
- **hours_per_week**  
- **salary** (target variable: ≤50K or >50K)  

These factors significantly impact income classification, making them crucial for the model.  

---

## **Machine Learning Models**  

### **1️⃣ Supervised Learning Models Tested**  
The following algorithms were used to train the model:  
- **Logistic Regression**  
- **Decision Trees**  
- **Random Forest**  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Machine (SVM)**  
- **Gaussian Naïve Bayes (GNB)**  

### **2️⃣ Performance Comparison**  

#### **After Hyperparameter Tuning:**  
| Model                 | Accuracy (%) |
|----------------------|-------------|
| Decision Tree       | 76.12%      |
| Logistic Regression | 80.59%      |
| SVM                 | **81.57%**  |
| Gaussian NB         | 80.99%      |
| Random Forest       | 79.01%      |
| KNN                 | 80.37%      |

#### **After Applying Bagging:**  
| Model                 | Accuracy (%) |
|----------------------|-------------|
| Decision Tree       | 78.87%      |
| Logistic Regression | 80.56%      |
| SVM                 | **81.66%**  |
| Gaussian NB         | 80.99%      |
| Random Forest       | 79.64%      |
| KNN                 | 80.36%      |

📌 **Support Vector Machine (SVM) performed the best with 81.66% accuracy** after applying bagging techniques.  

---

## **Techniques Used**  
✔ **Data Preprocessing** – Categorical encoding, handling missing values.  
✔ **Feature Selection** – Forward selection, backward selection, correlation analysis.  
✔ **Ensemble Learning** – Bagging was applied to improve model stability.  

---

## **Future Research 🔬**  
🚀 **Advanced Deep Learning:** Applying deep learning techniques (e.g., Recurrent Neural Networks, Transformers) could enhance accuracy.  
🚀 **Model Stacking:** Combining multiple models to further boost prediction performance.  
🚀 **Expanded Feature Engineering:** Exploring additional socioeconomic factors to improve predictions.  

---

## **Conclusion**  
This project demonstrates how machine learning can be effectively used to **predict income levels** based on demographic and work-related factors. By leveraging **SVM**, we achieved an **81.66% accuracy rate**, making it the best-performing model.  

📌 **Want to explore the code?** Check it out here: [GitHub Repo](https://github.com/akindream/adult_income_prediction)  
📌 **Medium:** [Predicting Income](https://medium.com/@akindream/predicting-income-levels-using-machine-learning-a-deep-dive-into-the-adult-census-income-dataset-5ff246087748)
📌 **LinkedIn:** [Predicting Income](https://www.linkedin.com/posts/ernest-braimoh-29284b141_predicting-income-levels-using-machine-learning-activity-7306296340110626816-Zmeb?utm_source=share&utm_medium=member_desktop&rcm=ACoAACJ5f84BSF16YQBlNnzy86sMhIc99PdU8l0)
---

Expecting your feedback 😊🚀
