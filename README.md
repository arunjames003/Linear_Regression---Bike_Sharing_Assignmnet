# Predictive Modeling for Bike-Sharing Demand


## Table of Contents
* General Information
* Conclusions
* Python Library Used for Analysis


## General Information
This project focuses on predicting post-lockdown bike-sharing demand for BoomBikes, a US-based provider facing revenue challenges due to the Covid-19 pandemic. The aim is to develop a multiple linear regression model to identify key factors influencing bike demand, helping BoomBikes tailor its business strategy for maximum profitability.

* Background:
BoomBikes, amidst a significant revenue downturn during the Covid-19 pandemic, seeks to proactively understand and meet the demand for shared bikes once the lockdown is lifted. The project's inception stems from the need to formulate a targeted business plan to accelerate revenue growth post-pandemic.

* Business Problem:
The primary business problem is the revenue decline experienced by BoomBikes due to the ongoing Covid-19 pandemic. The company aims to address this challenge by predicting and understanding the factors influencing bike-sharing demand post-lockdown, enabling them to adjust their business strategy and cater effectively to customer needs.

* Dataset:
The project utilizes a comprehensive dataset containing information on daily bike demand across the American market. The dataset includes various independent variables such as meteorological surveys and lifestyle factors, providing a rich source of data for building the predictive model. The analysis will be grounded in this dataset to uncover insights that can guide BoomBikes in optimizing their market approach.

* Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
As per our final Model, the top 6 predictor variables that influences the bike booking are:
* Temperature - A coefficient value of 0.544334 indicate that a unit increase in temp variable increase the bike hire number by 0.544334
* Light_snowrain - A coefficient value of -0.238456 indicate that a unit increase in Light_snowrain variable decreases the bike hire number by 0.238456
* Year - A coefficient value of 0.229886 indicate that a unit increase in year variable increase the bike hire number by 0.229886
* Windspeed - A coefficient value of -0.192512 indicate that a unit increase in windspeed variable decreases the bike hire number by 0.192512
* Humidity - A coefficient value of -0.169352 indicate that a unit increase in humidity variable decreases the bike hire number by 0.169352
* Winter - A coefficient value of 0.128776 indicate that a unit increase in winter variable increase the bike hire number by 0.128776




## Technologies Used
- numpy - version 1.24.3
- pandas - version 2.1.4
- matplotlib - version 3.7.2
- seaborn - version 0.12.2
- sklearn - 1.3.0
- statsmodels - 0.14.0




## Contact
Created by [@arunjames003] - feel free to contact me!
