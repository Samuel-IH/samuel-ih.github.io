---
layout: post
title:  "Battletide"
date:   2019-02-12 00:00:00 -0000
categories: unity
featured_img: /assets/images/battletide-1.jpg
tags:
  - unity
  - game
  - multiplayer
  - c#
  - photon
---

![Battletide -- gameplay](/assets/images/battletide-2.jpg){: width="500" }

Battletide was my first game made with Photon (PUN). It was a multiplayer FPS where the players competed to get monopoly of all the projectiles. I learned a lot about performance optimization in this game, due to the fact that I used a higher-quality resource pack than I had used for other projects. It didn't initially run very well, but after some optimization I managed to get it running at a solid 60fps.

Mechanics:
* 20 projectiles are added to the game per player.
* Players start with 10 projectiles each, and the remaining 10 are placed in a 'pool'.
* The un-claimed projectiles spawn randomly over time at different locations, players seek to pick them up.
* Players can shoot their projectiles at others, it takes 4 hits to 'kill' a player.
* When a player dies, they drop all their projectiles at the point of their death, and respawn at a random location.
* When a player shoots and misses, the projectile is dropped at the location where it hit.
* The first player to capture 75% of the projectiles in the game wins.

What I learned:
* How to use Photon's networking system (PUN).
* How to use profiling tools in Unity.
* How to bake lighting, and best practices for lighting (improve visual quality and performance).
* How to make modular components (C#) and prefabs in Unity, and how to improve my workflow with them.

What I would do differently if I did it again:
* I would add a timer, so that if no player has won after a certain amount of time, the player with the most projectiles wins.
* I would add a lobby system.
* I would improve the player controller. The one used in this game comes right out of the Unity Standard Assets, and it's not very good.
* I would improve the crosshair, make it more dynamic and add in a recoil/accuracy system.
* I would make the minimap use a pre-baked texture, instead of using a realtime top-down orthographic camera.
