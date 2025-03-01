# Result Management System

## Overview
The Result Management System is designed to efficiently generate, store, and analyze student performance data using Apache Spark. This project processes marks for 10,000 students across six subjects and stores the results in Google Drive. Statistical insights are generated and visualized using Python.

## Key Features
- **Automated Student Data Generation:** Randomly assigns marks to 10,000 students.
- **Distributed Processing with Apache Spark:** Enables efficient computation of statistics.
- **Persistent Storage Using Google Drive:** Acts as an alternative to HDFS for managing large datasets.
- **Statistical Analysis:** Computes averages, maximum, minimum, and standard deviation for each subject.
- **Data Visualization:** Uses Matplotlib to create insightful bar charts for performance analysis.

## Technology Stack
- **Apache Spark (PySpark):** Distributed data processing.
- **Google Colab:** Cloud-based execution environment.
- **Google Drive:** Storage solution for student data.
- **Python:** Data handling, statistical analysis, and visualization.
- **Matplotlib:** Generates bar charts for subject-wise statistics.

## How the Code Works
1. **Install Dependencies:** Installs PySpark for distributed computing.
2. **Initialize Spark Session:** Creates a Spark session to manage large-scale data operations.
3. **Generate Student Data:** Creates a dataset of 10,000 students with randomly assigned ages and marks.
4. **Store Data in Google Drive:** Saves the dataset as a CSV file for persistent storage.
5. **Load Data from Google Drive:** Reads the stored CSV into a Spark DataFrame.
6. **Compute Statistics:** Calculates subject-wise averages, maximum, minimum, and standard deviations.
7. **Save Analysis Results:** Stores computed statistics back into Google Drive.
8. **Visualize Data:** Uses Matplotlib to create bar charts showcasing student performance trends.
9. **Stop Spark Session:** Ensures a clean shutdown of Spark to free up resources.
