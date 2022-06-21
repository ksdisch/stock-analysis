# Stock Analysis

## Overview of Project

### Purpose

#### Green Energy Stocks Analysis
The first purpose was to write a script in VBA that would generate an analysis of green energy stocks for Steve to present to his parents. When the VBA macro is run, it generates the ticker, along with total daily volume and % return for a given year. To make the information easily consumable, it also uses conditional formatting to color stocks with positive returns green and negative returns red. 

#### Code Refactoring

The other purpose of this analysis was to refactor the original script to make it more efficient. After analyzing the green energy stocks, Steve decided he wanted to do more research for his parents by expanding the dataset to include the entire stock market over the last few years. The original script was fast enough for the 12 green energy stocks, but the entire stock market is a significant amount more data. To make sure the script works as efficiently as possible for the expanded dataset, I needed to refactor the original code to eliminate any inefficiencies.

## Results

### 2017 Versus 2018 Stock Performances

#### 2017

![2017 Performances](/resources/2017_stock_performances.png?raw=true "Title")

#### 2018

![2018 Performances](/resources/2018_stock_performances.png?raw=true "Title")

#### Comparison

Green energy stocks performed significantly better in 2017 than they did in 2018, as we can see in the screenshots above. In 2017, 11 out of 12 stocks finished with a positive return versus just 2 out of 12 in 2018. In 2017, the best performing stock was DQ with a 199.4% return and the worst was TERP with a -7.2% return. In 2018, the best performing stock was RUN with a 84.0% return and the worst was DQ with a -62.6% return. 

### Original Script Performance Versus Refactored Script Performance

#### Refactored Script Performance
![2017 Analysis Speed](/resources/VBA_Challenge_2017.png?raw=true "Title") ![2018 Analysis Speed](/resources/VBA_Challenge_2018.png?raw=true "Title")

#### Original Script Performance

##### 2017: 0.297 seconds
##### 2018: 0.293 seconds

#### Comparison

For the 2017 analysis, there was a 69.70% decrease in run time with the refactored script compared to the original script. For the 2018 analysis, there was a 70.65% decrease in run time with the refactored script compared to the original script. 

## Summary

### Refactoring Code: Advantages

The main advantage of refactoring code is that programmers often use it to make the code simpler. The reason this is beneficial is because it makes the program faster/more efficient, and it makes the code easier to understand if and when it needs to be debugged, altered, or updated. 

### Refactoring Code: Disadvantages

The main disadvantages of refactoring code are that it can be time consuming, and when a person or company has to pay someone for that time, it can be expensive. 

### Project Applications

While refactoring the original VBA script for this project, I experienced one of each of the aforementioned advantages and disadvantages. The advantage was that refactoring improved the code performance significantly, with a 70% approximate decrease in run time. The disadvantage was that it was time consuming, and I was not compensated for that time since this project was a favor for my friend Steve.
