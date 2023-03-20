# UsedCellPhone_PricePrediction

Explored the dataset of a company that specializes in the reselling of used and refurbished devices. The objective of this project was to determine the future price of used phones and identify the factors that significantly influence them. A linear regression model was used to determine the projected cost of used phones. One-Hot encoding was used for categorical values. Log transformation was used to correct distribution plots. Outliers were converted to 1.5x the third and first quartiles according to the side of whiskers. A linear regression model was made with statsmodels.api and dealt with multicollinearity using variance inflation factors(VIF). Deleted unnecessary variables determined through the p-value. It was tested for linearity, independence, and normality—determined homoscedasticity through the Goldfeld Quandt test.
