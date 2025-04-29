

# 🚀 **Databricks ADLS Mounting & Delta Lake Pipeline**

![Databricks](https://img.shields.io/badge/Built%20with-Databricks-orange?logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Powered%20by-Apache%20Spark-E25A1C?logo=apache-spark&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## 📁 **Project Overview**

This repository demonstrates how to:

- 🔗 Mount and unmount **Azure Data Lake Storage (ADLS)** in **Azure Databricks**
- 🧱 Implement a **Bronze-Silver-Gold** data pipeline using **Delta Lake**
- 🧪 Perform data transformations and optimizations with **PySpark**
- 🧰 Utilize **Databricks Utilities (`dbutils`)** for filesystem operations

---

## 📂 **Project Structure**

- **`Mounting ADLS.ipynb`** – Mounts ADLS Gen2 storage to Databricks File System (DBFS)
- **`UnMounting.ipynb`** – Unmounts the previously mounted storage
- **`Bronze Layer.ipynb`** – Ingests raw data into the Bronze layer
- **`Silver Layer.ipynb`** – Cleanses and transforms data into the Silver layer
- **`Gold Layer.ipynb`** – Aggregates and prepares data for analytics in the Gold layer
- **`README.md`** – Project documentation and usage instructions

---
### 🏗️ **Project Architecture**

<p align="center">
  <img src="https://raw.githubusercontent.com/Jasper1007J/DataBricksMounting/main/assets/Architecture.png" alt="Sample Output" width="600"/>
</p>


---
## 🧰 **Technologies Used**


- **Azure Data Factory** 
- **Azure Databricks** 
- **Azure Data Lake Storage Gen2 (ADLS)**
- **Apache Spark with PySpark**
- **Delta Lake**
- **Databricks Utilities (`dbutils`)**
- **Python 3**

---

## ⚙️ **Setup Instructions**

1. **Mount ADLS to Databricks:**
   - Open `Mounting ADLS.ipynb`
   - Replace placeholder values with your ADLS credentials and configurations
   - Run the notebook to mount the storage to `/mnt/<mount-name>`

2. **Verify Mount:**
   - Use `dbutils.fs.ls("/mnt/<mount-name>")` to list files and confirm the mount

3. **Data Pipeline Execution:**
   - **Bronze Layer:** Run `Bronze Layer.ipynb` to ingest raw data
   - **Silver Layer:** Run `Silver Layer.ipynb` for data cleansing and transformation
   - **Gold Layer:** Run `Gold Layer.ipynb` to create aggregated datasets for analysis

4. **Unmount ADLS:**
   - After processing, run `UnMounting.ipynb` to unmount the storage if necessary

---

## ✅ **Key Features**

- 📁 **Mounting & Unmounting ADLS:** Seamless integration with Azure Data Lake Storage
- 🧱 **Delta Lake Architecture:** Structured Bronze, Silver, and Gold layers for data processing
- ⚡ **Efficient Data Processing:** Leveraging PySpark for scalable data transformations
- 🔄 **Data Versioning:** Utilizing Delta Lake's ACID transactions for reliable data management

---

## 📸 **Sample Output Preview**
<div>
<p align="center">
  <img src="https://raw.githubusercontent.com/Jasper1007J/DataBricksMounting/main/assets/Company wise Mission Status.png" alt="Sample Output" width="600"/>
  <br>
  <i>Figure: Company Wise Mission Status</i>
</p>

  <p align="center">
  <img src="https://raw.githubusercontent.com/Jasper1007J/DataBricksMounting/main/assets/Map View.png" alt="Sample Output" width="600"/>
  <br>
  <i>Figure: Map View of SpaceX Rocket Status</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Jasper1007J/DataBricksMounting/main/assets/Rocket Launches Count.png" alt="Sample Output" width="600"/>
  <br>
  <i>Figure: Rocket Launches Count</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Jasper1007J/DataBricksMounting/main/assets/Success Rate Heat Map.png" alt="Sample Output" width="600"/>
  <br>
  <i>Figure: Success Rate Heat Map</i>
</p>
</div>
---

## 🧠 **Future Enhancements**

- 🔄 **Automated Workflows:** Integrate with Databricks Workflows for scheduled pipeline runs
- 📊 **Visualization Dashboards:** Connect with Power BI or Tableau for data visualization
- 🛡️ **Data Governance:** Implement Unity Catalog for fine-grained access control
- 📈 **Monitoring & Logging:** Set up monitoring for pipeline performance and logging

---
