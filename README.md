# Guns-And-Spaceships

This interactive two-player, two-dimensional game was created in the programming language Python, more specifically using the built in library Pygame. The game’s objective is to go against another user-controlled spaceship striking bullets at them until one’s heart level reaches zero. This game contains two spaceships: yellow spaceship (left of screen) and red spaceship (right of screen). Each player will be able to move their spaceship with specific keyboard keys. The purpose of developing this game is to gain more knowledge in Python, more specifically Pygame, as I had been interested in doing so. I used Tech with Tim’s series in Pygame tutorials to help me develop this game. This game uses many Pygame Rect objects to store and manipulate rectangle objects, which will allow to detect collision of objects. In addition, spaceships are rotated 90 degrees so they directly face their opponent. \
The game has the following features: 
1. Initial heart levels of 10 for each spaceship which will decrease by 1 if opponents bullets hit their spaceship. This is displayed on the screen.
2. A separation line in the middle of the screen in which neither spaceship can cross.
3. Keyboard keys to move spaceships and strike bullets. Yellow spaceship uses “w” to move up, “s” to move down, “a” to move left, “d” to move right, and CTRL-LEFT to strike bullets. Red spaceship uses UP-ARROW to move up, DOWN-ARROW to move down, LEFT-ARROW to move left, RIGHT-ARROW to move right, and CTRL-RIGHT to strike bullets.
4. Player can only strike 3 bullets at a time.
5. Spaceships move at a constant velocity of 5 pixels per second, with 60 frames per second. 
6. Mathematical expressions are used to create a linear line animation for the bullet's path when striked.
7. Pygame mixer library is used to play sound when user either strikes or gets hit with a bullet.

## Captures
![video](https://github.com/rbrueda/guns-and-spaceships/assets/93105329/babb17db-f1b9-4e3f-a852-885413f75f50)
