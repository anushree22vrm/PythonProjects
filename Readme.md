## PythonProjects
This repository is a consolidated collection of all the live projects and exercises completed during my Python learning journey. 
It includes everything from basic Python practice to hands-on implementation of advanced libraries like pandas, numpy, and more.
#### Project 1: Basic Python Programming Exercises
The first project focuses on strengthening core Python concepts through a series of structured practice questions. Topics covered include:
1. Variables and data types
2. Conditional statements (if, elif, else)
3. Looping structures (for, while)
4. Functions and argument handling
5. List and string operations (slicing, indexing, methods)
6. Dictionary manipulations and sets
7. File I/O basics
8. UDFs

[Base Python Programming Exercise](https://github.com/anushree22vrm/PythonProjects/blob/master/Base%20Python%20Programming%20Exercise.ipynb)

#### Project 2: Retail Sales Data Analysis
This project analyzes transactional and customer data from a retail business to generate insights into sales performance, customer segmentation, and product category trends. The project showcases the complete data analysis pipeline using Python (pandas, NumPy, Matplotlib).
##### Data Used:
1. Customer.csv: Customer demographic and registration details<br>
2. prod_cat_info.csv: Product category and subcategory mapping<br>
3. Transactions.csv: Sales transaction history<br>
##### Data Preparation & Cleaning:
1. Merged transactional, product, and customer datasets
2. Removed duplicates and irrelevant records
3. Handled missing values and corrected column names
4. Converted data types (e.g., date columns) for time-based analysis
##### Key Analyses Performed:
1. Identified top product subcategories and high-revenue segments
2. Analyzed sales trends over time (monthly/yearly)
3. Segmented customers by gender, city tier, and marital status
4. Examined revenue contributions by product category and state
##### Tools & Libraries:
1. pandas, numpy for data transformation
2. matplotlib, seaborn for visual exploration
3. Merge operations for relational data handling

[RetailSalesDataAnalysis](https://github.com/anushree22vrm/PythonProjects/blob/master/Retail_Project.ipynb)

#### Project 3: Credit Card Data Analysis
This project analyzes customer acquisition, repayment, and spend data for a credit card company to uncover customer behavior, repayment patterns, and revenue insights. The analysis showcases how credit card businesses can better manage risk and customer engagement using data.

##### Datasets Used:
Customer Acqusition.csv: Customer demographics, credit limits, and card types<br>
Repayment.csv: Monthly repayment behavior by customer<br>
Spend.csv: Customer spend behavior across months and categories<br>
##### Data Preparation:
1. Cleaned and merged multiple datasets using customer_id
2. Handled missing values and corrected data types
3. Filtered invalid or negative records from repayment/spending data
##### Key Analyses Performed:
1. Total and average monthly spend and repayment
2. Identified high-value customers (top spenders)
3. Segmented customers by card type, category, and spending patterns
4. Calculated monthly profit for bank
##### Tools & Libraries:
1. pandas, numpy for data analysis
2. matplotlib, seaborn for visualization
3. GroupBy and pivot tables for monthly/annual breakdowns

[CreditCardDataAnalysis](https://github.com/anushree22vrm/PythonProjects/blob/master/Credit_CardProject.ipynb)

#### Project 4: Insurance Claims Data Analysis
This project analyzes insurance claim records and customer demographic data to uncover claim trends, fraud indicators, and customer behavior insights. It demonstrates data integration, cleaning, and analytical exploration using Python.

##### Datasets Used:
claims.csv: Policy claim records with details like claim amount, date, and cause<br>
cust_demographics.csv: Demographic details of customers (age, income, gender, marital status, etc.)<br>
##### Data Preparation:
1. Merged claim and customer datasets using customer_id
2. Cleaned null values and renamed columns for clarity
3. Transformed and engineered new features like claim age, age group, and claim frequency
##### Key Analyses Performed:
1. Relationship between number of claims and total claimed amount
2. Distribution of claim amount by incident cause, gender, and customer age group
3. Claims analysis by state, policy type, and claim timing
4. Statistical tests (e.g., t-tests, correlation) to validate relationships
##### Tools & Libraries:
1. pandas, numpy for data wrangling
2. matplotlib, seaborn for plotting trends
3. scipy.stats for statistical analysis

[InsuranceClaimsDataAnalysis](https://github.com/anushree22vrm/PythonProjects/blob/master/Insurance_ClaimsProject.ipynb)

#### Project 5: Basic Data Manipulation and Visualization
This Jupyter notebook is a beginner-to-intermediate level project focused on exploring, cleaning, and analyzing structured data using the pandas library. It includes hands-on coding practice for fundamental operations that are widely used in data analysis, reporting, and business decision-making.

##### Key Topics Covered

##### 1. Data Cleaning
* Handling missing values and zeros<br>
* Changing data types<br>
* Removing or renaming columns<br>

##### 2. Data Transformation
* Creating new columns using apply() and map()
* Aggregating using groupby() and custom functions
* Filtering and slicing data

##### Data Exploration & Visualization
* Using summary statistics to understand trends
* Sorting and ranking values
* Plotting bar charts, pie charts, and line plots with pandas & Matplotlib

##### Working with Multiple DataFrames
* Merging and joining datasets
* Concatenation and appending data

#### Project 6: Python Visualization on Sales Data
This notebook explores data visualization techniques using Python libraries like Matplotlib and Seaborn, applied to a sales dataset from the pharmaceutical industry. It compares sales across years, regions, and market tiers to reveal business insights through compelling visual plots.

##### Key Analyses Covered:<br>
1. Bar Charts comparing sales by region (2015 vs 2016)<br>
2. Pie Charts showing sales contribution by region<br>
3. Stacked Bar Charts for multi-variable comparisons<br>
4. Visualizations segmented by Tier, Product, and Month<br>
5. Includes data cleaning and filtering steps for visual accuracy<br>

##### Libraries Used
1. Pandas
2. Matplotlib
3. Seaborn
4. Numpy

#### Project 7: Basic Statistics- Hypothesis Testing
This project focuses on applying hypothesis testing techniques to solve various business problems using real-world datasets. The goal is to explore statistical methods to make data-driven decisions and validate assumptions through different tests.

##### Key Analysis Covered:<br>
1. Independent T Test
2. Correlation Test
3. Anova Test
4. Hypothesis Formulation

##### Libraries Used
1. Pandas 
2. NumPy 
3. Matplotlib/Seaborn 
4. SciPy/Statsmodels 
