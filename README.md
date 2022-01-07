# King County Housing Data Sale Price Prediction Model
## Overview
This project analyzes the King County Housing Data from May 2014 to May 2015. This data includes all houses sold in the county during that time as well as describing characteristics of these houses, including sale price.

## Stakeholder
A real estate agency in King County who is looking for help with data analysis in a price prediction model and who wants more quantitative information about what influences sales price.

## Business proposal
Use data science to develop a better model of predicting housing prices in the region. We are also offering inferential information to better advise clients on when to sell or whether it is worthwhile to make changes to their house before selling and for them to get an estimated selling price or an idea of how much the house of their dreams costs.

## Data
As mentioned, data from the King County Housing Data 2014-2015 was the primary focus though the 2010 census, the zip codes of the area, population and population densities for the various communities in the county. Using zip codes, columns Distance from Seattle and Redmond were added also as features to determine the housing prices.

Below are maps to visualize how sale price is by location in King County. 

![Map 1](http://url/to/img.png)
![Map 2](http://url/to/img.png)
![Map 3](http://url/to/img.png)



## Methods
This analysis uses correlations, heat maps, linear regression, and other methods to understand the effects on sales price. The train-test split was used throughout to train our model and the test was then used to determine the effectiveness of that training.


## Results
Our methods have improved the ability to predict the predicted price of a house. This is shown in improved RMSE (in $) and in R-Squared (in %). 


Below we can see the table of how our train and test preformed thoughout improving our models.
![Model Improvements_Table](http://url/to/img.png)


Below we can see the table of how our train and test preformed thoughout improving our models.
![Model Improvements_Bar](http://url/to/img.png)

On our final model, called the **Bestimate**, we can see how the predictions have less error compared to the **Baseline** model in the scatter plots below:

![Scatter Plot Baseline](http://url/to/img.png)

![Scatter Plot Bestimate](http://url/to/img.png)

### Inferential Model
We also created a high performing inferntial model with scaled numeric data to show the effect of each coefficient to sale price. 
See below the bar graph respresenting the coefficients in the model:

![Inferential Bar Graph](http://url/to/img.png)

## House Prediction Application
For usability purposes, we designed a private online application just for your real estate agents in the company to use to predict home prices. We will share a link in the chat for you to explore after this presentation.  
[Private Online Calculator Link](https://kingcountycalculator.czarinagarcia.repl.co/)


## Conclusions 
We have found that the majority of features examined affect the sales price of the house. This is shown in all of our models. Some of the features which affect price, and their effect, are shown below: (update graph after scaling)


## Next steps:
The models greatly improved the predictiveness of house prices (as seen above) but there are more factors that are likely to improve our predictiveness. These include:
- Comparing crime data vs. sale prices
- Comparing community school quality vs. sale prices
- Collecting data over more years, especially more recent data

For more information
Please contact the contributors to this analysis: 
Hatice Erdogan
Czarina Luna
Weston Shuken
Ross McKim

**Repository Structure:**

