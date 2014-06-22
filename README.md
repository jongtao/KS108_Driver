KS108 Driver
============

A minimal KS108 LCD Driver Implemented for AVR with PC utilities to convert PNG
images to C constants.


lcd.c
-----

The low level driver for the KS108 LCD controller.



graphics.c
----------

The higher level graphics driver, containing text and drawing functions. This
is not necessary to drive the LCD, but it includes text and rectangle drawing
functions.


png2hex.c
---------

Command line utility to convert a PNG image into a C constant (in hex values).
Simply copy output into your C program to use it. graphics.c includes examples
of use.
