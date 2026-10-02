# Analyzing-International-Debt-Statistics_PostgreSQL
foundational PostgreSQL project - analyzing intl debt data provided by The World Bank
project uses international debt data collected from The World Bank on the amount of debt in USD owed by developing countries across several categories to answer the following questions using basic PostgreSQL: 
1. What is the number of distinct countries present in the database?
2. What country has the highest amount of debt?
3. What country has the lowest amount of repayments?

Table contents - table called: international_debt
column: country_name  definition: name of country   data type: varchar
column: country_code  definition: code representing the country  data type: varchar
column: indicator_name definition: description of the debt indicator data type: varchar
column: indicator_code definition: code representing the debt indicator data type: varchar
column: debt definition: value of the debt indicator for the given country (in current USD) data type: float
