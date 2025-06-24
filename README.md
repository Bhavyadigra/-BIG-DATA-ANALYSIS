COMPANY : CODTECH IT SOLUTIONS 

NAME: BHAVYA DIGRA 

INTERN ID: CITS0D698

DOMAIN:DATA ANALYST 

DURATION: 4 WEEKS 

MENTOR:NEELA SANTOSH

# Task 1: Big Data Analysis using PySpark

## Introduction

This project is part of my internship with **CodTech** under the Data Analysis domain. In **Task 1**, I was required to perform big data analysis on a large dataset using a scalable tool such as **PySpark**. The main objective was to handle real-world data that is too large or complex for traditional tools like Pandas or Excel, and to extract meaningful insights from it.

For this task, I chose to analyze the **latest global COVID-19 dataset** provided by *Our World in Data*. It contains detailed statistics about COVID-19 cases, deaths, population, and vaccinations for countries around the world.

##  Tools and Technologies Used

- **PySpark** – for scalable, distributed data processing
- **Google Colab** – for writing and running the notebook in the cloud
- **GitHub** – for version control and submission
- **Python** – for all coding and calculations

##  What I Did (Project Workflow)

1. **Setup PySpark on Google Colab**  
   I used the official PySpark package from PyPI and initialized a SparkSession to get started.

2. **Data Loading**  
   I downloaded the COVID-19 dataset from a public URL using `wget`, and loaded it into a PySpark DataFrame.

3. **Data Exploration**  
   I viewed the schema and sample rows to understand the structure of the dataset. I also identified key columns like `location`, `total_cases`, `total_deaths`, `population`, and `people_vaccinated`.

4. **Basic Analysis**  
   I performed simple queries like sorting countries by total cases and calculating death rates using PySpark operations.

5. **Deeper Insights**  
   To make the project more impactful, I went deeper into the data with the following analyses:
   - **Vaccination Rate**: I created a new column to calculate how many people were vaccinated as a percentage of the population, and found the top vaccinated countries.
   - **Cases Per Million**: I normalized total COVID-19 cases by population to find countries with the highest infection density.
   - **Vaccination vs Death Rate**: I compared the vaccination rate and death rate to explore whether more vaccinated countries had lower death rates.

##  Key Findings

- Countries like **San Marino**, **Andorra**, and **Gibraltar** showed extremely high case counts per million people due to their small populations.
- Highly vaccinated countries like **Portugal** and **UAE** had better control over death rates, suggesting a positive correlation between vaccination and lower mortality.
- PySpark made it very efficient to process and analyze thousands of records with just a few lines of code.

##  What I Learned

- I learned how to use PySpark for big data analysis — from loading and exploring data to performing complex transformations.
- I understood the importance of scalability and how tools like PySpark can handle data that would otherwise crash a local system.
- I also gained experience in cloud-based development using Google Colab and GitHub for clean submissions.

##  Files Included

- `Task1_COVID_PySpark.ipynb`: My complete analysis notebook with all code, outputs, and insights
- `covid.csv`: The dataset used (downloaded inside the notebook)
- `README.md`: This file
 

##  Conclusion

This project helped me take my data analysis skills to the next level by introducing me to big data tools. It was a great learning experience, and I'm proud to have completed this as part of my internship with CodTech.


