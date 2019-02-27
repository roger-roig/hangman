# hangman

This game of hangman consisting in guessing one word chosen randomly from a word bank.

Steps:

1 - Create a list of words or import an existing list

2 - Create a list consisting of the characters of the word

  Loop over steps 3-7 until word is found or game is over:
  
  3 - Print the word with all the characters replace with underscores
  
  4 - Ask the user for a letter
  
  5 - If the letter is on the list, delete it from the list and replace the corresponding underscore(s) with the letter
  
  6 - Else (if the letter is not on the list), start drawing the hangman.
  
  7 - Keep a list with all the used letters.

8 - If the list of letters is empty then the user wins the game

9 - If the hangman draw is completed then the game is over

10 - Ask the user if he wants to play another game

 
