## Web Scraping TrustPilot for Customer Sentiment

This project demonstrates the process of web scraping reviews from Trustpilot using **Selenium** and **BeautifulSoup**, followed by sentiment analysis using **NLTK's VADER SentimentIntensityAnalyzer**. The goal is to scrape customer reviews, clean and preprocess the data, and classify sentiments as Positive, Negative, or Neutral.

### Features

- **Web Scraping with Selenium**:  
  Automates the process of navigating Trustpilot pages, loading dynamic content, and extracting customer reviews.

- **Data Preprocessing**:  
  Cleans the extracted data to remove non-review elements (e.g., dates or metadata) and standardizes the review content for further analysis.

- **Sentiment Analysis**:  
  Classifies reviews into three categories (Positive, Negative, Neutral) based on sentiment polarity scores using NLTK's VADER:

- **Data Visualization**:  
  Provides insights into sentiment trends using:
  - Bar charts for sentiment distribution.
  - Pie charts for sentiment proportions.
  - Boxplots to analyze review length by sentiment.
