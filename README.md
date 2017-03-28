# Pacman_CTF
This is an implementation of intelligent pacman agents for the Pacman Capture the Flag game designed at UC Berkeley. I worked on this project with Liyuan Zheng. This work was done as the final project for the artificial intelligence class at the University of Washington (CSE 573). All the code for our agents is contained in the file myTeam.py in the Code directory.

Based off performance against a baseline agent design, our agent team was awarded the #1 seed and the only first round bye in our 15 team class tournament. We made it to the semifinals before losing to a more defensive focused agent.

Our agent design used a Hidden Markov Model for tracking opposing agents with noisy distance readings that were received, and chose moves using the Expectimax algorithm. One agent used an evaluation function that caused it to be entirely offensively focused while the second agent only attacked when our teams territory was not at risk. A further description of the methodologies is given in the agent_description.pdf document.

Game_Recording is a recording of our agent playing as the blue team versus the baseline agent playing as the red team. In this game, our agent manages to win by 15 points.

# Running Instructions
To run the game use the following command inside the Code directory:

python capture.py -r < team name > -b < team name >

The team names can either be myTeam or baselineTeam. An example is below.

python capture.py -r myTeam -b baselineTeam

Other options can be found by running:

python capture.py --help


