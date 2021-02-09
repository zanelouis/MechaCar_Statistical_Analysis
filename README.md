# MechaCar_Statistical_Analysis
## Study Design: MechaCar vs Competition
What are the variables and coefficients provided for a non-random amount of variance to the mpg values in the dataset?
Ground_clearance and vehicle_length had the most amount of random variance while vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. 
Is the slope of the linear model considered to be zero? Why or why not?
Our slope is not zero just by looking at the p-value, which is less than 0.05.
Does this linear model predict mpg of MechCar prototypes effectively? Why or why not?
Based on our R-squared value, roughly ~71% of the time the model will predict mpg values correctly. There are probably other factors that were not captured in the datasaet that contribute to the mpg variability of the MechCar prototypes.

## Summary Statistics on Suspension Coils
The design specifications for the MechCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
Lots 1 and 2 are both within design specifications and have nearly the same median and mean. Lot 3 shows the most variance and exceeds the manufacturers' specs.

## T-Tests on Suspension Coils
Lots 1 and 3 PSI values are not different from the population mean. Lot 2 has a p-value of .347 which means there is evidence that the suspension coil is different from the population mean. All t-tests can be seen below:
