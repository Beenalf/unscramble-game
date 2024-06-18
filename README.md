# unscramble-game
A text-based unscramble game played in the terminal

~~~ Coming Soon! ~~~

This game was created as an assignment for the CSSE2310 class at UQ. The files in the 'lib' and 'include' folders were provided by course staff.
In this game, the user is provided with a series of letters and must enter words into the command line. If the user's word can be
formed from the given letters, is greater than or equal to the minimum length requirement, is a valid word in the dictionary, and
has not been guessed already, then the user's score is increased by the length of the word.
If the word is of maximum length (all characters are used), 10 point bonus is applied. If the user enters "q", the game ends and
all valid words that can be made with the given letters are printed to the screen. Otherwise, the user can end the game with CTRL-C.

The command lines must be in the format: ./uqunscramble [--letters chars] [--dictionary dictfile] [--min-len len]
The default dictionary contains commonly used words, the default minimum word length is 4, and the program provides the user with
7 randomly generated letters if --letters is not specified on the command line
Some sample command lines are:
  ./uqunscramble
  ./uqunscramble --letters CCeiKRT
  ./uqunscramble --min -len 5
  ./uqunscramble --dictionary mywords --letters aeiilnr
