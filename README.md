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

#### Lot Summary

![](https://github.com/c3crocks/MechaCar_Statistical_Analysis/blob/main/Images/Part2-lot_summary.JPG)



#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The entire population data variance is 62.29 PSI which is within 100 PSI as per design specifications. 
However, when analyzing seperately lot 3 falls outside of the specification because the variance is 170.29 PSI. Lot 1 and Lot 2 are within limits.