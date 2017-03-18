# mnist-tensorflow-demo

Partial rewrite of sentdex's MNIST tensor flow demo. This removes all the copy-paste
wiring of layers together and instead loops over a list of layer sizes where
the hidden layer dimensions are capped on each end by the number of endpoint
and output nodes. I've also dropped his section entirely where a weights and
biases dictionary is and just created them as necessary while wiring up
the model.

See Sentdex's tutorial here:
https://pythonprogramming.net/machine-learning-tutorial-python-introduction/
