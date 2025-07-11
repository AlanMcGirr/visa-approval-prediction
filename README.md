# visa-approval-prediction
ML project predicting U.S. visa outcomes using ensemble models
=======
# Visa Approval Prediction 🚀

This project aims to build a machine learning model that predicts the approval status of visa applications based on applicant and employer attributes. It was completed as part of the Module 5 Capstone for the DSBA program.

## 💡 Objective

To assist visa officers and employers by predicting whether an application is likely to be **Certified** or **Denied**, using supervised learning techniques such as Random Forest, AdaBoost, Gradient Boosting, and XGBoost.

---

## 🔍 Key Features Used

- Education Level  
- Work Experience  
- Prevailing Wage  
- Employment Region  
- Company Size and Establishment Year  

---

## 🧠 Models Compared

- Decision Tree  
- Random Forest  
- AdaBoost  
- Gradient Boosting  
- XGBoost  

Threshold tuning and class balancing were also explored via SMOTE and undersampling.

---

## 📊 Performance Summary

| Model             | Test F1 Score |
|------------------|---------------|
| Gradient Boost v1| **0.8193**    |
| AdaBoost v2      | **0.8190**    |
| XGBoost v2       | 0.8159        |
| Random Forest v2 | 0.8163        |

Gradient Boost and AdaBoost were selected as final models based on generalization and stability.

---

## 🌐 Live Demo

Try the model here:  
🔗 [Visa Approval Demo (Claude)](https://claude.ai/public/artifacts/d8e15c07-0607-4bb8-85b3-f7ba42160b19)

---

## 📎 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Alan McGirr  
Part of the University of Texas DSBA Program  
