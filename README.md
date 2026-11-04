
# 15 Puzzle solver

This is a simple implementation of the A* algorithm in Haskell to solve the 15 puzzle (optimally or suboptimally). Note that optimal solving will most likely take an unreasonable amount of time to terminate if the optimal solution contains more than 55 moves.

## Run
```sh
runghc puzzle.hs
```
This solves an example puzzle suboptimally; edit `main` in `puzzle.hs` to solve another one (`optimalSolve` or `suboptimalSolve`). On case-sensitive file systems, the module files must match their module names (e.g. `astar.hs` → `AStar.hs`).
