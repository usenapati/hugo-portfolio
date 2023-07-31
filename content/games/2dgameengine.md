---
title: "2D C++ Game Engine"
date: 2023-06-07T14:44:10-04:00
draft: false
github_link: ""
author: "Udayan Senapati"
tags:
  - C++
  - SFML
  - 2D
  - Game Engine
  - Platformer
  - Top Down
  - Windows
  - Solo Project
image: /images/projects/CSC481-2DGameEngine/gameplay.gif
description: "A 2D Game engine developed for my class, Game Engine Foundations as a solo project. "
toc: false
---
The C++ Game Enginewas created for CSC481 Game Engine Foundations course. This was a solo project that was developed throughout my semester with multiple iterations. Each iteration added new features and systems related to topics such as Collision Detection, Input Handling, Multithreading, Networking, Time Scale, Game-Object Models, Event Management, and Scripting. Over the course of the class, I developed two games using the engine: a multiplayer side-scroller platformer and a top-down survival game with enemy AI. 

Contact me if you want to access the source code and games.

## My Work
Contribtions:
  - Iteration 1: 
    - Created a platformer with collision detection.
    - Implemented player that used keyboard inputs
    - Implemented platform objects
  - Iteration 2:
    - Implemented multithreading that handled player and platform movement
    - Implemented game time so the player could control the speed of the game (half speed, normal speed, and double speed)
    - Used ZeroMQ's library to implement networking. The clients communicate to the server using the REQ-REP model. 
  - Iteration 3:
    - Designed and implemented the Entity-Component game object model.
    - Refactored the entire engine to allow the entity-component system to interact with previous features.
  - Iteration 4:
    - Designed and implemented Event Management System that was tied to Player Spawn and Death, Client Connect and Disconnects, Player Collision and User Input.
    - Redesigned the collision detection system for more accuracy.
    - Created a debug mode to help monitor the player's transform information, game time, and hitboxes.
  - Iteration 5/Final Product:
    - Used Duktape and Dukglue libraries to implement scripting. 
      - The Player can change the color of platform or "kill" the player with the scripts.
    - Developed two games: a multiplayer platformer and a single-player top down arcade survival.
      - For the survival game, I used the behavior tree code from my Game AI class and created enemy AI that can chase the user.
      - Created a sword that can kill the the enemies if they collide.
      - Used Sprites from Legend of Zelda and created an animator component for the player and enemy with a walk animation.