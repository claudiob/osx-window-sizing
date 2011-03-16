OSX Window Sizing
=================

OSX Window Sizing is a set of apps that makes it dead-simple to change the size of 
your windows.

This fork includes extra scripts to resize specific apps to certain places on the screen. I have them bound to ctrl-[1,2,3,4,5,6,7,8,9] for easy access. Use them as a starting point for your own window management.

sizes
--------

* ctrl-[1,2,3,4] resize the current window to a quarter of the screen (top-left, top-right, bottom-left, bottom-right)
* ctrl-[5] resizes the current window to full screen
* ctrl-[6,7,8,9] resize the current window to half of the screen (left, right, top, bottom)

Installation
------------

Install the scripts by typing `rake install` in this directory. This will compile the
applescripts into .scpt files and copy them into your ~/Library/Scripts folder.

Usage
-----

To compile and run all scripts to ~/Library/Scripts, run

  rake install

It is recommended that you bind the scripts to shortcut keys in the system. I personally
use `ctrl-shift-M` for maximize and `ctrl-shift-C` for center.

Running `rake install_fastscripts` will download a free app called FastScripts Lite,
mount it, and open the mounted folder so you can complete the installation. This will
provide a menu-bar replacement for the `Scripts` menubar that will allow you to attach
keys to any script.

OSX Window Sizing will only work if the window in question is the front-most window
(future versions might provide support for choosing the window or windows you wish 
to resize).