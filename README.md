# Comp2611-Tetris

This project aims to re-build tetris in MIPS.

Currently it is completed. 
How to run:
  1.) Download NewMars File and run it.
  2.) Download Tetris.asm file.
  3.) After running the NewMars File click the "open" button on the top left, then select the tetris.asm file.
  4.) Then, click the crowbar button to assemble the code and click the green right arrow button to run.
  5.) Enjoy!
  
An interesting approached was used to determing when blocks would rotate, essentially the rotation position can be calculated for each block-type by creating an array of 
the differences. For example, if an L type block were to rotate, the x and y-coordinate would remain the same, but each block "cell" would rotate accordingly. 

