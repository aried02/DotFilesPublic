# DotFiles
My config files from Ubuntu 16.04 Xenial

Classic .bashrc on the front, still a work in progress please excuse my dirtiness

Inside .config, I only have my sublime-text plugins and my polybar setup. 

POLYBAR

Color is orangeish background and stuff, key commands are:

L-click inside the title goes to workspace middle bottom (normally spotify workspace)

R-click skips current song

L-click outside color pauses and plays

scroll up/down raises/lowers volume respectively

FOR SPOTIFY DESKTOP BACKGROUND

You need to sign up with spotify web api service and get a client id and client secret. There is a tutorial to get started on the online spotify thing and using this (idk if it uploaded correctly, but its a subdir called web-api....) and then visiting localhost:8888 you can find the refresh token and then fill in that in the file as well.

Automatically switches your desktop background to be the album cover of whatever song you are listening to. Updates every 10 seconds, but only redownloads after every song. When you hit ctrl-c to end it, it runs day-night-mode from the coolStuffForModes folder to set the background correct again.
