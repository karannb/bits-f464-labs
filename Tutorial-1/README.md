## Tutorial on Numeric Prediction.

Additional Note - <br>
In question 5, we derived update rules for a model being fit using the Least Squares Cost function, and from question 9, we know that under the assumption of independent and normally distributed errors, the Maximum Likelihood Estimate (MLE) is the estimate we get by minimizing Least Squares. However, for a class of functions, called the <a href="https://en.wikipedia.org/wiki/Exponential_family">exponential family</a> (of which Normal Distribution is a part), under similar assumptions, all have the same gradient update rules! <br>
It won't hurt to try out and see this for yourself for the Possion Distribution, i.e., assume <br>
$$p(y_i|x_i) \sim Poisson(\lambda)$$
OR <br>
$$p(y_i|x_i) = \frac{\lambda^{y_i}*e^{-\lambda}}{y_i!}$$
where $\lambda = e^{a + b*x_i}$.
You can refer to cs229's <a href="https://youtu.be/iZTeva0WSTQ?si=sZVZeiaRc5fgwIvD&t=2899">Lecture 4</a> (specifically where I have started it), for details on why I parametrized $\lambda$ as I did. 
