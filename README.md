# Chutes-and-Ladders-Simulation
Kyle Cranmer, Johann Brehmer, Marvin Meng Chutes &amp; Ladders Mining Gold Simulation

Created a Chutes & Ladders Simulation to test new "Mining Gold" Machine Learning Technique, which finds more data than typical computer simulations.

Normally, a Chutes & Ladders Simulation would only return something regarding the outcome x, such as number of turns it took, the rolls each player used or a list of each player's position for each turn.

If there were a parameter, theta, that affected the outcome, the simulation would give no information on that parameter theta.
Ex. Theta = chances of rolling each value of a die (i.e. not a fair die)
x = number of turns the game lasts
The simulation could say how many turns the game lasts, but couldn't say how the dice were loaded.


The Mining Gold technique returns not only the outcome, but also information about theta.

In this simulation, theta is a number that determines the weights of the die, and x is the number of turns the game lasts.

The game is played between 2 players.

Here is a link to the paper written by Johann Brehmer, Kyle Cranmer, and their colleagues:
https://arxiv.org/pdf/1805.12244.pdf
