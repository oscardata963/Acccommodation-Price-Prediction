# Project 1: Accommodation Price Predictions - A Regression Task

Accommodation costs share a significant portion of travellers' expenses. People always want to look for the best deals with rooms that fit their needs and preferences.
However, with over thousands of choices over the Internet, people easily fall into a never-ending cycle of trying to manually targeting the best price. An intuitive 
and convenient solution to this common conundrum is to create a price estimator that does the cumbersome job for these travellers.

This project aims at building an accommodation price estimator that inputs relevant features about the stays and predicts their prices corresponding to these 
preferences. The collection of data requires web scraping on popular accommodation sites for a specific location, date and number of guests. To ensure consistency, 
the accommodations for 1 adult in Tokyo, Japan at a specific date will be explored and used as the input data.

**Tools used**
1. Jupyer Notebook
2. Python
3. Selenium
4. Pandas
5. Numpy
6. Matplotlib
7. Sklearn

**Folders**
1. Scraping - data about the hotels are scraped from airbnb.com and booking.com using Selenium and Pandas.
2. Cleaning - Datasets obtained from the two websites are cleaned and combined using Pandas.
3. Prediction - Data are analyzed using Pandas and Matplotlib and the accommodation prices are predicted using models from Sklearn.
