# churn_classification_ANN
Customer Churn Prediction using Artificial Neural Networks (ANN) to identify customers likely to leave a business using deep learning techniques.

# Customer Churn Prediction using Artificial Neural Networks (ANN)

Predict customer churn using a Deep Learning Artificial Neural Network (ANN) built with TensorFlow/Keras. This project preprocesses customer data, trains an ANN model, and provides an interactive Streamlit web application for predicting whether a customer is likely to churn.

---

## Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project leverages an Artificial Neural Network (ANN) to classify customers as likely to churn or not based on their demographic and account information.

The application allows users to input customer details through a Streamlit interface and instantly receive churn predictions along with the predicted probability.

---

## Features

- Customer churn prediction using ANN
- Interactive Streamlit web application
- Data preprocessing and feature engineering
- One-Hot Encoding for Geography
- Label Encoding for Gender
- Standardization using StandardScaler
- Saved trained ANN model (.h5)
- Real-time prediction with probability score

---

## Project Structure

```
Customer-Churn-Prediction-ANN/
│
├── app.py                         # Streamlit application
├── Churn_Modelling.csv            # Dataset
├── experiments.ipynb              # Model training and experiments
├── predictions.ipynb              # Prediction examples
├── model.h5                       # Trained ANN model
├── scaler.pkl                     # StandardScaler
├── onehot_encoder_geo.pkl         # Geography encoder
├── label_encoder_gender.pkl       # Gender encoder
├── requirements.txt               # Dependencies
└── README.md
```

---

## Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit
- Pickle

---

## Model Workflow

1. Load Customer Dataset
2. Data Cleaning
3. Feature Encoding
4. Feature Scaling
5. Train Artificial Neural Network
6. Save Model
7. Predict Customer Churn
8. Deploy with Streamlit

---

## ANN Architecture

- Input Layer
- Dense Hidden Layer (ReLU)
- Dense Hidden Layer (ReLU)
- Output Layer (Sigmoid)
- Adam Optimizer
- Binary Crossentropy Loss

---

## Dataset Features

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

Target:

- Exited (0 = No Churn, 1 = Churn)

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-ann.git
```

Move into the project

```bash
cd customer-churn-ann
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## Model Performance

- Binary Classification
- Sigmoid Activation
- Adam Optimizer
- Binary Crossentropy Loss
- Accuracy evaluated on test dataset

---

## Future Improvements

- Hyperparameter tuning
- Early Stopping
- Dropout Regularization
- Explainable AI using SHAP
- Deploy on Streamlit Cloud
- Docker Support

---

## Applications

- Banking Customer Retention
- Telecom Customer Retention
- Insurance Companies
- Subscription Businesses
- Financial Analytics

---

## Author

**Shaik Shaheen**

Aspiring Machine Learning Engineer | Deep Learning Enthusiast

GitHub: https://github.com/your-username

LinkedIn: https://linkedin.com/in/your-profile

---

## License

This project is licensed under the MIT License.
