# DeepCover
Uncover Bugs in Deep Learning

DeepCover is a coverage-based bug finder for deep learning applications.
It is able to provide metrics for evaluating the robustness of a Deep Neural Network (DNN).
The basic idea of DeepCover is easy. For any neuron in the DNN, if its state changes,
there must be a cause for it: DeepCover aims to COVER a change and its immediate causes.
More details can be found in the paper [Testing Deep Neural Networks](https://arxiv.org/abs/1803.04792).

## To run the tool:
  These routine machine learning Python packages are needed and IBM CPLEX is used as the Linear Programming solver

