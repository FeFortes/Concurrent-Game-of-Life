# Concurrent-Game-of-Life
Coursework 1 of Concurrent Computing, University of Bristol

Check CourseworkDescription.pdf to see all the details of what the program should do

Implementation of a multi-threaded program on the xCore-200 Explorer board which simulates the ‘Game of Life’ on an image matrix. The board’s buttons, orientation sensors, and LEDs are used to control and
visualise aspects of the game. The game matrix is initialised
from a PGM image file and the user can export the
game matrix as PGM image files. The solution makes efficient
and effective use of the available parallel hardware of the
architecture by implementing farming
communication of parts of the game matrix across several
cores/tiles based on message passing.
