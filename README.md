# Fintech Review Analytics 📊

## Overview
A data engineering pipeline that scrapes, analyzes, and visualizes Google Play Store reviews for three Ethiopian banks.

## Banks Analyzed
- Commercial Bank of Ethiopia (CBE)
- Bank of Abyssinia (BOA)
- Dashen Bank

## Project Structure
fintech-review-analytics/
├── data/raw/          
├── notebooks/         
│   ├── scraping.ipynb
│   ├── task2_sentiment.ipynb
│   ├── task3_database.ipynb
│   └── task4_insights.ipynb
├── scripts/           
├── src/               
├── tests/             
└── requirements.txt

## Tasks Completed
- Task 1: Scraped 1000+ reviews from Google Play Store
- Task 2: Sentiment analysis and thematic analysis
- Task 3: PostgreSQL database design and population
- Task 4: Insights and visualizations

## Setup
pip install -r requirements.txt

## Run Scraping
python scripts/scrape_reviews.py

## Technologies Used
- Python 3.12
- Pandas
- Google Play Scraper
- PostgreSQL
- Matplotlib and Seaborn
- Jupyter Notebooks



