# Bankruptcy Prevention - Classification Project

## 📌 Business Objective
This project aims to predict the likelihood of a company going bankrupt based on various risk factors. It is a **binary classification problem** where the target variable is either **"bankruptcy"** or **"non-bankruptcy"**.

## 📊 Dataset Information
The dataset contains **250 company records** with **7 features**:
1. **industrial_risk**: 0 = Low risk, 0.5 = Medium risk, 1 = High risk.
2. **management_risk**: 0 = Low risk, 0.5 = Medium risk, 1 = High risk.
3. **financial_flexibility**: 0 = Low flexibility, 0.5 = Medium flexibility, 1 = High flexibility.
4. **credibility**: 0 = Low credibility, 0.5 = Medium credibility, 1 = High credibility.
5. **competitiveness**: 0 = Low competitiveness, 0.5 = Medium competitiveness, 1 = High competitiveness.
6. **operating_risk**: 0 = Low risk, 0.5 = Medium risk, 1 = High risk.
7. **class (Target Variable)**: **"bankruptcy"** or **"non-bankruptcy"**.

## 🏗 Project Workflow
1. **Data Preprocessing**:
   - Handle missing values (if any) and clean the dataset.
   - Normalize/standardize data for better model performance.
   - Split the dataset into **training** and **testing** sets.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing feature distributions and relationships.
   - Checking feature correlations using heatmaps.

3. **Model Selection & Training**:
   - Training various classification models:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - XGBoost
     - Support Vector Machine (SVM)
   - Evaluating model performance using metrics like **accuracy, precision, recall, F1-score, and ROC-AUC**.

4. **Model Deployment**:
   - Develop an interactive web application using **Flask or Streamlit**.
   - Deploy the trained model to make real-time predictions.

## 🛠 Installation & Setup
### Clone the Repository
```bash
 git clone https://github.com/yourusername/bankruptcy-prevention.git
 cd bankruptcy-prevention
```
### Install Dependencies
```bash
 pip install -r requirements.txt
```
### Run the Application (Streamlit)
For Streamlit:
```bash
 streamlit run app.py
```

## 📈 Results & Performance
- The best-performing model will be chosen based on evaluation metrics.
- Feature importance analysis will be conducted to interpret predictions.

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
- Feel free to fork the repository and submit pull requests.
- Report any issues or suggest improvements via GitHub Issues.

## 📬 Contact
For any queries, reach out via email: **nagarajugorantla972@.com**

