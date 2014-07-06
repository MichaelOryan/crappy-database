data-packager
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

6/7/14 update
---------------

I'm thinking that because I cover databases next year it might be best to leave that until I have a better understanding of databases. Or at least until I've practiced on handling data in a file in a simpler format.

So the goal at the moment is to make a library that can be used to compress a bunch of files or data into a single file and use the same library to pull those files out again. Maybe at random.

With that in mind my library should be able to do the following.

Take a bunch of different data and write it to a file. Without regard to type.
Pull that data out again and return it without regard to type.
Update data in the file. Since this is expected to be done minimally, at least compared to constant updates in a database. Writing the whole file or most of the file again is ok for the moment.
