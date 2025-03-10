# Data-Cleaning-and-Analysis: Titanic Data Cleaning and Analysis  

**Overview**  
This repository contains a Python script for preprocessing the Titanic dataset. The script loads raw data, cleans and structures it, and performs exploratory analysis to understand survival trends.  

**Features**  
**-Data Cleaning**  

.Column Removal: Irrelevant columns such as Name, Ticket, Fare, and Cabin are removed.  
.Missing Value Handling:The Age column is imputed with the mean age based on survival status.  
.The dataset is checked for null values, and any remaining missing values are handled.  

**-Data Type Conversion:**  

.The Sex column is converted into numerical values (Male = 1, Female = 2).  
.The Embarked column is transformed into numerical categories (S = 1, Q = 2, C = 3).  

**-Data Processing**  

.Handling Categorical Data: The Sex column is replaced with numerical values for easier analysis.  
.Handling Missing Data in Age: Missing age values are filled with the average age of survivors or non-survivors.  
.Encoding Embarked Data: The Embarked column is transformed into numerical values for consistency.  

**-Data Visualization**  

.Gender Distribution Pie Chart: A pie chart is created to visualize the distribution of males and females on board.  
.Survival Distribution by Gender: A pie chart is generated to show the survival distribution among males and females.  

**Outputs**  

.Cleaned Data: The raw dataset is transformed into a structured dataset with numerical categories.  
.Visual Insights: Pie charts help understand survival trends based on gender.  
.Further Exploration: The cleaned dataset can be saved for further analysis.  
