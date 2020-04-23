---
layout: post
title: "Portfolio Optimization Notes"
date: 2020-04-22
---

### Goal: optimize a portfolio of Lending Club investments

Notation:
1. <img src="https://render.githubusercontent.com/render/math?math=x_0"> is the total amount we can invest ([equation hack](https://gist.github.com/a-rodin/fef3f543412d6e1ec5b6cf55bf197d7b))
1. there are _n_ assets
1. <img src="https://render.githubusercontent.com/render/math?math=x_i = w_i \times x_0"> is the investment in asset _i_, where <img src="https://render.githubusercontent.com/render/math?math=\sum w_i = 1">

I would like to put this into a [portfolio optimization](https://en.wikipedia.org/wiki/Portfolio_optimization) framework, however why diversify?
What is the optimization?

Sharpe ratio is a good measure.  

 <img src="https://render.githubusercontent.com/render/math?math=S(x) = \frac{r_x - R_f}{\text{stdev}(r_x)}">
 
 - <img src="https://render.githubusercontent.com/render/math?math=r_x"> = average rate of return (expected return)
 - <img src="https://render.githubusercontent.com/render/math?math=R_f"> = risk free rate of return (probably zero in a lending context)
 - <img src="https://render.githubusercontent.com/render/math?math=\text{stdev}(r_x)"> = standard deviation of rate of return (standard error)
 
 Big is good.
 
 This is exactly the inverse of the coefficient of variation.
