# Tower-Of-Hanoi

Tower of Hanoi is a classic puzzle game that consists of three pegs and a number of disks of different sizes which can slide onto any peg. The puzzle starts with all the disks on one peg in ascending order of size, the smallest at the top, thus making a conical shape.

The objective of the puzzle is to move the entire stack of disks to another peg, obeying the following simple rules:

* Only one disk can be moved at a time.
* Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty peg.
* No disk may be placed on top of a smaller disk.

The minimum number of moves required to solve a Tower of Hanoi puzzle is 2^n-1, where n is the number of disks.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python tower.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The function TowerOfHanoi takes four arguments: n, the number of disks; source, the starting peg; destination, the peg to move the disks to; and auxiliary, the spare peg to use during the move.

* The base case is when there is only one disk, in which case the function simply prints the move from the source to the destination.

* For larger n, the function recursively calls itself, moving n-1 disks from the source to the auxiliary peg, then moving the largest disk from the source to the destination peg, and finally moving the n-1 disks from the auxiliary peg to the destination peg.

* The variable n is set to 3, meaning there are four disks to be moved.

* The TowerOfHanoi function is called with the arguments 'A', 'B', and 'C', representing the three pegs.

* The output of the program is a set of moves that would solve the Tower of Hanoi problem for four disks, printing the source and destination pegs for each move.
