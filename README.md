
# 🚀 **Space-X Rocket Launch Analysis (Databricks)**

This repository contains a detailed **Exploratory Data Analysis (EDA)** of Space-X's rocket launch data performed using **Databricks Notebooks**. The project explores **mission success rates**, **payload mass impact**, and the **influence of launch time and company** using powerful big data tools.

---

## 📁 **Project Structure**

- **`Space-X Rocket Analysis.ipynb`** – Exported Databricks notebook with full analysis and visualizations.  
- **`README.md`** – Project overview, instructions, and insights.

---

## 📊 **Key Features**

- 📌 **Data Cleaning & Wrangling** using `PySpark` and `Python`
- 📈 **Visualizations** built inside **Databricks Notebooks**
- 🔍 **Mission Success Analysis** by:
  - 🚦 Mission Status (Success / Failure/ Partial Failure/ Pre-launch Failure)
  - 🚀 Rocket Status (Active / Retired)
  - 🕒 Time of Day (Morning / Evening / Night)
  - 🏢 Company

- 🔗 **Insights** presented using:
  - Bar Plots
  - Pie Charts

---

## 🧰 **Tools & Technologies Used**

- **Databricks Notebook**
- **Apache Spark (PySpark)**
- **Python 3**
- **Databricks SQL**
- **GitHub**

---

## 📦 **Dataset**

- The dataset is derived from **Space-X's public launch data**.
- It can be uploaded to **DBFS (Databricks File System)** or accessed from **GitHub**.

---

## ⚙️ **Running This Project on Databricks**

To use this notebook inside Databricks:

1. 🔗 **Open your Databricks Workspace**.
2. 📁 **Import the notebook** (`Space-X Rocket Analysis.ipynb`) using:
   - *Workspace > Import > File*
3. 💻 **Attach it to a running cluster**.
4. 📂 **Upload the dataset** to DBFS:
   - *Data > Add Data > Upload File*  
   - Or mount from external sources like GitHub, Azure, or AWS
5. ▶️ **Run all notebook cells** to see data exploration and visualizations.

---

## ✅ **Output Highlights**

- 🚀 Find out which **mission types and companies** are most successful
- ⏱️ Evaluate **Time of Day's influence** on launch success
- 🛰️ Compare **rocket status and mission outcomes**

---

## 🧠 **Future Enhancements**

- 🔄 Integration with **live Space-X API** for real-time analysis using Delta Live Tables
- 📊 Dashboard creation using **Power BI**
- ⚙️ Scheduled notebook runs via **Databricks Jobs**

---
