💳 Credit Card Fraud Detection using Machine Learning


A machine learning project that detects fraudulent credit card transactions using a Random Forest Classifier.
The model analyzes transaction patterns and predicts whether a transaction is legitimate or fraudulent.

📌 Project Overview

Credit card fraud causes massive financial losses worldwide. Detecting fraud quickly and accurately is crucial for financial institutions and e-commerce platforms.

This project builds a machine learning pipeline that:

Loads and explores transaction data

Prepares training and test datasets

Trains a Random Forest classification model

Evaluates model performance

Visualizes feature importance and confusion matrix

📊 Dataset Information

The dataset contains anonymized credit card transactions.

Property	Value
Total Transactions	568,630
Features	31
Numerical Features	V1 – V28
Additional Feature	Amount
Target Column	Class

Target variable

Class	Meaning
0	Legitimate Transaction
1	Fraudulent Transaction

Dataset distribution:

Legitimate Transactions : 284,315
Fraudulent Transactions : 284,315
⚙️ Project Workflow
1️⃣ Load Dataset
2️⃣ Data Preparation
3️⃣ Model Training
4️⃣ Model Evaluation
📈 Feature Importance

Random Forest calculates how much each feature contributes to predictions.
Top influential features include:

V9
V10
V12

These features play a key role in detecting fraudulent transactions.

📉 Confusion Matrix Visualization
🧠 Key Insights

✔ Random Forest performs extremely well on this dataset
✔ Important variables strongly influence fraud detection
✔ High recall ensures fraudulent transactions are rarely missed

🛠 Tech Stack
Technology	Usage
Python	Programming language
Pandas	Data processing
NumPy	Numerical computation
Scikit-learn	Machine learning
Matplotlib	Visualization
Seaborn	Data visualization



download data set from kaggle here is the link below.

https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023?resource=download


