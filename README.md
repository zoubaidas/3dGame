# Flight shooter simulator

### Introduction

This project consists of improving a simple web game made as part of the TWEB course.  
The original game features vehicles that can send rockets. these rockets can injure vehicles when they hit them. Which leads to decrease the vehicle health.  
The game server is multiplayer, other players can join the game.  
https://github.com/tweb-classroom/07-websocket-solution

For this project we have chosen 2 improvements to make: 
- Create a 3d version of the game.
- Improve the gameplay.


### 1. 3D
#### Game UI 
  - Game scene: A single scene where tha game take place.  
  - Score scene: A scoreboard with game results.  
  - Sounds and Music: Game music, vehicule engine sound, crash sounds, hitting targets sounds.
  
#### Camera
Third-person shooter (TPS) or/and First-person shooter(FPS)

#### Map
A large empty cube that represents the sky with a solid ground terrain below.
Like the original game, when the plane reaches the limit of the map, it comes out on the other side

#### Plane movement

The plane moves straight ahead on its own.
- Click to toggle course Lock.
- Up Arrow to accelerate.
- Down Arrow to decelerate.
- Mouse as aircraft stick or yoke:
- Mouse up/down : to go up/down.
- Mouse Left/right : to turn.
- Space bar to shoot

#### Models
Planes, targets, skybox, terrain.   
Imported from the  internet 

### 2. Improve the gameplay

#### Goal 
The goal of the game is to gain the maximum number of points within the time limit.

#### Rules
- There will be floating targets in the sky. when the player hits the target, he destroys it and earns points.
- When the plane hits the ground, it crashes.
- When the plane hits another plane, it crashes.
- When the plane crashes, the player loses points and rejoins the game after a few seconds

#### the starting situation 
The player that joins the game, finds himself directly in game with 0 points.

#### End-of-game conditions and victory
At the end of the fixed time, the player's score is displayed.
