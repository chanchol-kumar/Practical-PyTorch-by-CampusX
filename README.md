![PyTorch Logo](https://github.com/pytorch/pytorch/raw/main/docs/source/_static/img/pytorch-logo-dark.png)

# Practical-PyTorch-by-CampusX


# Neural Network Training Process
- **Forward Pass:**
Compute the output of the neural network given an input.
- **Calculate Loss:** 
Evaluate the performance of the network by calculating a loss function. 
- **Backward Pass:** 
Compute the gradients of the loss function with respect to the network parameters. 
- **Update Gradients:**
Adjust the parameters using an optimization algorithm (e.g., gradient descent) to minimize the loss. 



### Forward Pass Computation:

1. **Linear Transformation:**
   `z = w * x + b`

2. **Activation (Sigmoid Function):**
   `y_pred = σ(z) = 1 / (1 + exp(-z))`

3. **Loss Function (Binary Cross-Entropy Loss):**
   `L = -(y_target * log(y_pred) + (1 - y_target) * log(1 - y_pred))`