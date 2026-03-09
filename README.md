# eda_website_analysis_python

Analyzing user behavior and traffic source performance to optimize website engagement and session quality using Python.

# Overview
This project explores a website's traffic data to understand how users interact with content across different hours and acquisition channels. By performing an Exploratory Data Analysis (EDA) process, the project identifies peak performance periods and the most effective traffic sources for driving user activity.

# Business Objective

The main objectives of this project are:

- Evaluate the performance of different traffic channels (Organic Social, Direct, etc.) in driving engaged sessions.

- Identify peak hours of user activity to optimize content release and marketing schedules.

- Analyze the correlation between session volume and user engagement rates.

- Monitor the average engagement time per session to assess content quality and relevance.

- Track the frequency of user events per session to understand the depth of site interaction.

# Dataset

The project uses the data-export (1).csv dataset containing 3,181 traffic records.
Important columns include:

- channel group

- DateHour

- Users & Sessions

- Engaged Sessions

- Engagement rate

- Average engagement time per session

# Tools & Technologies
The analysis was performed using:

- Python

- Pandas & NumPy 

- Matplotlib & Seaborn 

- Jupyter Notebook

# Data Cleaning & Preparation

Before performing analysis, several preprocessing steps were completed:

- Reassigned the first row of the raw CSV as the header and dropped initial metadata rows to structure the dataframe correctly.

- Converted the DateHour column from a numeric string into a standardized datetime format for time-series analysis.

- Extracted the specific hour from the timestamp to enable a detailed analysis of hourly traffic patterns.

- Transformed all metric columns from objects into numeric data types to allow for mathematical mean and sum calculations.

# Key Findings

- Channel Impact: "Organic Social" and "Direct" traffic often contribute significantly to the total session count and user volume.

- Engagement Patterns: Engagement rates fluctuate throughout the day, often showing an inverse relationship with total session volume during peak hours.

- Interaction Depth: The number of events per session provides a clear indicator of how deeply users are interacting with the site content.

- Temporal Trends: User activity shows distinct peaks, helping to pinpoint exactly when the audience is most active and engaged.

# Visualizations

<img width="969" height="720" alt="Screenshot 2026-03-09 162609" src="https://github.com/user-attachments/assets/aeb3574e-baee-42eb-9f1e-f518e3a6be57" />

<img width="988" height="689" alt="Screenshot 2026-03-09 162625" src="https://github.com/user-attachments/assets/332e006a-9bc1-4ef4-8571-d1dbd01bd7c7" />

<img width="1040" height="703" alt="Screenshot 2026-03-09 162639" src="https://github.com/user-attachments/assets/662473e1-478d-4e14-bd6a-2cf4494feafb" />

<img width="987" height="690" alt="Screenshot 2026-03-09 162653" src="https://github.com/user-attachments/assets/a84ef521-6cf5-40a0-bf20-c3ed5c0a2939" />

<img width="1247" height="706" alt="Screenshot 2026-03-09 162709" src="https://github.com/user-attachments/assets/798cdf34-c194-430f-a47e-2749b358ce7d" />

<img width="1148" height="611" alt="Screenshot 2026-03-09 162721" src="https://github.com/user-attachments/assets/9d6d0e81-ff1a-4ed5-88c8-27cd442a3258" />

# How to Run This Project

Clone the repository

git clone https://github.com/jannatulfeva/eda_website_analysis_python.git

Install required libraries
pip install pandas numpy matplotlib seaborn

Open and run the notebook
Run the notebook: eda_website_analysis_python.ipynb

# Author & Contact

Jannatul Ferdaus Eva

Data Analyst

📧 Email: jannateva76@gmail.com














