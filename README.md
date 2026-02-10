# Predictive_HR_Analytics_Employee_Attrition_Forecasting_using_ML_Streamlit_Deployment 📊 

An end-to-end Machine Learning web application that predicts whether an employee is likely to leave the company using HR analytics data. The system helps organizations identify high-risk employees and take proactive retention actions through predictive analytics.

---

🔗 **Live App:** https://employee-attrition-ml-app.streamlit.app/

<img width="1916" height="867" alt="image" src="https://github.com/user-attachments/assets/499c45e3-704b-4332-8002-5cb9408d582d" />

---

## 🚀 Project Overview

Employee attrition is a major challenge for organizations as it increases hiring cost, affects productivity, and disrupts workforce stability. This project applies Machine Learning to analyze employee performance and behavioral data to forecast attrition risk.

The solution is deployed as an interactive **Streamlit web application**, allowing real-time prediction based on employee input features. This makes the system practical for HR departments to identify employees who are likely to leave and take preventive actions.

---

## 🎯 Objectives

- Predict whether an employee will **Leave or Stay**
- Help HR identify high-risk employees early
- Enable data-driven workforce retention strategies
- Build and deploy an end-to-end ML web application
- Demonstrate real-world HR analytics use-case

---

## 🧠 Machine Learning Pipeline

1. **Data Collection**  
   HR Employee dataset containing performance and behavioral attributes.

2. **Data Preprocessing**  
   - Handling categorical variables using Label Encoding  
   - Data cleaning and feature preparation  

3. **Feature Engineering**  
   Selected key HR indicators influencing employee attrition.

4. **Model Training**  
   Decision Tree Classifier trained for classification.

5. **Model Serialization**  
   Saved trained model using Joblib (`model.pkl`) and encoders (`label_encoders.pkl`).

6. **Deployment**  
   Built an interactive Streamlit web application for real-time predictions.

---

## 🤖 Machine Learning Algorithm

**Decision Tree Classifier**

The Decision Tree algorithm is a supervised learning model used for classification tasks. It splits the dataset based on feature values to predict whether an employee is likely to leave.

**Why Decision Tree?**
- Handles non-linear relationships well  
- Easy to interpret  
- Works well with structured HR data  
- Requires minimal feature scaling  

---

## 📊 Input Features

The model predicts attrition based on the following employee attributes:

- Satisfaction Level  
- Last Evaluation Score  
- Number of Projects  
- Average Monthly Hours  
- Years in Company  
- Promotion in Last 5 Years  
- Department  
- Salary Level  

---

## 📌 Output

- Predicts whether employee is **Likely to Quit** or **Not Likely to Quit**
- Helps HR identify attrition risk for proactive retention planning

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Data Processing:** Pandas  
- **Machine Learning:** Scikit-learn (Decision Tree)  
- **Model Serialization:** Joblib  
- **Web Framework:** Streamlit  
- **Deployment:** Streamlit Cloud  

---

## 📂 Project Structure

```
├── app.py                  # Streamlit Web Application
├── model.pkl               # Trained Machine Learning Model
├── label_encoders.pkl      # Encoded categorical mappings
├── HR_file.csv             # Dataset used for training
├── Decision_Tree.ipynb     # Model training & experimentation
├── requirements.txt        # Project dependencies
```

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## ☁️ Live Deployment

The application is deployed on **Streamlit Cloud** and provides real-time employee attrition prediction via a simple and interactive UI.

🔗 Access the app here:  
https://employee-attrition-ml-app.streamlit.app/

---

## 📈 Business Impact

- Reduces employee turnover risk  
- Helps HR take proactive retention measures  
- Improves workforce planning and stability  
- Enables predictive HR analytics  
- Reduces hiring and training cost  

---

## 🔍 Key Highlights

- End-to-end ML pipeline implementation  
- Real-time prediction web app  
- Clean and interactive UI using Streamlit  
- Model + Encoder serialization  
- Deployable production-ready system  
- Real-world HR analytics application  

---

## 🚀 Future Enhancements

- Add model evaluation metrics (Accuracy, F1, Confusion Matrix)  
- Show prediction probability (Attrition Risk %)  
- Feature importance visualization  
- Compare multiple ML models (RF, XGBoost, Logistic)  
- Add EDA dashboard inside Streamlit  
- Explainable AI (SHAP) integration  
- Professional UI theme  

---

## 👨‍💻 Author

**Pratham Soni**  
Machine Learning | Data Analytics | Predictive Modeling  

---

## ⭐ Support:

If you found this project useful, consider giving it a **star ⭐** on GitHub.

---
