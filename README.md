# Overview

* This is my game called "Street Shooter" where you control the player at the bottom of the screen using the left and right arrow keys. The character automatically shoots bullets/lasers to destroy the crates that are falling towards him. 

* There are 4 types of crates: regular (brown), life (red), power (purple), and speed (green). Each crate has a number on it which indicates how much health it has. Once a crate has 0 or less health, it is destroyed. Destroying a regular crate increasing your score by 1. Destroying a life crate increasing your lives count by 1, and you can have 10 lives maximum. Destroying a power crate increasing your shooting power by 1, so if your shooting power is 5 then you will do 5 damage per shot to a crate. Destroying a speed crate increasing your shooting speed so your shots per second will increase.

* This game scales in difficulty as you play. Score and Power cause future crates to scale up by marginally increasing their minimum health and noticeably increasing their maximum potential health. Health is generated randomly per crate within a set of bounds, which like I mentioned previously will increase as those two factors increase while you play. 

* I also included background music in the game to allow you to listen to something while pleasant while smashing crates!

* This program uses variables, expressions, conditionals, loops, functions, classes, data structures, and inheritance.

* You will need to start the game by running the __main__.py file.

# Video Demonstration

* This is a brief video that I recorded which shows how to play the game and what goes on behind the scenes in terms of the code and structure.

* [Game Demo Video](http://youtube.link.goes.here)

# Development Environment

* The tool that I used to develop the software was Visual Studio Code. This is my favorite Integraded Development Environment because it is a very lightweight program yet it still includes a lot of advanced functionality.
* The programming language that I used to complete this project is Python in version 3.7.8 64-bit. It is a very interesting and unique language which is based around object oriented programming and I enjoy using it very much.
* I used the Arcade module in Python to create this game. It is very useful and allows for much of the functionality that you see on the screen while you play.
* I also used the Pygame module just to implement the music for the game.
* Github is the online repository I used to store this project.

# Useful Websites

These are some of the websites that were useful to me in making this project:
* [W3 Schools Python Tutorial](https://www.w3schools.com/python/)
* [Stack Overflow](https://stackoverflow.com/)
* [Python Arcade Module](https://api.arcade.academy/en/latest/)
