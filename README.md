# DS6014 - Bayesian Machine Learning

Language types: Python

Note: many of these notebooks were produced on a remote operating system with pymc3 pre-installed. This package is required to run many of the sampling methods used, and is challenging to install on many computers.

### HW1

- Description: Utilizing Bayes Theorem to solve practical problems, reparameterizing conjugate priors to see the impact on posterior distributions, conjugate analysis. 

- Associated files: "HW1.ipynb" is my code notebook for this assignment. "HW1-ProbabilityReviewPriors.pdf" contains the problems for this assignment. 

### HW2

- Description: LDA/QDA Bayes optimal classifiers, Naive Bayes Classifier for edible/non-edible mushrooms dataset, Bayesian generalized least squares approach (regression model), and Bayesian network model sketches.

- Associated files: "Bayesian_Assignment 2_30SEP2021_Final.ipynb" is my code notebook. "HW2-ClassifiersRegression.pdf" contains the problems for this assignment.

### HW3

- Description: Gibbs Sampling, Markov Chains, pooled/unpooled/hierarchical models, Hamiltonian Monte Carlo sampling (NUTS), using WAIC for model selection.

- Associated files: "Keeley_HW3 P3_P5_complete.ipynb" contains solutions for problems 3 and 5, which involve Monte Carlo sampling and WAIC analysis respectively. "Keeley_HW3 P2_complete.ipynb" contains solution for problem 2, which involves Gibbs Sampling. "Keeley_HW3P4_complete.ipynb" contains solution for problem 4, which involves pooled/unpooled/hierarchical models using Monte Carlo sampling.

### HW4

- Description: Expectation-Maximization implementation of Gaussian Mixture Model to segment image, variational inference (primarily using ADVI) on datasets previously used for sampling, ELBO plots, forest plots

- Associated files: "HW4_P1_P2_final(1).ipynb" contains code solution for problems 1 and 2, involving imagery segmentation through gaussian mixture models. "HW4_P3_final(1).ipynb" contains code solution for problem 3, involving ADVI density estimation. "HW4_P4_final(2).ipynb" contains code solution for problem 4, involving visualization of ELBO plots and forest plots of ADVI estimation for heart disease classification. "HW4_P5_final(1).ipynb" contains code solution for problem 5, involving application of variational inference using ADVI optimization to estimation proportion of women using contraception in Bangladesh using a partial-pooled model.

### HW5

- Description: Bayesian approaches in LDA topic modeling for train crash reports, variational inference vs. sampling/conjugate priors, the benefits of Bayesian approaches in Deep Learning, and Hidden Markov Models to automate stock performance predictions

- Associated files: "Keeley_HW5_P1 _1_(2).ipynb" contains code solution for problem 1, involving applying Bayesian approaches to LDA topic modeling for train crash reports. It also discusses the benefits of variational inference over sampling and conjugate prior approaches. "Keeley_HW5_P3 _1_.ipynb" contains the solution to problem 3, discussing the benefits of using Bayesian approaches in neural networks. "Keeley_HW5_P4_adapted _1_.ipynb" contains a partial solution to problem 4, involving the use of Hidden Markov Models and Naive Bayes to automate stock selection.

## BayesFinalProject (1).ipynb

- Description: For our final project, our team decided to compare a new "autoencoding variational Bayes" (AEVB) approach to topic modeling, which offers several benefits to traditional Bayesian approaches to topic modeling (e.g. MCMC sampling, Gibbs sampling, etc.). We replicated the "ProdLDA" (AEVB) topic model proposed by "2017, Akash Srivastava and Charles Sutton," and compared the word content of topics produced by ProdLDA against the topics produced by traditional Bayesian approaches using a Jaccard similarity index. We used a Kaggle news article database as our data. Although AEVB appears to be a viable approach to topic model that reduces computational complexity, among other things, it did produce more dissimilar topics than the traditional Bayesian approaches.

- Associated files: "Bayes Final Project Report_12DEC2021.docx" contains the final writeup of our report. "BayesFinalProject (1).ipynb" contains our Python replication of ProdLDA, as well as comparisons of topic content produced by traditional Bayesian approaches.
