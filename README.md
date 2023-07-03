# Comparing-the-performance-of-ETL-pipeline-using-Spark-and-Hive-under-Azure-VM

## Overview
   This project aimed to compare the performance of ETL (Extract, Transform, Load) pipelines using Spark and Hive in handling large datasets. The objective was to determine which technology provided better speed, accuracy, and a programmer-friendly environment. Additionally, the project sought to identify the best system design scenarios for using either Spark or Hive in an ETL pipeline.

   The environment was set up by installing and configuring Spark, Hadoop, and Hive on an Azure virtual machine (VM). These components were 
   crucial for building ETL pipelines and conducting performance evaluations.
   
## Steps Taken
 1. Setup: The environment was prepared by installing and configuring Spark, Hadoop, and Hive on an Azure VM.
 2. Data Preparation: Simulated datasets of different sizes (1MB, 50MB, and 1GB) were generated using scripts. These datasets were stored 
    in persistence storage, such as HDFS, and served as sources for both Spark and Hive ETL pipelines.
 3. ETL Pipeline Development: ETL pipelines were developed using Spark and Hive. These pipelines performed extraction, transformation, and 
   loading of data from various sources, including the simulated CSV datasets.
 4. Performance Evaluation: The performance of Spark and Hive ETL pipelines was analyzed based on speed, accuracy, and the programmer- 
   the friendly environment they provided.
 5. System Design Scenarios: The project investigated the best system design scenarios for using either Spark or Hive in an ETL pipeline. 
   This analysis took into account various factors, such as dataset size, complexity, and the specific requirements of the ETL process.
  
 ## Completed Work

   The project has been completed, and the following tasks were accomplished:

1. The ETL pipelines were refined and optimized to improve performance.
2. Performance metrics, such as execution time, resource utilization, and data quality, were collected for both Spark and Hive pipelines.
3. Experiments were conducted with different dataset sizes and complexities to evaluate the scalability and efficiency of Spark and Hive in 
   handling large-scale ETL tasks.
4. The collected data was analyzed, and the performance of Spark and Hive ETL pipelines was compared under different scenarios.
5. A detailed report summarizing the project's results, conclusions, and recommendations was prepared.
   Repository Contents

### The repository contains the following files and directories:

src/: Source code for the ETL pipelines implemented using Spark and Hive.

data/: Simulated datasets of various sizes (1MB, 50MB, and 1GB) used for performance evaluation.

scripts/: Scripts used for dataset generation and other auxiliary tasks.

results/: Performance metrics and analysis results obtained during the experiments.

docs/: Documentation files, including this README and the final project report.

### How to Use
To use the ETL pipelines implemented using Spark and Hive or refer to the project's findings, follow these steps:

1. Clone or download this repository to your local machine.
2. Review the source code (src/ directory) to understand the implementation details of the Spark and Hive ETL pipelines.
3. Explore the simulated datasets provided in the data/ directory.
4. Review the final project report in the docs/ directory for detailed findings, conclusions, and recommendations.
5. If desired, reproduce the experiments by following the instructions provided in the report and code comments.
6. Adapt and modify the ETL pipelines or experiment with different scenarios as needed, based on the project's findings.
