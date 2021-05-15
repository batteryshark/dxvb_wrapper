# DXVB Wrapper

This collection of files will let you run DX7VB/DX8VB applications properly in a portable fashion on a modern (w10) OS pretty easily.

It uses my Paradox registry library (https://github.com/batteryshark/pdx) to redirect all the old COM register stuff so you don't have to put a bunch of old DXVB libraries in your system directories.

It also uses a modified dx7vb to load necessary libraries (e.g. dsound, ddraw, d3drm) from your local directory first in the event you want to use a windower or other wrappers/enhancements.

Instructions: 
1. Shim pdxreg32.dll into your exe and away it goes.

Cheers!
