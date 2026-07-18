🗄️ Milestone 3: Structured Query Language (SQL) Extractions
Goal: Map Python structures into relational models using sqlite3 to perform advanced data filtering, aggregations, and performance rankings.

Core Queries Executed
1. Segment-Wise Item Aggregations
Calculates product metrics using COUNT, SUM, AVG, and GROUP BY:


2. Acquisition Channel Net Conversion Metrics
Filters operational leakages via WHERE to measure true financial metrics by referral pipes:


Top Order Extraction: Order ORD200789 generated the highest single transaction value of $3,456.40 via a 5-unit Tablet order.

Acquisition Leader: Instagram served as the highest net converting acquisition pipeline, generating $108,246.78 in clean closed sales.

🚀 Environment Setup & Deployment
Run this project within a local machine or a cloud space like Google Colab.

Dependencies Installation:
Bash
pip install pandas matplotlib seaborn openpyxl
Execution Steps:
Bash


# Run the exploratory metrics dashboard script
python eda_analysis.py

# Run the database query extracts script
python sql_insights.py
Developed during the Data Analyst Internship Program at DecodeLabs.
"""









🚀 Production Setup Instructions: Users ya team members ke liye repository clone karne, environments verify karne, dependencies install karne aur scripts run karne ki standard console commands add kiye hain.
