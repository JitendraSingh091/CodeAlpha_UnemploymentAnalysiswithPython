📊 Unemployment Analysis with Python
🧠 Overview

This project analyzes unemployment rate data across different regions of India to understand trends, regional variations, and the impact of COVID-19. Using Python, the data is cleaned, explored, and visualized to uncover patterns that can inform economic and social policy decisions.

An interactive Streamlit dashboard is also created to visualize the findings dynamically.

🎯 Objectives

Analyze unemployment rate data representing unemployed people as a percentage.

Clean and preprocess the dataset for accuracy.

Explore unemployment trends using Python visualizations.

Investigate the impact of COVID-19 on unemployment rates.

Identify seasonal or regional patterns in unemployment.

🛠️ Technologies Used

Python

Pandas – Data cleaning, transformation, and analysis

NumPy – Numerical computations

Matplotlib / Seaborn – Static visualizations for EDA

Plotly – Interactive visualizations

Streamlit – Dashboard for real-time data exploration

📂 Dataset

Source: Unemployment in India – Kaggle Dataset

File Used: unemployment_data.csv

Each record includes:

Date – Observation date

Region – Indian state or region

Area – Urban / Rural

Estimated Unemployment Rate (%)

Estimated Employed

Estimated Labour Participation Rate (%)

🔍 Data Processing

Data Cleaning:

Removed missing or inconsistent values.

Converted Date column to datetime format.

Renamed and standardized columns for clarity.

Exploratory Data Analysis (EDA):

Summary statistics for unemployment, employment, and participation rates.

Time-series trend analysis of unemployment over months.

Regional and area-wise comparisons.

COVID-19 period segmentation (Pre-COVID vs During COVID).

📈 Analysis & Visualizations
✅ 1. Average Unemployment Rate by Region

Bar chart comparing the average unemployment rate across regions.

✅ 2. Average Unemployment Rate Over Time

Line chart visualizing unemployment trends month-by-month.

✅ 3. Change in Average Unemployment Rate by Region

Bar chart showing which regions had the highest rise or fall during COVID-19.

✅ 4. Distribution of Unemployment Rates in India

Histogram/KDE plot visualizing how unemployment rates are distributed.

✅ 5. Labour Participation vs Unemployment Rate

Scatter plot showing the relationship between participation rate and unemployment.

✅ 6. Unemployment Rate Before and During COVID

Comparison metrics and line chart revealing the COVID-19 impact.

📊 Streamlit Dashboard

An interactive dashboard was built to visualize the results dynamically.
Users can:

Select Regions and Areas (Urban/Rural) from sidebar filters.

View interactive line charts using Plotly.

Navigate between analysis images through sidebar selections.

💡 Insights
COVID-19 caused a significant rise in unemployment globally.
Some regions recovered faster post-lockdown than others.
Seasonal patterns show recurring economic effects on employment.
