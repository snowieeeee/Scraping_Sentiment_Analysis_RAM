# Royal Air Maroc Customer Reviews Sentiment Analysis

This project involves scraping customer reviews for Royal Air Maroc from Skytrax, cleaning and preprocessing the reviews, and performing sentiment analysis using VADER, TextBlob, and Flair. The results are compared, evaluated, and analyzed to extract insights.

## Overview

- **Web scraping**: Customer reviews were scraped from the Skytrax website by using requests with BeautifulSoup
- **Cleaning and Preprocessing**: The scraped data was cleaned and preprocessed to remove noise and irrelevant information.
- **Exploratory Data Analysis (EDA)**: This part helps to get a better understanding of the overall reviews and ratings (with visualizations).
- **Sentiment Analysis**: Categorizing customer reviews into positive, negative, and neutral sentiments using 3 libraries :
  - VADER
  - TextBlob
  - Flair
- **Comparison and Evaluation**: Results from each sentiment analysis method were compared and evaluated to understand the sentiment of the customer reviews.
- **Extracting insights**: Findings derived from the analysis are documented in the report.

## Files

- `scraping_cleaning_RAM.ipynb`: Jupyter Notebook containing the code for scraping, preprocessing and discovering RAM customer reviews.
- `sentiment_analysis_RAM.ipynb`: Jupyter Notebook containing the code for sentiment analysis using VADER, TextBlob, and Flair + comparison & evaluation.
- `report_RAM.pdf`: Report detailing the analysis, findings, and insights extracted from the sentiment analysis results.
