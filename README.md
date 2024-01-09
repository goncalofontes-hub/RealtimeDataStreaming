# RealtimeDataStreaming

This project is a end-to-end Data Engineering Pipeline. It covers the ingestion of data using a API to generate random user data (```randomuser.me```), the processing using robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Spark and finnaly storage using Cassandra.

---

# System Architecture

![image](https://github.com/goncalofontes-hub/RealtimeDataStreaming/assets/61528618/c71e7829-27e1-4632-986e-40a5315d2703)

The pipeline is designed with the following components:
+ **Data Source:** ```randomuser.me``` API to generate random user data.
+ **Apache Airflow:** Platform for designing, scheduling, and monitoring workflows.
+ **PostgreSQL:** Used for storage the fetched data.
+ **Apache Kafka:** Used for streaming data from PostgreSQL to the processing engine.
+ **Apache Spark:** Used for the data processing using the master and worker nodes.
+ **Cassandra:** Used to storage the processed data.

---
# Tech Stack

+ **Docker**
+ **Apache Kafka**
+ **Python**
+ **Apache Spark**
+ **Cassandra**
+ **PostgreSQL**
+ **Apache Airflow**

---

