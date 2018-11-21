# Computing many shot classes
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/epic-kitchens/epic-many-shot-classes/master?filepath=many-shot-classes.ipynb)

Many shot verb and noun classes are defined as those classes that have > 100
instances in training.

Many shot actions are the subset of the cross product between the many shot verb
and many shot nouns that appear at least once in training.

* 26 verb classes
* 71 noun classes
* 819 action classes

[Check out the notebook](./many-shot-classes.ipynb) for deriving these numbers from the training labels
alone.
