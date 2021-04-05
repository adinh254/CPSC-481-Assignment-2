# CPSC 481 Project 2 - Heuristics for Pacman
## Authors
- RJ Andaya
- Andrew Dinh
- Fanghua Gu
- Bijaya Shrestha

## Introduction (Algorithm Used)
TODO A* explanation

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
