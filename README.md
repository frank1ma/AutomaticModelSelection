# Automatic Model Selection for Fully Connected Neural Networks.
Neural networks and deep learning are changing the way that artificial intelligence is being done. Efficiently choosing a suitable
network architecture and fine tuning its hyper-parameters for a specific dataset is a time-consuming task given the staggering
number of possible alternatives. In this paper, we address the problem of model selection by means of a fully automated
framework for efficiently selecting a neural network model for a selected task, whether it is classification or regression. The
algorithm, named Automatic Model Selection, is a modified micro-genetic algorithm that automatically and efficiently finds
the most suitable fully connected neural network model for a given dataset. The main contributions of this method are: a
simple, list based encoding for neural networks, which will be used as the genotype in our evolutionary algorithm, novel
crossover and mutation operators, the introduction of a fitness function that considers the accuracy of the neural network
and its complexity, and a method to measure the similarity between two neural networks. AMS is evaluated on two different
datasets. By comparing some models obtained with AMS to state-of-the-art models for each dataset we show that AMS
can automatically find efficient neural network models. Furthermore, AMS is computationally efficient and can make use of
distributed computing paradigms to further boost its performance.
