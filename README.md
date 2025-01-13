# Personal Portfolio
Personal Porfolio with data related projects

# Technologies used
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-you?style=for-the-badge&logo=azure&logoColor=white&label=Microsoft&color=%23015AD8)
![Data Bricks](https://img.shields.io/badge/Data_Bricks-you?style=for-the-badge&logo=databricks&logoColor=%23FFD43B&color=white)
![Python](https://img.shields.io/badge/Python-you_like?style=for-the-badge&logo=python&logoColor=%23FFD43B&color=%23306998)
![Visual Studio](https://img.shields.io/badge/VSCode-9354CD?style=for-the-badge&logo=azure&logoColor=white)
![Data Factory](https://img.shields.io/badge/Data_Factory-%20?style=for-the-badge&logo=%23222222&label=Azure&labelColor=%2359B4D9&color=%2376BF49)
![EXCEL](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Tableau](https://img.shields.io/badge/tableau-61859C?style=for-the-badge&logo=tableau&logoColor=EB912C)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Jupyter_Lab](https://img.shields.io/badge/Jupyter-Notebooks-%20?style=for-the-badge&logoColor=%23F37726&labelColor=%23F37726&color=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-356df1?style=for-the-badge)
![My SQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)


Welcome to my personal portfolio repository! Here you will find a collection of projects and dashboards that demonstrate my skills and expertise in data engineering, data exploration, data visualization, business intelligence and reporting analytics using different cutting edge technologies.


## About Me
I am a passionate data enthusiast with a strong background in software engineering. I have extensive experience in transforming raw data into meaningful insights, creating interactive dashboards and helping businesses make data-driven decisions. This portfolio showcases my proficiency in various technologies and highlights my ability to effectively communicate complex data visually.


## [Project 1: Premier League Statistics: Gamble your favorite team](https://github.com/IvanRamosDataTech/Premier-League)

### Summary

A robust database of English Premier League matches that contains full match information from session 1992-1993 up to date. It also contains bet odds from the most popular bet websites which is a plus if anyone is interested in performing bet analysis. Project contains a friendly Power BI dashboard with current session positions and interactive controls to navigate to historic general results as well as one vs one previous results.
New match data gets refreshed automatically every few days to keep up to date database and upload public dataset in Kaggle.

### Preview & live demo

[comment]: #!([sales](https://github.com/tushar2704/tushar2704-GIFs/blob/main/salesd1.gif))

[Premier League Dashboard](https://app.powerbi.com/groups/me/reports/ab4d3a82-dcb1-4dfe-827e-ef6a51f40402/ReportSectionb0961a8901a5cf17d54b?experience=power-bi)


### Tech specifications
Data Engineering - A docker image is setup to hold a Postgresql database. A legacy version of ETL was initially performed using Power Query to extract and clean up individual csv files downloaded from API source. Now, project uses Python scripts with pandas, numpy and psycopg2 to perform ETL.
Project gets refresh automatically thanks to a job scheduled using orchestration software Airflow and public dataset is published using Kaggle's official CLI tools.

Data Analysis - Contains common SQL scripts for validation of integrity and maintance of database. Also some DAX scripts for exploratory analysis and validation of data. Contains a Power BI interactive report with beautiful visuals, season statistics and filters to navigate in historical data.

## [Project 2: Analyzing A/B test results: What page design users preffer?](pending link to Repository)

### Summary
This project analyses an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Preview & live Demo

(TODO Insert an gif)
(TODO Insert a public jupyter-notebook web url)

### Tech specifications

Data Analysis - All investigation is implemented in a jupyter notebook. Project uses pandas, numpy and matplotlib for exploratory data analysis. A/B testing analysis is performed with the help of statsmodels Python api. Project includes an alternative analysis by performing regression and p-value techiniques to wrap up conclusions.

## [Project 3: Insurance Complaints report: leverage the power of KPIs](https://github.com/IvanRamosDataTech/Insurance-Complaints)

### Summary

### Preview & live demo

### Tech specifications

## [Project 4: INEGI house purchasing power in Mexico: A case of study](https://github.com/IvanRamosDataTech/ENSAFI2023)

### Summary

### Preview & live demo

### Tech specifications

## [Project 5: Hotel Revenue: insights of new business opportunities](https://github.com/IvanRamosDataTech/HotelRevenueManagement)

### Summary

### Preview & live demo

### Tech specifications

## [Project 6: Market Stocks: How did your portfolio of investments open today?](link to repository)

### Summary

### Preview & live demo

### Tech specifications

## Contact Information

If you have any questions about implementation details, feedback or collaboration opportunities, please feel free to reach out to me. You can contact me via email at [ivanramos.datatech@gmail.com](mailto:ivanramos.datatech@gmail.com)

 <b>[LinkedIn](https://www.linkedin.com/in/ivan-rcortes/)</b>  
 <b>[Novypro](https://www.novypro.com/profile_projects/ivan-ramos-data-tech)</b>  
 <b> ![Medium](https://img.shields.io/badge/%20-%20?style=social&logo=medium)[  @ivanramos.datatech](https://medium.com/@ivanramos.datatech)</b>  
 <b>![Kaggle Badge](https://img.shields.io/badge/%20-22aeff?style=social&logo=kaggle)[  IvanRamosDataTech](https://www.kaggle.com/ajaxianazarenka)</b>  

Thank you for visiting my Data Tech Portfolio! I hope you find my projects informative and insightful.
  
## License
All my projects are public. Feel free to fork them or make suggestions in case you find them useful for your own purposes.


 
 

