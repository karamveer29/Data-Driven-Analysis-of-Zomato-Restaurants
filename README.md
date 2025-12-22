# Data-Driven-Analysis-of-Zomato-Restaurants
🍽️ Zomato Restaurant Insights: An Exploratory Data Analysis
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Zomato restaurant data to uncover meaningful insights about restaurant types, ratings, customer voting behavior, online ordering, table booking, and pricing trends.
The analysis helps understand customer preferences and business patterns using data-driven techniques.

🎯 Objectives

Analyze restaurant ratings and distribution

Study customer voting patterns across restaurant types

Understand cost trends for two people

Compare ratings based on online ordering and table booking

Perform correlation analysis on numerical features

🗂️ Dataset

Source: Zomato restaurant dataset (CSV format)

Key Columns:

rate

votes

listed_in(type)

online_order

book_table

approx_cost(for two people)

🛠️ Technologies & Libraries Used

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualization

Jupyter Notebook

🔄 Data Cleaning Steps

Converted rating values (4.1/5) into numeric format

Handled missing and invalid values (NEW, -)

Cleaned and converted cost column to numeric

Selected numeric columns for correlation analysis

📊 Exploratory Data Analysis Performed

Restaurant type distribution

Votes by restaurant type

Rating distribution

Cost analysis for two people

Online order vs rating comparison

Table booking vs rating comparison

Correlation heatmap for numerical features

📈 Key Insights

Delivery and dine-out restaurants dominate the dataset

Higher votes generally correlate with higher ratings

Restaurants offering online ordering tend to receive better ratings

Mid-range pricing restaurants are most common

Ratings show moderate correlation with votes

🧠 Business Value

Helps restaurant owners understand customer behavior

Identifies popular restaurant categories

Supports pricing and service strategy decisions

Useful for market analysis and business planning

▶️ How to Run the Project

1. Clone the repository:

git clone https://github.com/your-username/zomato-eda-project.git

2. Install dependencies:
   pip install pandas, numpy, matplotlib, seaborn

3. Open Jupyter Notebook:
   jupyter notebook

   📌 Project Structure
├── Zomato_data.csv
├── Zomato_EDA.ipynb
├── README.md

🚀 Future Enhancements

Apply machine learning models for rating prediction

Perform sentiment analysis on customer reviews

Add location-based analysis

Build an interactive dashboard

👤 Author

Karamveer Singh
Aspiring Data Scientist
📍 India



