# VBA_Challenge (Module 2)
## Overview of Project
Steve is a financial planner and in order to better help his clients, he wants to be able to quickly analyze stocks. Steve already has a VBA script to quickly analyze stocks but is limited to one stock and one year.  In order to help him meet his goals, we need to refactor Steve's orignal VBA script to analyze multiple stock performances on a yearly basis.  Key metrics that are require are total volume, and % total yearly return. 

## Results
### Stock Results
Our Vba script was able to quickly return key metrics of stocks from 2017 and 2018. Two key general trends were notice while analyzing the data.

The first general trend observed was that most stocks performed better in 2017 than in 2018.  Eleven (11) out of the 12 stocks had a positive return in 2017, while only two (2) stocks had a positive return in 2018. See Images below. 

![VBA_Challenge_2017.png](C:\Users\rdsm1\Documents\GitHub\VBA_Challenge\Resources\VBA_Challenge_2017.png).

![VBA_Challenge_2018.png](C:\Users\rdsm1\Documents\GitHub\VBA_Challenge\Resources\VBA_Challenge_2018.png).

The second general trend observed is that 2017 and 2018 both had a similar volume of trading.  The 2017 stocks average volume per stock was about 260M trades, while the 2018 stocks average at 270M trades.  
### Code Performance Results
Execution times for both the 2017 and 2018 were similar; The 2017 code ran at 1.3 seconds while the 2018 code ran at 1.2 seconds. 

## Summary: 
### Advantages and Disadvantages of Refactoring Code
Refactoring code has both advantages and disadvantages.  Two (2) main advantages of refactoring code are the fact that you already have most of the variable assigments set, and you skip the anti pattern/kluges stage of coding (the stage where you are building up the skeleton of the code)  
However, the main disadvantage of refactoring code is that you are not familiar with the code as if you had built it up from its inception.  When you are not familiar with the code you must infer the purpose of the code and slowly understand the limits of the code.  
### Refactoring the Original VBA Script
Refactoring of the original VBA script was challanging due to the fact there where missing details on how much of the code was completed.  Luckily notes left on the original VBA script help decipher the overall framework of the code.  The main advantage of refactoring of this specific code was due to is well layout organization of having variable assignment, variable declarations and little to know anti pattern/kluges code. 

