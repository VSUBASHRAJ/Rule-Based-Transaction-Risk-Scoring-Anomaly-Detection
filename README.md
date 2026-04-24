#  Rule-Based Transaction Risk Scoring & Anomaly Detection

### (Power BI Dashboard with ETL Workflow Design - Alteryx Concept)

---

##  Project Overview

This project focuses on analyzing financial transaction data to identify **high-risk and potentially fraudulent activities** using a **rule-based risk scoring model**.

The solution combines:

* **Data transformation and feature engineering (ETL concept)**
* **Risk scoring and anomaly detection**
* **Interactive dashboard visualization using Power BI**

---

##  Problem Statement

Organizations face challenges in identifying fraudulent transactions due to:

* Large volumes of transaction data
* Hidden behavioral patterns
* Lack of real-time risk indicators

This project aims to **detect high-risk transactions and visualize patterns** to support better decision-making.

---

##  Solution Approach

```text
Raw Data → Data Cleaning → Feature Engineering → Risk Scoring → Visualization → Insights
```

* Built a **rule-based scoring system**
* Identified **anomalies using transaction patterns**
* Created **interactive dashboards for analysis**

---

##  Dataset

* Source: Credit Card Fraud Dataset
* Contains anonymized transaction data
* Key fields:

  * `Time` → Transaction timestamp
  * `Amount` → Transaction value
  * `V1–V28` → Anonymized behavioral features
  * `Class` → Fraud (1) / Normal (0)

---

##  ETL Workflow (Alteryx Conceptual Design)

> Note: ETL pipeline is designed conceptually using Alteryx workflow logic.
> Implementation was performed using Power BI transformations.

### Workflow Steps:

* **Input Data Tool** → Load dataset
* **Data Cleansing Tool** → Handle missing values, standardize data
* **Formula Tool** → Create:

  * Risk Score
  * Risk Level
* **Filter Tool** → Identify anomalies
* **Output Tool** → Export processed dataset

---

##  Feature Engineering (Power BI)

Created calculated columns:

* **Hour** → Extracted from Time
* **High Amount Flag** → Based on transaction value
* **Risk Score** → Rule-based calculation
* **Risk Level** → High / Medium / Low
* **Anomaly Flag** → Identifies unusual transactions

---

## 📊 Dashboard Features (Power BI)

###  Key Metrics (KPIs)

* Total Transactions
* Fraud Count
* High Risk Transactions

###  Visualizations

* Fraud vs Normal Distribution
* Risk Level Distribution
* Transaction Trends by Time
* Amount vs Risk Score Analysis

###  Filters (Slicers)

* Risk Level
* Time (Hour)
* Anomaly Flag

---

##  Key Insights

* High-value transactions contribute significantly to risk levels
* Fraudulent transactions show clustering in specific time ranges
* Risk scoring helps prioritize suspicious transactions for investigation

---

##  Tools & Technologies

* **Power BI** → Data visualization and dashboarding
* **DAX** → Feature engineering and calculations
* **Excel / CSV** → Dataset
* **Alteryx (Conceptual)** → ETL workflow design




##  Dashboard Preview

*(Add screenshots here after building your dashboard)*

---

##  Future Enhancements

* Real-time data pipeline integration
* Machine learning-based fraud detection
* Deployment using cloud platforms


---

##  Key Takeaways

* Demonstrates **ETL + Analytics + Visualization**
* Shows **business-focused problem solving**
* Applies **risk detection concepts in real-world data**

---


🔗 LinkedIn: https://www.linkedin.com/in/v-subash-raj/

---
