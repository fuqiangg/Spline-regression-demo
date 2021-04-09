# Spline regression 

## 1. Data
This demo data is from this this article Edwards, J. R., & Parry, M. E. (2018). On the use of spline regression in the study of congruence in organizational research. Organizational Research Methods, 21(1), 68-110.
The link for the original data is http://public.kenan-flagler.unc.edu/faculty/edwardsj/index.htm

I select some variables of job attributes: athh, athw, relh, relw, varh, varw, auth, autw, jobsat
jobsat = job satisfaction;
ath = authority; 
rel = relationships;
var = variety;
aut = autonomy;
h means actual job attribute
w means desired job attribute

## 2. Analysis 
Analysis is in the Rmd file (spline regression.Rmd)
Block 1.1 and 1.2 (plot) include a simple piecewise regression y = a0 + a1x + a2w + a3xw, and W is a dummy variable that equals 0 when x(authority) is less than or equal to 3, and equals 1 when x is greater than 3.
Block 1.3 contains plot of continuous piecewise regression
Block 2.1 and 2.2 include the equivalent spline regression
