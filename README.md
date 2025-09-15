# 🧠 Prediction of Cerebrovascular Disease Using Machine Learning

This repository contains the code and documentation for my published research project on **predicting cerebrovascular disease (stroke) using machine learning algorithms**. The work was published in the **International Journal of Information Technology and Computer Science (IJITCS)**.

---

## 📌 Project Overview
Cerebrovascular disease is a leading cause of death and disability worldwide. Early prediction of risk factors can assist in preventive care and treatment planning.  

This project explores machine learning techniques for disease prediction, focusing on model performance, interpretability, and fairness in healthcare.

---

## ⚙️ Methodology
1. **Data Acquisition**  
   Patient data including demographics, clinical factors, and lifestyle attributes.

2. **Preprocessing**  
   - Missing value handling  
   - Categorical encoding  
   - Feature scaling
   - Data Balancing  

3. **Models Implemented**  
   - Logistic Regression  
   - Random Forest Classifier  
   - Support Vector Machine (SVM)  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrices  
   - ROC Curves  

5. **Tools Used**  
   - Python (scikit-learn, pandas, numpy)  
   - Matplotlib, Seaborn (visualization)  

---

## 📊 Results
- **Logistic Regression**: Most balanced predictions across both classes; interpretable and reliable.  
- **Random Forest**: Highest accuracy but showed bias toward the majority class (overfitting risk).  
- **SVM**: Competitive results but more computationally intensive.  

👉 **Key Finding:** Logistic Regression provided the best tradeoff between accuracy, fairness, and interpretability for healthcare deployment.

---

## 💡 Discussion
This study highlighted the need to go beyond accuracy when evaluating medical prediction models. For imbalanced healthcare data, interpretability and fairness are as important as raw performance.

---

## ✅ Conclusion
Machine learning is a powerful tool for disease prediction when combined with careful preprocessing and evaluation. Logistic Regression stood out as the most practical choice for healthcare applications in this project.  

Future work could expand into ensemble methods and deep learning while ensuring interpretability remains intact.

---

