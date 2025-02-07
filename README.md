# **Project Title: Analysis of Adolescent Alcohol Use in Oklahoma**

## **Description:**
This project focuses on analyzing patterns of adolescent alcohol use in Oklahoma, specifically targeting respondents aged 18-24. The primary objective is to identify which areas in the state have the highest and lowest percentages of alcohol abuse among adolescents. The dataset used for this analysis comes from the **Behavioral Risk Factor Surveillance System (BRFSS)** for Oklahoma, which includes key variables such as geographic information (city, county, zip code), demographic breakouts (age, gender, income), and quantitative data on alcohol use.

The project involves creating a **star schema** in MySQL to organize and analyze the data efficiently. SQL queries are used to calculate the percentage of adolescent respondents who reported alcohol abuse, broken down by city and county. The results provide insights into the prevalence of alcohol consumption among adolescents in different regions of Oklahoma.

---

## **Key Features:**
- **Data Analysis**: Analysis of adolescent alcohol use in Oklahoma using BRFSS data.
- **Star Schema Design**: Creation of a star schema with fact and dimension tables for efficient querying.
- **SQL Queries**: Use of SQL to calculate alcohol abuse percentages by city and county.
- **Geographic Insights**: Identification of regions with the highest and lowest levels of adolescent alcohol abuse.
- **Data Import and Cleaning**: Importing and cleaning data from multiple CSV files into MySQL.

---

## **Requirements:**
- **MySQL**: For database management and querying.
- **MySQL Workbench**: For creating the database, running SQL queries, and performing calculations.
- **CSV Files**: The dataset is provided in CSV format, including:
  - BRFSS data
  - Demographic data
  - Demographics data in Oklahoma
- **ERDPlus Tool**: For creating the Entity-Relationship Diagram (ERD) and designing the star schema.

---

## **Files in the Repository:**
1. **BRFSS Data**: Contains the raw data from the Behavioral Risk Factor Surveillance System (BRFSS) for Oklahoma.
2. **Demographic Data**: Contains demographic information such as age, gender, and income.
3. **Demographics Data in Oklahoma**: Contains geographic information (city, county, zip code) for Oklahoma.
4. **DataWarehouse.docx**: Documentation of the project, including the introduction, research, methods, and conclusion.
5. **DataWarehouse.sql**: SQL scripts used for creating the database, importing data, and running queries.

---

## **Results:**
- **City Analysis**: Oklahoma City has a total sample size of **4,366**, with **2,446** respondents reporting alcohol abuse, resulting in a percentage of **56.02%**.
- **County Analysis**: 
  - **Oklahoma County**: Sample size of **4,078**, with **2,200** respondents reporting alcohol abuse, resulting in a percentage of **53.95%**.
  - **Cleveland County**: Sample size of **288**, with **246** respondents reporting alcohol abuse, resulting in a percentage of **85.42%**.
- **Key Findings**: Cleveland County has the highest percentage of adolescent alcohol abuse (**85.42%**), while Oklahoma County has the lowest (**53.95%**).

---

## **Conclusion:**
The project successfully analyzed adolescent alcohol use in Oklahoma, identifying regions with the highest and lowest percentages of alcohol abuse among respondents aged 18-24. The use of MySQL and SQL queries allowed for efficient data manipulation and analysis, while the star schema design streamlined the querying process. However, the dataset was limited to Oklahoma City for the 18-24 age group, which restricted the ability to compare data across multiple cities and counties.

---

## **Contributors:**
- **Akhila Singaraju**  
