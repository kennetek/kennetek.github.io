---
title: VEXU Tipping Point
description: Retroactive post about my robots for the 2021-2022 VEX game, Tipping Point
author: kenneth
date: 2022-05-05 17:00:00 -0700
categories: [VEXU]
tags: [vexu, pyro, tipping point, retroactive]
pin: false
math: false
mermaid: false
image:
  path: assets/img/vexu/tip/thumb.jpg
  alt: Cerberus (24") on the field at worlds
---

> This post was written in May 2024 to reflect the robot states at the end of the Tipping Point season
{: .prompt-info }

## Background
![Desktop View](assets/img/vexu/tip/orthrus2.jpg){: width="300" .right}
For Tipping Point, I was leading a small team, but larger than the two-person team last year. I was still the only one building the robots, but this season there were two programmers and a notebooker. I had just gotten a 3D printer, so used many more 3D printed parts on the robots. Additionally, VEXU requires each team to have two robots, one that fits in a 15" cube and one that fits in a 24" cube at the start of the match. They are very similar, one was named "Orthrus" (2-headed dog, the 15") and one was named "Cerberus" (3-headed dog, the 24"). For more information about the game, see the official game reveal.[^reveal] The most important aspect of the game was being able to grab the large buckets (goals) as fast as possible. 

## Unique Mechanism
![Desktop View](assets/img/vexu/tip/head.png){: width="360" .left}
The unique part of this robot are the heads. They use a single motor to open the jaws, which are on a slip gear setup, so that they can rapidly clamp onto the goals. The inside of the mouth has four bumpers, which trigger limit switches that form logic gates. This is because the geometry of the goal is a heptagon, so we know that the head is in position when either of the middle bumpers are pushed, or both of the edge bumpers are pushed. This allows a single cable to provide a single signal when a goal is ready to be grabbed, allowing the goal to be grabbed as fast as possible. Five of these heads were constructed for the two robots.

## Orthrus

There were two versions, one that was mirrored, and one that had a larger lift for one head and a fixed back head. The robot had to start within a 15" cube bounding box at the start of the match. 
![Desktop View](assets/img/vexu/tip/orthrus1.jpg){: width="330" .left}
![Desktop View](assets/img/vexu/tip/orthrus3.png){: width="360" .normal}

![Desktop View](assets/img/vexu/tip/gif3.gif){: width="500"}

## Cerberus
There were a total of 5 goals available to us to grab, so the idea was to have a total of 5 grabbers between the two robots. That meant the bigger robot had three heads. The robot had to start within a 24" cube bounding box at the start of the match. 

![Desktop View](assets/img/vexu/tip/cerberus1.jpg){: width="350" .left}
![Desktop View](assets/img/vexu/tip/cerberus3.jpg){: width="360" .normal}
![Desktop View](assets/img/vexu/tip/cerberus2.jpg){: width="360"}

![Desktop View](assets/img/vexu/tip/gif1.gif){: width="360" .left}
![Desktop View](assets/img/vexu/tip/gif2.gif){: width="360" .normal}

## CAD Model
![Desktop View](assets/img/vexu/tip/render.JPG){: width="600"}
_CAD model and render of Cerberus by Kenneth_

## Results
We won the Build award at the 2022 VEX Robotics World Championships, which is a recognition for well-constructed robots. 

## Footnotes

[^reveal]: [VEX Robotics Competition Tipping Point : 2021 - 2022 Game](https://www.youtube.com/watch?v=H8XcvADUXTE)
