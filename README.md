# 🏅 Paris 2024 Olympic Data Engineering & Analytics Project

## 📌 Overview
This project demonstrates an **end-to-end data engineering pipeline** built on Microsoft Azure to process, transform, and analyze **Paris 2024 Olympic data**.  

The pipeline ingests raw data, performs transformations, and delivers actionable insights through interactive dashboards.

---

## Architecture
![Architecture](Outputs/Olympic%20Data%20Analytics%20%20Architecture.jpg)

### 🔄 Workflow:
1. **Data Source**  
   - Olympic dataset containing athlete, country, medal, and event-level data  

2. **Data Integration (Azure Data Factory)**  
   - Ingests raw data from source  
   - Loads into Azure Data Lake Storage Gen2  
![Data Factory](Outputs/df%20olympic%20sc.jpg)


3. **Raw Data Storage (ADLS Gen2)**  
   - Stores unprocessed raw data  
   - Maintains data in its original format  

4. **Data Transformation (Azure Databricks)**  
   - Cleans and transforms data  
   - Removes inconsistencies and null values  
   - Aggregates medal counts (Gold, Silver, Bronze)  

5. **Transformed Data Storage (ADLS Gen2)**  
   - Stores processed and structured data  
   - Ready for analytics  

6. **Analytics (Azure Synapse Analytics)**  
   - Performs querying and analysis  
   - Enables optimized data access  
![Azure Synapse Analytics](Outputs/Azure%20Synapse%20Analytics.jpg)
7. **Visualization (Power BI)**  
   - Builds interactive dashboards  
   - Displays medal distribution, rankings, and trends  

---

## Tech Stack
- **Azure Data Factory** – Data ingestion  
- **Azure Data Lake Storage Gen2** – Data storage  
- **Azure Databricks (PySpark)** – Data transformation  
- **Azure Synapse Analytics** – Data analysis  
- **Power BI** – Data visualization  
- **Microsoft Excel** – Initial data cleaning  

---

## 📊 Key Features
- End-to-end data pipeline from ingestion to visualization  
- Data cleaning and transformation using PySpark  
- Medal aggregation and ranking by country  
- Scalable cloud-based architecture  
- Interactive Power BI dashboard  

---

## 🔍 Data Processing Steps
- Removed duplicates and handled missing values  
- Standardized categorical fields (country, medal types)  
- Converted data types for consistency  
- Aggregated medal counts by country  
- Ranked countries based on total medals  

---

## 📈 Sample Insights
- Top countries by total medals  
- Gold medal distribution across nations  
- Event-wise participation trends  
- Gender-based performance analysis  

---

## 💡 Future Enhancements
- Real-time streaming using Azure Event Hub  
- Advanced analytics using Machine Learning models  
- Automation using CI/CD pipelines  

---

## 🧠 Learnings
- Built scalable data pipelines using Azure services  
- Gained hands-on experience in data transformation with PySpark  
- Developed analytical dashboards for business insights  


---

## ⭐ If you like this project
Give it a ⭐ on GitHub!
