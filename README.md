# zsx2_w10
Greetings from the Land of the Marzipan Puffins!

This collection of files will let you run Zombie Smashers X2 properly in a portable fashion on a modern (w10) OS pretty easily.

It uses my Paradox registry library (pdxreg32.dll) to redirect all the old COM register stuff so you don't have to put a bunch of old DXVB libraries in your system directories.
It also uses a modified dx7vb to load necessary libraries (e.g. dsound, ddraw, d3drm) from your local directory first in the event you want to use a windower or other wrappers/enhancements.

This game was a great way to test some of my COM proxy redirection logic.

Cheers!
