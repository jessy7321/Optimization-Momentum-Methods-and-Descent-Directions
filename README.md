# Optimization-Momentum-Methods-and-Descent-Directions
A study on optimization techniques of Gradient Descent with Momentum for a specific convex function in consideration.

Traditionally, gradient descent updates take the form
<br>xk+1 = xk − αk∇F (xk). <br>We occasionally modify this by modifying the descent direction, whose rate is adjusted by α. 
<br><br>
Momentum Methods include an additional descent direction term, whose rate is adjusted by β.
<br>xk+1 = xk − αk∇F (xk) + βk(xk − xk−1)

<br>For a convex function: F(x) = 1/2 x^T Q x − x^T c
<br>(where x and c are real vectors of dimension D, and Q is a real symmetric D × D matrix):
<br>This is an attempt to understand optimization techniques at a deeper level by trying to optimize the above function. The project proceeds in stages listed below:


* Vanilla Gradient Descent (constant alpha)
* Optimized Gradient Descent (variable alpha)
* Vanilla Momentum (constant alpha, beta)
* Optimized Momentum (variable alpha, beta)
* Looking for a method with Better Direction
