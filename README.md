# Descriptive-Project-Analyzing-Reliability-of-Airlines-and-Routes

Descriptive Project: Analyzing Reliability of Airlines and Routes

Objective

The goal of this project was to analyze the reliability of airlines and flight routes using descriptive statistics, data visualization, and unsupervised learning techniques.

Dataset

The dataset contained flight information such as:

Airline

Origin and Destination

Departure/Arrival Delays

Flight Length

Day and Month of flight

Steps & Methodology

Data Import and Cleaning:
Loaded and cleaned flight data to handle missing or inconsistent values.

Exploratory Data Analysis (EDA):
Visualized top airlines, busiest routes, and delay distributions.

Statistical Analysis:
Computed measures like mean, median, and standard deviation of delays to quantify reliability.

Visualization with Matplotlib & Seaborn:
Created bar charts, heatmaps, and time-series plots to observe trends by route, airline, and time.

Clustering with Scikit-learn:
Used KMeans to identify airline reliability clusters based on average delay, delay variability, and average flight length.

Results & Findings

Certain airlines consistently showed lower average delays, indicating higher reliability.

Routes between major hubs had greater variability in delay times, likely due to congestion.

Peak travel months (especially holidays) displayed higher average delays.

KMeans clustering separated airlines into three categories:

Cluster 0: Highly reliable, short and consistent flights.

Cluster 1: Moderately delayed, medium-length routes.

Cluster 2: Least reliable, high delay variability and longer flights.
