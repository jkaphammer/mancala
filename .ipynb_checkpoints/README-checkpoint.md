# Mancala
**AI application that plays a (modified) version of mancala.**

*Modified rules:*
- On every turn, select a pit on your side of the board that contains one or more
stones, the distribute its stones, one stone per pit or Mancala, in an counter-
clockwise direction until you have no stones remaining
- If the last stone lands in the other player's mancala, in an opponent's pit, or in
one of the player's non-empty pits, no further action is taken, and the current
player's turn ends
- If the last stone lands in your empty pit (on your side of the board) and the
opposite pit on the opponent's side has 1 or more stones, collect all of these
stones, including the one that just landed, and place them into your Mancala.
- If any of the player's pits are entirely empty, the game concludes. The player
with the most stones in their mancala is declared the winner. If both players
have an equal number of stones in their mancala, the game results in a tie.

**Current Progess**
- User can play and input moves as a player
- Random opponent will select a random legal move

**To-Do's**
1. Analyze 100 games of random player against random player
2. Build an AI player that uses minimax to choose the best move with a variable
number of plies and a utility function
3. Play 100 games with the random player against the minimax AI player at a
depth of 5 plies, and analyze 100 games
4. Build an AI player that uses Alpha-Beta to choose the best move
5. Play 100 games with the random player against the Alpha-Beta AI player at a
depth of 5 plies, and analyze
6. Play 100 games with the random player against the Alpha-Beta AI player at a depth of 10 plies, and analyze
