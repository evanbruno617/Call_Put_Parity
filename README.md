# Call Put Polarity
---

## Overview
---

The purpose of this project is to develop code to calculate arbitrage opporunities with options using the put call parity equation. For clarification the put call parity equation follows - P + S = C + Ee^(-r(T-t)) The right side of the equation is the value of the put at a certain expiration + the stock price must be equal to the value of the call at the same expiration + the expiration price * exponential ^ (negative interest rate *  time to expiration in years). 

![image](https://github.com/evanbruno617/Call_Put_Polarity/blob/main/Resources/Put_Call_Parity.png)

This snippet from the code is the put call parity put into action by calculating arbitrage opportunities in the market. An arbitrage opportunity occurs when one side of the equation is more than the other which allows someone to buy the undervalued side and sell thje overvalued side and the difference between the two would be the gauranteed profit. 

## Result
---

The final product results in a dataframe which shows the user which stocks and their options have a arbritradge opportunity in the market to take advtantage of

![image](https://github.com/evanbruno617/Call_Put_Polarity/blob/main/Resources/Profit.png)
