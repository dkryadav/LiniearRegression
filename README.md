# LiniearRegression
Linear regression is a supervised learining algorithm used when target / dependent variable continues real number. It establishes relationship between dependent variable  y  and one or more independent variable  x  using best fit line. It work on the principle of ordinary least square  (OLS)  / Mean square errror  (MSE) . In statistics ols is method to estimated unkown parameter of linear regression function, it's goal is to minimize sum of square difference between observed dependent variable in the given data set and those predicted by linear regression fuction.


We will use  xi  to denote the independent variable and  yiyi  to denote dependent variable. A pair of  (xi,yi)(xi,yi)  is called training example. The subscripe  ii  in the notation is simply index into the training set. We have  mm  training example then  i=1,2,3,...mi=1,2,3,...m .

The goal of supervised learning is to learn a hypothesis function  hh , for a given training set that can used to estimate  yy  based on  xx . So hypothesis fuction represented as

hθ(xi)=θ0+θ1xi
hθ(xi)=θ0+θ1xi
 

θ0,θ1θ0,θ1  are parameter of hypothesis.This is equation for Simple / Univariate Linear regression.

For Multiple Linear regression more than one independent variable exit then we will use  xijxij  to denote indepedent variable and  yiyi  to denote dependent variable. We have  nn  independent variable then  j=1,2,3.....nj=1,2,3.....n . The hypothesis function represented as

hθ(xi)=θ0+θ1xi1+θ2xi2+.....θjxij......θnxmn
hθ(xi)=θ0+θ1xi1+θ2xi2+.....θjxij......θnxmn
 
θ0,θ1,....θj....θnθ0,θ1,....θj....θn  are parameter of hypothesis,  mm  Number of training exaples,  nn  Number of independent variable,  xijxij  is  ithith  training exaple of  jthjth  feature.
