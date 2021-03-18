---
layout: post
title: Position Monsters in Top Left and Top Right of Canvas
description: 
summary: 
tags: 
---
Today, I began work with finishing up a task I started on Monday. The task revolves around positioning both monsterx in the Catch Monster game, one monster needs to be in the top left, and the other monster needs to be in the top right. I positioned Monster 1 on the top left with the coordinates of (0,0). I positioned Monster 2 on the top right with the coordinates of (448,0). The position of Monster 2 refers to the x axis increasing on the canvas, and we want to position Monster 2 within the canvas. For the position of Monster 2, we had to subtract monster width from canvas width, as if we placed Monster 2's coordinates with (512,0), Monster 2 would position outside of the canvas boundaries. Below is the sketch kajari provided for figuring out Monster positions. 
```
    y
x   0 -----------------------------------------------------------------------------------------canvas.width = 512                                                                 Monster(448,0)              |
    |                                                                                    |      |
    |                                                                                    |      |
    |                                                                                    |______|
    |                                                                                           |
    |                                                                                           |
    |                                                                                           |
    |                                                                                           |
    |                                              Hero(256,240)                                |
    |                                               _______                                     |
    |                                               |     |                                     |
    |                                               |     |                                     |
    |                                               |_____|                                     |
    |                                                                                           |
    |                                                                                           |
    |                                                                                           |
    |                                                                                           |
canvas.height = 480-----------------------------------------------------------------------------
```