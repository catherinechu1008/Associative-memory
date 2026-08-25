# Associative-memory

## Research question

Can a network recover a stored pattern when some of the pattern's elements have been changed?

In this notebook, I use a simple Hopfield network to explore associative memory. 

1. What does one number in the pattern represent?
2. Why do we flatten the 5x5 image into a vector?
3. What does it mean to "corrupt" a memory in this model?
4. How many units where changed?
5. What would successful memory retrieval look like?

Each unit represents one simplified neuron.
5x5 pattern contains 25 units, so it represents a network of 25 simplified neurons.
Each neuron has a state of either 1 or -1.
The 25x25 weight matrix describes connections between those neurons.

weights[0, 1] -> connection between neuron 0 and neuron 1
      
