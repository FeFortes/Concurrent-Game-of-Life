# Concurrent-Game-of-Life
Coursework 1 of Concurrent Computing, University of Bristol

Check **CourseworkDescription.pdf** to see all the details of what the program should do  
Check **COMS20001/GameOfLifeReport.pdf** for information about Functionality and Design; Tests and experiments; Critical analysis 

## Description


Implementation of a multi-threaded program on the xCore-200 Explorer board which simulates the ‘Game of Life’ on an image matrix. The board’s buttons, orientation sensors, and LEDs are used to control and
visualise aspects of the game. The game matrix is initialised
from a PGM image file and the user can export the
game matrix as PGM image files. The solution makes efficient
and effective use of the available parallel hardware of the
architecture by implementing farming
communication of parts of the game matrix across several
cores/tiles based on message passing.

## Analysis


**COMS20001/GameOfLifeReport.pdf** is divided in 3 sections, containing information such as: 

* Functionality and Design
* Experiments: time measurements as a function of the number of workers, how they are distributed between the tiles and the image size (to execute 100 cycles of the game of life). The results are interpreted analysed in detail.
* Critical analysis: performance of the system and ways to improve it
