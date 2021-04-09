# Spline regression 

## 1. Data
The data for this demo is from this article Edwards, J. R., & Parry, M. E. (2018). On the use of spline regression in the study of congruence in organizational research. Organizational Research Methods, 21(1), 68-110. <br /> 
The link for the original data is http://public.kenan-flagler.unc.edu/faculty/edwardsj/index.htm <br /> 

I select some variables of job attributes: athh, athw, relh, relw, varh, varw, auth, autw, jobsat <br /> 
jobsat = job satisfaction; <br /> 
ath = authority;  <br /> 
rel = relationships; <br /> 
var = variety; <br /> 
aut = autonomy; <br /> 
h means actual job attribute <br /> 
w means desired job attribute <br /> 

## 2. Analysis 
Analysis is in the Rmd file (spline regression.Rmd) <br /> 

Block 1.1 and 1.2 (plot) include a simple piecewise regression y = a0 + a1x + a2w + a3xw, and W is a dummy variable that equals 0 when x(authority) is less than or equal to 3, and equals 1 when x is greater than 3. <br /> 

Block 1.3 contains plot of continuous piecewise regression <br /> 

Block 2.1 and 2.2 include the equivalent spline regression <br /> 
