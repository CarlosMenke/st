st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


#Pathes
This is my custom fork of st, with some patches applied
* enter a vim like browse mode witch MOD + c (scroll/search throu history, copy marked text...)
* new Colorsheme (gruvebox(
* hide cursor when pressing a key
