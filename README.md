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

## T-Tests on Suspension Coils

### Total Sample T-Test
![image](https://user-images.githubusercontent.com/107777321/202932915-6a7936e9-ac18-46e0-adfc-6348451ca1ee.png)
The p-value for the t-test of the overall sample is 0.06028 which puts it right above the significance level. This means that we do not have enough evidence to reject the null hypothesis and that the population and sample means are statistically similar.

### T-tests by Lot
![image](https://user-images.githubusercontent.com/107777321/202934418-2895ea88-eeb6-44c2-ba3d-e224e7001dc9.png)
The p-value for the t-test of the sample data from lot 1 and 2 is 1 and 0.6072 respectively which means that we do not have enough evidence to reject the null hypothesis and that the population and sample means are statistically similar for these lots. The p-value for the t-test of the sample data for lot 3 is 0.04168 which suggests that we have enough evidence to reject the null and that the population and sample means are statistically different.

## Study Design: MechaCar vs Competition
To continue evaluating the performance of MechaCars versus other competitors, we can run an analysis that compares the costs, miles per gallon, and safety rating of other companies. The null hypothesis would be that MechaCars perform the same as the average competitor in affordability, safety, and efficiency. The alternative hypothesis would be that MechaCars performs better than the average competitor in affordability, safety, and efficiency. We would run an ANOVA statistical test to determine whether there are statistical differences for each metric. In order to run this test, we would need data from other similar competitors that contain their safety ratings, miles per gallon, and cost.

