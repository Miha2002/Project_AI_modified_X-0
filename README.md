# Modified X-0  (Tic-Tac-Toe)

This is an university project for the subject: Artificial Inteligence.

It is a game of X-0. The player can choose the board's dimensions, the score needed to win the game, one of two bot AIs and a symbol ( X/0 ).

## Game rules:

- The board dimensions have to be: odd number vertically and even number horizontally.
- At the start of the game, there will be two symbols (one of each) already places in the middle of the board.
- No matter what symbol is chosen by the player, X is always the first to make a move.
- The last symbol places by each of the players will be marked by a change of color (green).
- The player and the bot take turns placing new symbols on the board. A new symbol can be placed 1 block away from the last one (the green one). The distance can be vertical, horizontal or diagonal. The spaces 1 block away from the last one placed = neighboring blocks.

    e.g.

    <img src="https://user-images.githubusercontent.com/81815165/222347024-659cf662-846a-4248-a3ac-856e012f0dfc.jpg" width="300" height="300">


- The player can place a symbol in any of those position as long as they aren't already taken. The player can still place an symbol over an opposite symbol in one of the neighnoring blocks if:
    - the symbol is not the last symbol of the opposite player.
    - the symbol is not a neighbor to the last symbol of the opposite player.
    - the symbol has 2 or less neighboring blocks with the same symbol as itself.

- If a player places a symbol over the other player's symbol that counts as a point taken.
- 
