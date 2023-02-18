#MechaCar Analysis

## Linear Regression to Predict MPG

Using multiple linear regression I created the model with miles per Gallon (MPG) as the dependant variable and tested the P_values and R-squared values. 


![MechaSummary](https://user-images.githubusercontent.com/111584967/218908242-bfb58124-1a86-4a6d-ae39-4efe087db8c5.PNG)


the p-value is 5.35e-11 

vehicle length, ground clearance, and vehicle weight(if threshold is 0.7149)  


## Summary Statistics on Suspension Coils
After fitting the model I ran a summary command on the model the following sumary statistics were produced.


![lot_summary](https://user-images.githubusercontent.com/111584967/218908573-0c70d182-6088-426e-839b-382c13af0aae.PNG)




## T-Tests on Suspension Coils

![lot1](https://user-images.githubusercontent.com/111584967/218909455-3f34ccf6-d822-49d2-983c-4aabcf701978.PNG)

![lot2](https://user-images.githubusercontent.com/111584967/218909472-9f714984-4284-4a3f-9a15-75f6b2b5035c.PNG)

![lot3](https://user-images.githubusercontent.com/111584967/218909511-56571089-7842-4fa1-937d-e9d5a28678f6.PNG)

Lot one produces a p-value of 1 which means there is not a direct coralation between the two variables with 100% chance of these being the result of random fluctuations therefore I accept the null hypothosis. Lot two has a p-value of .6 this is still highter than the .5 this is still too high with a 60% chance therefore once again I accept the null hypothosis. Lot three however has a p-value of .04 this one is below the 0.5 threshold with only a 4% chance of this being due to random fluctuations I therefore reject the nulll hypothosis and accept the alternate hypothosis and reconize that there is a statisical relationship between the two values.

## Study Design: MechaCar vs Competition
The metric(s) I will test is vehicle_weight and mpg.
The null hypothothis for this will determine whether there is a realtionship between vehicle weight and MPG (miles per gallon). 
If the p-values of mpg is greater than 0.5 than I accept the null hypothothis and there is no relationship between them and the results are due to random fluctuations. If the p-values of mpg is less than 0.5 I will reject the null hypothosis and accept the alternet hypothisis that there is in fact a statisical relationship between the two metrics. In order to test this I will run a two-sample t-test as we need to test the relationship of both values to each other.
The data needed will be thw two collumns from the MechaCar_mpg file. they will then be fitted into the t-test.

