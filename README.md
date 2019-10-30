
This is the R Simulation code for the DLSA method.

Please run 'main.sh' to obtain the Example 1--Example 5.

## 1. Distributed LSA
 - main.R: main demo code, which runs the distributed logistic regression using ALasso penalty
 - wlse_func: five regressions with DLSA implementation
 - dlsa_alasso_func: shrinkage DLSA estimation
 - func_others: other functions, e.g., output function, format function and others.
 - simulator: simulate data in local workers

## 2. Compare with CSL method 
CSL method: proposed by Jordan and Yang (2019, JASA) [in the file comparison]
 - dlsa_compare.R: main demo code, which runs the distributed logistic regression and compares with CSL method
 - compare_func.R: functions which implement CSL method
 
## 3. Spark implementation
See https://github.com/feng-li/dlsa for more details.