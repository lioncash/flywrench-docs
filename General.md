---
layout: default
title: General
order: 2
---

# General

This section lays out general techniques or notes that don't necessarily correspond to a particular planet.


## Use level boundaries to your advantage

When the ship spawns into a level, it falls quite slowly. This can waste milliseconds if the goal is beneath the spawn point. We can use the bounce mechanic the game gives us to save time, however.

Consider Pluto's first level:

![Pluto - Level 1]({{ site.url }}/images/PlutoLevel1.png)

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

Similarly, when the ship spawns into a level where the exit portal is to the side of the ship or the level progresses in those directions, the level ceiling can be used to get directional velocity depending on how it's angled. For example, consider Neptune's first level.

![Neptune - Level One]({{ site.url }}/images/NeptuneLevel1.png)

In this case, super-fluttering up twice from the spawn point and bouncing off the level boundary close to the vertex can help propel the ship slightly faster than just moving the ship right. The following webms are a comparison between just moving right and bouncing off level geometry:

<div class="video-box">
  <div class="video-box-left">
    <video src="{{ site.url }}/videos/Neptune1RegularRoute.webm" controls muted>
      Your browser does not support the video tag
    </video>
  </div>
  <div class="video-box-right">
    <video src="{{ site.url }}/videos/Neptune1FastRoute.webm" controls muted>
      Your browser does not support the video tag
    </video>
  </div>
</div>
<br>

## The timer is kind of quirky

If you fullscreen the first pluto video above and slowly move the playback slider between 0:00–0:01, the timer goes from 00:00:00.00 to 00:00:00.80, and then drops back to 00:00:00.13. This also similarly occurs between 0:01–0:02. If you think a time you've gotten for a level is kind of bad by a few milliseconds, wait until the next level loads and see if the timer self-corrects itself before starting a run over again.

## Aim for the center of the exit portal

This seems kind of obvious, but it should still be explained.

Exit portals act like a gravity well if the ship is close enough to them—they pull the ship into themselves. Problems with this occur when the ship is entering a portal on a side-angle. If entering on a side-angle, the gravitational pull will cause the ship to drift around the portal a little bit before entering it. This can waste anywhere between a few milliseconds to around 0.2 seconds depending on how wide the drift is.

The following webm shows the gravity well effect.
<video src="{{ site.url }}/videos/ExitPortalGravity.webm" controls muted>
  Browser does not support the video tag
</video>
