GRADIENT DESCENT

AI-Based Cubic Equation Solver Using Stochastic Gradient Descent (SGD) and ReLU

This solver finds roots for cubic equations in the form 
𝑎𝑥3+𝑏𝑥2+𝑐𝑥+𝑑=0ax 3 +bx 2 +cx+d=0, where 𝑎a, 𝑏b, 𝑐c, and 𝑑 are integers. 
It uses machine learning techniques like Stochastic Gradient Descent (SGD) for optimization and the Rectified Linear Unit (ReLU) activation function to handle non-linearity.

Key Features:
SGD Optimization:
The solver minimizes the error between the predicted and actual roots by iteratively adjusting 
x using SGD, an efficient method for finding solutions in complex problems.

ReLU Activation Function:
ReLU, defined as 𝑓(𝑥)=max(0,𝑥)
f(x)=max(0,x), introduces non-linearity and prevents the model from getting stuck in local minima, improving convergence.

Training Process:
The solver initializes coefficients and iteratively adjusts 
x using SGD and ReLU until the equation equals approximately zero.
