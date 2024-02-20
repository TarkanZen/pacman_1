**THIS IS A PROJECT ASSIGNMENT CREATED AND OWNED BY UC BERKLEY, ALL RIGHTS BELONG TO THEM.
Project contents can be viewed under the search.py file
OVERALL SCORE: 25/25**

Coded for Python 3.6.0
Set CD to *search* in the Python Terminal

*python pacman.py* to test it out for yourself

*python pacman.py --help* to view command lines

**TEST THE ALGORITHMS CODED WITH THE COMMAND LINES BELOW**

**Depth First Search:**

python pacman.py -l tinyMaze -p SearchAgent

python pacman.py -l mediumMaze -p SearchAgent

python pacman.py -l bigMaze -z .5 -p SearchAgent

python autograder.py -q q1

**Breadth First Search:**

python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs

python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

python eightpuzzle.py

python autograder.py -q q2

**UCS Agent:**

python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs

python pacman.py -l mediumDottedMaze -p StayEastSearchAgent

python pacman.py -l mediumScaryMaze -p StayWestSearchAgent

python autograder.py -q q3

**A*** **Search:**

python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic

python autograder.py -q q4

**Corners Problem:**

python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem

python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem

python autograder.py -q q5

**Heuristic Corners Problem:**

python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5

python autograder.py -q q6

**Eating All The Dots:**

python pacman.py -l testSearch -p AStarFoodSearchAgent

python pacman.py -l trickySearch -p AStarFoodSearchAgent

python autograder.py -q q7

**Suboptimal Search:**

python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5

python autograder.py -q q8


