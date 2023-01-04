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
p_hat = x/N  
To use normal: check N*p >5 and N*(1-p)>5   
m = Z-score * StandardError(binominal)  
m = Z-score * sqrt(p(1-p)/n)  
confidence interval = [p-m,p+m]  



