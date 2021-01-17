# Project Title:
Correlation between Change of Closing Prices of Stocks and Words Frequency of Korean News Titles

# Motivation:
The easiest way to get information about foreign(not Korean) companies to Korean people is to trace how Korean internet news says about those companies.
My question here is whether there is enough linear relationship between change in stock price and frequency of specific words.

# Procedure
1. Extort data of closing prices of stock from Yahoo Finance and make an excel file. (We can specify a timeframe and a company)    
(graph_close_prices.ipynb)

2. Extort titles of news from Naver(The biggest Korean website) and calculate the frequency of the specific words.    
(Relationship between word 'Iphone' and closing price of Apple stock..ipynb)

3. Combine the data frame of change in closing prices and the data frame of the frequency of the word to make one data frame.    
(Relationship between word 'Iphone' and closing price of Apple stock..ipynb)

4. Apply linear regression to check the correlation between the change of closing prices and the frequency of the word.    
(Relationship between word 'Iphone' and closing price of Apple stock..ipynb)

# Result

![image](https://user-images.githubusercontent.com/68969884/104856084-6a0aaa80-58de-11eb-8c36-0e8236d9b945.png)
![image](https://user-images.githubusercontent.com/68969884/104856096-84dd1f00-58de-11eb-9192-54dc4f5cc1fc.png)




# Condition
Ex) On 12.23.   
    Frequency of words between 12.22. 10 ~ 11am (US est time) and 12.23. 10:59~11:59am(US est time)   
    Change of closing prices between 12.22. 4pm (US est time) and 12.23. 4pm (US est time)
