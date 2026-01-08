# Zomato Analysis
This project performs comprehensive exploratory data analysis (EDA) on Zomato resaurant data. The analysis includes data cleaning, statistical analysis, text mining, and geospatial visualization to derive actionable insights about restaurant trends, customer preferences, and localation patterns.

## Overview
This project performs comprehensive exploratory data analysis (EDA) on Zomato resaurant data. The analysis includes data cleaning, statistical analysis, text mining, and geospatial visualization to derive actionable insights about restaurant trends, customer preferences, and localation patterns.

## Dataset
1. Source: SQLite database containing Zomato restaurant data
2. Scope: Restaurant listings
3. Key Features: Restaurant names, locations, ratings, cuisines, online ordering avilabilty, revies, and more

## Analysis Performed
### Data Cleaning & Preprocessing
1. Handled missing values in key columns (rate, cuisines, restaurant type)
2. Converted rating formats from string to numerical values
3. Cleaned and standarized data for analysis
### Statistical Analysis
1. Explored relationship between online ordering avilability and restaurant rating
2. Analyzed restaurant type distributions and popularity
3. Created frequency tables and cross-tabulations
### Text Analysis & NLP
1. Unigram Analysis: Identified most frequently mentioned words in customer reviews (food, place, good, chicken, taste, service)
2. Bigram Analysis: Discovered key food preferences (fried rice, ice cream, chicken biryani) and quality factors (good food, pocket friendly, value for money)
3. Trigram Analysis: Revealed specific cuisine preferences (North Indian food, Soth Indian food, paneer butter masala)

## Geospatial Analysis
1. Extracted latitude and longitude coordinates for all restaurant locations using Geopy
2. Created interactive heatmaps using Folium to visualize restaurent density

## key Insights
### Value Factors
Price consciousness is important - "pocket friendly" and "value for momey" are frequently mentioned in positive reviews
### Online Ordering
Relationship exists between online ordering avilabilty and restaurant ratings

## Technologies Used
Python 3.11
Libraries:
  pandas, numpy - Data manipulation
  matplotlib, seaborn - Data visualization
  sqlite3 - Database connectivity
  nltk - Natural Language Processing
  folium - Interactive maps
  geopy - Geocoding services

## How to Run
1. Clone this repository
2. Install required pacakges: pip install pandas numpy matplotlib seaborn nltk folium geopy
3. Download NLTK stopwords: nltk.download('stopwords)
4. Update the database path in the notebook
5. Run all cells in the Jupyter notebook

## Future Enhancements
1. Sentiment analysis on customer reviews
2. Price range analysis and recommendations
3. Cuisine-wise rating comparisons
4. Time-series analysis if temporal data is avilable
