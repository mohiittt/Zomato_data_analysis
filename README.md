# Zomato Data Analysis Project

This project performs data analysis on a Zomato restaurant dataset. The objective is to explore various attributes such as ratings, online ordering, table bookings, and cost to derive meaningful insights.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Dataset Description](#dataset-description)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)

## Introduction

The project aims to analyze restaurant data from Zomato. Through the analysis, the following aspects are examined:
- Popularity of online ordering and table booking
- Restaurant ratings and votes
- Approximate cost for two people
- Types of restaurants listed

The analysis is conducted using Python libraries and visualized with various graphs to understand trends in the dataset.

## Project Structure

📂 zomato-data-analysis
│
├── 📁 data                  # Dataset used for analysis
├── 📁 images                # Visualizations and graphs
├── zomato_data.ipynb    # Jupyter Notebook with the full analysis
└──  README.md                # Project documentation


## Technologies Used

- **Python**: For data manipulation and analysis.
- **Google Colab**: Used to run the analysis.
- **Pandas**: For data manipulation.
- **Matplotlib & Seaborn**: For visualizations.
- **NumPy**: For numerical operations.
- **Scikit-learn**: (Optional) For preprocessing and analysis.

## Dataset Description

The dataset used in this project consists of restaurant information from Zomato, with the following key columns:

- **name**: Name of the restaurant.
- **online_order**: Whether the restaurant supports online ordering (Yes/No).
- **book_table**: Whether the restaurant allows table booking (Yes/No).
- **rate**: Customer rating of the restaurant (in the form of "X.X/5").
- **votes**: Number of votes the restaurant has received.
- **approx_cost(for two people)**: Approximate cost for two people.
- **listed_in(type)**: Type of dining experience (e.g., Buffet, Dining).

## Data Cleaning

Before performing any analysis, the dataset was cleaned:
1. **Rate Column**: Ratings were initially stored as a string ("X.X/5"). We cleaned and converted this into a numeric format.
2. **Missing Values**: Handled missing or null values in the dataset.
3. **Duplicate Entries**: Checked and removed duplicates for cleaner analysis.

## Exploratory Data Analysis

EDA was performed to identify patterns and trends in the dataset:
- **Rating Distribution**: Visualized the distribution of ratings across restaurants.
- **Online Order & Book Table Analysis**: Checked how many restaurants support online ordering and table booking.
- **Cost Analysis**: Investigated the distribution of the approximate cost for two people.
- **Correlations**: Explored relationships between votes, ratings, and cost.

### Key Visualizations
- **Rating Distribution**: A histogram showing the spread of restaurant ratings.
- **Online Ordering vs. Rating**: Bar plot comparing ratings of restaurants with and without online ordering.
- **Cost Distribution**: A histogram displaying the distribution of costs for two people.

## Results

Some key takeaways from the analysis:
- Restaurants with online ordering tend to have slightly higher ratings.
- The average cost for two people ranges between ₹300 and ₹950, with the majority of restaurants falling in the ₹500-₹800 range.
- The number of votes and ratings are moderately correlated, suggesting that popular restaurants generally receive higher ratings.

## Conclusion

This project provided insights into how online ordering and table booking affect restaurant ratings and cost structures. Future work could involve predictive modeling or deeper analysis of customer preferences based on location and restaurant type.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/mohiittt/Zomato_data_analysis.git

2. Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt

3. Open the Jupyter Notebook:
- You can run the notebook in Google Colab or locally by opening zomato_analysis.ipynb.
  
4. Run all cells to reproduce the analysis.

