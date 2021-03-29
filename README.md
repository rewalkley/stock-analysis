# stock-analysis
Challenge 2

## Overview of Project
The purpose of this analysis is to help Steve analyze the stock data for helping his parents. We set Steve up to run a script to compare 2017 and 2018 stock data, and then refactored the code to utilize an index variable.

## Results
The results we found for Steve were that 2017 had almost the opposite outcome vs 2018. 2017 provided almost all postivie returns (TERP being the only negative), whereas 2018 provided almost all negative returns (ENPH and RUN being the only positive).

The tables below show the results by year:

![2018 Returns](https://user-images.githubusercontent.com/80076110/112773853-40b47c00-8ffd-11eb-8da4-8e1cb31382fe.PNG)

![2017 Returns](https://user-images.githubusercontent.com/80076110/112773849-3d20f500-8ffd-11eb-8b5a-01b69a01b24a.PNG)

Further, the execution times of the refactored script is significantly reduced vs the original code written. The run times for the refactored script were sub 0.2 seconds, where the unfactored script runtimes were in the 0.6 - 0.7 second ranges.

![2017 Refactored Runtime](https://user-images.githubusercontent.com/80076110/112773859-46aa5d00-8ffd-11eb-8777-6733a8eeab45.PNG)

![2018 Refactored Runtime](https://user-images.githubusercontent.com/80076110/112773862-490cb700-8ffd-11eb-9544-de4ca45b88a9.PNG)

## Summary

### Advantages and Disadvantages of Refactored Code
The main advantage of the refactored code is that when using an  Index, you can eliminate redundant code lines. DRY is a key concept in this type of coding.

One disadvantage of refactored code is the analyst reading the code may or may not have any background knowledge of the code, and not only will have to adjust the code, but will have to learn it first. this creates an extra step in the coding process.

These pros and cons apply to the refactoring of the orignal VBA script by cleaning up the redundant coding, and minimizing the re-learning process (we did just write the code).
