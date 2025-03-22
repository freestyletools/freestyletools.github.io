---
layout: default
---

<video width="100%" controls>
    <source src="/video/FreeStyleTools-overlay-1.0.mp4" type="video/mp4">
</video>

Use the [EO SwimBETTER smart paddles](https://www.eolab.com/swimbetter) and some python magic to create video overlays for analyzing freestyle swimming! ([YouTube version](https://youtu.be/eUXJ5JU0cXE)).

The graphs at the bottom show the force pointing backward per arm. The other graphs display the path of each hand, with red arrows representing the direction and magnitude of the force applied to the water. For each stroke, the time spent in the glide, pull, and recovery phases is displayed, along with the stroke rate at that moment.

## One pull analysis

Here are four frames from the video of a single pull with the left arm. Look at the graph in the bottom left: there is a larger peak followed by a smaller peak. Let's analyze what is happening:

![](/images/left-1.jpg){: width="100%" }
*The left arm generates force toward the back.*


![](/images/left-2.jpg){: width="100%" }
*Now there is a dip in the backward force, and we can see that the hand is actually pointing and pushing inward.*

![](/images/left-3.jpg){: width="100%" }
*The hand has straightened again and is pushing backward.*

![](/images/left-4.jpg){: width="100%" }
*The hand is pointing inward again and has stopped pushing backward.*

## Source Code

Want to try creating the overlays yourself? If you know what you are doing, you can find the source code [here](https://github.com/freestyletools/swimbetter-plot)
