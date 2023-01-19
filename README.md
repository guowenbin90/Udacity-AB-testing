# Udacity A/B testing

## Overview of A/B testing
### Business example
**Customer funnel**  
-Home page visits  
-Exploring the site  
-Create account  
-Complete course  

### Metric 
Click-through-probability = Unique visitors who click/Unique visitors to page

### Binomial Distribution
1. 2 types of outcomes  
-success  
-failure
2. Independent events
3. Identical distribution  
-P same for all

### Confidence level
[z-table](https://www.had2know.org/academics/normal-distribution-table-z-scores.html)  
p_hat = x/N  
To use normal: check N*p >5 and N*(1-p)>5   
m = Z-score * StandardError(binominal)  
m = Z-score * sqrt(p(1-p)/n)  
confidence interval = [p-m,p+m]  

### Size and Power
alpha = P(reject null | null true)  
beta = P(fail to reject | null false)  
1 - beta = sensitivity (80%)  
Small sample: alpha low, beta high  
Large sample: alpha high, beta low  
- [use this calculator](https://www.evanmiller.org/ab-testing/sample-size.html)

<img src="https://github.com/guowenbin90/Udacity-AB-test/blob/main/significance.png" width=40% height=40%>

## Policy and Ethics for Experiments
## Choosing and Characterizing Metrics
### Expanding Customer funnel
-Home page visits  
-Course list visits  
-Visits to course pages  
-Account created  
-Enrollment  
-Coaching use  
-Completion  
-Jobs  
### Techniques to gather additional data
1. User experience research (UER): eye-tracking  
2. Focus group: get feedback on hypothesis   
3. Survey  
### Metrics
### Variablity
## Design an Experiment
## Analyzing Results
## Final Project
