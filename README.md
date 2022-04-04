# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Looking at the output from the linear regression, we can deduce the following:
1. Vehicle weight, spoiler angle, and All Wheel Drive (AWD) provide a non-random amount of variance within the dataset, as evidenced by their p-values.

2. The p-value for this model (p-value: 5.35e-11) is much smaller than the assumed significance level of 0.05%. Therefore, the null hypothesis is rejected, which further indcates that the slope of this linear model is not zero.

3. The linear model's r-squared value is 0.7149, which means that approximately, 71% of the time the predictions will be correct using this linear regression model.

ADD IMAGES HERE

## Summary Statistics on Suspension Coils

When looking at summary of all the lots, the variance of the coils is well within the 100 PSI variance requirement (62.3 PSI) of the design specifications.

When looking at the individual manufacturing lots, Lot 1 & Lot 2 have PSI variances well below the 100 PSI requirements. However, Lot 3 has a PSI variance of 170.3, which is above the design specifications.

ADD IMAGES HERE

## T-Tests on Suspension Coils

Using the T-test function, we can determine that the PSI across all manufacturing lots is NOT statistically different from the population mean of 1,500 poounds per square inch.

When looking at the individual manufacturing lots, Lot 1 and Lot 2 have a p-value that is less than the recommended 0.05, and thus their PSI is NOT statisticaly different from the population mean of 1,500 pounds per square inch.

However, Lot 3 has a p-value of 0.04, which indicates that it's PSI is statistically different from the population mean, and thus allowing us to reject the null hypothesis.

## Study Design: MechaCar vs Competition

A stastical study can be done to compare performance of teh MechaCar vehicles against performance of vehichles from other manufacturers.

The study would involve collecting data on MechaCar and its comparable models across several different manufacturers (Ford, Toyota, Honda, Tesla) over a period of last 5 years.

Metrics to be collecting and compared would include the following: 
- Independent Variables: Safety Rating, Type of Engine (Hybrid, Electric, Conventional), Average Annual Maintenance Cost, MPG
- Dependent Variable: Current Selling Price

Hypothesis:
- Null Hypothesis: MechaCar's current selling price represents fair market value based on its performance of certain key factors (safety raing, type of engine, average annual maintenance cost, and MPG) over the past 5 years.
- Alternative Hypothesis: MechaCar's current selling price DOES NOT represent fair market value based on its performance of certain key factors (safety raing, type of engine, average annual maintenance cost, and MPG) over the past 5 years.

Statistical Test:
The ANOVA test would be able to test if the means from multiple different samples are significantly similar or different. This means that the averages of different cars in these categories can be compared to the average of MecaCar. If the p-values are below the 0.05 threshold, then the MecaCar's selling price does represent a fair market value.