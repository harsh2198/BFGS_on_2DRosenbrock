# Broyden-Fletcher-Goldfarb-Shanon optimizer evaluated on 2-D Rosenbrock function
<p style="font-size:18px;"> Learned the effectiveness of BFGS optimizer in finding the optimal solution of the Rosenbrock function, a widely-used test function for evaluating optimization algorithms. The BFGS algorithm is a quasi-Newton method that utilizes gradient information to update an approximation of the inverse Hessian matrix iteratively. BFGS algorithm is capable of accurately and quickly identifying the global minimum of the function. The convergence rate of the BFGS algorithm is influenced by the starting point and the initial Hessian approximation.
</p> <br>
##Function to be Optimised:
$f(\mathbf{x}) = \sum_{i=1}^{D-1} \left[ 100(x_{i+1} - x_i^2)^2 + (x_i - 1)^2 \right]$
Dimensions: D=2, $x_0$ = [-1.2,1]
