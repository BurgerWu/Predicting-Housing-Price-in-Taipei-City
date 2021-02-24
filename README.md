# Predicting-Housing-Price-in-Taipei-City
This repository contains information required for my project --Predicting Housing Price in Taipei City

## Dataset 
The original dataset is named "2020_H2_Resident_CHI.csv", which is written in Chinese and encoded with uft-8 We then process the dataset to translate it from Chinese to English and export it to a new csv file called "2020_H2_Resident_ENG.csv". You can find the final processed dataset in "2020_H2_Resident_ENG", which is also encoded with utf-8. Main process are contained within Notebook Predicting Housing Price in Taipei City

## Libraries 
In this project, following python libraries are used:
- Pandas
- Numpy
- matplotlib
- Seaborn
- urllib.request
- json
- folium
- sklearn
- statsmodels.api
- statsmodels.stats.outliers_influence

## Motivation
Housing price rising has become a serious social problem in Taiwan, especially in Taiwan’s capital city — Taipei City. The price to income ratio index is extremely high even when comparing with other cities worldwide. Out of curiousity of this phenomena, we decided to build a predictive linear model to analyze the housing price using transaction data in second half of 2020. We would like to first explore the data to find some trend of recent real estate transaction and then analyze factors that affect housing price the most.

## Files and Folders
- Raw Dataset: contains the raw dataset downloaded from opendata database of Ministry of Interior of Taiwan
- 2020_H2_Resident_CHI.csv: Chinese version of dataset after first stage transformation
- 2020_H2_Resident_ENG.csv: English version of dataset after first stage transformation
- Dataset Preparation.ipynb: Notebook that performs first stage transformation of raw dataset
- Predicting Housing Price in Taipei City.ipynb: Notebook that performs data cleaning, feature engineering, exploratory data analysis, modeling and evaluation.

## Summary
We observe the trend that suburban house market is rising despite the fact that average price is still lower than downtown area. We also conclude that location is a critical factor that influences housing price in either positive or negative way. Whereas building age is the main factor affecting housing price negatively.

## Acknowlegement
Special thanks to Ministry of Interior of Taiwan for providing such a complete dataset, and Udacity Data Scientist Nanodegree for prompting me to start this project as well as offering useful assistance.


#### You can find blog post of this project here :
#### https://burgercewu.medium.com/predicting-housing-price-in-taipei-city-6f0c797f034a

#### Last update of this Repository takes place on 2021/02/24
