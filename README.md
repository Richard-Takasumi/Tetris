# Comp2611-Tetris

This project aims to re-build tetris in MIPS.

Currently it is completed,

An interesting approached was used to determing when blocks would rotate, essentially the rotation position can be calculated for each block-type by creating an array of 
the differences. For example, if an L type block were to rotate, the x and y-coordinate would remain the same, but each block "cell" would rotate accordingly. 

