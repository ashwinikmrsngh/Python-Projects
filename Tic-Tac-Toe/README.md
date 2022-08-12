# PROJECT  Tic-Tac-Toe
### Scenario
<p>
  A simple program which pretends to play tic-tac-toe with the user. To make it all easier for you, we've decided to simplify the game. Here are our assumptions:
<ul>
  <li> the computer (i.e., your program) should play the game using 'X's.</li>
  
  <li> the user (e.g., you) should play the game using 'O's.</li>
  
  <li> the first move belongs to the computer − it always puts its first 'X' in the middle of the board.</li>
  
  <li> all the squares are numbered row by row starting with 1 (see the example below for reference).</li>
  
  <li> the user inputs their move by entering the number of the square they choose − the number must be valid, i.e., it must be an integer, it must be greater than 0 and less than 10, and it cannot point to a field which is already occupied.</li>
  
  <li> the program checks if the game is over − there are four possible verdicts: the game should continue, the game ends with a tie, you win, or the computer wins.</li>
  
  <li> the computer responds with its move and the check is repeated.</li>
  
  <li> a random field choice made by the computer is good enough for the purpose of this game.</li>
</ul>  </p>
<break>
  
_* FOR EXAMPLE *_
<pre>
+-------+-------+-------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   4   |   X   |   6   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-------+-------+-------+
</pre>
