---
layout: default
title: Summer 2020 DREU Project Site
---

* TOC
{:toc}

## About Me

Hi! My name is Alina Hu. I am a rising junior (class of '24) at Harvey Mudd College. I major in Computer Science and Math with a second major in Economics.
My email address is ahu@hmc.edu

## About My Mentor

Meredith Rawls, my primary mentor, is a research scientist in the Department of Astronomy at the University of Washington (UW). She writes software and data pipelines to handle terabytes of nightly images from Vera C. Rubin Observatory's Legacy Survey of Space and Time (LSST), which will produce the highest resolution movie of the night sky ever made. Her background is in stellar astrophysics, and she earned her PhD from New Mexico State University. Lately she studies the plethora of newly-launched commercial satellites in the hopes observers worldwide don't lose the sky. [Her website](https://staff.washington.edu/mrawls/)

Peter Yoachim, my secondary mentor, is also a research scientist at UW Astronomy. He primarily works on telescope scheduler optimization and calibration for Rubin Observatory's LSST. His background is in galaxy formation and evolution, and he earned his PhD from UW. [His website](http://yoachim.github.io)

## About My Project
Vera C. Rubin Observatory's Legacy Survey of Space and Time (LSST) is a ten-year astronomical imaging survey that will begin in 2024 from a new telescope in Chile. Instead of soliciting individual requests for what the telescope should point at, the LSST will uniformly survey the sky every three nights in six color filters to essentially create a decade-long “high resolution color movie” of the entire southern sky, and share massive quantities of data products with the astronomy community. To accomplish this, there is a complex scheduler algorithm that takes into account various science priorities, what has recently been observed, how long it takes the telescope to move to a new target, etc. A new challenge has recently come up with a hugely increasing number of bright low-Earth-orbit satellites (e.g., Starlink) that will leave streaks in LSST images. However, there is not yet a plan to incorporate known commercial satellites into the Rubin scheduler so the worst of them may be avoided. My project is to create realistic simulated forecasts of satellite trajectories and brightnesses, build a tool that uses that data to create new scheduler constraints, and test what the impact is to various Rubin LSST observing programs. In my project, I will explore dodging the satellites predicted to be brightest, dodging areas of the sky with the largest number of forecast satellites, etc.

[Github Repo](https://github.com/dirac-institute/satellite-dodging)

[My Poster](files/poster.pdf)

[My Final Report](files/finalreport.pdf)

## My Blog

[My Blog](blog.html)
