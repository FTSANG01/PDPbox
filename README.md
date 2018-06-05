
# PDPbox
[![PyPI version](https://badge.fury.io/py/PDPbox.svg)](https://badge.fury.io/py/PDPbox)

python partial dependence plot toolbox

## Motivation

This repository is inspired by ICEbox. The goal is to visualize the impact of certain features towards model
prediction for any supervised learning algorithm. (now support all scikit-learn algorithms)


## The common headache

When using black box machine learning algorithms like random forest and boosting, it is hard to understand the
relations between predictors and model outcome.

For example, in terms of random forest, all we get is the feature importance.
Although we can know which feature is significantly influencing the outcome based on the importance
calculation, it really sucks that we don’t know in which direction it is influencing. And in most of the real cases,
the effect is non-monotonic.

We need some powerful tools to help understanding the complex relations
between predictors and model prediction.


## Highlight

1. Helper functions for visualizing target distribution as well as prediction distribution.
2. Proper way to handle one-hot encoding features.
3. Solution for handling complex mutual dependency among features.
4. Support multi-class classifier.
5. Support two variable interaction partial dependence plot.


## Documentation

- Latest version: http://pdpbox.readthedocs.io/en/latest/
- Historical versions:
  - [v0.1](https://github.com/SauceCat/PDPbox/blob/master/docs_history/v0.1/docs.md)


## Installation

- through pip
  ```
  $ pip install pdpbox
  ```

- through git
  ```
  $ git clone https://github.com/SauceCat/PDPbox.git
  $ cd PDPbox
  $ python setup.py install
  ```

## Gallery
