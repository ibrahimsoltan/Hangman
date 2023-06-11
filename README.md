# Hangman Game

This repository contains the source code for a multiplayer version of the classic game Hangman. Written in Java,
the game can be run as a client-server application.

Description
The game offers a multiplayer experience, where players can create teams and join games. The gameplay is based on the traditional Hangman game rules where players take turns guessing letters in a hidden word.

The program uses a socket-based approach uning multi-threading for client-server communication. 
Client-side operations include actions like sending username details to the server, creating teams, joining teams, sending game guesses, and requesting game configurations. The server handles client connections, maintains lists of online users, active games, teams, and more.
