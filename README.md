# stock-analysis (VBA Challenge)

## Overview of Project
During this challenge, we worked on refactoring our code to know if there were better ways to make it run more smoothly. The goal was to create a macro that accomplished the same goal of analyzing our data set, but faster. 

## Results
We found that refactoring the code worked thanks to the timer method which helped us measure how long it took for the code to accomplish its goal. During the original script for 2017, it ran for 1.51 seconds. However, with our refactored code, it ran for 0.75 seconds. For 2018, the original code ran for 0.85 seconds whereas the refactored code was aprox. 10 seconds faster.

Here you can see the time it took to analyze 2017:
<img width="953" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/88563922/134840658-7eeff397-4be6-4f92-9867-08687aa9333c.PNG">

Here you can see the time it took to analyze 2018:
<img width="952" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/88563922/134840298-0962a9bc-0448-42bc-82bb-8222a29c4c1a.PNG">


## Summary
In conclusion, I learned very clearly that the first time coding might not be the most effective way. However, it is important to get the job done first, get code to work and accomplish the goal it was meant to, and then take the time to go over it and truly see which parts could use refactoring. As we saw in the results, refactoring allowed us to save time and energy doing the exact, same job.

### What are the advantages or disadvantages of refactoring code?
As stated previously, refactoring can make code run more smoothly than the original way. However, as a disadvantage I could say the famous quote "If it ain't broke, don't fix it" as a perfect example of how we could make a mistake by trying to refactor and end up with broken code. 

### How do these pros and cons apply to refactoring the original VBA script?
Crealy during this exercise, the first analysis we made had longer scripts and loops that had to check every single row before continuing. During the second refactored analysis, we created arrays that made loops more efficient and that translated to time effiency.  Of course, during this exercise we saw relatively small differences in time, but if we used bigger data sets, we would see more relevant improvements. Perhaps we can save hours, instead of seconds. 
