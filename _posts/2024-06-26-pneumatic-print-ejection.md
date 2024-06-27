---
title: Continuous 3D Printing via Pneumatic Part Ejection
description: Fulfilling client request using a quick and simple solution
author: kenneth
date: 2024-06-26 17:00:00 -0700
categories: [Machines]
tags: [manufacturing]
pin: false
math: true
mermaid: true
image:
  path: assets/img/machines/autoprinter.jpg
  alt: Cylinder in process of ejecting the part
---

A client required a large quantity of a printed ring display. Their requirements are that to use a specific filament, have a smooth surface finish, and have high detail so that small text can be readable. The filament requested is a wood-filled PLA, which suffers from stringing and adhesion issues.

![Desktop View](assets/img/machines/ringer.gif){: width="600"}

To solve this problem, I quickly modified my 3D printer with a pneumatic cylinder to allow for automatic part ejection. This is so that each part can be printed one at a time. This means stringing is not an issue since the printer does not need to move between parts on the build plate, and all the stringing can be contained inside the infill. Then, the printer automatically ejects the parts allowing for continuous printing without operator intervention. This was done by using custom G-Code to make the print head close limit switches, allowing power to flow to solenoids or fans as needed, without the need for another control system. See the video for a full explanation. 

{% include embed/youtube.html id='xiWzBGstu98' %}

