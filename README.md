# 🌱 Renewable Energy Analytics

### ☁️ AWS S3 → ❄️ Snowflake → 🗄️ SQL → 📊 Tableau

An end-to-end data analytics project that demonstrates how raw renewable energy data can be stored in **Amazon S3**, loaded into **Snowflake**, analyzed using **SQL**, and visualized through an interactive **Tableau dashboard**.

---

## 🔎 Project Overview

The project focuses on analyzing renewable energy consumption across **countries, regions, and energy sources**.

The complete workflow covers:

**Cloud Storage → Data Warehouse → SQL Analysis → Data Visualization**

---

## 🏗️ Data Pipeline


Renewable Energy CSV
        ↓
   ☁️ Amazon S3
        ↓
   🔐 AWS IAM Role
        ↓
   ❄️ Snowflake
        ↓
   🗄️ SQL Analysis
        ↓
   📊 Tableau
        ↓
 Interactive Dashboard

---

## ☁️ AWS S3 & IAM

- Uploaded the raw CSV dataset to an **Amazon S3 bucket**.
- Created an **AWS IAM role** to provide the required permissions for Snowflake to access the S3 data.
- Established the cloud storage layer for the analytics pipeline.

---

## ❄️ Snowflake

- Connected **Snowflake with Amazon S3**.
- Configured the required access and data-loading setup.
- Loaded the dataset into Snowflake.
- Used **Snowflake SQL** for data analysis and aggregation.

---

## 📊 Tableau Dashboard

Built an interactive Tableau dashboard to analyze:

- ⚡ **KWh by Country**
- 🌍 **KWh by Region**
- 🔋 **KWh by Energy Source**
- 📈 **CSU by Region**
- 🌱 **CSU by Energy Source**

The dashboard provides a visual comparison of renewable energy consumption across different geographical regions and energy sources.

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| ☁️ Cloud | AWS S3, AWS IAM |
| ❄️ Data Warehouse | Snowflake |
| 🗄️ Querying | SQL |
| 📊 Visualization | Tableau |
| 📁 Data | CSV |

---

## 💡 Key Skills Demonstrated

- Cloud Data Storage
- AWS IAM & Access Management
- Snowflake Data Warehousing
- SQL Data Analysis
- Data Loading & Integration
- Data Visualization
- Dashboard Development

---

## 📂 Project Files


📁 Renewable-Energy-Analytics
│
├── 📄 Renewable-Energy-Usage-Sampled.csv
├── 📊 Energy Consumption Dashboard.twbx
└── 📖 README.md

--- 
## 🎯 Outcome

Built a complete cloud-to-dashboard analytics workflow, integrating AWS S3, IAM, Snowflake, SQL, and Tableau to transform raw renewable energy data into meaningful visual insights.

---

## 🌱 AWS S3 → ❄️ Snowflake → 🗄️ SQL → 📊 Tableau
