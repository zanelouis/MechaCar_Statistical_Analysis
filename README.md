# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
  To summarize, ground clearance and vehicle length had the most amount of random variance while vehicle weight, spoiler_angle & AWD provided a non-random amount of variance to the mpg values in the dataset. Our slope is not at zero as the p-value was less than 0.05. Roughly ~71% of the time this model will predict mpg values correctly based on our R-squared value and factors other than those captured in the datasaet will likely contribute to the mpg variability of the MechaCar prototypes.

![summary](https://user-images.githubusercontent.com/71358697/107325293-604c1100-6a5e-11eb-94cc-f6042a37c28f.png)

## Summary Statistics on Suspension Coils
  The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. While Lots 1 and 2 are both within design specifications and have nearly the same median and mean, Lot 3 shows the most variance and actually exceeds the manufacturers' specs.

## T-Tests on Suspension Coils
  Lot 2 has a p-value of .347 which means that there is evidence the suspension coil is different from the population mean. Lots 1 and 3 have PSI values that are similar to the population mean. 

## Study Design: MechaCar vs Competition
  When buying a car, one metric often used is how much horsepower the car has. In fact, three factors that go into consumer decision making are horsepower, engine size and miles per gallon. We can prove this in a study that compares MechaCar with its competiton. We can make a null hypothesis stating that it is not different from the competition and by using our t-test with collecting data from different types of competitor vehicles, we can compare the population of all types of competitor vehicles.

![t-test](https://user-images.githubusercontent.com/71358697/107325294-60e4a780-6a5e-11eb-8fb2-1bacb4a4777c.png)
