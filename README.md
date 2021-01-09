
# TradingAlgorithmSimulator - Work In progress
This is a personal project to learn and test different trading algorithms. Also to review C++

## Uses
The goal is to simulate different trading algorithms algorithms with historic stock market data. The program can run with the following algorithms.

1. Mean Reversion

## Trading algorithms
### Mean Reversion
```
RunSimulator 1 [int starting cash per stock] [int ] [String stock1] [String Stock2] ...
```

## How To Use
### Generating Stocks
You need to generate stock csv. We will use the data points obtained from alpha vantage.
To get a stock csv use 
GenerateStock [Stock Name]

To keep things simple for the simulation we will use Daily Adjusted times from AlphaVantage

## Dependencies
To include "csv.h" we use https://github.com/vincentlaucsb/csv-parser

### Input arguments
Run the simulator with its respective arguments.
### UI - Not Done and Probably never will

Upon start
```
Welcome to Samin's Trading simulator.
Select which algorithm you would like to use?
1) Reversion
2) Quitgoo
```

Upon Quit
```
Goodbye
(Then Quits application)
```

Upon Selecting a strategy
```
Enter the stock you would like to use.
```

It would then repeat this line until a blank line is enter

Upon blank line
```
Enter the max amount of initial money you want to spend on each stock.
```

Upon entering money
```
Here are the results!
[Stock 1]: [Gain/Loss]
[Stock 2]: [Gain/Loss]
...
Total Gain: [Gain/Loss]