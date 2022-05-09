# Olympics Dataset Analysis

![alt text](https://github.com/zuzanadostalova/Olympics-dataset-analysis/blob/main/Screenshot%202022-05-09%20at%2015.07.08.png)
-------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------
## The objective:

- The purpose of this project is to:
    - analyze Olympics data from 1960 till present
    - find the most important features for winning the Olympics

-------------------------------------------------------------------------------------------------------------------------------------------------------
## Method Used:

- Supervised Machine Learning Algorithms (random tree classifier)

-------------------------------------------------------------------------------------------------------------------------------------------------------
## Technologies:

- Python
- Pandas, jupyter
- Auto-sklearn
- Sklearn

-------------------------------------------------------------------------------------------------------------------------------------------------------
## Project Description:

Olympics is the most prestigious event celebrated and respected around the world. The dataset consists of Olympics data of over a century, from the year 1896 to 2016. However, only data after 1960 was used as many earlier entries were missing. Three most represented summer Olympics sports (Athletics, Gymnastics, Swimming) were analyzed to establish what features had the most important role in winning a medal.

-------------------------------------------------------------------------------------------------------------------------------------------------------
## Hypothesis:

- The analysis of this dataset will help uncover patterns of the most successful athletes and countries in the history of Olympics 

-------------------------------------------------------------------------------------------------------------------------------------------------------
## Conclusions:

- Because of the strong class imbalance, the classifier was very succesful in predicting the negative class (no medal), but not in predicting the positive one (medal) with overall F1-score=0.67
- The most important feature for winning a medal was the athlete BMI

-------------------------------------------------------------------------------------------------------------------------------------------------------

## Getting Started

- Clone this repo (for help see this tutorial).
- Raw Data is being kept here within this repo.
- Data processing/transformation scripts are being kept here
- Follow setup instructions
