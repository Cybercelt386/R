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

Lot one produces a p-value of 1 which means there is a direct coralation between the two variables with 100% of the change in one number being directly responcable for the change in the other a rather incredible statistic. Lot two has a p-value of .6 this is still highter than the .5 value we would expect to see from a statisticly significant number there fore there is a high liklyhood of a corralation between these numbers and not just random fluctuations. Lot three however has a p-value of .04 this is way below the expected .5 value and therefore this value is not statisticly significant. 
