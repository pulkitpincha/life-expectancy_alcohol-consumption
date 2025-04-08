# life-expectancy_alcohol-consumption

Dataset: https://www.kaggle.com/datasets/thedevastator/relationship-between-alcohol-consumption-and-lif?select=lifeexpectancy-verbose.csv

## Analyzing life-expectancy in relation to alcohol consumption

This dataset contains information of the alcohol consumption, life-expectancy as well as a 
few other factors like income and sex from different countries around the world. It will help 
us draw a connection between life-expectancy and average alcohol consumption of the 
population in different countries.

# Research Questions:

1. Does alcohol consumption have an impact on the life-expectancy of people?
2. What are the top countries in terms of alcohol consumption as well as the least life- 
expectancy?

## The independent variables in the dataset are:

- GHO Code
- GHO Display
- Publish State Code
- Publish State Display
- Year Code
- Year Display
- Region Code
- Region Display
- World Bank Income Group
- Group Code
- World Bank Income Group Display
- Country Code
- Country Display
- Sex Code
- Sex Display
- Country
- Beer servings
- Spirit servings
- Wine servings
- Total litres of pure alcohol

**The dependent variable** is the life-expectancy of people in each country. The goal is to find out the relationship between the alcohol consumption and life-expectancy in each country.

## Added Variable:

Continent Display: This variable is a group of many different countries that fall under the 
same continents.

# Procedure:

To begin the making of the model, it had to start with make dummy variables for the 
categorical ones as well as the new variable that was added into the dataset. Then making a 
Linear Regression Model to find the significant variables, being; Income Type, Sex, 
Continent, Total Litres of Alcohol, and Year Recorded. The model was then measured using 
VIF scores of the variables, and RMSE was also calculated. Next a Regression Tree model 
was made with the significant variables and was measured using RMSE and MAPE.

After this the data was split into Test and Train datasets, and another Linear Regression 
model was made and RMSE was calculated and graphs were plotted to see the fitting of the 
model in the dataset. Next another Regression Tree model was made and RMSE and MAPE 
were recorded for it likewise.

# Final Result:

In the end, we can see that the Linear Regression model is better as it has a RMSE score of 
21.83 which is lower than that of the Regression Tree Model with an RMSE of 22.08 and a 
MAPE score of 0.687.
The Linear Regression Model also tells us just how much each variable’s significance to life 
expectancy is; which can help in possibly increasing people’s expected lifespans.
