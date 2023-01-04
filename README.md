# An Analysis of Mega Ball Numbers in Mega Millions Data
This project analyzes winning Mega Ball numbers from 2002 to 2022. 

#### -- Project Status: [Completed]

## Project Objective
The purpose of this project is to analyze winning Mega Ball numbers from 2002 to 2022 to derive any notable findings in the data, such as number of occurrences and patterns.

### Methods Used
* Pandas
* NumPy
* Matplotlib
* Data Cleaning

### Technologies
* Python
* Jupyter Notebook

## Project Description
The data used for this project can be found here: https://data.ny.gov/Government-Finance/Lottery-Mega-Millions-Winning-Numbers-Beginning-20/5xaw-6ayf.
The data is provided by the New York State Gaming Commission and is made available by NY Open Data, and is updated twice-weekly.

This project contains the following:
- Data cleaning: removing unnecessary columns such as 'Winning Numbers', 'Draw Date', and 'Multiplier', removing values <= 25 due to Mega Ball numbers only ranging 1-25 (unlike past years).
- value_counts: taking a count of all Mega Ball number occurrences
- sort_values: sorting values by occurrence only, and in descending order to quickly rank most occurring numbers to least occurring numbers.
- Data visualization: created a scatterplot using Matplotlib to visualize Mega Ball numbers and their occurrences.

## Conclusion

Through this analysis, I was able to conclude that Mega Ball number occurrences are indeed random and don't follow a pattern, but there are numbers that occur more often than some.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept at megaball/Lottery_Mega_Millions_Winning_Numbers__Beginning_2002.csv within this repo.
