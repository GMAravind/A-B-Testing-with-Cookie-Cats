# A-B-Testing-with-Cookie-Cats

Introduction:
Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. 
It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. Hedonic adaptation is the tendency for people to get less and less enjoyment out of a fun activity over time if that activity is undertaken continuously. By forcing players to take a break when they reach a gate, their enjoyment of the game is prolonged. As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

Experiment:
This experiment is to understand if increasing the threshold for a break from gate 30 to gate 40 improves customer retention.

Data Overview:
userid - a unique number that identifies each player.
version - whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).
sum_gamerounds - the number of game rounds played by the player during the first 14 days after install.
retention_1 - did the player come back and play 1 day after installing?
retention_7 - did the player come back and play 7 days after installing?




