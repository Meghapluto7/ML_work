Regression Metric are used to check the performance of regression metrics.

1.Mean Absolute Error-it is the absolute error between atual point and predicted point and after taking average of all this error is MAE.
loss function
Formula=summation(i is equal to 1 to n)=(|yi-yi predicted|)/n

The MAE is loss and it shold be minimum. 

if outliers are there use MAE

Advantages:
1.the unit of MAE and y is same. 
2.Robust to outliers.can handle outlier.
Disadvantages:
1.Graph is not differenciable at 0.

2.Mean Squared Error-it gives squared value of error that is (yi-yipredicted)2
loss function
Formula=summation(i is equal to 1 to n)=((yi-yi predicted))/n
Advatages-
1.it is differentiable at all points 

if outliers are present try to avoide it.
Disadvantages
1.it squares the error so difficult to interpreate
2.Not robust to outliers

3.Root Mean Squared Error-it is root of MSE 
loss function
Formula=rootsquared(summation(i is equal to 1 to n)=((yi-yi predicted))/n) 
Advantages-
1.the unit is same as y so easy to interpreate
2.Not that robust to outliers

4.R2 square/coefficient of determination/goodness of function
1-(sum of squared error in regression line(ssr)/sum of squared error in mean line (ssm))
Formula=squared(summation(i is equal to 1 to n)=((yi-yi predicted))/n)regression line /squared(summation(i is equal to 1 to n)=((yi-yi predicted))/n)mean line

r2 square value lies between 0 to 1 and higher values are good  

r2 square will be negative when model is performing very bad 

if r2 square is 0.80 means  explain 80 of variance in output column is able to explained in output column

Disadvantages-
1.whenever we are adding new features values are always increasing so not able to differentiate mpact of features

5.Adjusted R2 square-
Formula=1-[((1-r2)(n-1))/(n-1-k)]
r2-normal r2 value
n-no of rows
k-independent variable 

if you are adding irrelevant column then r2 value decreases so its overcome disadvantage of r2 sqaure 

 
