# fraud_detection
This project presents a machine learning-based system for detecting fraudulent banking transactions. In modern financial systems, real-time fraud detection is critical to protect users and institutions from losses. The aim is to build a reliable and scalable model that can accurately identify suspicious transactions using historical transaction data.

The solution covers the full data science pipeline — from data preprocessing, model training, and evaluation, to deployment through a user-friendly Streamlit interface.

Key highlights include:

Preprocessing of raw transaction data including encoding categorical variables, handling missing values, and normalization.

Training multiple ensemble machine learning algorithms such as XGBoost, LightGBM, Gradient Boosting, and AdaBoost for binary classification.

Evaluating model performance using metrics like Accuracy, Precision, Recall, F1-Score, and AUC-ROC to ensure reliability and robustness.

Building an interactive web application using Streamlit, where users can input transaction details and receive instant predictions on whether the transaction is fraudulent.

Saving the trained model with joblib for seamless reuse and deployment.

This project is a practical demonstration of how machine learning can be applied to real-world fraud detection problems, helping banks and financial institutions improve their security infrastructure.
