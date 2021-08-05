DFS -- python pacman.py -l bigMaze -z .5 -p SearchAgent
BFS -- python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
UCS -- python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=ucs
A* -- python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic