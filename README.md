Zomato Data Analysis Using Python

Exploratory Data Analysis (EDA) on Zomato restaurant data to understand customer preferences, ratings, pricing and ordering behaviour.

Business Problem

A restaurant business wants to know what customers prefer so it can decide what type of restaurant to open and how to take orders. This project answers 6 questions using data and visualizations.

Dataset
File: Zomato data .csv
Rows: 148, Columns: 7
No missing values

Column	Description
name	Restaurant name
online_order	Accepts online orders (Yes/No)
book_table	Table booking available (Yes/No)
rate	Customer rating out of 5
votes	Number of votes
approx_cost(for two people)	Approximate cost for two
listed_in(type)	Restaurant type (Dining, Cafes, Buffet, etc)

Tools Used
* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Jupyter Notebook
  
Steps
1. Imported libraries and loaded the dataset
2. Cleaned the rate column (converted values like 4.1/5 to float 4.1)
3. Checked data types and null values
   
Answered 6 questions with visualizations
Questions and Insights
#	Question	Chart	Insight
1	What type of restaurants are most common?	Count Plot	Most restaurants are Dining type

2	Which type of restaurant gets the most votes?	Line Graph	Dining restaurants are preferred by the largest number of people

3	What ratings do most restaurants get?	Histogram	Most restaurants are rated between 3.5 and 4

4	What cost do couples prefer?	Bar Graph (Count Plot)	Most couples prefer restaurants costing about ₹300 for two

5	Do online orders get higher ratings than offline?	Box Plot	Online-order restaurants get higher ratings than offline ones

6	Which restaurant types get more online vs offline orders?	Heatmap	Dining gets mostly offline orders, Cafes get mostly online orders

Conclusion
* Dining is the most common and most voted restaurant type.
* Most restaurants are rated 3.5 to 4.
* Online ordering is linked with better ratings.
