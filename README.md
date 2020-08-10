**Collaborators: Sufian Mushtaq, Nishith Atreya **
**Note: Due to the University of Rochester Computer Science Department's project guidelines, I cannot share the entire code of this project publicly, thus I have replaced many parts of this project with comments for privacy reasons.**
There are four main classes defined in our game.
**Main.java --** This is the driver class for our game. It will ask the user to enter the game size,
color choice and the kind of algorithm it wants to play with. To start the game, the user just has
to run this driver class and rest will be handled by the game.

**State.java --** This class has all the abstract elements for the game. This class is the core part
of the game which has all the methods to calculate heuristics, possible moves, making jumps
and multiple kills. This class uses Minimax and Alpha_Beta_Minimax classes to perform moves
for the game.

**Minimax.java --** This algorithm implements the Minimax algorithm for the game. It calls getMin
and getMax recursively and uses the heuristic method to find the optimal move for the game.

**Alpha_Beta_Pruning.java --** This algorithm is quite similar to Minimax algorithm but uses
alpha and beta values to prune the unnecessary game states in the game.

How to run the program
javac main.java
java main
After running the main methods, the game will ask the user to input game size and color choice
to construct the game.
Rows are represented by a,b,c,d,e,f,g....
Columns are represented K, L, M, N, O, ...
Each cell is represented by [rows][columns] -- eg aK, bL. Now in order to move a piece from
one place to another, the user has to input the cell values by using -- [initial position] space
[final position] eg aK bL.
Users have to enter q to validate each move
