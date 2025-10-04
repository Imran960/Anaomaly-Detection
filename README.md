Anomaly Detection in Credit Card Transactions
This project focuses on detecting anomalies (fraudulent transactions) in credit card data using custom implementations of popular machine learning algorithms such as Isolation Forest, Random Forest, XGBoost, and AdaBoost.  
The aim is to reduce false positives and improve fraud detection accuracy through experimental model design.

•	Project Overview
- Dataset: Credit Card Fraud Detection Dataset (imbalanced dataset with legitimate and fraudulent transactions).
- Problem: Fraud detection is a binary classification problem with very few fraudulent cases, making anomaly detection techniques suitable.
- Key Objective: Minimize false positive errors while ensuring high fraud detection.

•	Features Implemented
- Custom Isolation Forest (from scratch implementation)
- Custom Random Forest Classifier
- Custom XGBoost-like Classifier
- Custom AdaBoost Classifier
- Data preprocessing with StandardScaler
- Model evaluation using  accuracy score

•	Tech Stack
- Python  
- Pandas, NumPy  
- scikit-learn  
- Seaborn & Matplotlib (visualization)

•	Project Workflow
1. Load dataset (`creditcard.csv`).
2. Preprocess features (scaling using `StandardScaler`).
3. Train-test split (80% train, 20% test).
4. Train models:
   - Isolation Forest (custom)
   - Random Forest (custom)
   - XGBoost-like model (custom)
   - AdaBoost (custom)
5. Evaluate predictions and analyze anomaly detection capability.

•	How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Anomaly-Detection.git
   cd Anomaly-Detection
