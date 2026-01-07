# 📊 E-commerce Business Intelligence Dashboard (GCP)

## Overview
This project demonstrates an end-to-end Business Intelligence (BI) workflow using Google Cloud Platform.
The goal was to design, scale, and visualize e-commerce transaction data in a way that reflects real-world BI practices.

The final result is an interactive dashboard built with BigQuery and Looker Studio.

---

## 🏗 Architecture
Cloud Storage  
→ BigQuery (Raw & Scaled Tables)  
→ Analytics Layer (CTAS)  
→ Looker Studio Dashboard

---

## 🧱 Data Modeling

### Raw Layer
- transactions_scaled
- Synthetic scaled dataset (~1,000+ rows)

### Analytics Layer
- monthly_revenue_scaled
- category_revenue_scaled
- customer_metrics_scaled

---

## 📊 Dashboard Metrics
- Total Revenue (€)
- Monthly Revenue Trend
- Revenue by Product Category
- Top Customers by Lifetime Value

---

## 🛠 Tools & Technologies
- Google Cloud Platform
- BigQuery (SQL, CTAS)
- Looker Studio
- SQL

---

## 📸 Dashboard Preview
Screenshots are available in the `/dashboard` folder.

---

📌 Built as part of a professional BI portfolio.
