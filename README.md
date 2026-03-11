# EveryMind: Clinical Data Integrity Sentinel
**Project Lead:** Marilyn MM | **Domain:** Health Data Science & Decision Support

## 🎯 Project Objective
This project was developed as a proactive data governance solution for **EveryMind Mental Health Services**. As the Lead Agency for child and youth mental health in the **Region of Peel**, EveryMind manages complex clinical data from multiple entry points. This "Sentinel" uses Machine Learning to automatically identify data integrity risks before they impact provincial reporting or clinical care.

## 🛠️ The Tech Stack
* **Engine:** Python (Google Colab)
* **Models:** DBSCAN (Density-Based Spatial Clustering) & Isolation Forest
* **Storage:** GitHub (Version-controlled clinical datasets)
* **Visualization:** Power BI (Executive Decision Support Dashboard)

## 🧠 The "Sentinel" Logic
The system analyzes clinical intake data (up to age 25) to identify three types of anomalies:
1.  **Logical Errors:** (e.g., An 85-year-old in a youth-focused database).
2.  **Quality Gaps:** (e.g., Data entry typos like "999" days for wait times).
3.  **Clinical Priorities:** (e.g., High-severity cases with zero wait time, indicating a fast-tracked crisis intake).

## 📈 Decision Support Impact
Instead of manual, random audits, this tool provides the **Performance Measurement & Improvement Team** with an automated **"Audit Queue."** This ensures:
* **100% Accuracy** for Ministry of Health funding reports.
* **Operational Efficiency** by reducing manual database troubleshooting.
* **Clinical Safety** by highlighting urgent cases that deviate from the statistical norm.

---
*Note: This project utilizes synthetic data generated for the purpose of demonstrating clinical information system infrastructure.*
