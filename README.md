
# NYC Taxi Big Data Analysis 🚖
Big data Analysis and Insights on NYC yellow taxi data 

## Overview
This project analyzes the **NYC Yellow Taxi Trip Dataset (January 2015)** using **PySpark**.  
The goal is to demonstrate scalable **big data processing**, SQL-based analytics, and insights into urban transportation patterns.

The notebook replicates common **Databricks-style workflows** but runs locally in **VS Code/Jupyter** with PySpark.

---

## Features
- ✅ Built a **Spark data pipeline** to ingest and process millions of taxi trip records.  
- ✅ Used **Spark SQL + DataFrames** for scalable analysis.  
- ✅ Performed **exploratory data analysis (EDA)**:
  - Trip durations
  - Peak demand hours
  - Pickup & drop-off trends
- ✅ Demonstrated both **local (VS Code)** and **cloud (Databricks)** workflows.

---

## Tech Stack
- **Languages**: Python  
- **Frameworks**: Apache Spark (PySpark), Spark SQL  
- **Tools**: Jupyter Notebooks, VS Code, Databricks  
- **Data**: NYC Yellow Taxi Trip Data (2015-01)  

---

## Dataset
The dataset comes from NYC_YellowTripTaxi on Kaggle (https://www.kaggle.com/code/elemento/nyc-yellowtriptaxi/data).  
For this project, we use **January 2015 Yellow Taxi Trip Data**.

-- Important --- 
1. dowload the dataset and place the file in the same directory as  NYV_BigData_Analysis.ipynb
2. change .load("yellow_tripdata_2015-01.csv") to the name and year of the yellow_tripdata being used


Place the CSV in the same folder as the notebook and name it:
