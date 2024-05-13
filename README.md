# Rockbuster_Project
Data analytics project based on sample database of Rockbuster Stealth using SQL queries and aiming to launching online video rental service.  
# Objective
Rockbuster Stealth is a movie rental company that used to have stores around the world. Facing stiff competition from streaming services, the company’s management team is planning to use its existing movie licenses to launch an online video rental service. The objective of the analysis is to assist with launching the new business strategy. 
# Data
Open source tutorial data from PostgreSQL.
# Tools
PostgreSQL,
DbVisualizer,
Tableau,
Excel,
Power Point
# Insights & Recommendations

[Rockbuster Presentation] https://github.com/stepanova531/Rockbuster_Project/blob/ab5c0fc478eb8a4705a8b54eef9d14eafe0ea630/Presentation_Rockbuster.pdf

•	Our clients reside all over the world except Australia. The top-5 countries India, Chinese and Japan USA, Mexico. 
### Start streaming online by piloting in the top-5 countries. 
•	In the top-10 countries, 89% of our customers are based in non-English speaking countries. 
### Consider offering the movies with the audio in their native languages focusing on the most popular film categories in their geographical regions.
•	The most popular genres in the top-10 countries are Sport and Animation. 
There is no prevailing rating. All five rating categories are relatively equal in terms of revenue generated. Although, four of five ratings are assigned to the movies for the audiences 13 years and older.
### Develop a system for ranking films in the library by genre and film rating. Make decisions about purchasing new licenses based on the rating system, target audiences and their movie preferences.
•	Customers rented most frequently the movies at the lowest rate of $0.99. These transactions account for 35% of all sales. However, these sales have generated 20% of revenue. The sales of movies at the highest rental rate generated almost half of the revenue, e.g. 49%. The movies on the top-10 list are being rented at the highest rate: $4.99. 
### Invent a pricing strategy based on the films’ popularity and move films to a lower rental rate category once the number of sales shows a decreasing trend.
### Review the maturity of license on a regular basis and discontinue those which have not been rented in the last 12 months (43 items on the current list) or the movies that have been purchased less than 10 times in the last 12 months (166 films) 
# Key takeaways
•	Common Table Expressions (CTE) sometimes can be used for the same purposes as subqueries. However, CTE has a more readable structure, and can be referenced multiple times from a calling query. It also allows saving time for running queries, e.g. our comparison shows 30% less time cost for running the average payment and top customers list. 

•	When data is stored in multiple tables, we may need to create several joint tables, and this makes our statements long and hard readable. We can simplify the queries if we use WHERE / IN. However, this option is not advisable if we are using constantly changing data.

•	Comparing Excel and SQL for data analysis, the latter is a better option for a relational database with multiple tables. Whatever tool we use, we must start our analysis by verifying the data consistency, data integrity and uniqueness. 
