---
layout: default
title: General
order: 2
---

# General

This section lays out general techniques that don't correspond to a particular planet.


## Use level boundaries to your advantage

When the ship spawns into a level, it falls quite slowly. This can waste milliseconds if the goal is beneath the spawn point. We can use the bounce mechanic the game gives us to save time, however.

Consider Pluto's first level:

![Pluto - Level 1]({{ site.url }}/images/Level1.png)

In this case it would be faster to super-flutter upwards twice and then bounce off the apex of the diamond, rather than just letting the ship fall downwards.

Compare the time differences between performing the level by just allowing the ship to fall into the portal, versus using 'bounce strats':

<div class="video-box">
  <div class="video-box-left">
    <video src="{{ site.url }}/videos/Pluto1RegularRoute.webm" controls muted>
      Your browser does not support the video tag
    </video>
  </div>
  <div class="video-box-right">
    <video src="{{ site.url }}/videos/Pluto1FastRoute.webm" controls muted>
      Your browser does not support the video tag
    </video>
  </div>
</div>

<br>
## Aim for the center of the exit portal

This seems kind of obvious, but it should still be explained.

Exit portals act like a gravity well if the ship is close enough to them—they pull the ship into themselves. Problems with this occur when the ship is entering a portal on a side-angle. If entering on a side-angle, the gravitational pull will cause the ship to drift around the portal a little bit before entering it. This can waste anywhere between a few milliseconds to around 0.2 seconds depending on how wide the drift is.

The following webm shows the gravity well effect.
<video controls muted>
  <source src="{{ site.url }}/videos/ExitPortalGravity.webm" type="video/webm">
  Browser does not support the video tag
</video>
