Frog-Leap Game


Introduction:

The Frog-Leap game is a fun and interactive puzzle game implemented in Python. The goal of the game is to switch the positions of the green frogs (G) and the brown frogs (B) by making valid moves. The game is won when all the brown frogs are on the left and all the green frogs are on the right.

How to Play:

The game board consists of seven positions represented as follows:

[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', 'G', 'G', '-', 'B', 'B', 'B']
Frogs can move in the following ways:

A green frog (G) can move to the right into an empty space (-) if it is adjacent.
A green frog (G) can jump over one brown frog (B) into an empty space (-).
A brown frog (B) can move to the left into an empty space (-) if it is adjacent.
A brown frog (B) can jump over one green frog (G) into an empty space (-).
Enter the position number of the frog you want to move. Valid moves will update the board.

The game ends when all green frogs and brown frogs have switched places, or if you decide to quit by pressing q.

Example Game:

[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', 'G', 'G', '-', 'B', 'B', 'B']
Enter position of piece: 2
Invalid Move
Enter position of piece: 1
[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', '-', 'G', 'G', 'B', 'B', 'B']
Enter position of piece: 4
Invalid Move
Enter position of piece: 5
Invalid Move
Enter position of piece: 6
[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', '-', 'G', 'G', 'B', '-', 'B']
Enter position of piece: q
You Lose

Requirements:
Python 3.x

Contributing:

If you have suggestions or improvements, please open an issue or create a pull request. Contributions are welcome!
