# Cinephiles Phase 2 Project

September 2023

Yasitha De Alwis (ydealwis@gmail.com)

Kendall McNeil (kendallmccneil@gmail.com)

Andrew Hendricks (AndrewHHendricks@gmail.com)


## Overview

Our company has decided to create its own new movie studio and wants to explore what types of movies are doing best at the box office.

The company asked our team to study which types of movies are doing the best and to translate our findings into actionable insights for the new movie studio head.

## Business Understanding

Our key stakeholder is the head of the new movie studio. The main question we explore is: Which factors have the strongest significance in relation to a movie's profitability?

## Data Understanding and Analysis

### Source of data

To perform our analysis, our team primarily relied on budgetary data from two sources.  The first source was The Numbers, which provided us with information about runtimes, release date, production budgets, and worldwide gross. The second source was IMDB, which provided us with data about genres and other movie characteristics as well as personnel such as directors, writers, and actors.

### Description of data

The budgetary data from The Numbers included approximately 5,500 records of movies from the past several decades. To perform our analysis of the relationship between factors from the IMDB database and profitability, we merged the data sets and eliminated Nan values as needed.

### Methods

To begin, we decided to calculate a ratio of worldwide gross relative to production budget to determine the profitability ratio for each film.  We used this value as our main indicator for profitability.

Next, for each factor we analyzed, we performed chi square tests to evaluate significance of statistical relationship between the factor and profitability. In order to conduct the analysis we translated profitability ratios into categorical form considering the uniformity of no of records per category and industry ratios for movies to become profitable.

The hypothesis considered for the analysis include:

H0:There is no significant relationship between factor and profitability category.

H1:There is a significant relationship between factor and profitability category.

For the factors that resulted as significant we conducted a secondary analysis grouping the data by element for that factor and reviewing the median profitability ratio for each element. In certain analyses involving smaller numbers of records, such as analyses of personnel categories, we used the best sample of data we had available.


### Results
Median Profitability Ratio by Movie Genre

![Movie Genre](https://github.com/ahendricks2/project2readme/assets/141271148/7695bcea-08b5-43b1-9985-d059dd49f6cb)

Median Profitability Ratio by Release Month

![image](https://github.com/kmcneil901/dsc-phase-2-project-v3/assets/139075900/edfec094-b8ac-47a4-907d-1f7e120e79af)

Median Profitability Ratio by Director

![image](https://github.com/kmcneil901/dsc-phase-2-project-v3/assets/139075900/149d7328-1d6f-4666-a4de-25711a8eab0d)

Median of Profitability Ratio by Duration of the Movie

![Runtime](https://github.com/ahendricks2/project2readme/assets/141271148/efd73f08-84e9-40d6-a0d8-b09c07e64ec8)


## Conclusion

Based on our analysis, we would make the following recommendations to the head of the company's new movie studio:
1. The most profitable genre is horror/mystery/thriller.
2. The most profitable months to release a film are June and July.
3. The most profitable directors are Henry Joost, Ariel Shulman, David F. Sandberg, Pierre Coffin, Christopher Landon, James DeMonaco, M. Night Shyamalan, James Wan, Damien Chazelle, and Jake Kasdan. We recommend Henry Joost and Ariel Shulman, who coincidentally often work together on horror/mystery/thriller films. 
4. The most profitable run time is over two hours, derived average run length of 134-137 minutes.

