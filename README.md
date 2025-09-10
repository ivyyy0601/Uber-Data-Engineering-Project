# 🚖 Uber Data Analytics | Modern Data Engineering on GCP

## 📌 Introduction
The goal of this project is to perform **data analytics on Uber data** using a modern data engineering stack.  
We leverage **Google Cloud Platform (GCP)** and open-source tools to build a scalable data pipeline, run transformations, and create insightful dashboards.

---

## 🏗️ Architecture
*building*  

The architecture follows a modern ELT approach:
1. Data is ingested and stored in **Google Cloud Storage (GCS)**.  
2. A **Compute Instance** runs Python scripts and pipelines.  
3. **Mage** is used as the orchestration/data pipeline tool.  
4. Transformed data is loaded into **BigQuery**.  
5. Visualizations and dashboards are built using **Looker Studio**.

---

## ⚙️ Technology Used
- **Programming Language**: Python  
- **Google Cloud Platform**:
  - Google Cloud Storage  
  - Compute Instance  
  - BigQuery  
  - Looker Studio  
- **Modern Data Pipeline Tool**: [Mage](https://www.mage.ai/)  



---

## 📂 Dataset
This project uses the **NYC TLC Trip Record Data**:  

- Includes **yellow and green taxi trip records**  
- Fields include:
  - Pick-up and drop-off dates/times  
  - Pick-up and drop-off locations  
  - Trip distances  
  - Itemized fares  
  - Rate types & payment types  
  - Passenger counts  

📊 **Dataset Used in Demo**: [uber_data.csv](https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv)  

🔗 More information:  
- [NYC TLC Trip Record Website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
- [Data Dictionary (Yellow Trips)](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

---

## 🗄️ Data Model
*(Here you can describe or attach your data model diagram — e.g., staging → fact & dimension tables, schema design, etc.)*

Example structure:
- **Staging Tables**: Raw trip data  
- **Fact Table**: Trip details with fares and distances  
- **Dimension Tables**: Locations, payment types, rate codes  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/uber-data-engineering.git
   cd uber-data-engineering
