# Stock-Analysis-VBA
## Purpose 
The main purpose for this project was to help Steve analyze various stocks to help his parent find a green energy stock that would be worth their investment. In order to help Steve break down all the data, we had to create a code through VBA and have it be automated for Steve to use. The code we created would help steve visualize which stock had the most daily volume of trades, and the highest yearly percentage return. Once the code does a run through it will be able to calculate through thousands of data and find which stock would be the best to invest in based on the yearly return. We were able to do this for both the years of 2017 and 2018. 
In order to make the original code more effective we have refactored the code for it work more efficiently provided more data is collected, the code can be reused and it may help with the execution time of each year. 
## Results 
### Code Analysis
In our code, we refactored it by creating an index variable that would be able to go through all arrays, this helps the code become more efficient since it now has an index that is able to decrease the speed of locating the array and data in each array. We were able to incorporate this code into the original, which is why you can still see the formatting done to our date. Please see below for our newly improved code. 
![Resources/VBA_Challenge_Code.png](https://github.com/Mparra14/Stock-Analysis/blob/main/Resources/VBA-Challenge_Code.png)
![Resources/VBA_Challenge_Code II.png](https://github.com/Mparra14/Stock-Analysis/blob/main/Resources/VBA_Challenge_%20Code%20II.png)
### Stock performance in 2017 Vs. 2018
Looking at the data from our "All Stocks Analysis" sheet, we can see that in the year of 2017 there was a 11 stocks that had a positive outcome in the yearly return column, this means that investors were able to gain money as they traded their stocks. The only company that had a low yearly return percentage in 2017 was the stock for *TERP*. 
When it comes to the year of 2018, the majority of the stocks did not do well. While their daily volume incresed significatly from 2017, their yearly return was on the negative spectrum. This could mean that many investors were trading stocks but they were not gaining money, and could be possibly loosing their investents. There were only two stocks that had a positive outcome this year, *RUN* and *ENPH*. If Steve were to advise his parents on which stock to invest in it should be either *RUN* or *ENPH*, since these both had positive outcomes two years in a row. 
### Code Execution Times
One of the reasons why this code was refactored was to decrease the execution time of the code itself. With the original code the time that it took for the code to be  executioned was around 0.485 seconds, which is not bad, but if Steve were to use this code with even more stocks the time frame would increase. Having refactored the original code we were able to bring the performance time around 3 seconds faster than the original. This would be able to efficiently perform the code when there is even more data to run through. Please see below for the refactored execution times for the year of 2017 and 2018, respectively.
![VBA_Challenge_2017](https://github.com/Mparra14/Stock-Analysis/blob/main/Resources/VBA_Challenge_%202017.png)


## Summary
*
*
