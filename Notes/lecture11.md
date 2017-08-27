# Neural Networks for Machine Learning - Geoffrey Hinton
## Lecture 11 Notes by pyh

Truth to be told, this lecture is, to some extent, intricate for me. Professor talked a lot about _Hopfield Network_, and introduced the conception about _Energy function_, _Memory_, _unlearing_, etc.

This kind of network seems to be very useful and magical, both physicians and biologics want explain it from their own perspective. It may be closely related to the mechanism that our brain use to memorize stuffs.

In lecture 11e, the Hopfield network with hidden units is used to __representation__, the new representation of the input data is a long binary vector that is consisted of the hidden node state with 1 means on and 0 means off.

In lecture 11d, to escape from poor local minima, the professor introduced the classical and well-known algorithm __stimulated annealing__. I think the stimulated annealing possess is a kind of Markov Chain model with a transformation matrix related to the 'temperature'.

At first, the temperature is high, the particles have abundant velocity so they can travel around the while space even thought there are some barriers. As the temperature goes down, the probability that particles move from low-valued point to high-valued point will decline drastically. So the particles, namely, the solutions will stay in the low-value point in a large probability.

Lecture 11e is about *Boltzmann Machine*.

*Markov Chain Monte Carlo* is involved in lecture 11d.
