# Python-Data-Cleaning-FIFA21

## FIFA21 Dataset Cleaning

Introduction
This repository hosts the code and documentation for the data cleaning process of the FIFA21 dataset. The main objective of this project is to clean and enhance the dataset, providing improved information about players featured in the popular FIFA21 video game.

Dataset Source and Overview
The FIFA21 dataset utilized in this project was acquired from a data cleaning challenge on Twitter, in which I actively participated. The dataset encompasses player attributes, statistics, and other pertinent information.

The original FIFA21 dataset consists of over 18,000 records of player data. Each record represents a unique player and includes various attributes such as player name, age, nationality, club, overall rating, and more.

Issues Found in the Data
During the initial exploration and analysis of the FIFA21 dataset, several issues were identified, including:

Missing Values:

The 'Hits' and 'Loan Date End' columns had missing values, requiring careful handling and computation.
Inconsistent Formatting:

Inconsistent formatting was observed across different columns, making it necessary to standardize the data for consistency. The 'Heights' and 'Weights' columns each had values stored in different units.
Tools Used
For the data cleaning project, the following tools and libraries were employed:

Python: Used for data cleaning tasks.
Pandas: Instrumental in data manipulation, cleaning, and handling missing values.
NumPy: Utilized for mathematical operations and array handling during the cleaning process.
Jupyter Notebooks: Provided an interactive environment for code development, exploration, and documentation.
Data Cleaning Process
The data cleaning process involved the following steps:

Data Understanding:

Thorough examination of the dataset to understand its structure, columns, and meanings. A data dictionary was created with the help of online sources to enhance understanding.
Data Exploration:

Exploratory Data Analysis (EDA) was performed to gain insights into the data, identify patterns, and uncover anomalies.
Handling Missing Values:

Missing values in the 'Hits' and 'Loan Date End' columns were carefully addressed. The 'Hits' column, representing the number of times a player had been searched in the FIFA database, had blank records for players who were never searched. The 'Loan Date End' column, indicating when the contracts for players on loan would end, had blank records for players who were free or not on loan.
Standardizing Formatting:

Inconsistent formatting issues, such as values in the 'Heights' and 'Weights' columns stored with different units, were resolved using transformations, lambda functions, and data normalization techniques.
Validation and Quality Checks:

The cleaned dataset underwent rigorous validation to ensure data quality, accuracy, and integrity.
Feel free to explore the code and documentation for a detailed understanding of the data cleaning process. If you have any questions or suggestions, please don't hesitate to reach out.
