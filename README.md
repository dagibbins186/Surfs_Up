# Overview
This project used SQLite, SQLAlchemy, and Flask. SQLite facilitated a quick prototype. SQLAlchemy supported the queries in SQLlite. Flask, a web framework, accessed Python code to share and visualize the analysis. The goal of this project was to test an idea for a surf and shake shop. To increase the odds of investor backing, this analysis explored weather patterns in Oahu. Analysis verified the viability of this location for the business.
# Results
Analysis examined Oahu's preciptation over the course of one year. On average, Oahu received .177 inches of rain. At maximum, 6 inches of rain fell on the island. Preciptitation should not deter sales of a surf and shake shop.

9 stations exist on Oahu. Analysis evaluated the most active station. This location's temperature averaged 72 degrees. 
\
\
!["Histogram_Surfs_Up_Temp_Analysis.PNG"](https://github.com/dagibbins186/Surfs_Up/blob/main/Surfs_Up/Histogram_Surfs_Up_Temp_Analysis.PNG)
Temperatures primarily fell beween 70 and 80 degrees over the past year. Warm weather should improve the odds of ice cream and water-activity sales.
\
In addition, the weather appeared temperate year-round. The average temperature was 71 degrees in December and 74 degrees in June. Consistently beautiful days should encourage customers to frequent the surf and shake shop.
# Summary
In conclusion, SQLite stored the weather data, and supported testing and easy prototyping. The create engine feature of SQLAlchemy set up the ability to query the SQLite database. Automap Base created a base class for an automap schema in SQLAlchemy. This foundation permitted the code to function properly. Flask displayed these results. For the investor who wanted to see the data without the code, Flask made it possible to summarize the key ideas of the code in an easy-to-interpret way.
