# HedgingBasket
Create a hedging basket from a pool of stocks to hedge the fluctuations of target instruments.

Introduction

The proxy basket can be defined as a combination of securities. These securities are typically highly liquid and readily available to buy or sell. Your task is to build and validate an algorithm that will find optimal baskets from the available universe of
securities. Estimated time to complete 3 hours. 

Hedging procedure:

• Buy the target, sell the basket
• Hold both positions for time T
• At time T, sell the target, buy the basket
• Net position is zero (ideal case)

The Data

In the data folder you will find three files:
• X.csv Universe of 444 securities. Table 1
• y.csv Securities to hedge, four total (four targets). Table 2
• categorical.csv Categorical variables. Feel free to use them in your model. Table 3