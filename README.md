# micrograd-karpathy
Gentle introduction to backprop and neural networks. From Andrej Karpathy's NN series

# Autograd
Efficiently and automatically compute gradients of mathematical expressions involving tensors with respect to weights of a neural network. Backpropagation allows us to iteratively tune a neural network's parameters (i.e. weights and biases of neurons) to minimize a loss function that measures the difference between the network's prediction and actual outputs. 

For large deep learning frameworks with complex expressions with tensors, autograd keeps track of the operation and the tensor's gradient with respect to the operation's inputs. Thus, autograd is able to compute the gradients of the entire expression by recursively applying the chain rule of differentiation. 