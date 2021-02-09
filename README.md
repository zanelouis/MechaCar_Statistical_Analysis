# MechaCar_Statistical_Analysis
R-programming , tidyverse, ggplot2, Statistical Tests, Hypothesis Testing, A/B Testing

## Linear Regression to Predict MPG
  To summarize, ground clearance and vehicle length have the most amount of random variance while vehicle weight, spoiler_angle & AWD provided a non-random amount of variance to the mpg values in the dataset. Our slope is not at zero as the p-value was less than 0.05. Roughly ~71% of the time this model will predict mpg values correctly based on our R-squared value and factors other than those captured in the datasaet will likely contribute to the mpg variability of the MechaCar prototypes.

![summary](https://user-images.githubusercontent.com/71358697/107325293-604c1100-6a5e-11eb-94cc-f6042a37c28f.png)

## Summary Statistics on Suspension Coils
  The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. While Lots 1 and 2 are both within design specifications and have nearly the same median and mean, Lot 3 shows the most variance and actually exceeds the manufacturers' specs. Based on the high standard deviation of ~7.89 the dataset is spread out and has a normal distribution with almost zero skewness.

![summ](https://user-images.githubusercontent.com/71358697/107325610-e7998480-6a5e-11eb-9a36-7da38d7c6935.png)

## T-Tests on Suspension Coils
  The mean of the hypothesized, potential population dataset is given as 1,500 pounds per inch. Lot 3 has a p-value of 0.04168 while Lots 1 and 2 have p-values between 0.6 - 1.0 and were found to have a normal distribution.

## Study Design: MechaCar vs Competition
  When buying a car, one metric often used is how much horsepower the car has. In fact, three factors that go into consumer decision making are horsepower, engine size and miles per gallon. We can prove this in a study that compares MechaCar with its competiton. We can make a null hypothesis stating that it is not different from the competition and by using our t-test with collecting data from different types of competitor vehicles, we can compare the population of all types of competitor vehicles.

![t-test](https://user-images.githubusercontent.com/71358697/107325294-60e4a780-6a5e-11eb-8fb2-1bacb4a4777c.png)
