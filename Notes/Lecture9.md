# Neural Networks for Machine Learning - Geoffrey Hinton
## Lecture 9 Notes by pyh

### something about prevent **overfitting**
  * more data
  * the right model capacity
  * average the result from different models or *bagging data*
  * *Bayesian* Use a single neural network architecture, but average the predictions made by many different weight vectors.



### how to choose **Hyperparameter**？
  * divide data in to *train*,*validation*, and *test*.
  * N-fold cross-validation

![Screen Shot 2017-08-19 at 9.13.30 PM](https://i.loli.net/2017/08/19/5998398a4581e.png)


### *Bayesian* and *Maximum Likelihood*

![Screen Shot 2017-08-19 at 8.50.53 PM](https://i.loli.net/2017/08/19/59983624f162f.png)

P(D|W) : Given the W (that's what you choose), the probability that you can observe the data (which is already in your train set).

P(D): value of this term is not affected by which W you choose, so we usually ignore it.


P(W|D): the final goal of learning is to find a W that maximize the P(W|D).


### Regularization methods for Weight

Different regularization methods have different effects on the learning process. For example L2 regularization penalizes high weight values. L1 regularization penalizes weight values that do not equal zero. Adding noise to the weights during learning ensures that the learned hidden representations take extreme values. Sampling the hidden representations regularizes the network by pushing the hidden representation to be binary during the forward pass which limits the modeling capacity of the network.


### Incoming works
###### _Bayesian_ and _Information Theory_

And I will continue to explore a few days later, perhaps with the book *the methods for statistical learning* by Hang Li.
