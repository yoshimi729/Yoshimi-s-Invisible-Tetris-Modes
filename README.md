Repository of invisible tetris modes written for the Cambridge block stacker by me, Yoshimi :)
## Cambridge Download
See [the Cambridge repository](https://github.com/cambridge-stacker/cambridge/releases/) for the application required to run these modes. Once installed, open the app and drop the .lua files downloaded from this repository onto the window, choose "mode" for each entry, and enjoy.
# Practice-Oriented Modes and Modifications
## Phantom Mania N GM+
Clone of "Phantom Mania N" included in the base install of Cambridge with expanded grading and pace statistics. After the game ends, statistics shown are: 
- Tetrises (Total count of cleared tetrises over the course of the game)
- Section Tetrises (Count of cleared tetrises in each 100 level section, where 2 are required in the first 9 sections and 1 is required in the final section for a GM grade)
- GM Pace (Multiple of GM grade that you would get by clearing the mode at the same pace, taking into account the worst section tetris performance as a cap)
- Tetris Pace (GM grade pace that you are on, disregarding section tetris requirements)

See image in the section below if clarification is needed.

*Grades above Grandmaster are now recognized as multiples of GM when clearing the mode.*\
This mode functions the same as that in the base game during play, so should be acceptable to perform community-recognized Grandmaster attempts.



## Phantom Mania N GM+ Practice
The same stats included in Phantom Mania N GM+ are here as well, but now shown during the gameplay. This is intended as a practice tool to judge how well you need to do to reach your GM multiple goal, not for doing legitimate runs. 


<img src = "/screenshots/pmn_gm%2B_1.png" alt = "Image of player stats in the 700 section on GM pace 2.38." width = "170" height = "189"> <span>  -->  </span> <img src = "/screenshots/pmn_gm%2B_2.png" alt = "Image of player stats in the 800 section after having only gotten 4 section tetrises. GM pace is now capped at 2.00, but tetris pace remains higher than that at 2.24" width = "166" height = "819">\
Shown above is a player on good pace into the 700 section. However, a series of major mistakes prevents her from clearing at least 5 tetrises in the section, causing her GM pace to be capped once the section is passed. Note that tetris pace remains above the GM pace cap. The grade awarded at the end of the game if the player keeps pace is GM x 2.00.

## Phantom Practice Appearing
Modification of Kirby703's [Phantom Practice Fading](https://github.com/Kirby703/cambridge-practice-modes) where the placed blocks gradually appear rather than fade away. This emphasizes recall of stack contour, which is a very important skill in stacking cleanly.\
The stack gradually takes longer and longer to appear, then stops appearing at level 900. Completion at level 999.
