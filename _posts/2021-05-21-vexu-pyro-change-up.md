---
title: VEXU Change Up
description: Retroactive post about my robot for the 2020-2021 VEX game, Change Up
author: kenneth
date: 2021-05-21 17:00:00 -0700
categories: [VEXU]
tags: [vexu, pyro, change up, retroactive]
pin: false
math: false
mermaid: false
image:
  path: assets/img/vexu/changeup/thumb.jpg
  alt: PYRO Change Up robot (15")
---

> This post was written in May 2024 to reflect the robot states at the end of the Change Up season
{: .prompt-info }

## Background

![Desktop View](assets/img/vexu/changeup/gif1.gif){: width="200" height="200" .right}
I had joined PYRO last year for the previous VEX game, Tower Takeover, but this year most of the team had graduated. And by most, I mean all. And due to the pandemic, the only two people who remained on the team were myself and a programmer. This meant, with very little VEX experience, I had to learn how to build and lead a team. Because everything was closed down, including the school, we were unable to get travel funding to go to the world championships, but we did qualify regardless through our skills score. This year acted as a practice year when I learned the basics. For more information about the game, see the official game reveal.[^reveal]

![Desktop View](assets/img/vexu/changeup/gif2.gif){: width="360" .left}

![Desktop View](assets/img/vexu/changeup/gif3.gif){: width="360" .normal}

## Unique Mechanism

![Desktop View](assets/img/vexu/changeup/clutch.png){: width="360" .left}

The unique part of this robot was the one-way bearing used on the intake arms. It was inspired from a design found online.[^footnote] It allowed us to use a single motor per intake arm, where rotating the motor one direction would open the arm, and rotating the other would spin the intake rollers to pick up a ball. It works by allowing free movement in one direction, but in the other it jams the pins into the walls and restricts movement. The main improvement this offered over the alternative, which is a ratchet, is that both arms move in sync. A ratchet has a discrete number of teeth, so when moving the arms backwards, the pawl will catch at a different time on each arm, so the arms do not expand together. These 3D printed clutches have no discrete catch, so both move out at with the same delay, allowing simpler programming and a more reliable robot.

## CAD Model

CAD was done using Solidworks, but only the drivetrain and arms were completed, the rest of the robot was built freehand. 

![Desktop View](assets/img/vexu/changeup/render.png){: width="640"}


## Footnotes

[^footnote]: [Maker's Muse one way bearing](https://www.youtube.com/watch?v=UIhCPl8eb7s)
[^reveal]: [VEX Robotics Competition Change Up: 2020 - 2021 Game](https://www.youtube.com/watch?v=Hxs0q9UoMDQ)