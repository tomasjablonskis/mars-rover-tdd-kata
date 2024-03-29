# Mars Rover - TDD Kata

**Requirements**

1) You are given the initial starting point (x, y) of a rover and the direction (N, S, E, W) it is facing.
2) The rover receives a character array of commands.
3) Implement commands that move the rover forward/backward (F, B).
4) Implement commands that turn the rover left/right (L, R).
5) Implement wrapping at edges. Connect the x edge to the other x edge, so (0, 0) for x-1 to (5, 0), but connect vertical edges towards themselves in inverted coordinates, so (0, 0) for y-1 connects to (0, 5).
6) Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point, aborts the sequence and reports the obstacle.
