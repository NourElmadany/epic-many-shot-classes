# Computing many shot classes

Many shot verb and noun classes are defined as those classes that have > 100
instances in training.

Many shot actions are the subset of the cross product between the many shot verb
and many shot nouns that appear at least once in training.

* 26 verb classes
* 71 noun classes
* 819 action classes

[Check out the notebook](./many-shot-classes.ipynb) for deriving these numbers from the training labels
alone.
