Travel Package Data Analysis (Web Scraping + EDA)
Project Overview
This project focuses on collecting and analyzing travel package data from a travel website using Web Scraping and Exploratory Data Analysis (EDA) techniques.

The main objective is to understand pricing patterns, discount strategies, trip durations, and customer savings across different travel packages. 
Travelling analysis ppt updated


By analyzing the dataset, the project extracts meaningful insights that can help travel companies optimize pricing strategies and help customers find cost-effective travel packages.

Dataset Information
The dataset contains 1000 rows and 9 columns representing travel package details. 
Travelling analysis ppt updated


Columns Description
Column	Description
Location	Travel destination
Discount	Discount percentage
Discount Price	Price after discount
Original Price	Actual package price
Rating	Customer rating
Days	Trip duration in days
Nights	Trip duration in nights
Savings	Money saved on the package
Savings Percentage	Percentage savings
Project Workflow
1. Web Scraping
Travel package data was collected from Travel Triangle website using Python. 
Travelling analysis ppt updated


Steps performed:

Sent HTTP requests to multiple web pages

Parsed HTML using BeautifulSoup

Extracted package details such as price, location, ratings, and duration

2. Data Cleaning
The raw scraped data required preprocessing to make it analysis-ready.

Cleaning steps:

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

Histogram

Countplot

Donut chart

Bivariate Analysis:
Examined relationships between variables using:

Bar Plot

Scatter Plot

Multivariate Analysis:
Analyzed multiple variable relationships using:

Correlation Heatmap

Pair Plot

Business Questions Addressed :

Does trip duration affect travel package price?

Do higher discounts lead to higher savings?

What is the relationship between original price and discounted price?

These questions help identify travel pricing trends and discount strategies. 
Travelling analysis ppt updated


Key Insights:

Travel package prices vary based on trip duration and discounts

Original price and discounted price have a strong correlation

Higher discount percentages result in greater customer savings

Trip duration plays a significant role in determining package price

Technologies Used:

Python

Requests

BeautifulSoup

Pandas

NumPy

Matplotlib

Seaborn

Skills Demonstrated:

Web Scraping

Data Cleaning

Feature Engineering

Exploratory Data Analysis

Data Visualization

Business Insight Generation

Author : Mokshagna Jagarlamudi
