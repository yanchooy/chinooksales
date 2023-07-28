# Introduction
SQLite Sales Analysis of Chinook music store with hypothetical business questions

# Project Goals
1) Analyze sales by genres in the USA, to make a recommendation for which 3 albums to select to sell at the store

2) Analyze sales by Employee Sales Performance

3) Analyze sales by country, to make a recommendation on which country to spend advertising dollars on

4) Comparing sales performance between album versus tracks

# Conclusion
1) Rock, Alternative & Punk and Metal are the top 3 genres favoured in USA, so new labels should be aligned with these genres.

2) Chinook's best salesperson brings in average of 38 dollars monthly worth of sales, about 5% more than the next best salespersons.

3) Total sales is the highest in USA, followed by Canada and Brazil.
   Czech Republic, Portugal and India have a higher per customer/order value though larger sample size is required to give us more confidence to invest campaigns in these countries.

5) Tracks only purchase make up the bulk of Chinook's sales. We recommend a preference-targeted mixtape strategy to boost sales of more track sales from various artists.

# SQL queries used
- Left and Inner Join multiple tables
- CTE tables for independent query before joining
- Date function like JULIANDAY()
- Aggregation like SUM, COUNT(DISTINCT) with GROUP BY and HAVING statements
- Case statements
- Subquery to introduce values from other tables
