# Neural Network Model of Semantic Cognition

In this notebook, we have implemented and analyze a neural network model of semantic cognition.
Semantic knowledge includes observations of which objects have which properties, and storage of these facts in long term
memory. It also includes the ability to generalize, or predict which properties apply to which objects although
they have not been directly observed.

This notebook explores a neural network model of semantic cognition developed by Rogers and McClelland
(R&M). R&M sought to model aspects of semantic cognition with a multi-layer neural network, which
contrasts with classic symbolic approaches for organizing semantic knowledge. They model the cognitive
development of semantic representation as gradient descent (the backpropgation algorithm), using a neural
network trained to map objects to their corresponding properties. R&M also modeled the deterioration of
semantic knowledge in dementia by adding noise to the learned representations.
