## Reproducing the results of  “Prediction of Pedestrian Speed With Artificial Neural Networks” by Tordeux et al.


The project is grounded on the research paper titled ”Prediction of Pedestrian Speed with Artificial
Neural Networks” by Todeux et al.. Their work incorporated several neural networks (NNs) to forecast
individual pedestrian speeds in two distinct scenarios - a bottleneck and a corridor. The accuracy of their
NNs was then evaluated against that of a classical model founded on Weidmann’s physical model [2]. Their
findings demonstrated that the NNs were adept at distinguishing between the two scenarios they were trained
on, providing more precise predictions than the traditional approach.
Our project aspires to partially reconstruct the NNs used by Todeux et al., and corroborate their findings.
To accomplish this, the exercise includes:

1. Preprocessing the data to make it compatible for NN training
2. Implementing the NN and fine-tuning its hyperparameters
3. Developing a classical FD-based model for subsequent comparison
