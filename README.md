# Tokyo-Olympics-Azure-Data-Engineering-Project

---

## 🌟 Project Highlights  
This project implements a comprehensive **ETL pipeline** leveraging Microsoft Azure services to process and analyze data from the Tokyo 2021 Olympics. The goal is to explore Azure tools while building a robust framework for data ingestion, transformation, storage, and visualization. This learning-oriented project lays the foundation for scalable data engineering workflows.  

![image](https://github.com/user-attachments/assets/2bc1b2b9-243e-49c6-a1cd-efec06ecb737)


---

## 📂 Dataset Overview  
The dataset includes five CSV files related to the Tokyo 2021 Olympics:  
- **Athletes**: Information on participants.  
- **Coaches**: Details of coaching staff.  
- **EntriesGender**: Gender-based participant statistics.  
- **Medals**: Medal distribution by event and country.  
- **Teams**: Information on participating teams.  

---

## 🛠️ Azure Services Utilized  

### 1. **Azure Data Factory (ADF)**  
- Facilitates data ingestion pipelines.  
- Transfers raw data from GitHub to Azure Data Lake Storage Gen2 (ADLS Gen2).  

### 2. **Azure Data Lake Storage Gen2 (ADLS Gen2)**  
- Centralized storage for raw and transformed data.  
- Organized into folders: `raw-data` and `transformed-data`.  

### 3. **Azure Databricks**  
- An Apache Spark-powered platform for processing and transforming data.  
- Handles schema validation, data cleaning, and transformations.  

### 4. **Azure Synapse Analytics**  
- A data warehousing solution for structured analysis.  
- Hosts transformed data in SQL pools for querying and analysis.  

### 5. **Power BI**  
- A visualization tool for creating interactive dashboards.  
- Planned integration for insights such as medal distributions, gender participation, and team performance.  

---

## 🚀 ETL Workflow  

### **Step 1: Data Ingestion**  
- Used ADF pipelines to import raw data from GitHub.  
- Stored data in the `raw-data` folder of ADLS Gen2.

  ![image](https://github.com/user-attachments/assets/d2d47001-c51b-4c4f-9768-bd610eb9fc79)

  ![image](https://github.com/user-attachments/assets/5c46b0f1-d950-4b15-a6b6-e69b1c0c7310)



### **Step 2: Data Transformation**  
- Processed data in Azure Databricks using PySpark:  
  - Loaded CSV files into DataFrames.  
  - Conducted schema validation and handled missing values.  
  - Stored cleaned data in the `transformed-data` folder of ADLS Gen2.
 
    ![image](https://github.com/user-attachments/assets/d41eb1d6-0e48-49b6-86b2-37e106e06190)
    ![image](https://github.com/user-attachments/assets/4b29c061-e7b9-44a0-9274-9ae540b1822c)
    ![image](https://github.com/user-attachments/assets/edc83f2f-1309-45f4-82cd-b88499793972)
    ![image](https://github.com/user-attachments/assets/d860d803-2f25-4d10-8d26-4d9cf6996125)





### **Step 3: Data Warehousing**  
- Linked transformed data to Azure Synapse Analytics.  
- Created structured tables in a SQL pool for querying and analysis.

  ![image](https://github.com/user-attachments/assets/4a77ff3a-2306-4073-9033-20722c4e67e5)


### **Step 4: Visualization (Planned)**  
- Initiating Power BI integration for interactive dashboards.  
- Expected reports include insights on medal distributions, participation trends, and team performances.  

---

## 💡 Key Takeaways  
- **Integrated Solution**: Seamless use of Azure services for efficient data processing.  
- **Scalability**: Design ensures performance at scale with ADLS Gen2 and Synapse Analytics.  
- **Efficiency**: PySpark in Databricks ensures fast and reliable data transformations.  
- **Analytics-Ready Data**: Outputs are prepared for immediate querying and visualization.  

---

## 🔧 Project Implementation  

### **Requirements**  
- An active **Microsoft Azure account**.  
- Familiarity with ADF, ADLS Gen2, Databricks, Synapse Analytics, and Power BI.  
- Access to the Tokyo 2021 Olympics dataset.  

### **Setup Instructions**  
1. Clone this repository.  
2. Configure Azure resources as described in the ETL workflow.  
3. Use the provided PySpark scripts for data processing in Databricks.  
4. Link transformed data to Synapse Analytics for querying.  
5. (Optional) Create Power BI dashboards for visualization.  

---

## ✍️ Potential Enhancements  

### **Production-Ready Additions**  
- Incorporate robust monitoring and logging in ADF pipelines.  
- Implement Role-Based Access Control (RBAC) for data security.  
- Optimize transformations for better performance.  

### **Advanced Transformations**  
- Conduct outlier detection and advanced data cleaning.  
- Apply feature engineering for richer analytics.  

### **Dashboard Completion**  
- Finalize Power BI dashboards for actionable insights.  
- Add detailed visualizations for medal counts, participation trends, and team performance.  

---

## 📝 Conclusion  
This project highlights the potential of **Microsoft Azure services** for building efficient and scalable ETL pipelines. With minor enhancements, it can transition from a learning exercise to a production-ready solution.  

---

## 👤 Author  
- **Name**: Sivaprasad V 
- **LinkedIn**: https://www.linkedin.com/in/sivaprasad-v-213011213?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

Feel free to contribute or suggest improvements!  

---

---

## 🎥 Credits
This project was inspired and guided by the excellent tutorial series created by [Darshil Parmar](https://github.com/darshilparmar).  
Check out his YouTube channel for the full tutorial series: [Darshil Parmar - YouTube](https://www.youtube.com/@DarshilParmar).

Tutorial video for this project: [Tokyo 2021 Olympics ETL Pipeline Tutorial](https://www.youtube.com/watch?v=IaA9YNlg5hM&list=PLBJe2dFI4sgvQTNNkI3ETYJgNPR4CBpFd&index=6).

---
