# CPSC 481 Project 2 - Heuristics for Pacman
## Authors
- RJ Andaya
- Andrew Dinh
- Fanghua Gu
- Bijaya Shrestha

## Introduction (Algorithm Used)
In search.py file, we simply implement the search algorithm functions that
consists of 4 types which are breadthFirstSearch, uniformCostSearch, nullheuristic and
aStarSearch and these functions are called by another file called searchAgents.py. As a
breadthFirstSearch, it goes by level-wise rather than depth into one node and its
children. So, breadthFirstSearch uses a queue to record the track of the state. In the
uniformCostSearch function, it helps to search the node that reaches to the final state at
first in very lower cost.

As for the nullheuristic function, it will help to find out the estimate cost from
current to the final state as it generates the estimates cost from initial to the current
state. And aStarSearch reflects the lowest cost with the best or first heuristics path to the
final(goal) state.

As requirement for the project, the search will be able to find a path through out
all the four corners of the maze and also able to collect the food if its available in the
any corner. 

## Setup and Installation
Download the project code, and execute the project by executing one of the commands listed in the command.txt in Command Prompt(Windows) or Terminal(macOS/Linux). Pacman will navigate efficiently through the maze.

## Sample Invocation
By executing the following commands, Pacman will be able to explore the maze along the highlighted path.

Command for A* search for bigMaze pathfinding: <br />
	python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic <br />


Commands for the CornersProblem search for tinyCorners and mediumCorners pathfinding: <br />
	python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem <br />
	python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem <br />
	

## Bugs
N/A

## Issues
N/A
