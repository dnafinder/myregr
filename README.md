# myregr
This function computes a least-square linear regression suppling several output information.<br/>

Syntax: 	myregr(x,y)
     
    Inputs:
          X - Array of the independent variable 
          Y - Dependent variable. If Y is a matrix, the i-th Y row is a
          repeated measure of i-th X point. The mean value will be used
          verbose - Flag to display all information (default=1)
    Outputs:
          - Slope with standard error an 95% C.I.
          - Intercept with standard error an 95% C.I.
          - Pearson's Correlation coefficient with 95% C.I. and its
            adjusted form (depending on the elements of X and Y arrays)
          - Spearman's Correlation coefficient
          - Regression Standard Error
          - Total Variability
          - Variability due to regression
          - Residual Variability
          - Student's t-Test on Slope (to check if slope=0)
          - Student's t-Test on Intercept (to check if intercept=0)
          - Modified Levene's test for homoschedasticity of residuals
          - Power of the regression
          - Deming's regeression
          - a plot with:
               o Data points
               o Least squares regression line
               o Red dotted lines: 95% Confidence interval of regression
               o Green dotted lines: 95% Confidence interval of new y 
                                      evaluation using this regression.
          - Residuals plot

SEE also myregrinv, myregrcomp

           Created by Giuseppe Cardillo
           giuseppe.cardillo-edta@poste.it

To cite this file, this would be an appropriate format:
Cardillo G. (2007) MyRegression: a simple function on LS linear regression with many informative outputs. 
http://www.mathworks.com/matlabcentral/fileexchange/15473
