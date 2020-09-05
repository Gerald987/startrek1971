================
 Star Trek 1971
================
------------
 for Python
------------

About
=====

I recently discovered the classic old BASIC game `Star Trek`_ from 1971, through a post seen on Reddit_.

The post contained a version of the game rewritten in C-Sharp which I thought was quite good.
I wondered if anyone had ported it to Python.

After a little bit of research, I didn't find a definitive version for Python.

This is by no means a definitive version itself; I just took the C# version and converted it to Python.

.. _Star Trek: http://en.wikipedia.org/wiki/Star_Trek_%28text_game%29
.. _Reddit: http://www.codeproject.com/Articles/28228/Star-Trek-Text-Game

Improvements
============

There's heaps that can be done with this program. A lot of implementations used global variables.
I tried to fix this by encapsulating them in a global object, but this can definitely be improved further.

Here is a list of possible improvements:

- Encapsulate everything in classes
- Include help/instructions
- Add extra features;
   + new ships, celestial objects, etc
   + new weapon types
   + crew functions
- Easier navigation (using cartesian system maybe)
- Make some parts more 'Pythonic'
- ...Plenty more!

How to use
==========
I changed the game so that there would be a difficulty. But while doing it I made it so that you need the use a command prompt
to get the difficulty, so if you would like to play this game, then download it and run with something like ubuntu.My brother 
made the code from python2 to python3 so I could make further changes to it.