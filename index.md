---
layout: post
title: Contents
---
These notes form a concise introductory course on deep generative models.
They are based on Stanford [CS236](https://deepgenerativemodels.github.io/), taught by [Stefano Ermon](http://cs.stanford.edu/~ermon/) and [Aditya Grover](http://aditya-grover.github.io/), and have been written by [Aditya Grover](http://aditya-grover.github.io/), with the [help](https://github.com/deepgenerativemodels/notes/commits/master) of many students and course staff.
{% marginnote 'mn-id-whatever' 'The notes are still **under construction**!
Although we have written up most of the material, you will probably find several typos. If you do, please let us know, or submit a pull request with your fixes to our [Github repository](https://github.com/deepgenerativemodels/notes).'%}
You too may help make these notes better by submitting your improvements to us via [Github](https://github.com/deepgenerativemodels/notes).


1. [Introduction](assets/files/introduction/)

2. [Autoregressive Models](assets/files/autoregressive/)

3. [Variational Autoencoders] Coming soon!

4. [Normalizing Flow Models] Coming soon!

5. [Generative Adversarial Networks] Coming soon!

6. [Energy-based models] Coming soon!




## Preliminaries

1. [Introduction](preliminaries/introduction/) What is .

2. [Review of probability theory](preliminaries/probabilityreview): Probability distributions. Conditional probability. Random variables.

3. [Examples of real-world applications](preliminaries/applications): Image denoising. RNA structure prediction. Syntactic analysis of sentences. Optical character recognition.

## Representation

1. [Bayesian networks](representation/directed/): Definitions. Representations via directed graphs. Independencies in directed models.

2. [Markov random fields](representation/undirected/): Undirected vs directed models. Independencies in undirected models. Conditional random fields.

## Inference

1. [Variable elimination](inference/ve/) The inference problem. Variable elimination. Complexity of inference.

2. [Belief propagation](inference/jt/): The junction tree algorithm. Exact inference in arbitrary graphs. Loopy Belief Propagation.

3. [MAP inference](inference/map/): Max-sum message passing. Graphcuts. Linear programming relaxations. Dual decomposition.

4. [Sampling-based inference](inference/sampling/): Monte-Carlo sampling. Importance sampling. Markov Chain Monte-Carlo. Applications in inference.

5. [Variational inference](inference/variational/): Variational lower bounds. Mean Field. Marginal polytope and its relaxations.

## Learning

1. [Learning in directed models](learning/directed/): Maximum likelihood estimation. Learning theory basics. Maximum likelihood estimators for Bayesian networks.

2. [Learning in undirected models](learning/undirected/): Exponential families. Maximum likelihood estimation with gradient descent. Learning in CRFs

3. [Learning in latent variable models](learning/latent/): Latent variable models. Gaussian mixture models. Expectation maximization.

4. [Bayesian learning](learning/bayesianlearning/): Bayesian paradigm. Conjugate priors. Examples.

5. [Structure learning](learning/structLearn/): Chow-Liu algorithm. Akaike information criterion. Bayesian information criterion. Bayesian structure learning.

## Bringing it all together

1. [The variational autoencoder](extras/vae): Deep generative models. The reparametrization trick. Learning latent visual representations.

2. List of further readings: Structured support vector machines. Bayesian non-parametrics.