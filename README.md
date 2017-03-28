# Pacman_CTF
This is an implementation of intelligent pacman agents for the Pacman Capture the Flag game designed at UC Berkeley. I worked on this project with Liyuan Zheng. This work was done as the final project for the artificial intelligence class at the University of Washington (CSE 573). 

Based off performance against a baseline agent design, our agent team was awarded the #1 seed and the only first round bye in the 15 team class tournament. We made it to the semifinals before losing to a more defensive focused agent.

Our agent design used a Hidden Markov Model for tracking opposing agents with noisy distance readings that were received, and chose moves using the Expectimax algorithm. One agent used an evaluation function that caused it to be entirely offensively focused while the second agent only attacked when our teams territory was not at risk.




