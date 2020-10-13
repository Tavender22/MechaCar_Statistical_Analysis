# MechaCar_Statistical_Analysis
##Module 15 challenge: Deliverable 1
[insert link to phote]
### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The following variables based upon their Pr(>|t|) score are unlikely to provide a non-random variance: the Intercept, Vehicle Length and Ground Clearance. With the Intercept having a high level of statistical significance, it means there are other variables and factors that contribute to the variation in mpg.

### Is the slope of the linear model considered to be zero? Why or why not?
The Slope is not considered to be zero. If there is no significant linear relationship, each dependent value would be determined by random chance and error. As seen in the question above and the data, there is a sigificant linear relationship, therefore our slop is not considered zero.

### Does this linear model predict mpg of MechaCar prototypes e ffectively? Why or why not?
The R-Squared value of 0.7149 indicates that it is an effective model to predict mpg, although it may be guilty of overfitting given the lack of significant variables (only vehicle length and ground clearance)

