![Header](https://user-images.githubusercontent.com/88597956/148665908-8397c92c-f5c9-4a7b-a1d2-5aa94a7feabd.png)

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

![LM_Summary](https://user-images.githubusercontent.com/88597956/148665678-ee846b31-fe09-4a0c-b68b-86d86f28ee70.png)

## Summary Statistics on Suspension Coils

For this deliverable, I created two summary statistical dataframes looking at the suspension coil's PSI. One looked at all of the manufacturing lots and the other grouped by the individual manufacturing lots. The design specification for the MechaCar suspension coils dictate the variance must not exceed 100 PSI. Based on the current data across all manufacturing lots we could conclude that the they are meeting the required design specifications. When diving further into the data by grouping it by the manufacturing lot one can determine that Lots 1 and 2 are well within the design specification for variance sitting at .98 and 7.47 respectively . However, Lot 3 is far exceeding the specifications outlined, sitting at a variance of 170.29. Images of the summary statistics are shown below.

**Total Summary**

![total_summary](https://user-images.githubusercontent.com/88597956/148661685-abb50196-691c-488b-a171-18a2f938f0a6.png)

**Lot Summary**

![lot_summary](https://user-images.githubusercontent.com/88597956/148661694-a89793be-f550-408d-82e4-c435de0af93e.png)

## T-Tests on Suspension Coils
To determine if all manufacturing lots and each individual lot is statistically different from the mean population of 1500 PSI I conducted t-tests. 

Null Hypothesis: There is no statistical difference between the population mean and the individual lot means

Alternative Hypothesis: There is a statistical difference between the population mean and the individual lot means.

Based on the below t-tests, one can conclude that there is no statistical difference when looking at the population mean. The p-values for all tests are above the .05 significance level. There for we are unable to reject the null hypothesis at this time .

**Across All Manufacturing Lots**

![t-test1](https://user-images.githubusercontent.com/88597956/148665699-c8b39e26-8045-494a-81b2-1d79de257a3f.png)

**Lot 1**

![Lot1_t-test](https://user-images.githubusercontent.com/88597956/148665725-19a3fe84-0ce5-41e5-9d32-3a5d5946aa06.png)

**Lot 2**

![Lot2_t-test](https://user-images.githubusercontent.com/88597956/148665728-844bc5f0-4fe4-4942-a8ae-6c102e5b7195.png)

**Lot 3**

![Lot3_t-test](https://user-images.githubusercontent.com/88597956/148665753-89740956-3084-47d2-ae71-317d696cb1be.png)

## Study Design: MechaCar vs Competition
I would like to see MechaCar conduct a statistical study on the depreciation of their vehicals similat to that of their competitors. It is important for consumers to know that they are getting their moneys worth when purchasing a new car. It is also important for them to know that when it comes time for them to upgrade vehicles that they will be able to get top dollar when selling or trading-in. 

**Metrics:**
- Depreciation Rate over the life of the vehicle.

**Hypothesis:**
- Null Hypothesis: The rate of depreciation on MechaCars is equal to their competitors
- Alternative Hypothesis: The rate of depreciation on MechaCars is not equal to their competitors

**Statistical test:**
To complete this study, the analysts at MechaCar would want to use linear regression. as this would show you the depreciation over time. 

**Data:**
- Age 
- Mileage
- Condition
- Class
- Make
- Model 
