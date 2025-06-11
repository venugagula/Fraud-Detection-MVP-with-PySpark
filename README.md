# 🚨 Fraud Detection MVP with PySpark

An end-to-end fraud detection pipeline using PySpark, built as a minimum viable product (MVP) for identifying suspicious financial transactions. This solution leverages scalable data processing on Azure Databricks and basic machine learning techniques for rapid fraud detection, integrated with real-time analytics dashboards in Power BI.

---

## 🧠 Project Overview

- **Goal**: Detect financial fraud from transaction data using PySpark and machine learning.
- **Model**: Binary classifier to identify potentially fraudulent activity.
- **Accuracy Achieved**: ~82% with limited historical data.

---

## ⚙️ Architecture

![Architecture Diagram](architecture.png)

**Pipeline Stages:**
1. **Raw Data** – Ingest transactional logs from source systems.
2. **Preprocessing** – Clean and normalize features using PySpark.
3. **ML Model** – Train and evaluate a fraud detection classifier.
4. **Prediction Output** – Save flagged transactions for audit.
5. **Dashboarding** – Visualize fraud patterns via Power BI.

---

## 🔧 Technologies Used

| Stack | Tools/Frameworks |
|-------|------------------|
| Programming | Python, PySpark |
| ML Libraries | Scikit-learn, Pandas |
| Big Data | Azure Databricks |
| Visualization | Power BI |
| Cloud | Azure Data Lake, Azure Blob Storage |

---


