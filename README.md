# Comp2611-Tetris

This project aims to re-build tetris in MIPS.

Currently it is completed. 
How to run:
  * Download NewMars File and run it.
  * Download Tetris.asm file.
  * After running the NewMars File click the "open" button on the top left, then select the tetris.asm file.
  * Then, click the crowbar button to assemble the code and click the green right arrow button to run.
  * Enjoy!
  
An interesting approached was used to determing when blocks would rotate, essentially the rotation position can be calculated for each block-type by creating an array of 
the differences. For example, if an L type block were to rotate, the x and y-coordinate would remain the same, but each block "cell" would rotate accordingly. 


Showcase Link:
https://youtu.be/4xtXJETVsz0
