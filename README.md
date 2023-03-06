# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="611" alt="Screen Shot 2023-03-03 at 7 22 36 PM" src="https://user-images.githubusercontent.com/44278585/223211738-7fcc8c74-d6dd-4181-bc6b-6b6a1d01dd49.png">

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 The vehicle length and the ground clearance 

2. Is the slope of the linear model considered to be zero? Why or why not?
No the slope is not zero, since the p-value is much smaller that the significance level of 0.05%

3. Does this linear model predict the mpg of MechaCar prototypes effectively? Why or why not?
Yes it does predict it effectively since the r-squared value is 0.7149.

## Summary statistics on Suspension Coils

1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The variance of the suspension coils is at 62.29356, which is below the 100 ponds per square inch requirement.

However when we look at the lots individually we see that Lot 3 has a variance which is way above the limit of 100 pounds per square inch as shown in the table below:

<img width="631" alt="Screen Shot 2023-03-04 at 2 19 17 PM" src="https://user-images.githubusercontent.com/44278585/223212225-6c9e3b1a-d940-4a26-9e45-0cce52886928.png">

## T-Tests on Suspension Coils

Below is the results of the T-Test across all manufacturing lots:

<img width="623" alt="Screen Shot 2023-03-06 at 2 01 09 PM" src="https://user-images.githubusercontent.com/44278585/223212277-1e9c0bb0-724f-4f1d-a45b-85e2dd1aff86.png">

Here we can see that the mean is 1498.78, and the p-value is 0.06. Here we can conclude that there is not enough evidence to reject the null hypothesis. 


Looking at the T-Tests for each individual lot, we get the following:

<img width="423" alt="Screen Shot 2023-03-06 at 2 06 29 PM" src="https://user-images.githubusercontent.com/44278585/223212334-f99cd392-7f5d-4cde-a359-64c3a89bc454.png">


<img width="407" alt="Screen Shot 2023-03-06 at 2 06 35 PM" src="https://user-images.githubusercontent.com/44278585/223212361-7c644065-34b0-417f-ac28-ab1afab2c471.png">


<img width="426" alt="Screen Shot 2023-03-06 at 2 06 41 PM" src="https://user-images.githubusercontent.com/44278585/223212375-2d96200b-06d4-487f-996d-e3dc09df972c.png">


##  Study Design: MechaCar vs Competition
One of the most common factors that people look into before buying a car would be the cost of buying and maintaining the car. In order to see how MechaCar would do against its competition we can create a statistical study by answering the following questions:

- What metric or metrics are you going to test?
Current/Selling price, MPG ( miles per gallon efficiency), Maintenance cost, Resale value, Engine type

- What is the null and alternative hypothesis?
The Null Hypothesis could be if the MechaCar model is priced correctly according to its direct competition in the market.
Alternative Hypothesis could be the MechaCar is priced higher or lower compared to competition. 

- What statistical test would you use to test the hypothesis?
We could use a multiple linear regression tests to check our hypothesis

- What data is needed to run the statistical test?
The data that would be needed would be the competitors data of similar cars, and factors of the car that are relevant in their selling price.
