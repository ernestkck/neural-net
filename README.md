# COMP4660 Assignment: Neural network

### Classifying posed and genuine anger from observers' pupillary response using distinctiveness-based network pruning

Recent studies have shown that physiological signals of observers can predict the veracity of emotions better than the verbal response of the same individuals. We construct a simple feedforward neural network to classify observed genuine or posed anger from the pupillary responses of the observers. Pruning techniques are then used to improve the performance of the network, by identifying hidden neurons with similar functionality. We consider two different pruning methods, one based on the behaviour of the hidden neurons and the other based on the trained weight matrix. We conclude that only the distinctiveness of neuron output activation vectors was appropriate for pruning the network, which increased the test accuracy to 75%. We were not able to achieve the same accuracy (95%) in Chen et al.’s study. Nonetheless, it is considerably better than human judgement (60%).


Source file: anger (timeseries)/anger.ipynb
