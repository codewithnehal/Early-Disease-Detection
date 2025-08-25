# ❤️ Early Disease Detection (Heart Disease)

This project predicts the likelihood of **heart disease** based on patient data. It includes **EDA, preprocessing, and classification models** (Logistic Regression, Decision Tree, Random Forest) with evaluation using **Accuracy, Precision, Recall, F1, ROC-AUC, and Confusion Matrix**. The best model is saved for future predictions.  

---

## 📌 Project Overview  
The goal of this project is to build a **classification model** that detects early signs of **heart disease** using demographic, lifestyle, and health-related attributes. It demonstrates the complete pipeline of **data exploration, preprocessing, model training, hyperparameter tuning, evaluation, and model persistence**.  

---

## 📂 Features Implemented  
- **Exploratory Data Analysis (EDA):**  
  - Class balance visualization  
  - Distribution of numerical features  

- **Data Preprocessing:**  
  - Handling missing values  
  - Encoding categorical features with **OneHotEncoder**  
  - Scaling numerical features with **StandardScaler**  

- **Classification Models:**  
  - Logistic Regression  
  - Decision Tree Classifier  
  - Random Forest Classifier  

- **Model Evaluation Metrics:**  
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  
  - ROC-AUC  
  - Confusion Matrix  

- **Model Saving:**  
  - Best-performing model stored as **`partC_best_model.joblib`**  

---

## 📊 Dataset  
- Contains patient data such as **age, cholesterol, blood pressure, chest pain type, etc.**  
- Target column: **`disease`** (1 = has heart disease, 0 = no disease).  
- Works with CSV/Excel or Google Sheets.  

---

## 🚀 Installation & Setup  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/Early-Disease-Detection.git
   cd Early-Disease-Detection
