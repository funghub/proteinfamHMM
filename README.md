# proteinfamHMM
This code creates a HMM model that represents a given diagram based on a practice problem.
There are two protein families that each have a different set of parameters for their emission and transition states. I will find the most likely sequence of hidden states for each family. In addition, given a sequence of observations, I will also find the likely family that would have generated those observations and find the possible sequence of hidden states with the Viterbi algorithm.

There are 3 states, rectangle, circle, and hexagons
Each state can emit a symbol: a,b,c,d,e.
Each iteration starts with R1 and ends with R3
