Video Game Sales Analysis
Project Overview
This project is based on analyzing video game sales data using Python. The main purpose is to understand how video games perform across different platforms, genres, publishers, and regions. It helps identify best-selling games and understand sales trends in the gaming industry.
Problem Statement
The video game industry is growing rapidly, and sales vary across different platforms, genres, and regions. By analyzing sales data, we can understand market trends, identify popular games, and compare the performance of different publishers.
Objectives
- Identify the top-selling games globally and regionally.
- Understand sales distribution across different platforms and genres.
- Analyze video game sales trends over different years.
- Find the best-performing publishers.
- Compare sales across different regions.
Dataset Description
The dataset contains the following columns:
- Rank: Overall sales ranking.
- Name: Name of the video game.
- Platform: Platform on which the game was released.
- Year: Game release year.
- Genre: Category of the game.
- Publisher: Name of the game publisher.
- NA_Sales: Sales in North America.
- EU_Sales: Sales in Europe.
- JP_Sales: Sales in Japan.
- Other_Sales: Sales in other regions.
- Global_Sales: Total worldwide sales.
Data Preparation
- Loaded the dataset using Pandas.
- Checked missing values using df.isnull().sum().
- Handled missing values where required.
- Checked and converted data types.
- Prepared the dataset for analysis.
Exploratory Data Analysis (EDA)
- Generated descriptive statistics using df.describe().
- Used groupby() to calculate total and average sales.
- Analyzed sales across platforms, genres, and regions.
- Created visualizations using Matplotlib and Seaborn.
- Used histograms and box plots to understand data distributions.
Top Selling Games Analysis
- Identified the top-selling games based on global sales.
- Calculated total global sales across all years.
- Sorted games according to their sales performance.
Platform Performance Analysis
- Analyzed global sales across different platforms.
- Identified platforms with the highest sales.
- Compared platform-wise sales using bar charts.
- Studied platform performance over different years.
Genre Analysis
- Identified the most popular genres based on global sales.
- Compared genre performance across different platforms.
- Analyzed regional preferences for different game genres.
- Studied changes in genre preferences over time.
Publisher Performance Analysis
- Identified publishers with the highest global sales.
- Compared publisher performance across different genres.
- Analyzed publisher sales in different regions.
Regional Sales Analysis
- Compared sales across North America, Europe, Japan, and other regions.
- Identified regional gaming preferences.
- Analyzed regional sales contributions using visualizations.
Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
Conclusion
In this project, I analyzed video game sales data using Python. I explored different games, platforms, genres, publishers, and regional sales. I also used data cleaning, grouping, statistical analysis, and visualization techniques to understand sales patterns and market trends.
