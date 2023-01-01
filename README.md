# Comp2611-Tetris

This project aims to re-build tetris in MIPS.

Currently it is completed. To run the project, download the "NewMars" Java file and then on the top left click "open" and then select the "tetris.asm" file.

Next: Click the crowbar button to assemble the code and click the green right arrow button to run.

An interesting approached was used to determing when blocks would rotate, essentially the rotation position can be calculated for each block-type by creating an array of 
the differences. For example, if an L type block were to rotate, the x and y-coordinate would remain the same, but each block "cell" would rotate accordingly. 

