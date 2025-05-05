
Topics: [[Topics/Statistics/Statistics]] [[Econometrics]] 

- Covariance, Correlation, Beta, independence  
	- $\rho$= $\frac {Cov(x,y)}{\sigma_x,\sigma_y}$ 
	- $Cov(x,y) = \rho \sigma_x \sigma_y$ = $E[XY]-E[X]E[Y]$ 
	- $\operatorname{Cov}(X+Y, Z)=\operatorname{Cov}(X, Z)+\operatorname{Cov}(Y, Z)$ 
	- $\operatorname{Cov}\left(\sum_{i=1}^m a_i X_i, \sum_{j=1}^n b_j Y_j\right)=\sum_{i=1}^m \sum_{j=1}^n a_i b_j \operatorname{Cov}\left(X_i, Y_j\right)$ 
	- $\beta$ = $\rho \frac{\sigma_y}{\sigma_x}$ = $\frac{Cov(Stock,Mkt)}{Var(Mkt)}$ = regression coefficient, x= mkt, y= stock
- Not correlate but dependent:   (correlation only measures ***linear*** correlation)
	- Y=1,-1,1,-1..
- Correlated but independent  
	- Not possible.
		- Indep => Correlated
		- $E[XY] = E[X]E[Y]$
		- $Cov(X,Y) = E[XY] - E[X]E[Y] =0$
		- $\rho = 0$ 
- Test for independence
	- Using JPT, see if P(A AND B)=P(A)P(B