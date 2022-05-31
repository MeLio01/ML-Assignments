I Deep Learning
1. Implement the following operations (forward and backward pass)
(a) Matrix multiplication layer W X
(b) Bias addition layer
(c) Mean squared loss layer
(d) Soft max layer
(e) Sigmoid layer
(f) Cross entropy loss layer
2. Using the sklearn.load boston() function, obtain boston house pricing dataset.
Train a regression model using the operations implemented above. You need to
write a stochastic gradient descent function to train.
3. Load the iris dataset in sklearn. This data sets consists of 3 different types of
irises’ (Setosa, Versicolour, and Virginica) petal and sepal length, stored in a
150x4 numpy.ndarray. Using the operations implemented above create a multi-
class classifier (Cross entropy loss + soft max)
4. Create a Neural Network class. This class takes in list of Layer objects. It
also takes a loss object. You can also allow it to take a seed as input. The
seed is used for reproduciblity across runs. Each layer is characterized by its
activation function and count of output neuron. Examples of activation include
linear (W x + b), sigmoid, tanh etc.
5. Using the above create following networks with the following
• just one output neural with linear activation and least mean square loss.
(This is linear regression).
• two layers. Layer 1 with 13 output neurons with sigmoid activation. Layer
2 with one output neuron and linear activation. use mean squared loss
• three layers. Layer 1 with 13 output neurons with sigmoid activation.
Layer 2 with 13 output neurons and sigmoid activation. Layer 3 with one
output neuron and linear activation. use mean squared loss
Train this model on boston dataset using SGD.
6. Using the above create following networks with the following
• two layers. Layer 1 with 89 output neurons with tanh activation. Layer 2
with ten output neuron and sigmoid activation. use mean squared loss
• two layers. Layer 1 with 89 output neurons with tanh activation. Layer
2 with ten output neuron and linear activation. use softmax with cross
entropy loss.
Train this model on mnist (sklearn) dataset using SGD.
7. Implement the convolution layer for 1 channel input and (n¿=1) channel output.
Implement both forward and backward passes. Implement the flatten operation
8. (extra credit bonus:) generalize this for any number of input and any number
of output channel. Implement both forward and backward passes
9. Train this CNN on mnist dataset. Layer 1: Convolution layer with 16 out-
put channels+flatten+tanh activation. Layer 2: 10 output neuron with linear
activation. Softmax cross entropy loss
10. (extra credit bonus:) Implement the CNN layer in C++. Invoke this object via
python wrappers. Note any performance improvements.

  
II CalTech experiments
1. Replicate the experiment described here. https://youtu.be/EQWr3GGCdzw?t=889  
2. Replicate the experiment described here. https://youtu.be/EQWr3GGCdzw?t=1744  
