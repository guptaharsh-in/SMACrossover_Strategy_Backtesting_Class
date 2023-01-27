# SMACrossover_Strategy_Backtesting_Class

# SMACrossover Strategy Backtesting Class of Indian Stocks using NSEPY

Create SMACrossover Class

Create Get Data Function 

Calcutate Log Returns and Simple Moving Averages (Short and Long)

Calcutate Buy and Hold Returns and Drawdown Columns
 
Calcutate Strategy Returns and Drawdown Columns

Calcutate Strategy Returns and Drawdown

Calcutate Buy and Hold Returns and Drawdown
 
Calcutate Performance and Outperformance

Return Results

Create Plot Results Function

# Result and Conclusion

![result](https://user-images.githubusercontent.com/121168657/215059216-615dc662-c237-4ab1-a1f6-b6e81018f5fc.JPG)


With just 3 lines of code below we can backtest any stock or index in Indian stock market for SMACrossover Strategy(BUY when sma_s>sma_l and SELL when sma_s<sma_l).

test = SMACrossover("NIFTY", 50, 200, date(2020,1,1), date(2023,1,1), True)

test.test_results()

test.plot_results()



