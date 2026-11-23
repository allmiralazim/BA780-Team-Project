# Talking Before Trading: Are StockTwits Comments Linked to Apple's Trading Volume?

## A Study of AAPL (January 2020 – February 2022)

### Project Overview
This project looks at whether activity on StockTwits can help explain changes in Apple's (AAPL) daily trading volume. We analyzed more than 914,000 StockTwits comments and compared them with Apple's stock trading data to see whether the number of comments and investor sentiment were related to trading volume on the following day.

We also looked at how major events, including Apple's earnings announcements and the COVID-19 market crash, affected online discussions and trading activity.

### Research Questions

Does a higher number of StockTwits comments today relate to higher trading volume for Apple on the next trading day?

Does the number of comments have a stronger relationship with next-day trading volume than investor sentiment (bullish or bearish)?

### Data Sources
StockTwits: More than 914,000 comments about Apple from December 2019 to February 2022, downloaded from Kaggle.
Yahoo Finance: Apple's historical daily stock data, including trading volume and closing prices.

### Methodology
The project involved several steps:

Cleaned and combined 62 StockTwits CSV files with different column structures.

Extracted information such as comment dates, posting times, sentiment, likes, and replies.

Converted timestamps to New York time and matched comments to the correct trading sessions, including weekends and market holidays.

Combined daily StockTwits activity with Apple's historical trading data.

Compared daily comment counts with their previous 30-trading-day averages.

Analyzed correlations between comment activity, investor sentiment, and next-day trading volume.

Examined trading activity around earnings announcements and during the COVID-19 market crash.

### Key Findings
Same-day relationship: StockTwits comment volume had a stronger relationship with same-day trading volume (correlation of 0.65) than with next-day trading volume (0.35).

Higher comment activity: When comments were above their 30-day average, next-day trading volume was approximately 15% to 23% higher than normal.

Comment volume vs. sentiment: The number of comments was more closely related to next-day trading volume than bullish or bearish sentiment.

Earnings announcements: Comment activity increased to around 4 to 6 times its usual level on the day after earnings announcements.

COVID-19 period: Investor sentiment shifted during the market crash, with a lower share of bullish comments compared with the periods before and after COVID.

Overall, the results suggest that StockTwits activity can provide an indication of potentially higher trading activity on the following day, but it is not an exact prediction. The findings show a relationship, not causation.

### Tools 
Python

Pandas

NumPy

Matplotlib

Seaborn

yfinance

Jupyter Notebook / Google Colab

### Team Contributors
Almira Lazim

Alicia Mora

Pakaporn (Zoe) Leetrairong

Ricardo Huang Wei Di

