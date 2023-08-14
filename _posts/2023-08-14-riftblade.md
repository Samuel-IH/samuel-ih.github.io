---
layout: post
title:  "Rift Blade (LOWREZ Jam)"
date:   2023-08-14 00:00:00 -0000
categories: unity
featured_img: /assets/images/riftblade.jpg
tags:
  - unity
  - game
  - c#
  - 2d
  - jam
---

Rift Blade was a 14 day casual game jam that I participated in. The main objective and challenge of the jam is that you are only allowed a 64x64 output resolution. The game was built in Unity, all the coding done by me. You can play it [here](https://zilonis123.itch.io/rift-blade)!

Features:
- 2D Top-Down shooter
- 3 levels, and one tutorial
- 2 normal enemy types
- 2 bosses
- Different ammo types
- Powerups (health, armor, invisibility)
- 3D sound effects
- Music

What I learned:
- How to use Unity's 2D Tilemap system -- including advanced tile rules, and custom tile rule scripts
- How to make a low resolution output cam while being pixel perfect
- How to make TextMeshPro work with pixel perfect bitmap fonts
- How to achieve lighting effects in 2D

What I would do differently, if I did it again:
- I would include the cutscene system in an earlier stage of development. I ended up having to 'hack them in'.
- I would get a level designer to help me out. I ended up spending a lot of time on level design, and I think it would have been better if I had someone else to help me out.
- I would move the audio listener to a different object, and have it follow the target (camera) with a bit of drag. This would prevent issues where the audio makes blips and pops when the camera moves quickly.
- I would use rule tiles from the start. I didn't learn about rule tiles until I was almost done with the game, and I had to go back and redo a lot of the tilemaps.
