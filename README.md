# ML-study-Andrew-Ng
___
## catalog
* [First week](#Firstweek)
* [Second week](#Secondweek)
___
## Firstweek
### some definition:
	supervise & unsupervise
	regressive & classification
### important:
	Gradient decent
### also:
	sth about matrix:add/scolar multiplicative/matrix multiplicative
## Secondweek
### multiple features
	feature scaling&mena normalization
	debugging:can`t converge-> smaller alpha
	features:1 proper,eg:size=width*length;2 polynomial regression:quadratic/cubic...
	normal equation
[matlab-doc][matlab]
## Thirdweek
classification problem:logistic regression(contrast to linear regression)
g(z)
hypothesis:h(x)=g(sita*x)
cost function:  
<a href="https://www.codecogs.com/eqnedit.php?latex=cost(h_{\theta&space;}(x)),y)=\begin{Bmatrix}&space;-log(h_{\theta&space;}(x)),y=1\\&space;-log(1-h_{\theta&space;}(x)),y=0&space;\end{Bmatrix}" target="_blank"><img src="https://latex.codecogs.com/png.latex?cost(h_{\theta&space;}(x)),y)=\begin{Bmatrix}&space;-log(h_{\theta&space;}(x)),y=1\\&space;-log(1-h_{\theta&space;}(x)),y=0&space;\end{Bmatrix}" title="cost(h_{\theta }(x)),y)=\begin{Bmatrix} -log(h_{\theta }(x)),y=1\\ -log(1-h_{\theta }(x)),y=0 \end{Bmatrix}" /></a>  
<a href="https://www.codecogs.com/eqnedit.php?latex=cost({h_{\theta}(x),y})=-ylog(h_{\theta}(x))-(1-y)log(1-h_{\theta}(x))" target="_blank"><img src="https://latex.codecogs.com/png.latex?cost({h_{\theta}(x),y})=-ylog(h_{\theta}(x))-(1-y)log(1-h_{\theta}(x))" title="cost({h_{\theta}(x),y})=-ylog(h_{\theta}(x))-(1-y)log(1-h_{\theta}(x))" /></a>  
<a href="https://www.codecogs.com/eqnedit.php?latex=^{J_{\theta}=\frac{1}{m}\sum_{i=1}^{m}cost({h_{\theta}(x),y)}}" target="_blank"><img src="https://latex.codecogs.com/png.latex?^{J_{\theta}=\frac{1}{m}\sum_{i=1}^{m}cost({h_{\theta}(x),y)}}" title="^{J_{\theta}=\frac{1}{m}\sum_{i=1}^{m}cost({h_{\theta}(x),y)}}" /></a>  

|algorithm|advantage|disadvantage
|---|---|---
|gradient reduce|
|conjugate gradient|without alpha,faster|complex
|BFGS|without alpha,faster|complex
|L-BFGS|without alpha,faster|complex
-------
[matlab]:http://cn.mathworks.com/help/matlab/?refresh=true
