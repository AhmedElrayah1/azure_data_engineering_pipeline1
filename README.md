# Azure Data Engineering Pipeline

## 📌 Project Overview
This project demonstrates an end-to-end **Azure Data Engineering pipeline** using **Azure Data Factory** and **Azure Data Lake Storage Gen2**.

The pipeline is designed to ingest raw CSV data from a Data Lake, transform it into optimized **Parquet** format, and load it into a structured analytics-ready layer.

---

## 🏗 Architecture
Source (CSV Files)  
➡ Azure Data Lake Storage Gen2 (Raw Layer)  
➡ Azure Data Factory Pipelines  
➡ Data Transformation  
➡ Parquet Files (Curated Layer)  
➡ Azure Synapse / Data Pool (Optional)

---

## ⚙️ Technologies Used
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Blob Storage
- Parquet Format
- Azure Synapse Analytics
- Git & GitHub

---

## 🔄 Pipeline Features
- Automated data ingestion from Data Lake
- Data format conversion from CSV to Parquet
- Event-based trigger using Storage Events
- Re-runnable and scalable pipeline design
- Cloud-native ELT architecture

---

## ▶️ How the Pipeline Works
1. Upload CSV files to Azure Data Lake
2. Storage Event Trigger activates the pipeline
3. Azure Data Factory processes the data
4. Output is stored as Parquet files
5. Data is ready for analytics and reporting

---

## 🧠 Key Concepts Demonstrated
- Batch Data Processing
- Event-driven Pipelines
- Data Lakehouse Architecture
- Azure-native Data Engineering
- ETL / ELT best practices

---

## 📈 Future Enhancements
- Add data validation and monitoring
- Integrate Azure Synapse SQL Pools
- Implement CI/CD using Azure DevOps
- Add data quality checks

---

## 👤 Author
**Ahmed Elrayah**  
Azure Data Engineer  
GitHub: https://github.com/AhmedElrayah1
