# MechaCar_Statistical_Analysis
## Linear Regression to predict MPG
[insert link to phote]
### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The following variables based upon their Pr(>|t|) score are unlikely to provide a non-random variance: the Intercept, Vehicle Length and Ground Clearance. With the Intercept having a high level of statistical significance, it means there are other variables and factors that contribute to the variation in mpg.

### Is the slope of the linear model considered to be zero? Why or why not?
The Slope is not considered to be zero. If there is no significant linear relationship, each dependent value would be determined by random chance and error. As seen in the question above and the data, there is a sigificant linear relationship, therefore our slop is not considered zero.

### Does this linear model predict mpg of MechaCar prototypes e ffectively? Why or why not?
The R-Squared value of 0.7149 indicates that it is an effective model to predict mpg, although it may be guilty of overfitting given the lack of significant variables (only vehicle length and ground clearance)

## Summary Statistics on Suspension Coil
[insert photo total summary]
In total the variance of the suspension coils meets the design specifications as seen in the Total Summary data. 
[Insert Lot Summary photo]
However, in the Lot Summary data we see that both Lots 1 and 2 have very low variance, while within the design specifications, but Lot 3, with a variance of over 220 falls why outside the requirement.

## T-Tests on Suspension Coils
[insert photo]
Overall our Suspension Coil T-test is statistically signicant and we would not reject the null hypothesis.
Within each lot, the p-value is less than 0.05, and we would reject our Null Hypothesis.

## Study Design: Mechacar vs. Competition
How does the MechaCars perform vs. the competion on: City/Hwy MPG; horsepower and safety; all versus price? We want to determine whether the MechaCar performs better on these metrics vs. the cost of the car, vs. its competition.
Metrics that will be measured are: Price, MPG-City, MPG-huighway and Horsepower.
Null hypothesis: There is no significant difference between the competition and the MechaCar.
Alternative Hypothesis: there is a significant differecne between the competition and the MechaCar.
I will need the following metrics for each competitor and the MechaCar: Price, HorsePower, MPG-City, MPG-Highway. I will run the following tests:
Chi Square Test - deterimine frequency between groups.
Two Sample T-Tests - Is there a difference between the sample groups?
Anova sample for the two groups.

