Developing Data Products
========================================================
author: Dawit Mamo Zegeye
date: 22/08/2015

Body Mass Index (BMI) Calculator

========================================================

What is BMI?
The Body Mass Index (BMI) is a measure of body fat based on height and weight that applies to adult men and women. Regarding the BMI measure, the World Health Organization (WHO) proposes the following classification:

BMI <18.5 : Underweight
BMI [18.5-24.9] : Normal weight
BMI [25-29.9] : Overweight
BMI >=30 : Obesity

========================================================
How is it calculated?
There is a formula for calculating the BMI measure. The formula is the following:

BMI = weight(kg) / height(metres)2
Thus for the next example, the BMI will be:

```r
weight = 75
height = 1.8
BMI <- weight/height^2
BMI
```

```
[1] 23.14815
```
========================================================
For our example (weight=75 kg and height=1.80 m) the diagnostic would be:






```
Error in eval(expr, envir, enclos) : 
  could not find function "diagnostic_f"
```
