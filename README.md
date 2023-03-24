# JPMC Task 1
Task 1 of the JPMC software engineering program

## Purpose
We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

## Acceptance Criteria
* `getDataPoint` function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask
* `getRatio` function should return the ratio of the two stock prices
* `main` function should output correct stock info, prices and ratio

## Output
```
>> ./server3.py 

HTTP server started on port 8080
Query received @ t2019-02-10 10:07:43.237974
Query received @ t2019-02-11 18:12:31.763344
Query received @ t2019-02-13 00:41:03.061658

>> ./client3.py

Quoted ABC at (bid:118.13, ask:116.63, price:117.38)
Quoted DEF at (bid:115.14, ask:117.87, price:116.505)
Ratio 1.0075104072786576
Quoted ABC at (bid:118.13, ask:116.63, price:117.38)
Quoted DEF at (bid:115.14, ask:117.87, price:116.505)
Ratio 1.0075104072786576
Quoted ABC at (bid:118.13, ask:116.63, price:117.38)
Quoted DEF at (bid:115.14, ask:117.87, price:116.505)
Ratio 1.0075104072786576
```
