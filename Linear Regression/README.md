# Linear Regression
Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.
Basically, linear regression is a regression model used to predict the relationships between dependent output variables (Y) and independent input variables (X) in a linear fashion.
### Importance of Linear Regression
- Linear-regression models are relatively simple and provide an easy-to-interpret mathematical formula that can generate predictions. 
- Linear regression can be applied to various areas in business and academic study.
- Linear regression is a regression algorithm, meaning it generates continous outputs which can be used in many aspects today.
### Assumptions of Effective Linear Regression
- Linear relationship between the features and target: Linear regression assumes the linear relationship between the dependent and independent variables.
- Small or no multicollinearity between the features: Multicollinearity means high-correlation between the independent variables. Due to multicollinearity, it may difficult to find the true relationship between the predictors and target variables. Or we can say, it is difficult to determine which predictor variable is affecting the target variable and which is not. So, the model assumes either little or no multicollinearity between the features or independent variables.
- Homoscedasticity is a situation when the error term is the same for all the values of independent variables. With homoscedasticity, there should be no clear pattern distribution of data in the scatter plot.
- Normal distribution of error terms: Linear regression assumes that the error term should follow the normal distribution pattern. If error terms are not normally distributed, then confidence intervals will become either too wide or too narrow, which may cause difficulties in finding coefficients.It can be checked using the q-q plot. If the plot shows a straight line without any deviation, which means the error is normally distributed.
- No autocorrelations: The linear regression model assumes no autocorrelation in error terms. If there will be any correlation in the error term, then it will drastically reduce the accuracy of the model. Autocorrelation usually occurs if there is a dependency between residual errors.
### How to Make Sure the Data Meets Linear Regression Assumptions
Prior to conducting linear regression, it is essential to ensure that your data meets the necessary assumptions for analysis. These assumptions serve as prerequisites for applying the linear regression procedure.
Here’s how you can check for these assumptions:
1. The variables should be measured at a continuous level. Examples of continuous variables are time, sales, weight and test scores. 
2. Use a scatterplot to find out quickly if there is a linear relationship between those two variables.
3. The observations should be independent of each other (that is, there should be no dependency).
4. Your data should have no significant outliers. 
5. Check for homoscedasticity — a statistical concept in which the variances along the best-fit linear-regression line remain similar all through that line.
6. The residuals (errors) of the best-fit regression line follow normal distribution.
### Use Cases of linear Regression
1. Evaluating trends and sales estimates:
You can also use linear-regression analysis to try to predict a salesperson’s total yearly sales (the dependent variable) from independent variables such as age, education and years of experience.
2. Price Elasticity Analysis:
Changes in pricing often impact consumer behavior — and linear regression can help you analyze how. For instance, if the price of a particular product keeps changing, you can use regression analysis to see whether consumption drops as the price increases. What if consumption does not drop significantly as the price increases? At what price point do buyers stop purchasing the product? This information would be very helpful for leaders in a retail business.
3. Assess risk in an insurance company:
Linear regression techniques can be used to analyze risk. For example, an insurance company might have limited resources with which to investigate homeowners’ insurance claims; with linear regression, the company’s team can build a model for estimating claims costs. The analysis could help company leaders make important business decisions about what risks to take.
4. Sports analysis:
Linear regression isn’t always about business. It’s also important in sports. For instance, you might wonder if the number of games won by a basketball team in a season is related to the average number of points the team scores per game. A scatterplot indicates that these variables are linearly related. The number of games won and the average number of points scored by the opponent are also linearly related. These variables have a negative relationship. As the number of games won increases, the average number of points scored by the opponent decreases. With linear regression, you can model the relationship of these variables. A good model can be used to predict how many games teams will win.