---
title: MentorPi Follow The Gap
date: 2026-05-07
---

I just wrapped up my last class of my undergraduate career. Hopefully, its not my final class of my academic career.

## I. Introduction to Mobile Robotics

The last lecture of my last class (Introduction to Mobile Robotics) was for final project presentations. Our group chose to apply some of my expertise (ROS2 and racing algorithms) to a physical robot (HiWonder Mentor Pi). Our project focused on deploying [Follow the Gap](https://www.cambridge.org/core/journals/robotica/article/new-gapbased-obstacle-avoidance-approach-follow-the-obstacle-circle-method/1C71607DC5FBA83BF136168D1ECF7514), a common obstacle avoidance algorithm to the robot. 

## II. Follow the Gap Algorithm

Follow the gap, in the simplest way possible, finds a gap and tries to steer towards it. In practice its more complex than that, but for the sake of your time and mine, that's how it works.

From the lovely folks at UPENN:
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flejunjiang.com%2F2021%2F01%2F28%2Ff1tenth-lab-4%2Ffollowthegap.JPG&f=1&nofb=1&ipt=82b2aec3924e5f9bb7be1c0328343670fc2083a3bc799c1faa0bed5fd514d22b" width="500" height="300" alt="FTG Example">


## III. Hiwonder SUCKS.

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fm.media-amazon.com%2Fimages%2FI%2F51Irv27G4FL._AC_SL1200_.jpg&f=1&nofb=1&ipt=5a8c205d3817495e92fa8b8c83cbb0175166fe8643d73497322a39ba23f8daa4" width="200" height="150" alt="Hiwonder Robot">

This Hiwonder robot was one of the worst robots I've ever worked on in my life (I've maybe worked on a handful). The robot came preloaded with a bunch of bloated example code. And the kicker: **They have little to no documentation on how the actual robot works!!** 

## IV. Results and Code

In the end, we were able to get it working well enough for a somewhat impressive demo. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/tx_zpkABG7Y?si=CobjqYXGQw_1rnbT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


Code can be found [here](https://github.com/Tyler-Oswald/EECS690_project4)

Thanks to group members Tyler, Brandon, and Sophia for the great result! 

And if you were wondering, this was 100% human written! No post on **MY** blog will be AI generated 🔥

