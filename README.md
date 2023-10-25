# Techin_509_week_4
Techin 509 Week 4 Assignment 

Submit a link to your GitHub repository you created:

The repository should include your solution to the Flood Fill function
The repository should include a pull request that has been merged by a classmate
The repository should include a README.md file that has a link to the repository of a classmate's GitHub repository where you made a pull request that was merged into their project
Flood Fill Function
Flood-fill is a common algorithm used to fill connected regions of the board with a new value based on a specified condition. The code takes an input board, an old value, a new value, and coordinates (x, y) as arguments. It recursively updates the board by changing the old value to the new value for all connected cells.

For the code itself, please implement the flood fill function, which builds on the concepts of functions and recursions discussed in Week 3. The starter code for the code:
```
board = [
    "......................",
    "......##########......",
    "......#........#......",
    "......#........#......",
    "......#........#####..",
    "....###............#..",
    "....#............###..",
    "....##############....",
]


def flood_fill(input_board, old, new, x, y):
    """Returns board with old values replaced with new values
    through flood filling starting from the coordinates x, y
    Args:
        input_board (List[str]): The input board
        old (str): Value to be replaced
        new (str): Value that replaces the old
        x (int): X-coordinate of the flood start point
        y (int): Y-coordinate of the flood start point
    Returns:
        List[str]: Modified board
    """

    # Implement your code here.


modified_board = flood_fill(input_board=board, old=".", new="~", x=5, y=12)

for a in modified_board:
    print(a)

# Expected output:
# ......................
# ......##########......
# ......#~~~~~~~~#......
# ......#~~~~~~~~#......
# ......#~~~~~~~~#####..
# ....###~~~~~~~~~~~~#..
# ....#~~~~~~~~~~~~###..
# ....##############....

modified_board = flood_fill(input_board=board, old=".", new="~", x=1, y=1)

for a in modified_board:
    print(a)

# Expected output:
#~~~~~~~~~~~~~~~~~~~~~~
#~~~~~~##########~~~~~~
#~~~~~~#........#~~~~~~
#~~~~~~#........#~~~~~~
#~~~~~~#........#####~~
#~~~~###............#~~
#~~~~#............###~~
#~~~~##############~~~~

```
After finishing the above code, you can create a new GitHub repository either use the Web IDE to add the files or push the above code to the remote repository using an IDE or command line functions

#Version Control
After the repo is created and has the code,

- Fork your friend's repository to create a new repository, and either use the Web IDE or clone this to your local computer
- Make changes to this code. You can do one or more of the following changes:
- As there is a default test case (board) on line 3 of the starter code, add additional boards for the code to run on.
- If there is a bug in your friend's code, fix it.
- Add docstrings to the functions if they don't exist.
- Add assert statements to ensure the input is in the right format. (Ex. Ensure all the rows of the input board are of the same lengths through assert statements.)  
- After the above changes are made to the local computer or in the Web IDE, push this change to the remote, and make a pull request on GitHub to your friend's repository. Add a review message describing the change you made and why your friend should accept your pull request.

