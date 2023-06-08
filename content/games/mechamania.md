---
title: "Mecha Mania"
date: 2023-05-27T17:10:10-04:00
draft: false
github_link: "https://github.com/usenapati/Mecha_Mania"
author: "Udayan Senapati"
tags:
  - Unreal Engine
  - C++
  - FPS
  - Multiplayer
  - Windows
  - Steam
  - Active Development
  - Solo Project
image: /images/projects/mechamania/gundamevolution2.jpg
description: "A Multiplayer FPS fan game inspired by Titanfall 2 and Gundam franchise."
toc: false
---

Mecha Mania is a multiplayer first-person shooter inspired by Titanfall 2 and the Gundam franchise. The game is being developed in Unreal Engine 5 and will be available for Windows. Compete in a 3v3 team deathmatch where you must gather mech parts and obliterate the enemy team with your completed mech. Throughout the arena, you'll have an arsenal of weapons and tools to help you stop the enemy team. Use your movement abilities, including wallrunning, sliding, and climbing, to traverse your environment and outmaneuver your enemies.

The project's goal is to create a complete networked multiplayer game in Unreal Engine using C++, while learning the core fundamentals of the first-person shooter genre.

## My Work
For this project, I focused on implementing a first-person shooter (FPS) game using C++ and Blueprints in Unreal Engine 5. This project served as a learning opportunity for me to gain experience with developing a networked multiplayer game in Unreal Engine 5. Additionally, I wanted to understand and recreate features from modern FPS games, such as different weapon types, player abilities, and objective-based game modes.

Contributions:
- Multiplayer Plugin
  - Independent Plugin that connects to the Steam Online Subsystem (Requires Steam Login)
  - Handles Hosting and Joining Sessions
  - Loads Lobby and Game Map
- First Person/Third Person Character Class
  - Locomotion and Camera Controls (3Cs)
  - Swap between First Person and Third Person Camera
  - Keyboard and Controller Support
  - Animation State Machine (Aim Offsets, Blendspaces, and IK)
- Combat Component Class
  - Handles Character's Weapon Inventory
  - Weapon Firing and Reloading Montages
- Weapon Class
  - Projectile Spawning
  - Fire Effects
  - Hit Events
  - Bullet Shell Physics
  - Different Weapon Types (Projectile and Hitscan)
- Character Ability Component Class
  - Interfaces with Character Movement Component to allow for movement abilities
  - Wall Running
  - Sliding
- Match State Class
  - Game Timer
  - Custom States

## The Future
This project is currently in active development. I am currently working on fleshing out the player abilities and polishing the game mode. Afterwards, I plan to create the game map and AI bot system. Next, I want to add more features inspired by the Gundam franchise, particularly a Gundam that can be controlled by the player. Lastly, I am using Lyra Game models and animations, as well as Epic Games' weapon models and animations, which are sufficient for early development. Depending on whether I release this project publicly, I am interested in learning more about low-poly modeling and may try to create low-poly assets based on the PS1 Gundam games.