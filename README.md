# Project Title: Correlation between Change of Closing Prices of Stocks and Words Frequency of Korean News Titles

# Motivation:
The easiest way to get information about foreign(not Korean) companies to Korean people is to trace how Korean internet news says about those companies.
My question here is whether there is enough linear relationship between change in stock price and frequency of specific words.

# Procedure
1. Extort data of closing prices of stock from Yahoo Finance and make an excel file. (We can specify a timeframe and a company) 
(file name: graph_close_prices.ipynb)

2. Extort titles of news from Naver(The biggest Korean website) and calculate the frequency of the specific words. 
(file name: Relationship between word 'Iphone' and closing price of Apple stock..ipynb)

3. Combine the data frame of change in closing prices and the data frame of the frequency of the word to make one data frame. 
(file name: Relationship between word 'Iphone' and closing price of Apple stock..ipynb)

4. Apply linear regression to check the correlation between the change of closing prices and the frequency of the word. 
(file name: Relationship between word 'Iphone' and closing price of Apple stock..ipynb)

# Result

<img width="140" alt="캡처1" src="https://user-images.githubusercontent.com/68969884/104713610-1cc9e580-56f2-11eb-9ce4-dcab9e6b7ed4.PNG">

<img width="451" alt="캡처2" src="https://user-images.githubusercontent.com/68969884/104713786-57338280-56f2-11eb-9354-1e654527821b.PNG">


# Condition
Ex) Frequency of words between 12.22. 10 ~ 11am (US est time) and 12.23. 10:59~11:59am(US est time)
    Change of closing prices between 12.22. 4pm (US est time) and 12.23. 4pm (US est time)
