# Project_Two

Video Game Company Stock Price Web Scraper and News Article Sentiment Analysis

Using Python and MongoDB, perform the Extract, Transform, and Load (ETL) process on stock data for 8 video game development companies
(EA (EA), Nintendo (NTDOY), Ubisoft (UBSFY), Activision Blizzard (ATVI), Sega (SGAMY), Take Two Interactive (TTWO), Square Enix (SQNXF),
Bandai Namco (NCBDF)).

After the stock information is scraped from Yahoo Finance, the most recent news article for each company and its headline are scraped from
Forbes.com, and a sentiment analysis is performed. After enough data is collected, the sentiment analysis could later be used to spot
potential trends or a relationship between media articles and stock prices.

After all relevent information is collected and the sentiment analysis is performed, all of the information is pushed to a MongoDB database
where it can easily be accessed and served to end users via a Flask API.
