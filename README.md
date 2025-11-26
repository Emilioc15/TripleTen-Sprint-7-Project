# 📱 TripleTen Sprint 7: Megaline Plan Recommendation

## 📝 Project Overview

This project focuses on building a machine learning model that recommends one of Megaline’s modern mobile plans — **Smart (0)** or **Ultra (1)** — based on a customer’s monthly behavior. The goal is to help Megaline transition users away from outdated plans and improve their overall service experience.

You will train multiple classification models, compare their performance, and choose the one that achieves the **highest accuracy**, with a required minimum of **0.75** on the test set.

---

## 📊 Dataset Description

The dataset contains monthly usage information for Megaline customers:

| Feature      | Description |
|--------------|-------------|
| `calls`      | Number of calls made |
| `minutes`    | Total duration of calls (in minutes) |
| `messages`   | Number of SMS messages sent |
| `mb_used`    | Internet traffic used (in MB) |
| `is_ultra`   | Target variable: 1 = Ultra plan, 0 = Smart plan |

This is a **binary classification** problem.

---

## 🎯 Objectives

- Load and explore the dataset  
- Split the data into **training**, **validation**, and **test** sets  
- Train and compare different machine learning models  
- Tune hyperparameters to improve performance  
- Evaluate the best model using the test dataset  
- Confirm the accuracy meets or exceeds **0.75**

---

## 🔧 Models Explored

Typical models used in this sprint include:

- Logistic Regression  
- Decision Tree  
- Random Forest  

Hyperparameter tuning is applied to improve validation accuracy and select the best-performing model.

---

## 📈 Final Deliverables

- Clean, organized notebook with explanations  
- Model comparison summary  
- Final accuracy score on the test data  
- Brief conclusions on model performance and recommendation strategy  

---

## ✅ Success Criteria

A successful project will:

- Demonstrate clear reasoning and workflow  
- Achieve **at least 0.75 accuracy** on the test set  
- Show understanding of model selection and tuning  
- Provide concise, meaningful conclusions
