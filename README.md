# END3

### What is a neural network neuron?

The brain consists of cells called neurons which pass on electrical signals thrrough connection called synapses. These electrical signals pass on information through the entire nervous system. Similarly in the artificial neural network neurons act as non linear functions which transforms a set of input values to output. Different input recieve different weights based on their relative importance.

### What is the use of the learning rate?

The term Learning rate comes from an algorithm called Gradient descent. During the e3xecution of the algorithm we need to reduce or increase the weights based on 2 factors, the current derivative and the learning rates. Lowering the learning rate will result in lower chnage in weight. Time taken to converge to the solution (local minima) is inversely proportional to the learning rate.

### How are weights initialized?

There can be multiple ways where weights can be distributed. One possible way is to initialize them randomly. Studies have shown that random initilization leads to a faster convergence to the solution.

### What is "loss" in a neural network?

For creating a neural network for a particular problem we should start with defining a Loss function which determines what is the penalty we give to the network for misclassification so that it learns what not to do. In an ideal scenario the loss function's value should be 0. When we train the model, it learns how to reduce its Losses based on the loss function. For eg. A loss function can be RMSE of all the classifications.

### What is the "chain rule" in gradient flow?

