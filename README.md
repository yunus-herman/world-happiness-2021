# World happiness 2021
**by : Yunus Herman**

**Software Requirements:**
- Google Chrome
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- StandardScaler

## Table of Contents:

For our audience, please begin by examining the ReadMe and read the Introduction, Problem Statement, and Background to familiarize yourselves with the design and focus of the project. Then refer to the below ordered notebooks. Then you should be able to proceed with the remaining sections of the Readme detailing our process, and finally the Executive Summary/Recommendations can be found on Readme file.  

## Notebooks:

- 01_data_cleaning_EDA.ipynb

- 02_modeling.ipynb

## Executive Summary:

- README.md

## Data:

- world-happiness-report-2021.csv
- world-happiness-report.csv
- mortality-data.csv

## Introduction:

The world happiness 2021 focuses on the effects of COVID-19 and how people all over the world have fared. The state of global happiness also from economics, psychology, survey analysis, national statistics, health, public policy and more.This project will be presenting to goverments or any organizations all over the world to evaluate and understand the mental health during and after the pandemic.  

## Problem Statment:

How people all over the world happiness and covid-19 related. Can we predict people happiness from covid-19 data? Is the world happiness different from before the pandemic?   

## Background:


## Data Retrieval:

Data from Mathurin Ache on kaggle.com https://www.kaggle.com/mathurinache/world-happiness-report-2021 :

**world-happiness-report-before-2021.csv**

**world-happiness-report-2021.csv**

**mortality-data.csv**

This file contains the Happiness Score for 153 countries along with the factors used to explain the score.

The Happiness Score is a national average of the responses to the main life evaluation question asked in the Gallup World Poll (GWP), which uses the Cantril Ladder.

### Data Dictionary:


The Happiness Score is explained by the following factors:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|country name|object|world-happiness-report-2021|Name of country|
|regional indicator|object|world-happiness-report-2021|Region of country|
|ladder score|float|world-happiness-report-2021|Happiness score is from the Feb 26,2021 |
|Logged GDP per capita|float|world-happiness-report-2021|Purchasing power parity (PPP) at constant 2017 international dollar prices |
|social support|float|world-happiness-report-2021|The national average of the binary responses (either 0 or 1) to the GWP question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”|
|healthy life expectancy|float|world-happiness-report-2021|Healthy life expectancies at birth are based on the data extracted from the World Health Organization’s (WHO) Global Health Observatory data repository.|
|Freedom to make life choices|float|world-happiness-report-2021|the national average of responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”|
|Generosity|float|world-happiness-report-2021|the residual of regressing national average of response to the GWP question “Have you donated money to a charity in the past month?” on GDP per capita.|
|Perceptions of corruption|float|world-happiness-report-2021|The measure is the national average of the survey responses to two questions in the GWP: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?” The overall perception is just the average of the two 0-or-1 responses. In case the perception of government corruption is missing, we use the perception of business corruption as the overall perception. The corruption perception at the national level is just the average response of the overall perception at the individual level.

### Data Cleaning:



### EDA:
Findings:

1. 


### Modeling:



**Modeling Takeaways:**


### Executive Summary:

**Problem Statement:** How people all over the world happiness effected by covid-19. Can we predict people happiness from covid-19 data? Is the world happiness different from before the pandemic?   

**Recommendations:** 
