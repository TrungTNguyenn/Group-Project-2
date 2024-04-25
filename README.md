# Team 9 MIST 4610 Group Project 2



## Team Members

[Ainslie Noble](https://github.com/ainsliehn)

[Austin Pasley](https://github.com/apasley)

[Justin Leeds](https://github.com/justinleeds)

[Trung Nguyen](https://github.com/TrungTNguyenn)

# Data Set Description
The Dataset that we decided to analyze is the Quarterly Census of Employement and Wages(QCEW) Program, which is the Federal-state cooperative program between the U.S. Department of Labor's Bureau of Labor Statistics(BLS) and the California EDD's Labor Market Information Division(LMID). The QCEW produces extensive organization of employement and wage information 
for workers covered by Califronia Unemployment Insurance(UI) laws and workers under the Unemployment Compensation for Federal Employees(UCFE) program. 
 
Our Dataset came from the Data.Gov. The dataset has 15 Columns and 914275 Rows. The different columns include Area Type, Area Name, Ownership, Industry Name, Time Period which are VARCHAR data types. Other columns names are Year, NAICS Level, NAICS Code, Establisments, Average Monthly Employment, 1st Month Emp, 2nd Month Emp, 3rd Month Emp, Total Wages(All workers), and Average Weekly Wages which are all INTEGER data types.
# Questions
Question 1 - What is the average week in California counties with over 1 million people?
This question is important for understanding the livelihoods of individuals residing in populous California counties. It sheds light on income disparities, affordability, and overall economic well-being. This question directly ties to the dataset containing information on weekly wages of workers, broken down by industry and county, particularly focusing on counties with over 1 million people.


Question 2 - How do the average weekly wages compare in common industries when comparing the lowest/highest wage counties from the previous question?
# Manipulations/ calculations performed
-The first manipulation required was changing the Aggregation on the "Average Weekly Wages" column from SUM to AVG. This was required because summing the data provided no real value when our goal was to see what a person's weekly wage in a county was expected to be.

-Another manipulation that was required was Filtering. This dataset contained tons of data, as it was collected wage information on 1258 industries in every Californian county. To make it more meaningful and focused, our group decided to focus on counties that had over 1 million people, which narrowed the dataset down to 10 Californian counties. This resulted in data that was reflecting California's big population hubs. We also had to narrow down industries, and decided to focus on common, but distinct, industries that were present throughout the United States. This approach allows us to capture a broad representation of jobs while still identifying clear patterns and trends within each industry. This enabled us to create a picture that reflects a broad spectrum of job roles and economic activities. By selecting industries with widespread presence across the country, we ensured that our analysis would be relevant beyond California.
-While minimal, the manipulations like changing the data type for Year to date and changing Year to discrete were also required.
# Analysis/Results

# Tableau Packaged Workbook
