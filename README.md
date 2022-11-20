# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/107777321/202927490-56086d49-8307-4002-9b9d-dfb973c653f7.png)

The summary indicates that vehicle length and ground clearance, as well as the intercept, are statistically less likely to provide a non-random amount of variance to the mpg values in the dataset. The p-value of our linear regression is much lower than the 0.05% significance level which means that we can reject the null hypothesis that the slope equals zero. The linear model has a r-squared value of 0.6825 which doesn't give us much confidence to suggest that the model can effectively predict mpg of Mecha car prototypes. Given the significance of the intercept in our linear model, we may have to transform or scale our significant features, vehicle length and ground clearance, to improve the predictive power of the model.

## Summary Statistics on Suspension Coils

### Total Lot Summary
![image](https://user-images.githubusercontent.com/107777321/202931910-751990c9-b555-4008-8581-37acb9d33b13.png)

### Summary by Lot
![image](https://user-images.githubusercontent.com/107777321/202931976-00088b14-1ced-4ac0-b057-8d31efb86214.png)

When looking at the overall results, we might assume that the current manufacturing data meets the design specifications. However, the current manufacturing data doesn't meet the design specifications because the variance of the suspension coil of Lot 3 exceeds 100 pounds per square inch.



