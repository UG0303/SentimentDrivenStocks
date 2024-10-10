SentimentDrivenStocks
SentimentDrivenStocks is a project that analyzes the correlation between social media sentiment and stock price movements. This analysis utilizes sentiment data from Reddit and stock price data from financial APIs to provide actionable insights for traders.

Installation
To run this project, follow these steps:

Clone the repository
Install the required dependencies:
pip install -r requirements.txt

The following Python libraries are required for this project:

pandas
numpy
matplotlib
seaborn
sklearn
requests
nltk
datetime

Usage
Prepare Your Data: Ensure you have the sentiment and stock price data files ready. The sentiment data should be sourced from Reddit, while the stock prices should be obtained from a financial API.

Run the Analysis: Execute the main Python script:
python main.py

View the Results: The program will generate correlation analyses and plots, visualizing the relationship between sentiment and stock price movements. You will also receive recommendations based on the analysis.

Data Sources
Sentiment Data: Collected from Reddit using the Reddit API.
Stock Price Data: Obtained from financial APIs like Alpha Vantage or Yahoo Finance.
