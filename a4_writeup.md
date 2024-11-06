# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
    the most diffcult part of tiktactoe to me was creating the has_won function. I struggled to find out how to write all the possible win conditions and needed assisstance from group mates.
2. Explain how you would add a computer player to the game.
    I would try to import a math.random package for the computer to move.
3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
    If the computer goes first, they would always go center and then a space right next to the player next turn. If the opponent did not go to a corner piece, you can pin a double trap to guarentee win. If the opponent did go to a corner piece, then you can only tie with them and block their wins. If the computer goes second, they will try to go middle, if they can't, then it will just go to a corner space. Their next turn will block a win from player 1 and result in a draw.