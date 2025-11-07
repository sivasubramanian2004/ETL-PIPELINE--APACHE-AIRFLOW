## 🛠️ MySQL ETL Pipeline using Apache Airflow

This project demonstrates a simple **ETL (Extract, Transform, Load)** workflow orchestrated using **Apache Airflow**.

### 📌 ETL Flow
| Step | Description |
|------|-------------|
| **Extract** | Fetches raw data from a MySQL database. |
| **Transform** | Uses Python (`pandas`) to clean and process the data. |
| **Load** | Stores the transformed data into CSV files. |

---

### 🗂️ Tools & Technologies Used
- Apache Airflow
- Python (Pandas)
- MySQL
- CSV Output Storage

---

### ⏱️ DAG Schedule
- **Every 5 minutes** (Testing Mode)
- **Hourly** (Production-like Automation)

---

### Running the Pipeline
#### Start Airflow Scheduler
airflow scheduler

#### Start Airflow Web Server
airflow webserver -p 8085


### Open Airflow UI in browser:

http://localhost:8085




