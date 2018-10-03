# mechmania2018
Artificial Intelligence hackathon, team placed 8th of 41 teams

## Game Basics
This game is played on a board which is essentially an undirected graph. This means that there are a bunch of "nodes", or locations on the map, some of which are connected to each other. If two nodes are connected, then players can travel between them.

In a game, you and your opponent will each start at node 0. At each turn of the game, each player must choose a stance (either rock, paper, or scissors), as well as a destination (where you want to move). The stance you each choose determines which player deals damage to the other.

But watch out! There are dangerous monsters on some of the nodes of the board. However, these monsters provide rewards when defeated through their Death Effects.

## Strategy
Node navigation - evaluate moves each tick of game to constantly check what is the best move via a complex decision tree
Dueling - we anticipated a number of strategies that we wrote an algorithm to detect the opponent strategy and to counter it
