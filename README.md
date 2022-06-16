# MechaCar_Statistical_Analysis-

# Overview
Analysis of automotive sector using the R programming language. The project involved hypothesis testing and statistical analytics. 

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/99698846/173997352-c1555f13-09a1-47a5-9ccd-be1ddaee14fa.png)

- The Pr(>|t|) represents the probability of how each coefficient contributes to the (random) linear model. Results indicate a non-random amount of variance to the linear model of mpg (linear model).
- The slope of the linear model is not zero. 
- The linear model is considered relatively efficient in predicting the mpg of Mecha prototypes.

## Suspension Coil Summary Statistics

- The coils should not exceed 100 LBS per sq inch, per design specifications. 
- On a per lot basis, Lot 1 and Lot 2 are within the specifications with variances of 0.98 and 7.5 psi. Lot 3 is not within specifications at a variance of 170.3 psi.

## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/99698846/174001266-3c206eed-1482-41e0-9e66-7decfa475f0a.png)
- The p-value of .06 is below the common significance level. There is not sufficient evidence to reject the null hypothesis.

### Lot 1
![image](https://user-images.githubusercontent.com/99698846/174000098-4a85cc80-895b-44bf-ae2d-08783fd23d02.png)
- With p-value of 1, there is sufficient evidence to reject the null hypothesis.

### Lot 2
![image](https://user-images.githubusercontent.com/99698846/174001460-61ef6235-5963-4cc6-9c0e-8ef122f2bb2d.png)
- The p-value of .61 is below the common significance level. There is not sufficient evidence to reject the null hypothesis.

### Lot 3 
![image](https://user-images.githubusercontent.com/99698846/174001551-ad4d375c-5a30-4138-b545-be6e1a63a02d.png)
- The p-value of .04 is below the common significance level. There is not sufficient evidence to reject the null hypothesis.

## Study Design: MechaCar vs Competition
Comparing the performance of the MechaCar vs other vehicles, the following will be analyzed: 
- Time "0 to 60 mph" time,
- Brake Distance
- Fuel Economy (mpg)
- Power 
- Safety Rating 

## Null Hypothesis
Performance metrics will perform similar between the MechaCar and other vehicles. 

## Statistical Tests
A multiple linear regression can be conducted to analyze performance metrics of each vehicle, including the MechaCar. 
