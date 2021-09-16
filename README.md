# generalized-penney-s-game


Penney's game is a 2 player nontransitive game where the two players make a unique binary sequence of length 3 as a guess to flipping a series H or T with a 50-50 chance.


# Goal
To generalize the game to fit a sequence of length n  
To generalize the game to accomidate m people  
To generalize the game to fit more than a binary state (expanding the base)


# Checklist
1. Can generate the markov (transition) matrix for any base and any sequence length
2. Can get the probabilities for any base and any sequence length for any number of players < number of all possible sequences
3. Need to continue working on storing all possible probabilities in a matrix/tensor (difficult to visualize)
4. Need a method to iterate through the tensor and pic the winning sequence
5. Can simulate the Generalized Penney's game trough a simulation
