# Crime Data Analysis using MySQL and Python

##  🔍Project Overview:

This project involves the analysis of Crime data using MySQL Workbench and Python. The primary goal is to extract valuable insights and trends from the dataset, which can help in reducing the crime rate over the cities. The project includes tasks such as data quality checks, feature engineering, and giving various suggestions to concerned authorities.

## :page_facing_up:Data Description:

| Column       | Description                      | Data Type       |
|--------------|----------------------------------|-----------------|
| **DR_NO**    | Case identifier number.          | INT             |
| **Date_Rptd**| Reported date of incident.       | DATE            |
| **DATE_OCC** | Date incident occurred.          | DATE            |
| **AREA_NAME**| Name of police area.             | VARCHAR(30)     |
| **Crm_Cd**   | Crime code number.               | INT             |
| **Crm_Cd_Desc**| Description of crime code.     | VARCHAR(30)     |
| **Vict_Age** | Age of victim.                   | INT             |
| **Vict_Sex** | Sex of victim.                   | VARCHAR(30)     |
| **Premis_Desc**| Description of premises.       | VARCHAR(30)     |
| **Status**   | Current status of case.          | VARCHAR(30)     |
| **Location** | Incident location.               | VARCHAR(30)     |
| **LAT**      | Latitude of incident.            | DECIMAL(10, 2)  |
| **LON**      | Longitude of incident.           | DECIMAL(10, 2)  |



## 🔧Tools Used 

![image](https://github.com/sumitsingh44/Crime_Data_Analysis_with_MySQL_and_Python/assets/98682550/ab8da09f-e847-4ae9-afde-d91444c56b6b)

🟢MySQL Workbench: Utilized for writing and executing SQL queries.

🟢SQL: Used extensively for data manipulation, querying, and analysis.

![image](https://github.com/sumitsingh44/Crime_Data_Analysis_with_MySQL_and_Python/assets/98682550/8e386e35-c49e-48ae-a1e6-0ac809ae90eb)

🟢Python: Utilized for visualising graphs with the help of python libraries.

## 🛠️Steps Undertaken

:green_circle:**Database Setup and Import:** Create a MySQL database. Load the provided crime dataset into the MySQL database.

:green_circle:**Database Connection:** Use PyMySQL to establish a connection to the database in VS code. Verify the successful import of data in pycharm.

:green_circle:**Data Exploration:** Retrieve basic statistics on the dataset, such as the total number of records and unique values in specific columns. Identify the distinct crime codes and their descriptions.

:green_circle:**Temporal Analysis:** Analyze the temporal aspects of the data. Determine trends in crime occurrence over time.

:green_circle:**Spatial Analysis:** Utilize the geographical information (Latitude and Longitude) to perform spatial analysis. Visualize crime hotspots on a map.

:green_circle:**Victim Demographics:** Investigate the distribution of victim ages and genders. Identify common premises descriptions where crimes occur.

:green_circle:**Status Analysis:** Examine the status of reported crimes. Classify crimes based on their current status.

## :books:Learnings

:green_circle:**Database Management:** Gained hands-on experience in creating and managing a MySQL database. Learned how to import large datasets into a MySQL database and ensure data integrity.

:green_circle:**Python and MySQL Integration:** Developed skills in using the PyMySQL library to connect and interact with a MySQL database from a Python script. Successfully established database connections, executed SQL queries, and retrieved results for further analysis.

:green_circle:**Data Exploration and Cleaning:** Enhanced ability to perform exploratory data analysis (EDA) to understand the dataset's structure and basic statistics. Identified and handled missing values, duplicates, and outliers to clean and prepare the data for analysis.

:green_circle:**Data Visualization:** Leveraged Matplotlib and Seaborn libraries to create insightful visualizations, such as temporal trends, spatial hotspots, and demographic distributions. Improved skills in presenting data visually to uncover patterns and insights effectively.

:green_circle:**Analytical Thinking:** Developed a systematic approach to analyzing crime data, including temporal, spatial, and demographic analysis. Learned to formulate and answer specific research questions using data, such as identifying crime hotspots and analyzing victim demographics.

## :checkered_flag:Conclusion

This project provided hands-on experience in integrating MySQL with Python for comprehensive crime data analysis. Through database management, data exploration, and visualization, significant insights were gained into crime trends, hotspots, and victim demographics. The skills developed in this project are crucial for real-world data analysis and decision-making.
