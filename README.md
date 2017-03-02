# mini-practice-projects

###1. Number Guess
The function should generate a random number (you can choose the range but I suggest 1-10 to start). It should then prompt the user to input a number guess. If the number is too high or too low, the function should tell the user and they should be prompted to guess again. If they guess correctly, the user wins.

Hints: You'll need to import the randint module (no need to install, this is a standard module). [Some help with that](http://stackoverflow.com/questions/3996904/generate-random-integers-between-0-and-9)

You will also use the `input()` function in order to [prompt the user](http://anh.cs.luc.edu/python/hands-on/3.1/handsonHtml/io.html). 

And finally, think about the type of loop you may use to keep the function running until the user guesses correctly and the game ends. 

###2. Virtual Dice
When you call this function, it should return a random integer (1-6 if you want to go traditional dice). Then it should ask the user if they want to roll again. If the user says 'yes', roll the dice with a new random integer. Otherwise, end the game.

Hints: You'll use `input()` and randint again. 
