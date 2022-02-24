# Basic predictor model-FF5

A basic financial predictor analysis model in R that gives an investment strategy of a long-short decile hedge portfolio that generates a decent alpha relative to the Fama-French 5-factor model (FF5). 

Based on the variables you have chosen for your predictor, an example of the following graphs will be shown:

## Statistics of predictor
![image](https://user-images.githubusercontent.com/42922621/155521691-80339e00-2451-46b0-be58-bda3c30ccaeb.png)

## T-test of coefficients
![image](https://user-images.githubusercontent.com/42922621/155522041-5c991010-05b3-4df3-b69b-6edb70741f7d.png)
- Regression output of future stock returns based on the predictor variable.
- Shows the p-value and determines if it is statistically significant at 99% confidence level.

## Strategy Performance
![image](https://user-images.githubusercontent.com/42922621/155522540-41831535-4777-4d0e-b7f3-d1769307fc82.png) ![image](https://user-images.githubusercontent.com/42922621/155522547-cca08430-8617-48c6-bc28-05393af1f46a.png)
- Generates a bar chart (of decile portfolio) and a time series graph based on the predictor which determines the alpha and if it can generate a profit.

## Strategy Alpha
![image](https://user-images.githubusercontent.com/42922621/155523241-7ce7dd4d-7573-4071-b20b-255ea91eec2b.png)
- Determines the predictor alpha compared to the Fama-French 5-factor model (FF5)
