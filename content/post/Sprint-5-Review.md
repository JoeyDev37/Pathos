---
title: "Sprint 5 Review"
date: 2019-02-02T00:16:11-07:00
tags: [sprint-review, update]
author: Joey Weidman
draft: true;
---

# <center>Sprint 5 Review - Big Gameplay Update!</center>

***

### <span style="color:#012033"> <center>Enemy Behavior Revamp</center> </span>

In previous versions of Pathos, we pushed to give the player much more precise
control over the behaviors of enemies. After several iterations of testing the new
mechanics, we realized that passing control of the enemies' actions over to the
user interrupted the gameplay and lead to a somewhat choppy experience.

Our solution was to remove the direct control completely. There is no longer a
long list of well-defined actions that a player can load into a dart. A dart can
now be filled with one specific emotion: Anger, Sadness, Fear, or Joy. Injecting
a guard with one of these emotions forces him to behave in a chaotic, yet
predictable way. A guard will stay in their modified behavior until the
chemicals wear off.

**<span style="color:#c90000"><u>Anger:</u></span>**

Anger is used to **kill** other guards and **break** objects.

When injected with rage, the guard runs to attack the nearest object. His vision
cone narrows and gets further to represent his tunnel vision, and if the
player or another guard happens to be in his path, he will go out of his way to
try and attack them.

**<span style="color:#033f94"><u>Sadness:</u></span>**

Sadness is used to **distract** guards. It is more of a **non-violent** way to
accomplish your goal.

When injected with sadness, the guard will immediately start sobbing and his
vision cone will shrink into himself. This will gather the attention of nearby
guards and they will stare at him until he stops crying. This is a great way to
control the direction of the guards' vision cones and will help you sneak passed.

**<span style="color:#ffd666"><u>Fear:</u></span>**

Fear is primarily used to force guards to **move** to **directed areas**.

When injected with fear, the guard will run away from anyone close to him, and
that includes other guards. His vision cone will widen to the point where it's
an area 360 degrees around him to show his heightened senses. If nobody is near
him, he will cower in a ball. This makes it easy for the player to fear a guard,
and then lead him to a preferred location.

**<span style="color:#00b30c"><u>Joy:</u></span>**

TBD

**<center><u>Summary</u></center>**

This new system is meant to make our gameplay feel a lot smoother. It's a much
more refined, simple system that allows the player to pick up the gameplay
immediately. Although these behaviors are fairly basic at their core, there is
still a lot of room for creativity, chaos, and fun!

***

### <span style="color:#012033"> <center>Updated Vision Cones</center> </span>

The vision cone is our primary way of representing the emotions of an enemy:

- Pulses show their heart rate.
- Color change corresponding to the emotion they are in.
- Angle/Radius change to match with their emotion to show heightened or lowered
  senses. e.g. Anger narrows and increases the range of the vision cone to
  represent rage-induced tunnel vision.


Oh, and the vision cones now project out of their head instead of their knees.

***

### <span style="color:#012033"> <center>Art</center> </span>
Not all of it is in-game yet, but we have some really great art assets in the
making! Below is the model of the guard, and what he looks like in the scene
with some environment assets.
<center> ![Anger](/img/GuardBodyInGame.png) </center>

<center> ![Anger](/img/EnvProgress1.png) </center>

<center> ![Anger](/img/EnvProgress2.png) </center>

***

### <span style="color:#012033"> <center>Animations</center> </span>

We finally started to mess around with some animations. This added a lot to
Pathos because it's hard to convey emotions without the proper animations. There
is a lot more polish that has to be done, but here are some examples of our first
tests:

<center> ![Anger](/img/anger.gif) </center>

<center> ![Fear](/img/fear.gif) </center>

<center> ![Sadness](/img/sadness.gif) </center>

***

### <span style="color:#012033"> <center>Other Random Things</center> </span>

- Yup... literal camera heads! You probably saw them above but I thought I would
  point it out anyways.
- Backpack that displays the changing values of your resources.
- Crouch functionality that we may or may not use.
- Breakable boxes.

***

### <span style="color:#012033"> <center>Conclusion</center> </span>

Overall, our team is very happy with how this mini-pivot has turned out. We are
super excited to start polishing out all of these new mechanics and to start
building some creative levels with them. There is a lot more in the works for
this next sprint, so stay tuned!

<div align="right">- Joey Weidman</div>
