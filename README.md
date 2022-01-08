# MechaCar_Statistical_Analysis

## Overview
For this assignment we were tasked with 4 deliverables.
1. Complete a linear regression to predict MPG
2. Complete summary statistics on Suspension Coils
3. Complete a T-Test on Suspension Coils
4. Design as study comparing the MechaCar to the Competition


## Linear Regression to Predict MGP
Based on the linear regression summary show below we are able to identify 2 of the variables/coefficients stand out as being statistically significate. Both vehicle_length and ground_clearance show a p-value of less than .05, meaning the results not random and we would not at this time be able to accept the null hypothesis.

We are also able to conclude that the slope for the linear model would not zero. If you were to look at the two statistically significant variables as noted above you can see the slope (estimate) is greater than 6 and has a p-value of 2.60e-12 leading to the conclusion that that our slope is not zero.

Another item we can identify from the linear model is more effective at predicting the mpg of MechaCar prototypes. The can be identified by looking at the r-squared value of .6825. Meaning that there is a 68.3% chance that future data points will fit this model.

![LM_Summary](https://user-images.githubusercontent.com/88597956/148660205-7e9991ba-82d6-4849-ae8d-ca9cbedc0ec9.png)

## Summary Statistics on Suspension Coils

For this deliverable, I created two summary stataistic dataframes looking at the suspension coil's PSI. One looked at all of the manuafacturing lots and the other grouped by the individual manufacturing lots. The design specification for the MechaCar suspension coils dictate the variance must not exceed 100 PSI. Based on the current data accross all manufacturing lots we could conclude that the they are meeting the required design specifications. When diving further into the data by grouping it by the manufacturing lot one can determine that Lots 1 and 2 are well within the design specification for variance sitting at .98 and 7.47 respectively . However, Lot 3 is far exceding the specifications outlined, sitting at a variance of 170.29. Images of the summar statistics are shown below.

**Total Summary**

![total_summary](https://user-images.githubusercontent.com/88597956/148661685-abb50196-691c-488b-a171-18a2f938f0a6.png)

**Lot Summary**

![lot_summary](https://user-images.githubusercontent.com/88597956/148661694-a89793be-f550-408d-82e4-c435de0af93e.png)

