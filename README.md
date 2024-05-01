# Regularized-Cost-and-Gradient
The provided code demonstrates the implementation and computation of regularized cost functions and gradients for both linear regression and logistic regression. Regularization is a technique used to prevent overfitting by adding a penalty term to the loss function, which discourages overly complex models. In this context, the regularization term helps to control the complexity of the model by penalizing large parameter values.

For linear regression, the `compute_cost_linear_reg` function calculates the regularized cost function, incorporating a regularization term controlled by the hyperparameter lambda. Similarly, the `compute_gradient_linear_reg` function computes the gradients of the regularized cost function with respect to the model parameters w and b.

For logistic regression, the `compute_cost_logistic_reg` function computes the regularized cost function using the sigmoid activation function. The `compute_gradient_logistic_reg` function then calculates the gradients of the regularized cost function with respect to the model parameters w and b.

By incorporating regularization, these functions help to prevent overfitting and improve the generalization of the models to unseen data. The regularization term penalizes large parameter values, encouraging the model to favor simpler hypotheses and reducing the risk of fitting noise in the training data.
## Run over-fitting example
![e769375d-9177-48a7-a69a-cbd37b29d769](https://github.com/UMMY87/Regularized-Cost-and-Gradient/assets/117314436/8ae4195a-c514-466c-9d4d-3b20dfd6f146)
