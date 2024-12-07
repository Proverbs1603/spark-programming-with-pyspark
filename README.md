## 파이썬으로 해보는 Spark 프로그래밍

Pyspark을 사용하며 실습 환경은 Google Colab 입니다. 몇개의 example은 Spark Web UI를 활용해 Execution Plan을 확인하기위해 local에서 Spark standalone 모드를 설치하여 진행 하였습니다.   

---
<br/>

# **Advanced Spark Features: Learning and Exploration**

This repository is dedicated to understanding and experimenting with advanced features of **Apache Spark**, focusing on data engineering and machine learning use cases. The aim is to explore practical applications of Spark's capabilities and best practices for scalable data processing.

---

## **📚 Learning Objectives**

1. **Understand Spark's Core Components**
   - SparkSQL for querying and managing structured data.
   - PySpark for building ETL pipelines and data transformations.
   - SparkML for applying machine learning algorithms.

2. **Explore Advanced Spark Features**
   - **Bucketing**: Optimize joins and aggregations by reducing shuffle overhead.
   - **Partitioning**: Organize data efficiently to improve query performance.
   - **UDFs (User-Defined Functions)**: Write custom functions for advanced transformations.
   - **Schema Evolution**: Handle dynamic schema changes in datasets.
   - **Broadcast Joins**: Optimize small-to-large table joins.

3. **Integrate Hive Metastore**
   - Manage schema and metadata effectively for structured data.

4. **Learn Testing Practices**
   - Validate ETL pipelines and UDFs using unittest frameworks.

---

## **🚀 Features Explored**

### **1. Bucketing and Partitioning**
- Implemented bucketing to optimize shuffle operations during joins.
- Used partitioning to organize large datasets by keys (e.g., date, region) for faster filtering.

### **2. Custom Transformations with UDFs**
- Developed and tested user-defined functions to handle complex logic.

### **3. Broadcast Joins**
- Leveraged broadcast joins to reduce shuffle for small datasets.

### **4. Schema Evolution**
- Managed schema changes dynamically for Parquet/ORC files to handle evolving datasets.

### **5. Integration with Hive Metastore**
- Used Hive Metastore for schema and metadata management to query tables seamlessly with SparkSQL.
