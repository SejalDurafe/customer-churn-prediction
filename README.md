Customer Churn Prediction System

📌 Project Description

Customer Churn Prediction System is a machine learning application that predicts whether a customer will stay or leave the company. The application is developed using Python, Streamlit, and Random Forest.

🛠️ Technologies Used

- Python
- Streamlit
- NumPy
- Random Forest
- Pickle

📊 Input Features

The system uses the following customer details:

- Credit Score
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Estimated Salary
- Country
- Gender

⚙️ How It Works

1. The user enters the customer's details.
2. The input data is scaled using a pre-trained scaler.
3. The Random Forest model predicts customer churn.
4. The system displays whether the customer will stay or exit.

▶️ How to Run

Install the required libraries:

pip install streamlit numpy

Make sure these files are present in the same folder:

- "app.py"
- "random_forest_churn_model.pkl"
- "scaler.pkl"

Run the application:

streamlit run app.py

🎯 Objective

The main objective of this project is to help identify customers who are likely to leave, allowing businesses to take suitable actions to improve customer retention.

📌 Output

- Customer Will Stay – customer is predicted to remain.
- Customer Will Exit – customer is predicted to churn.

👩‍💻 Project

Customer Churn Prediction using Machine Learning
