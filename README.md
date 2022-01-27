# wordle_unlocked
A userscript for unlocking wordle.com

This userscript adds three buttons to the header of the Wordle game.
They
* allow you to regenerate the game with a new random word
* solve the game automatically
* generate the next best guess

### Some notes

#### The Solver
The solver does not cheat. It starts with all possible words and then filters them based on the feedback given by the game.

This does mean that sometimes it fails to find the correct cword within six guesses. I am currently working on fixing this.


#### The Guesser

The guesser just performs one step of the solver's work. It prioritizes words that contain the most common letters, and then the words that contain the most number of unique letters.


#### The Wordlist
The word list was taken directly from the original website.

