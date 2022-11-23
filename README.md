# names
Implementation of a multilayer perceptron (MLP) character-level language model. Takes one text file as input, where each line is assumed to be one training thing, and generates more things like it.For example, we can feed it a database of names, and makemore will generate cool name ideas that all sound name-like, but are not already existing names.
## Current implementation follows a few key papers:

* Bigram (one character predicts the next one with a lookup table of counts)
* MLP, following Bengio et al. 2003
