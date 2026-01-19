Exploratory Data Analysis (EDA) – Media Content Dataset
Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a media content dataset containing information about movies, TV series, and mini-series. The goal of this analysis is to understand data structure, identify patterns and relationships, detect outliers, and extract meaningful insights that can support future predictive modeling or business decisions.

EDA plays a critical role in the data analysis lifecycle by ensuring data quality and improving model reliability.

Dataset Description

The dataset includes the following attributes:

title – Name of the content

year – Year of release

kind – Type of content (Movie, TV Series, Mini Series, etc.)

genre – Genre category

rating – Average user rating

vote – Number of user votes

country – Country of production

language – Primary language(s)

cast – Main actors involved

director – Director(s)

composer writer – Composer and/or writer details

runtime – Duration in minutes

Tools and Technologies Used

Python

Google Colab

Pandas for data manipulation

NumPy for numerical operations

Matplotlib and Seaborn for data visualization

Objectives

Understand the structure and quality of the dataset

Perform data cleaning and preprocessing

Analyze numerical and categorical features

Identify outliers and anomalies

Examine correlations between key variables

Summarize insights for decision-making and modeling

Data Cleaning and Preparation

The following preprocessing steps were performed:

Handled missing values in categorical columns by replacing them with meaningful placeholders

Converted numerical columns to appropriate data types

Ensured consistency in column formatting

Removed invalid or unusable values for analysis

Exploratory Data Analysis Performed
Numerical Analysis

Distribution analysis of release year and runtime using histograms

Outlier detection for rating and runtime using box plots

Categorical Analysis

Content type distribution based on kind

Genre frequency analysis

Country-wise content distribution

Correlation Analysis

Correlation heatmap to identify relationships between:

Year

Rating

Vote count

Runtime

Key Insights

Movies constitute the majority of content compared to TV and mini-series

Most content was released after the early 1990s

Ratings are largely concentrated within a mid-range band

Runtime contains notable outliers indicating very short and very long content

Vote count and rating show a moderate positive correlation

Genre and country are influential categorical features

Important Features Identified

Based on EDA, the following features are significant for further analysis or predictive modeling:

year

kind

genre

rating

vote

runtime

country

Conclusion

This EDA process provided a comprehensive understanding of the dataset’s characteristics and quality. The insights derived from this analysis can be leveraged for downstream tasks such as feature selection, recommendation systems, or predictive modeling.
