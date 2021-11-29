# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle Length and Vehicle Ground Clearance

#### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the model is not zero because the value p-value is 5.35e-11 which is very small than the significance level of 0.05%.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model predicts (r-squared value = 71%) of the mpg predictions. 

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part1.JPG)





## Summary Statistics on Suspension Coils

#### Total Summary

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part2-Total_Summary.JPG)

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part2-Total_Summary.JPG)

#### Lot Summary

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part2-lot_summary.JPG)

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part2-lot_summary_plot.JPG)


#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The entire population data variance is 62.29 PSI which is within 100 PSI as per design specifications. 
However, when analyzing seperately lot 3 falls outside of the specification because the variance is 170.29 PSI. Lot 1 and Lot 2 are within limits.





## T-Tests on Suspension Coils

#### T-Tests Results

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part3.JPG)

All manufacturing lots are at a mean of 1498.78 pounds compared to individually Lot#1 which is 1500, Lot#2 which is 1500.2 and lot#3 which is 1496.14 pounds. There is not much of difference between the results except for lot#3 where the p-value is 0.04168 due to which we have to reject the null hypothesis for Lot#3. 


## Design a Study Comparing the MechaCar to the Competition
	
#### What metric or metrics are you going to test?
- MPG or MPe
- Annual Cost of ownership
- Current Price
- Resale Value
- Safety feature rating

#### What is the null hypothesis or alternative hypothesis?
- Null: Car being optimally priced based on the performance
- Alternative: Car not being priced compared to its competition

#### What statistical test would you use to test the hypothesis? And why? What data is needed to run the statistical test?
- Multiple linear regression would be used because multiple data sets would be analyzed to find the correlation
- Price and dependent variables that may impact the price