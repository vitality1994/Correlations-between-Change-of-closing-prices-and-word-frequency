# Project Title: Correlation between Closing Prices of Stocks and Words Frequency of Korean News Titles

# Motivation:
The easiest way to get information about foreign(not Korean) companies to Korean people is to trace how Korean internet news says about those companies.
My question here is whether there is enough linear relationship between change in stock price and frequency of specific words.

# Procedure
1. Extort data of closing prices of stock from Yahoo Finance and make an excel file. (We can specify a timeframe and a company)
2. Extort titles of news from Naver(The biggest Korean website) and calculate the frequency of the specific words. 
3. Combine the data frame of change in closing prices and the data frame of the frequency of the word to make one data frame.
4. Apply linear regression to check the correlation between the change of closing prices and the frequency of the word.
