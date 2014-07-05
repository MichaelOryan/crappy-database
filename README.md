crappy-database
===============


Aim
---------------

I read a post on r/learnprogramming where someone was asking about how to store data in a file and update it. It was a username and password. In lectures we dealt with fixed sized structures being stored in a file which was easy.

The aim of this program is to allow the storage of some variable sized data stored into a file and allow random access of that data. While reducing wasted space and time to build the file as much as reasonably possible. So we don't an infinitely growing file or a file that has to rewrite everything after some data has been updated in the middle.

The idea being that say you have a program you can store all the small pictures or sounds or what ever in one file and access them as required. Or simply have a small simple database you can plug into a program rather than having say an sql server.

TODO
---------------

Rather than just jumping into writing my code I'll be doing some design before writing the body of the code for the program.

Obviously prototype testing of idea and creation of header files are excluded and from what I understand are part of the design process. No real point in writing a function to do something if the idea for it isn't feasible.
