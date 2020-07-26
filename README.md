# Pacman

The repo implements tasks 1 through 4 of the Berkeley Pacman project, available at https://inst.eecs.berkeley.edu/~cs188/fa18/project1.html

It expands on those by:

1. adding an Iterative Deepening Search algorithm, run by calling:  
*python pacman.py -l mediumMaze -p SearchAgent -a fn=ids*

2. Adding a Weighted A* algorithm (default W = 2), run by calling  
*python pacman.py -l mediumMaze -p SearchAgent -a fn=wastar,heuristic=manhattanHeuristic*

3. Solving Berkeley task 7 with the additional limitation of the agent needing to eat a capsule before eating any of the regular pellets, run by calling:  
*python pacman.py -l capsuleSearch -p CapsuleSearchAgent -a fn=wastar,prob=CapsuleSearchProblem,heuristic=foodHeuristic*

This solution was created as part of University of Melbourne's COMP90054 AI Planning for Autonomy class.
