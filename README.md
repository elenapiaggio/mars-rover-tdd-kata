# Mars Rover Kata
## TDD
Develop an API that moves a rover around on a grid

## Description
1. You are given the initial  starting point (0,0,N) of a rover     
2. 0,0 are (X,Y) coordinates on a grid of (10x10)  
3. N is the direction it is facing (i.e. N, S, E, W)
4. L and R allow the rover to move one point in the current direction
5. M allows the rover to move one point in the current direction
6. The rover receives a char array of commands e.g. RMMLM and returns the finishing point after the moves e.g. 2:1:N
7. The rover wraps around if it reaches the end of the grid
8. The grid may have obstacles. If a given sequence of commands encounters an obstacle, the rover moves up to the las possible point ad reports the obstacle e.g. 0:2:2:N



