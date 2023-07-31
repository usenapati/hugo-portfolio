---
title: Galaga3D
date: 2023-06-07T17:21:10-04:00
draft: false
github_link: "https://github.com/Ankhman12/Galaga3D"
author: "Udayan Senapati"
tags:
  - Unity
  - C#
  - 3D
  - Windows
  - WebGL
  - Single Player
  - Game Jam
  - Group Project
image: /images/projects/galaga3d/galaga3d-1.png
description: "A 3D Space Shooter based off of the original Galaga arcade game. "
toc: false
---

Galaga3D is a 3D Space Shooter Game based off of the original Galaga arcade game. Fight and evade countless waves of enemies using your blasters or lasers and try to beat your own high scores. 

The game was developed with a team of three during the VGDC 2022 Spring Jam, where the theme was recycle. The game was developed using Unity and all game models were created using Blender. 

The team included:
- Udayan Senapati
- Mitchell Dunning
- Phillips Albright

Galaga3D is playable on browser on [itch.io](https://phillips-albright.itch.io/galaga3d) can be downloaded for Windows.

## My Work
Due to the Game Jam's theme being Recycle, I reused my [Asteroid3D](https://chonibi.itch.io/asteroids-3d) Project from CSC461 Computer Graphics course. The project included the ship's controls and abilities, wave system, high score system, HUD UI, and Menu UI. 

For the new game, I designed and implemented the AI Wave system using the[Boid Flocking](https://www.red3d.com/cwr/boids/) algorithm. The waves contained multiple squads that were led by a squad leader. The goal of the system was to recreate a similar Galaga wave system that seemed more realistic for a 3D space. I implemented enemy types, including the base Wasp enemy and Shielded Beetle enemy. The Flocking system can be adjusted through different heuristics including separation, alignment, cohesion, and aggression. The aggression heuristic increases each waves as enemies would target the player ship more often. 

Contributions:
- Player Ship
  - Ship Controls (Thrust, Roll)
  - Camera Controls (Turn, Pan)
  - Input System (Mouse and Keyboard and Controller Input)
  - Third Person/First Person Camera Switching
  - Boosting
  - Weapons (Blaster Projectile and Laser Hitscan)
  - Ship Health Component
- Wave System
  - Flocking System
  - Enemy Class
    - Enemy Aggression
    - Enemy Health
- High Score System
- User Interface
  - Menu Interfaces
  - In-Game HUD