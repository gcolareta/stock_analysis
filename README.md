# Stock_Analysis Challenge 2
Analysis of data from various alternative energy stocks.

## **Overview of Project**

In this Module, I analized data from various alternative energy stocks to help Steve make informed recommendations to his parents on the stocks they should invest in. Through a series of steps, I ran a Macro to return the total daily volume and the percentage of return for each stock. The purpose of this project was to refactor the code to loop through all the data in order to collect the same information in less time, and to be able to apply the same code to a larger dataset.

## **Results**

One of the main changes was to create a tickerIndex to have Excel look through all the tickers' name in the dataset and calculate such ticker's daily volume, and percentage of return. The later calculation was made by having a code to identify the stock's starting and ending price. By having a tickerIndex I can more precisely tell Excel when to look for the next ticker's name and calculate the values needed. Thus the loop becomes more efficient.

<img width="696" alt="Loop for 3 values" src="https://user-images.githubusercontent.com/104762216/169718902-ec6bbe7e-8cd0-4132-872c-22f5a601ab1b.png">

Another element added to the code was an array to hold the outputs of the calculated values per ticker. By making an array I am indicating that each calculation (tickersDailyVolume, tickersStartingPrice and tickersEndingPrice) hold store 12 values. This makes the code more accurate.
  
<img width="584" alt="Loop output array" src="https://user-images.githubusercontent.com/104762216/169719061-6a427ce6-4e13-462c-8c42-f042553dbc49.png">
  
As a result of these changes, the macro ran faster, as seen on the pictures below.
  
##### *Before the code was refactored*

<img width="1130" alt="Before Refactor" src="https://user-images.githubusercontent.com/104762216/169719071-92e9c563-928f-4866-a25c-7c24d9ad5226.png">

  
##### *After the code was refactored*


