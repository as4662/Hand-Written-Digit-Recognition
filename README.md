# Hand-Written-Digit-Recognition
We are implementing digit recogniton using tensorflow,taking hand-drawn 
images of the numbers 0-9 and build and train a neural network to recognize 
and predict the correct label for the digit displayed.
This model is implemented using Tensorflow implementation.Tensorflow 
models are built layer by layer. We specify a layer's output dimensions and this 
determines the next layer's input dimension.
Activation functions used in this neural network model are Relu activation 
function and linear activation function.Relu activation function is implemented 
in the input layer and the hidden layer.Linear activation function is used in 
output layer.
The ReLU provides a continuous linear relationship. Additionally it has an 'off' 
range where the output is zero. The "off" feature makes the ReLU a Non-Linear 
activation.
It is common because it is both simple to implement and effective at 
overcoming the limitations of other previously popular activation functions, 
such as Sigmoid and Tanh. Specifically, it is less susceptible to vanishing 
gradients that prevent deep models from being trained, although it can suffer 
from other problems like saturated or “dead” units. 
The linear activation function is also called “identity” (multiplied by 1.0) or “no 
activation.”
This is because the linear activation function does not change the weighted sum 
of the input in any way and instead returns the value directly.
A multiclass neural network generates N outputs. One output is selected as the 
predicted answer. In the output layer, a vector 𝐳 is generated by a linear function 
which is fed into a softmax function. The softmax function converts 𝐳 into a 
probability distribution as described below. After applying softmax, each output 
will be between 0 and 1 and the outputs will sum to 1. They can be interpreted 
as probabilities. The larger inputs to the softmax will correspond to larger 
output probabilities.
