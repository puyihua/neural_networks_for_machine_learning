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


They are sophisticated and intricate.

The best way master it is to revise the lecture 9 Page 19 again.

And I will continue to explore a few days later, perhaps with the book *the methods for statistical learning* by Hang Li.
