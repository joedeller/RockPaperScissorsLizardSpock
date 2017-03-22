# Rock Paper Scissors Lizard Spock
Python 3 version of Rock Paper Scissors Lizard Spock using a dictionary for the rules.

Most implimentations of this seem to go down the if elif elif.... route which starts to get clumsy. 
Python's dictionarys are very powerful and the game rules can be defined in the dictionary
and kept separate from the implimentation of the game.

Additional moves can be added or the rules changed without affecting the core code.
Only two if statements are needed to determine the winner.

Consider the case of adding a "Nuke" option, which beats everything apart from Spock
(Spock's katra survives fatal radiation...)
To impliment this:

add nuke = "Nuke" to the moves list

Change the spock entry in winmoves to spock:[scissors, rock, nuke]

add nuke:[rock, paper,scissors, lizard] to the winmoves dictionary

No code changes are necessary and removing the nuke option would
just mean removing it from the moves list



