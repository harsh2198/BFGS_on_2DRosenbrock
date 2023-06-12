# Broyden-Fletcher-Goldfarb-Shanon optimizer evaluated on 2-D Rosenbrock function
Learned the effectiveness of BFGS optimizer in finding the optimal solution of the Rosenbrock function, a widely-used test function for evaluating optimization algorithms. The BFGS algorithm is a quasi-Newton method that utilizes gradient information to update an approximation of the inverse Hessian matrix iteratively. BFGS algorithm is capable of accurately and quickly identifying the global minimum of the function. The convergence rate of the BFGS algorithm is influenced by the starting point and the initial Hessian approximation. <br>
## Function to be Optimised:
$f(\mathbf{x}) = \sum_{i=1}^{D-1} \left[ 100(x_{i+1} - x_i^2)^2 + (x_i - 1)^2 \right]$ <br> Dimensions: D=2, $x_0$ = [-1.2,1]
<br>
## Optimal Solution:
<img width="570" alt="Screenshot 2023-06-12 at 12 46 34 PM" src="https://github.com/harsh2198/BFGS_on_2DRosenbrock/assets/49284471/b4b3ba5b-dcea-40c6-be9b-f45ed12a558b">
