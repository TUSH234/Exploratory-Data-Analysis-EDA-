Titanic Data Visualization & Analysis

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn.
The goal is to understand the distribution of data, identify patterns, and highlight key observations through different visualizations.

📊 Visualizations Created
* Histogram
* Boxplot 
* Scatterplot
* HeatMap

📊 Observations

1. Histogram – Passenger Age Distribution
Most passengers were between 20–40 years of age.

* Very few infants (<5 years) and elderly passengers (>65 years).

* Age distribution is slightly right-skewed (more young/middle-aged passengers).

2. Boxplot – Age by Passenger Class
* 1st Class passengers had higher median age (~38 years), with fewer young passengers.
* 3rd Class had many young passengers (median ~24 years) and more variation.

* Outliers present in all classes, indicating a few very old or very young passengers.

3. Scatterplot – Fare vs Age (Survival Status)
   
* Higher fares generally correspond to 1st Class passengers and had better survival rates.

* Survivors (Survived=1) cluster more in higher fare ranges.

* Age does not strongly determine survival, but children had slightly better chances.


4. Heatmap – Correlation Between Numerical Variables
   
* Pclass is strongly negatively correlated with Fare (-0.55), meaning higher class = higher fare.
* Survival is moderately correlated with Fare (0.26) and Pclass (-0.34).
* Age has very weak correlation with survival.


🛠 Technologies Used
Python (jupyter notebook in vs code)

Pandas – Data loading & cleaning

Matplotlib – Visualization(histogram)

Seaborn – Advanced statistical plotting 
(box plot, scatter plot, heatmap)


* SUMMARY   OF   FINDINGS

· Majority of Titanic passengers were young adults; children and elderly were fewer.
·   Passenger class influenced demographics — higher classes had older passengers.
·  Fare had a positive relationship with survival — wealthier passengers had better outcomes.
·  Age alone was not a strong predictor of survival, but children had slightly better chances.
·  Class and Fare show strong inverse relationship — an indicator of socioeconomic differences on board.

created by
Tushar Parashar


  
