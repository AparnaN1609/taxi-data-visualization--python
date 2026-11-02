🚕 Taxi Data Analysis & Visualization

  Python | Pandas | Matplotlib | Seaborn

📌 Project Overview

This project is a practical exercise in Python-based data analysis and visualization using the Seaborn Taxis dataset. The main purpose was to explore taxi trip data, understand its structure, handle missing values and create different visualizations using Python libraries. The analysis covers taxi fares, trip distances, payment methods, pickup boroughs and tip distributions.

🛠️ Technologies & Libraries

Technology                      Purpose
  

 Python                       Data analysis

 Pandas                       Data handling and preprocessing

 NumPy                        Numerical operations

 Matplotlib                   Creating visualizations

 Seaborn                      Creating statistical visualizations
 
 Jupyter Notebook             Writing and running Python code


📂 Dataset 
Dataset: Seaborn Taxis Dataset

The dataset includes information about taxi trips, such as: 
* Pickup and drop-off timestamps
* Trip distance
* Fare
* Tip
* Tolls
* Total trip amount
* Payment method
* Pickup and drop-off boroughs and zones

Dataset Source: Seaborn built-in dataset (sns.load_dataset("taxis")).

🔍 Project Workflow

01. Data Exploration

* Loaded the Taxis dataset using Seaborn.
* Checked the dataset shape, columns and data types.
* Viewed sample records and descriptive statistics.
* Identified numerical and categorical columns.
* Checked missing values and their percentages.

02. Data Cleaning & Preprocessing

* Converted the pickup column into datetime format.
* Removed rows with missing values in selected important columns.
* Identified numerical and categorical columns.
* Filled remaining numerical missing values using the median.
* Filled remaining categorical missing values using the mode.
* Checked the dataset again after preprocessing.

03. Data Visualization

Created 10 visualizations using Matplotlib, Pandas and Seaborn.

A. Matplotlib & Pandas
* No.                                                     * Visualization                                                      * Purpose
 
01                                                          Line Chart                                                           Explore fare changes over pickup time

02                                                          Bar Chart                                                            Compare fare totals across pickup boroughs

03                                                          Pie Chart                                                            View trips by payment method

04                                                          Histogram                                                            Examine the distribution of trip distances

05                                                          Box Plot                                                             Explore tip distribution by pickup borough


B. Seaborn

No.                                                        * Visualization                                                       * Purpose

06                                                           Count Plot                                                           View the number of trips by pickup borough

07                                                           Scatter Plot                                                         Explore the relationship between distance and fare

08                                                           Heatmap                                                              Examine correlations between numerical variables

09                                                           Pair Plot                                                            Explore relationships between selected numerical variables

10                                                           Violin Plot                                                          Compare fare distributions by payment method


📊 Areas Explored

Through these visualizations, I explored:

* Fare changes over pickup timestamps.
* Fare totals across different pickup boroughs.
* Trips recorded under different payment methods.
* Distribution of taxi trip distances.
* Tip distribution across pickup boroughs.
* Relationship between trip distance and fare.
* Correlations between numerical variables.
* Fare distribution across payment methods.

🎯 Key Learning Outcomes

While completing this project, I practised:

* Exploring datasets using Pandas.
* Checking and handling missing values.
* Working with datetime columns.
* Using median and mode for missing-value treatment.
* Creating different types of charts using Matplotlib and Seaborn.
* Exploring data distributions and relationships through visualizations.
* Understanding how visualizations can help present data.


This project was completed as part of my learning journey in Data Analytics to practise data exploration, preprocessing and visualization using Python. 
