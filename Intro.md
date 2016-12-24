---
layout: default
title: Intro
order: 1
---

# Intro

This section lays out a basic crash course on game mechanics.

## What is Flywrench?

A really good game made by Messhof, LLC. See the homepage [here](http://www.flywrench.com).

## Goal

The goal of every level in Flywrench is to move your baton-looking ship into a square-looking exit portal.

## States

There are three states that you can shift your ship into and out of:

### Neutral

![neutral state]({{ site.url }}/images/Neutral.png)

This is the default state that your ship will be in when you aren't pressing anything. In this state, the ship can pass through white barriers as well as be moved left or right freely, however the ship will fall towards the bottom of the level with increasing velocity. This state is the most flexible state for precision-based movement.

### Flap

![flap state]({{ site.url }}/images/Drop.png)

Flap state is named as such, because changing into this state and then back to neutral state in succession repeatedly is how you make the ship stay aloft. While held in this state, any other directional velocity of the ship is slowly lost and the ship will begin to fall towards the bottom of the level as with neutral state. However this state allows the ship to pass through red barriers. While this state allows the ship to move left and right, its range of movement is significantly less than what neutral state allows.

When entering flap state without holding the up direction, the ship will lightly rise and then begin to fall. When the up direction is held, however, the ship will raise even higher—this is called a super flap. There's also different sound effects that the game plays to distinguish between which kind of flap occurred.

When the down direction is held and flap state is entered, the ship will not gain any height. This is useful when traveling downwards but wanting to maintain speed through a red barrier—this is called an anti-flap.

### Bounce

![bounce state]({{ site.url }}/images/Bounce.png)

In this state, the ship rotates on its center and begins to fall downwards or arc downwards depending on how the ship was moving. This state will cause the ship to bounce if it hits yellow level geometry — picture a bouncy ball hitting a wall, but replace the bouncy ball with an interstellar ship. Significance of a bounce depends on what direction a surface was hit, and the speed of the ship on contact.

While in this state, moving in any direction will not move the ship itself, but will influence bounces very slightly. It also allows the ship to pass through green barriers.
