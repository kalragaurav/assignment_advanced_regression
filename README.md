# Project Name
> To model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project models the price of houses with the available independent variables.
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. For which we are required to build a model to predict the Sale Prices.
- The Dataset contains around 1400+ rows and 80 Predictor Variables and Sale Price.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- After carefully analyzing the performance of all models on Test data, Lasso Model was finalized. Predictor variables such as GrLivArea, TotalBsmtSF, YearBuilt, Neighborhood_Crawfor, OverallQual_9, OverallQual_10, GarageArea positively impact the SalePrice. Whereas variables such as OverallQual_3 and OverallCond_3 negativvely impact pricing.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas 1.3.4
- numpy 1.20.3
- matplotlib 3.4.3
- seaborn 0.11.2
- statsmodels 0.12.2
- scipy 1.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the Advanced Regression Course conducted by IIITB and UpGrad.  
- References: Wikipedia and Stackoverflow Forums.

## Contact
Created by @kalragaurav - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->