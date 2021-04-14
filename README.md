# sx_PromotionVsPrevention
---
## Part 1 comparing promotion and prevention in each group
* one promotion vs prevention in group 0
### H0: there is no significant difference between promotion and prevention values in group 0
### H1: Values in prevention are greater than promotion
t-test report
data:  value by group
t = -13.974, df = 473.71, p-value < 2.2e-16
alternative hypothesis: true difference in means is less than 0
95 percent confidence interval:
       -Inf -0.6289518
sample estimates:
mean in group 0.1 mean in group 0.2 
         3.640547          4.353594
* two promotion vs prevention in group 1
### H0: there is no significant difference between promotion and prevention values in group 1
### H1: Values in prevention are greater than promotion
t-test report
Welch Two Sample t-test

data:  values by group
t = -6.602, df = 474.41, p-value = 5.444e-11
alternative hypothesis: true difference in means is less than 0
95 percent confidence interval:
       -Inf -0.2845992
sample estimates:
mean in group 1.1 mean in group 1.2 
         3.809325          4.188606 
---
## Part 2 comparing group 0 and group 1 in each parts
* one group 0 vs group 1 in prevention
### H0: there is no significant difference between group 0 and group 1 in prevention
### H1: Values in group 0 are greater than group 1
t-test report
Welch Two Sample t-test

data:  Prevention by condition
t = 3.5194, df = 493.43, p-value = 0.0002363
alternative hypothesis: true difference in means is greater than 0
95 percent confidence interval:
 0.08773209        Inf
sample estimates:
mean in group 0 mean in group 1 
       4.353594        4.188606 
* two group 0 vs group 1 in promotion
### H0: there is no significant difference between condition 0 and condition 1 in promotion group
### H1: Values in condition 1 are greater than condition 0
t-test report
	Welch Two Sample t-test

data:  Promotion by condition
t = -2.7723, df = 499.84, p-value = 0.002887
alternative hypothesis: true difference in means is less than 0
95 percent confidence interval:
        -Inf -0.06845397
sample estimates:
mean in group 0 mean in group 1 
       3.640547        3.809325 
