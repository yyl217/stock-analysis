# Stock Analysis

## Overview of Project

### Background

The green_stocks.xlsx is an excel file that contains a dataset of the stocks with tickers, date, pricing, and volume details. 

### Purpose

This project aims to summarize the green_stocks.xlsx with a simple click of the button and a preliminary analysis of the generated summary.

## Results

### 2017

![alt text](https://github.com/yyl217/stock-analysis/blob/main/result_2017.png?raw=true)

The 2017 stock result took 0.09 seconds to generate. From the result, we can see that SPWR has the highest total daily volume of 782,187,000 while DQ has the highest rate of return of 199.4%.

### 2018

![alt text](https://github.com/yyl217/stock-analysis/blob/main/result_2018.png?raw=true)

The 2018 stock result took 0.09 seconds to generate. From the result, we can see that ENPH has the highest total daily volume of 607,473,500 while RUN has the highest rate of return of 84%

## Summary


1. Refactoring code, in general, has many positives, for example, reducing CPU processing power and saves time. It is always a good idea to refactor code to make the script faster.

2. The advantage of refactoring code is effectively reduced unnecessary CPU processing power and processing time. With the original code, the loop has to run 11 times of the entire rows to get the result. The refactoring code only runs one time of the whole rows. The refactoring code only took 0.09 seconds to run the 2018 stock result compare to 0.5 seconds for the original code. The refactoring code's disadvantage is that it might be harder to write code because it involves arrays. It may be harder to troubleshoot and debug the code.