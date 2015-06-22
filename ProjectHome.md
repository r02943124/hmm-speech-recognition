Matlab code for recognizing spoken words. Create one folder for each word and place the training files inside. One hidden Markov model will be trained for each word.

The observable output from each hidden state is modeled as a multivariate Gaussian distribution with mean and covariance depending on the state. The forward algorithm is used for classification, and the Baum-Welch expectation-maximization algorithm is used for training. The approach is explained by L. R. Rabiner, "A tutorial on hidden Markov models and selected applications in speech recognition," Proceedings of the IEEE, vol. 77, pp. 257–286, Feb 1989.

Created by Håkon Sandsmark.