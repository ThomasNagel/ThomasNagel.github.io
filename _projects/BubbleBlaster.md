---
layout: page
title: Bubble Blaster
description: School project with AI
img: assets/img/BubbleBlaster.gif
importance: 1
category: School
---

This is a project I made with a friend for our PWS.
We made a simple little game where two players try to get as much bubbles as possible.
The red submarine is a real player and the yellow submarine is an AI.
To make the game more interresting we added a nuclear bubble that gives a speedboost.
The AI is trained with the [NEAT](https://neat-python.readthedocs.io/en/latest/) python library.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BubbleBlaster.gif" title="Game" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example of a match between AI (yellow) and human (red)
</div>

This game was made in pygame.
Every frame a new background image is drawn and all the objects in the game are drawn over it.
This new image is the displayed on the screen.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BubbleBug.gif" title="Game with bug" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Background image is not drawn. Resulting in this visual bug.
</div>

You can find the code [Here](https://github.com/ThomasNagel/BubbleBlaster-PWS)