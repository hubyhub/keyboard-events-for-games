keyboard-events-for-games
=========================

This script checks keyboard inputs using polling

This script is meant to be used in javascript games, that need to communicate the keyboard-inputs to a server.
The status of pressed keys is stored in an array, which can be sent to a server on each keyup and keydown event.
To keep that array short, there is the possibility to add "allowed keys".
Also the "repetitive keydown"-events are disabled, to send only 1 event per keyup and keydown.
