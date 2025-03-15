# AI-Powered-Data-Quality-Monitoring

* Project Overview *

This project implements Machine Learning (ML)-based anomaly detection to monitor data quality. It detects inconsistencies in data pipelines using:

Isolation Forest (Unsupervised Anomaly Detection)

Autoencoder (Deep Learning-based Anomaly Detection)

📂 Project Structure

├── ai_data_quality_notebook.ipynb   # Jupyter Notebook with full implementation
├── anomaly_report.csv               # Output file with detected anomalies
├── REPORT.md                         # Detailed project report
├── README.md                         # This file

🛠️ Setup Instructions

1️⃣ Install Dependencies

Ensure you have Python 3.8+ installed. Then, install required packages:

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow imbalanced-learn

2️⃣ Run Jupyter Notebook

Start Jupyter Notebook and open ai_data_quality_notebook.ipynb:

jupyter notebook

Run all cells to execute data preprocessing, model training, and anomaly detection.

3️⃣ View Anomaly Report

After running the notebook, an anomaly report will be saved as anomaly_report.csv. You can open it in Excel or view it using:

import pandas as pd
df = pd.read_csv("anomaly_report.csv")
df.head()

🔬 Methodology

Data Preprocessing: Standardization using StandardScaler.

Anomaly Detection Models:

Isolation Forest (sklearn.ensemble.IsolationForest)

Autoencoder (tensorflow.keras)

Performance Evaluation: Precision, Recall, and F1-score.

📊 Results Summary

Isolation Forest Accuracy: 97%

Autoencoder Accuracy: 95%

Best Model: Isolation Forest (higher recall and precision for anomalies)

🚀 Future Enhancements

Hyperparameter tuning for Autoencoder.

Integration with BigQuery for real-time anomaly detection.

Ensemble method combining Isolation Forest + Autoencoder.

📞 Contact

For questions or contributions, feel free to reach out!

