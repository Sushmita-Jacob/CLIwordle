# **CLI Pokemon Wordle**

This project is a clone of the popular New York Times game, Wordle. Wordle is one of many NYT games, including Crossword, Connections, Spelling Bee. 

This project was made using the following YouTube tutorial (Build Wordle in Python - Word Game Python Project for Beginners by pixegami):
https://www.youtube.com/watch?v=SyWeex-S6d0

Past the tutorial, the following features were added/changed:
- The secret word is the name of a pokemon
- Instead of guessing a five-letter word like in typical Wordle, the player must guess a seven-letter word
- After each game, a Wikipedia article to the pokemon is linked
- Allows lowercase guesses to still be valid

The number seven was chosen because seven-letter pokemon was most frequent in the data set.

**To play, download the dist folder (not just the executable) and run play_wordle.exe inside of it.** It is important to do this because the game needs information from the data folder, which is also inside of the dist folder.