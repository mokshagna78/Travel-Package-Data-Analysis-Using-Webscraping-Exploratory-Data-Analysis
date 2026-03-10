Travel Package Data Analysis (Web Scraping + EDA)


Project Overview :

This project focuses on collecting and analyzing travel package data from a travel website using Web Scraping and Exploratory Data Analysis (EDA) techniques.

The main objective is to understand pricing patterns, discount strategies, trip durations, and customer savings across different travel packages. 
Travelling analysis ppt updated


By analyzing the dataset, the project extracts meaningful insights that can help travel companies optimize pricing strategies and help customers find cost-effective travel packages.

Dataset Information:
The dataset contains 1000 rows and 9 columns representing travel package details. 

1. Web Scraping
Travel package data was collected from Travel Triangle website using Python. 
Travelling analysis ppt updated


 *Steps performed:

1. Sent HTTP requests to multiple web pages
2. Parsed HTML using BeautifulSoup
3. Extracted package details such as price, location, ratings, and duration

2. Data Cleaning

The raw scraped data required preprocessing to make it analysis-ready.

  *Cleaning steps:

Removed currency symbols (₹) and commas

Converted price columns to numeric format

Extracted numeric values using Regex

Separated trip duration into Days and Nights

Handled missing values and removed unnecessary columns

3. Feature Engineering
New variables were created to improve analysis.

Savings

Savings = Original Price − Discount Price

Savings Percentage

Savings Percentage = (Savings / Original Price) * 100

4. Exploratory Data Analysis (EDA)
EDA was performed to understand patterns in travel package pricing. 
Travelling analysis ppt updated


Univariate Analysis:
Analyzed individual variables using:

1. Histogram
2. Countplot
3. Donut chart

Bivariate Analysis:
Examined relationships between variables using:

1. Bar Plot
2. Scatter Plot

Multivariate Analysis:
Analyzed multiple variable relationships using:

1. Correlation Heatmap
2. Pair Plot

Business Questions Addressed :

1. Does trip duration affect travel package price?
2. Do higher discounts lead to higher savings?
3. What is the relationship between original price and discounted price?

These questions help identify travel pricing trends and discount strategies. 


Key Insights:

1. Travel package prices vary based on trip duration and discounts
2. Original price and discounted price have a strong correlation
3. Higher discount percentages result in greater customer savings
4. Trip duration plays a significant role in determining package price

Technologies Used:

1. Python
2. Requests
3. BeautifulSoup
4. Pandas
5. NumPy
6. Matplotlib
7. Seaborn

Skills Demonstrated:

1. Web Scraping
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Data Visualization
6. Business Insight Generation

Author : Mokshagna Jagarlamudi
