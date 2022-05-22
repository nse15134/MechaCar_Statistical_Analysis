# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
  ### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  The Vehicle Length and ground clearance will likely be the variables to provide a non-random amount of variance to the MPG values.  These both have a statistical significance on MPG
  ### Is the slope of the linear model considered to be zero? Why or why not?
  P-Value being equal to 5.35e-11 which allows us to reject our null hypothesis since it is well below .05%.  This helps us to conclude that the slope of the linear model is not 0
 ### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 71% of predictions will be determined by this model as we see an r-squared value of .71, allowing us to successfuly predict mpg effectively.
 
 ## Summary Statistics on Suspension Coils
 ### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
 
 Lot Summary:
 ![image](https://user-images.githubusercontent.com/98061420/169714886-c8161ea1-98d4-4f4c-b7ed-8144912ae14e.png)
 
 Total Summary:
 ![image](https://user-images.githubusercontent.com/98061420/169714904-f569646b-5046-4f2a-8838-916ef2ac6b6b.png)


Lot 1 and 2 meet that requirements to be under 1000 pounds per square inch.  Lot 3 has a much larger variance at 170.286.

## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/98061420/169715083-e3c143a9-366b-4a19-98ac-ae1d3e36c08d.png)

Lot 1 is equal to 1500, Lot 2 is equal to !500.2, and Lot 3 is equal to 1496.14.  Looking at the P-Values, we can begin to reject or not reject the null hypotheses.  
Lot 1 cannot reject the null hypothesis with a P-Value of 1.
Lot 2 cannot reject the null hypothesis with a P-Value of .61
Finally, Lot 3 can reject with a p-value of .04.


## Study Design: MechaCar vs Competition
We want to test the following metrics:
Safety Feature Rating: Independent Variable
Current Price (Selling): Dependent Variable
Drive Package : Independent Variable
Engine (Electric, Hybrid, Gasoline / Conventional): Independent Variable
Resale Value: Independent Variable
Average Annual Cost of ownership (Maintenance): Independent Variable
MPG (Gasoline Efficiency): Independent Variable

We can then look to to determine the null hypothesis:

Null Hypothesis is  'MechaCar is priced correctly based on its performance of key factors for its genre'
Alternative Hypothesis is 'MechaCar is NOT priced correctly based on performance of key factors for its genre.'

The statisical test would be: A multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the list selling price; which combination has the greatest impact on price.



 
  
