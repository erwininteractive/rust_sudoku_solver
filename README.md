# Sudoku Solver
## summary
This is my first attempt at Rust! I don't know the language yet.


## code self review
Here are some things I would like to improve as I actually learn Rust.

1. The ```solve``` function creates several copies of ```puzzle```. I believe I can use a stack to keep track of the puzzle?
2. I think there must be a better way to represent the puzzle than a 2D array?
3. Maybe some sort of caching as well?
