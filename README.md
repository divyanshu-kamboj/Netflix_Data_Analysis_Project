# Netflix_Data_Analysis_Project
DATA ANALYSIS PREPROCESSING AND VISUALIZATIION

🎬 Netflix Movies Data Analysis Project
📖 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Netflix Movies dataset containing information about movie titles, ratings, popularity, genres, release dates, and user votes.

The objective of this project is to clean, transform, analyze, and visualize the data to uncover meaningful insights and trends that can help understand audience preferences and movie performance.

🎯 Project Objectives

The main goals of this project are:

✅ Data Cleaning
Identify and handle missing values.
Remove duplicate records.
Convert data into appropriate formats.
✅ Data Preprocessing
Transform date columns into usable formats.
Categorize numerical variables for better analysis.
Remove irrelevant features.
✅ Exploratory Data Analysis (EDA)
Analyze movie popularity.
Study voting patterns and ratings.
Explore genre distributions.
Identify outliers and unusual observations.
✅ Data Visualization
Create meaningful charts and graphs.
Present insights in an easy-to-understand format.
📊 Dataset Information

The dataset contains information about movies available on Netflix.

Dataset Summary
Attribute	Value
Total Rows	9,827
Total Columns	9
Missing Values	0
Duplicate Values	0
Features Used
Column Name	Description
Release_Date	Movie release date
Title	Movie title
Popularity	Popularity score
Vote_Count	Total number of votes
Vote_Average	Average rating
Genre	Movie category
Overview	Movie description
Original_Language	Original movie language
Poster_Url	Movie poster URL
🛠️ Technologies Used

The project was developed using the following tools and technologies:

Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Development Environment
Google Colab
Version Control
Git
GitHub
🔍 Data Cleaning Process

Data cleaning is one of the most important stages of any data analysis project.

The following operations were performed:

1. Missing Value Analysis

The dataset was checked for null values using Pandas functions.

Result: No missing values were found.

2. Duplicate Record Detection

Duplicate rows were identified and removed.

Result: No duplicate records were present.

3. Feature Removal

The following columns were removed because they were not useful for statistical analysis:

Overview
Original_Language
Poster_Url

Removing unnecessary columns improves model efficiency and reduces noise.

4. Date Transformation

The Release_Date column was converted into datetime format.

Benefits:

Easier year extraction
Time-based analysis
Better visualization
⚙️ Feature Engineering

Feature engineering was performed to improve data interpretation.

Vote Average Categorization

Movie ratings were grouped into four categories:

Rating Group	Description
Not Popular	Lowest ratings
Below Average	Below average ratings
Average	Moderate ratings
Popular	Highest ratings

This transformation makes analysis easier and more meaningful.

📈 Exploratory Data Analysis

Several analyses were performed to understand the dataset.

Popularity Analysis

Popularity scores were analyzed to understand how movies are distributed across popularity levels.

Findings
Most movies have moderate popularity scores.
A few movies have extremely high popularity.
Significant outliers exist in the popularity column.
Vote Average Analysis

Movie ratings were analyzed to identify audience preferences.

Findings
Most movies fall into average rating ranges.
Highly rated movies represent a smaller portion of the dataset.
Rating distribution is slightly skewed.
Genre Analysis

Genre information was cleaned and analyzed.

Findings
Certain genres dominate the Netflix catalog.
Some genres appear significantly more often than others.
Multi-genre movies contribute to genre diversity.
Release Year Analysis

Movie release trends were analyzed over time.

Findings
Netflix contains movies from multiple decades.
Recent years show increased movie production.
Release patterns reveal growth in content availability.
📊 Data Visualizations

The following visualizations were created:

📌 Distribution Plots

Used to understand the spread of popularity and ratings.

📌 Count Plots

Used to analyze genre frequencies.

📌 Box Plots

Used to identify outliers.

📌 Correlation Analysis

Used to understand relationships between numerical variables.

💡 Key Insights

After completing the analysis, the following insights were discovered:

Insight 1

The dataset contains clean and reliable data with no missing values.

Insight 2

Popularity scores contain several extreme outliers.

Insight 3

Most movies receive average ratings.

Insight 4

A small number of genres dominate the catalog.

Insight 5

Recent years have experienced significant growth in movie releases.
