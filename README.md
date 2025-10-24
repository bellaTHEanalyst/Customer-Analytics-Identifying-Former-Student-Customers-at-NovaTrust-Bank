# 💳 Customer Analytics: Identifying Former Student Customers at NovaTrust Bank

This project delivers an **end-to-end customer analytics solution** for **NovaTrust Bank**, using **SQL Server** and **Power BI** to identify former student customers who have transitioned into the workforce and are eligible for tailored upselling opportunities.

🎥 **Watch the full walkthrough:** [👉 Click here to view the video](https://drive.google.com/drive/folders/1mdkPQu-OMhH6dgknc13EpdgCZOvvXTr-?usp=drive_link)

---

##  Project Overview

NovaTrust Bank noticed that many of its student account holders continued using their student accounts after graduation, despite qualifying for upgraded financial products.  
This project was developed to help the bank identify, segment, and engage these customers through **data-driven insights**.

Using **SQL for querying and segmentation** and **Power BI for visualization**, the project builds a complete analytics pipeline — from raw transactional data to actionable marketing insights.

---

##  Key Features

- **🏦 Customer Identification:**  
  Extracts customers who opened student accounts and now receive regular salary payments.

- **💰 Segmentation by Salary Behavior:**  
  Groups customers based on salary frequency and amount (e.g., ≥ 10 deposits + avg salary > ₦200,000).

- **📈 RFM Scoring:**  
  Computes **Recency, Frequency, and Monetary** scores to quantify engagement and value.

- **📊 Power BI Dashboard:**  
  Visualizes KPIs like total transitioning customers, salary ranges, segmentation distribution, and engagement potential.

- **📄 Reporting & Recommendation Layer:**  
  Provides actionable insights for the marketing team to target qualified customers with credit cards, loans, and investment products.

---

##  Behind the Build

1. **Data Extraction →** Queried `Customers` and `Transactions` tables in SQL Server Express 2022 using joins and filters.  
2. **Data Preparation →** Cleaned, standardized, and validated data integrity in SSMS 19.1.  
3. **Segmentation →** Used computed RFM scores to group customers by engagement potential.  
4. **Visualization →** Imported results into Power BI to build interactive visuals for salary trends and customer movement.  
5. **Automation →** Designed reusable SQL views to refresh data automatically for future campaign cycles.

---

## 🛠️ Tech Stack

- **SQL Server Express 2022** — relational database & querying engine  
- **SQL Server Management Studio (SSMS 19.1)** — query development & optimization  
- **Power BI** — dashboard creation & interactive reporting  

---

##  Key Deliverables

| Dashboard Insight | Description |
|:---------------------------|:-------------------------------|
| **Total Transitioned Customers** | Number of student accounts now receiving salaries |
| **Average Monthly Salary** | Mean salary per segment |
| **Salary Range Distribution** | Visual breakdown of income brackets |
| **Customer Segmentation** | Grouping by RFM score and salary pattern |
| **Engagement Opportunities** | Recommended upgrade or upsell categories |

---

##  Insights & Impact

- Highlighted **high-value former student segments** with strong salary activity.  
- Enabled **targeted marketing** for cross-selling credit cards, loans, and investment services.  
- Established a **repeatable SQL + Power BI workflow** for future campaigns.  
- Reinforced NovaTrust’s customer-centric strategy by improving retention and lifetime value.

---

## 📁 Project Structure

