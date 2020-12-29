## Variables
- `x` - Input
- `w` - Weights
- `b` - Bias
- `y` - Output
- `z` - `xw + b`

## Links
- https://en.wikipedia.org/wiki/Activation_function
- https://en.wikipedia.org/wiki/Universal_approximation_theorem
- https://en.wikipedia.org/wiki/Loss_function
- http://neuralnetworksanddeeplearning.com/chap2.html

## Note for capitalization
If any variable is capitalized, it is a tensor.

## Why do we need weights
We need weights to make sure our neural network is learning

## Why do we need bias
Biases are used to make sure that we have a non-zero value when input `x` is 0. 
For example, in `xw + b = z`
if `x = 0`. `b` will make sure that `z` is not zero.
Here, the value of `(x*w)` should surpass the value of `b` to have an effect.

## Why do we need activation function
We need to control the value of output variables in our neural network. For example: For classification problem, we may want output to be 0 or 1. To control the value of outupt variables, we need to apply an activation function.

## Activation function: `f(z)`
`z = xw + b`
Assuming that `f` is an activation function. The complete expression would be `f(z)` where `z` is the parameter.

The complete formula for the neuron's output would be `f(z) = y`

## Backpropagation
find a good tutorial i can't explain this

## Multi-Class Classification
Non-exclusive classes | Mutually Exclusive Classes
--------------------- | --------------------------
Data point can have multiple classes | Data point can have only 1 class
Output from neurons usually don't sum up to 1 | Output from neurons sum upto 1
`['Soft', 'fluffy', 'comfortable']` | `['red', 'green', 'blue']`
`[0.2, 0.6, 0.8]` | `[0.1, 0.3, 0.6]`
Sigmoid activation function is common | Softmax function is common

## Cost Functions
Cost functions help us figure out how well the model has predicted compared to the actual value. Some examples are Quadratic loss function and crossentropy.

## Gradient Descent
To minimize loss/cost.

## Adaptive Gradient Descent
Gradient descent but learning rate adapts. Adam optimizer is an example.

## Vanishing Gradient Descent (ReLU)
to write