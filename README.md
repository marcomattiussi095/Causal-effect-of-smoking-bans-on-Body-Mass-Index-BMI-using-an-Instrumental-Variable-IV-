# Causal effect of smoking bans on Body Mass Index (BMI) using an Instrumental Variable (IV)

## Overview
This research project was conducted as a hands-on experience with an IV at my graduate school. The papers explores the causal effect of smoking bans in indoor worksite places on the Body Mass Index. The analysis establishes a causal and significant negative effect on BMI. The data used in this research project are from the BRFSS database (year 1998-2006)

## Identification Issues
In estimating the causal effect of smoking on the Body Mass index (BMI), an OLS regression with BMI as dependent variable and smoking as an independent variable isn’t enough to conclude on causality. Three main identification issues threaten this conclusion: primarily, BMI could have an effect on smoking. One way to illustrate this reverse relationship could be explained by the satiating effect of nicotine to control low BMI. Another identification issue is the absence in the regression of a variable that affects smoking and has a causal effect on BMI. An example of confounding factor could be the prevalence of smoking culture, which would affect smoking and simultaneously have less emphasis on adopting healthy behaviors. This is referred to as Omitted Variable Bias. Finally, -in a lesser degree- since the data is self-reported, we might be concerned about measurement error, which could take the form of guilt regarding real nicotine intake levels or some form of denial, or inaccurate consumption estimation.

## Identification Method
