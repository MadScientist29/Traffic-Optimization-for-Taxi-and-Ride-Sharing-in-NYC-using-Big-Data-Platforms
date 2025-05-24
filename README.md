# 🚖 Traffic Optimization for Taxi and Ride-Sharing in NYC using Big Data Platforms

**Course:** DATA 603 – Platforms for Big Data Processing  
**Term:** Spring 2025  
**Team Members:** Sai Bhargav K, Giridhar Sriram J, Abhinav Varma V.  

---

## 📌 Project Overview

This project aims to optimize traffic flow and improve ride-sharing efficiency in New York City by leveraging big data platforms. By analyzing traffic volume and ride-sharing data using scalable tools like Apache Spark and Hadoop, we provide strategic insights for better route planning and resource allocation.

---

## 📊 Dataset

We utilized the **New York City Taxi and Limousine Commission (TLC)** trip record data, encompassing millions of taxi and ride-sharing trips. Key features include:

- **Trip Details:** Pickup and drop-off timestamps, locations, trip distances, and durations.
- **Fare Information:** Total fare, tip amount, payment type.
- **Geospatial Data:** Taxi zone lookup for mapping trips to specific NYC zones.

---

## 🔍 Methodology

1. **Data Ingestion and Storage**
   - Loaded TLC datasets into Hadoop Distributed File System (HDFS).
   - Queried structured data using Apache Hive.

2. **Data Processing**
   - Used Apache Spark for scalable data transformation.
   - Cleaned and filtered raw trip records.

3. **Analysis**
   - Identified peak hours, high-demand zones, and traffic congestion patterns.
   - Evaluated ride-sharing opportunities based on route overlap.

4. **Optimization Strategies**
   - Proposed dynamic routing and clustering techniques.
   - Suggested demand-based pricing adjustments.

---

## 📁 Project Structure

<pre>
  Traffic-Optimization-for-Taxi-and-Ride-Sharing-in-NYC-using-Big-Data-Platforms/
│
├── README.md
├── 603_project_s3 Colab.pdf
│
├── data/
│   └── taxi+_zone_lookup (3).csv
│
├── notebooks/
│   └── [Jupyter notebooks for data processing and analysis]
│
├── reports/
│   └── [Detailed analysis reports]
│
└── scripts/
    └── [Spark and Hive scripts used in the project]
</pre>

## 📄 Files Included

- `603_project_s3 Colab.pdf`: Final report including results, graphs, and conclusions.
- `taxi+_zone_lookup (3).csv`: NYC Taxi Zone Lookup data.
- `notebooks/`: Jupyter notebooks for Spark and EDA.
- `scripts/`: Spark SQL and Hive scripts used for analysis.

---

## ✅ Key Findings

- **High Demand Zones**: Midtown Manhattan and JFK Airport showed the most ride activity.
- **Ride-Sharing Potential**: ~30% of trips had overlapping routes within 5-minute intervals.
- **Congestion Patterns**: Weekdays between 5–7 PM had the highest traffic load.

---

## 📈 Recommendations

- **Dynamic Routing**: Use real-time congestion data for adaptive path planning.
- **Encourage Ride-Sharing**: Especially in dense zones like Midtown during peak hours.
- **Smart Pricing**: Implement dynamic fares to encourage off-peak usage.

---

## 📬 Contact

For queries or collaboration, please reach out via GitHub or connect with any team member through UMBC's Data Science program.

