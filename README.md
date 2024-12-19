
# Tic Tac Toe 

Implemented with Python using PyGame framework.




## Features

- Gamemodes for PvP and Ai Opponent 
- 2 Difficulty settings of a standard opponent or an optimized Ai opponent
- Use keys to swap between features 
- G: Change between PvP or Ai opponents
- 0: standard Ai 
- 1: optimized Ai
- R: Restart the game
## MiniMax Algorithm for Tic Tac Toe
    Terminal/Base Case:
        Player 1 Wins : Wants to minimize value -> -1
        Player 2 Wins : Wants to maximize value -> 1
        Draw : Neutral Value -> 0
    
    Intermedate State:
        Simulate through the algorithm by taking into account the 
        number of empty squares and place squares till a terminal
        state is reached. The algorithm based on the player will 
        choose the smallest or largest value of a move.
        The value of a move in the intermediate state depends more 
        so on denying the terminal state of the other player
        rather than achieving a win, though if a win is achievable
        on the next turn for either player then that action has
        the largest or smallest value.
