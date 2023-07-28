---
layout: post
title:  "Freeze Tag"
date:   2019-05-06 00:00:00 -0000
categories: unity
tags:
    - unity
    - game
    - multiplayer
    - c#
    - photon
featured_img: /assets/images/freezetag.jpg
---

Freeze tag was my take on hide'n'seek CS:GO maps. It was a multiplayer game where one player (the host) was the seeker, and the other players were the hiders/runners.

Mechanics:
* The host is the seeker, and the other players are the hiders/runners.
* The host can run faster than the hiders, and can freeze them by colliding with them.
* When/if all hiders are frozen, the host wins.
* If a hider is frozen, they can be unfrozen by another hider.
* There are many interesting hiding spots, including multiple secret rooms that can only be discovered by clipping through walls or jumping over objects.
* The hiders can see each other though walls due to a special outline shader pass.

What I learned:
* How to use Photon's lobby system.
* How shader passes work.
* How to use Unity's audio effects, for audio distortion while underwater.

What I would do differently if I did it again:
* I would allow players to select their own seeker, instead of having the host be the seeker.
* I would add a timer, so that if the host doesn't find all the hiders in time, the hiders win.
* I would make the system a little bit more modular, so that it would be easier to add new maps.
