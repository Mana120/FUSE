# FUSE
SEM 4 Socket Programming Project.
The game is called "FUSE," and it involves two players controlling colored rectangles on a screen, trying to reach a randomly generated target point.

Here's a brief overview of the project:

Game Description:

The game is called "FUSE."
Two players control colored rectangles on the screen.
The objective is to reach a randomly generated target point (green rectangle) by moving the players using keyboard inputs.
Pygame Window and Graphics:

The game window is created using Pygame with the title "FUSE."
The game graphics include player rectangles and a target rectangle (green).
The "win" object represents the Pygame window.
Network and Server:

The game uses sockets and pickling for network communication between clients and the server.
The server listens for incoming connections from clients and handles them in separate threads.
The server maintains a list of active games, each identified by a unique game ID.
Game Logic:

The game keeps track of the player's movements, the target's position, and the number of wins for each player.
The game is divided into multiple rounds, and each round is complete when one player reaches the target.
Players can move their rectangles using keyboard inputs (arrow keys).
The game checks if a player has reached the target and updates the score accordingly.
The game ends when all rounds are completed, and a winner is determined based on the number of wins.
Menu Screen:

The project includes a menu screen where players can click to connect to the game.
The "menu_screen()" function displays the menu, and when the players are connected, it starts the main game loop.
Overall, this project demonstrates a basic implementation of a multiplayer game using Pygame and a simple client-server architecture. Players control colored rectangles to reach a target, and the server handles game logic and communication between players.

The starting window
![image](https://github.com/Mana120/FUSE/assets/90771545/4eade5ee-25e5-42ae-8ba0-038182af96d1)


The waiting window as the game will not start untill two players join the game.
![image](https://github.com/Mana120/FUSE/assets/90771545/0ab5f15e-fdd5-4227-98f4-18a98e10e492)


The game window
![image](https://github.com/Mana120/FUSE/assets/90771545/30e5df50-3599-447b-8057-62a8f1282443)

The game ending winndow
![image](https://github.com/Mana120/FUSE/assets/90771545/e9f8ea33-44b2-40ec-a38c-278d20153611)

![image](https://github.com/Mana120/FUSE/assets/90771545/aa20143b-0c36-475a-9f0a-dcaa2d3023ad)



