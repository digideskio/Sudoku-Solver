Sudoku-Solver
=============

Constraint solver for those pesky sudoku puzzles.

## Output

    [ chaoticryld ~/CS/Sudoku-Solver ] $ ruby sudoku_cp.rb 

    Running benchmarks...
    0.812 secs to solve 50 easy puzzles (avg: 0.016 secs (61 Hz))
    4.162 secs to solve 95 hard puzzles (avg: 0.044 secs (22 Hz))
    0.202 secs to solve 11 hardest puzzles (avg: 0.018 secs (54 Hz))

    ORIGINAL PUZZLE:
    4 . . |. . . |8 . 5
    . 3 . |. . . |. . .
    . . . |7 . . |. . .
    ------+------+------
    . 2 . |. . . |. 6 .
    . . . |. 8 . |4 . .
    . . . |. 1 . |. . .
    ------+------+------
    . . . |6 . 3 |. 7 .
    5 . . |2 . . |. . .
    1 . 4 |. . . |. . .

    SOLUTION:
    4 1 7 |3 6 9 |8 2 5
    6 3 2 |1 5 8 |9 4 7
    9 5 8 |7 2 4 |3 1 6
    ------+------+------
    8 2 5 |4 3 7 |1 6 9
    7 9 1 |5 8 6 |4 3 2
    3 4 6 |9 1 2 |7 5 8
    ------+------+------
    2 8 9 |6 4 3 |5 7 1
    5 7 3 |2 9 1 |6 8 4
    1 6 4 |8 7 5 |2 9 3

## Notes

I tested my code with 50 easy, 95 hard, and 11 hardest puzzles from [Peter Norvig’s Sudoku Page](http://norvig.com/sudoku.html). For those of you who don’t know him, he is the Director of Research at Google and has “possibly the best compsci job on the planet” according to my high-school AI professor. His sudoku page is a great resource for anyone who wants to learn about constraint programming and searching. (Anyone who wants to learn Python idioms, please look at his sudoku solver…it is quite clever).
