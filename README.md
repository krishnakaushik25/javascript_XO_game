# javascript_XO_game

Build Tic Tac Toe Game With JavaScript

In a two-player (A vs B) game, if player A scores x points , player B loses x points. Total gains/losses always sum up to 0 and we know everything about the current game state.

Tic-tac-toe or noughts and crosses or Xs and Os is a paper-and-pencil game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.

This project is easy to create but there a lot of things to learn though for beginner, it is lot of fun to start with.Anyone knowing  JavaScript Basics (For loops, variables, functions, Arrays, if statements ... etc) can build this game fromsratch.

HTML elements we're going to need for our game is in index.HTML page.

We will need two files choices.js and XO_game.js forJavascript. choices.JS is where the code that handles the player's options is present, like who is the opponent and symbol it has opt. XO_gam.JS is where our game code ,how our game is gonna function is present.


## General things to do:
* 1D Array called "gameData" to store the players moves.
* Draw the board on the canvas
* add Event listener to the CANVAS.
* Determine which space on board the player has selected.
* Update the gameData array.(if the space clicked by the player is blank)
* Draw the player's move on the board.
* Check if current player wins , if it is win, We show the message pop up game over and end the game.
* If it doesn't win, we check for a tie game, if it's a tie we show the game over message and stop the game.
* If there is no winner and it's not a tie game, then the turn goes to other player.

**If the opponent selected is computer,then we have to design a game algorithm for making the possibility chances of win for computer more i.e optical moce by computer.(AI)**

**Known as Minimax algorithm that is widely and successfully used across the fields like Artificial Intelligence, Economics, Game Theory, Statistics**

##### Minimax: Minimax is a recursive algorithm which is used to choose an optimal move for a player assuming that the opponent is also playing optimally. As its name suggests, its goal is to minimize the maximum loss.(minimizing the loss considering worst case scenario).Algorithm as a representation of the human thought exploring all the different moves taken by the exponent.


## References:
[allen-kim medium article](https://medium.com/allenhwkim/how-to-build-a-carousel-in-pure-javascript-98d758a18811),[Slideshow by W3-schools](https://www.w3schools.com/howto/howto_js_slideshow.asp)


## Support 

If you like this repo and find it useful, please consider (★) starring it (on top right of the page) so that it can reach a broader audience.



