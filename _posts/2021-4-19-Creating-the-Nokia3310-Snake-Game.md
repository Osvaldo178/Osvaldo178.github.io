---
layout: post
title: Creating the Nokia3310 Snake Game
description: 
summary: 
tags: 
---
Today, Kajari is absent for the next 3 weeks as she's on vacation and in a different timezone. She gave us a notice of asking for any help by messaging her coworkers questions regarding code or help. During her absence, our tasks are to start off with typing club, and than move on after to completing the last four games of the practice. For today, I continued the practice and completed the Nokia3310-Snake game. The game revolves around the player using the arrow keys to move the snake around the border, trying to collect as much apples as possible, while also not trying to collide with itself. The more apples the snake eats, the longer and faster it gets. [Link to the Snake game](https://osvaldo178.github.io/Nokia3310-Snake/) I did as usual, listened to the instructer, and later copied the code. I began with creating a 10x10 grid or 100 sqaures. We also added a height and width of th border, with both being 200 or 20px. 

```.grid div {
  width: 20px;
  height: 20px;
}
```

```<div class='grid'>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
```

After, we drew the snake, applied its functions, and added its color and the color of the apple its hunting. 

```
  let currentIndex = 0 //so first div in our grid
  let appleIndex = 0 //so first div in our grid
  let currentSnake = [2,1,0] 
  let direction = 1
  let score = 0
  let speed = 0.9
  let intervalTime = 0
  let interval = 0
 ```

The code finds the difference between the snakes head and tail, by using the ```<div>``` code, as the ```<div>``` of the snakes head and tail have the value of 2, while the border has a value of 0.


```.snake {
  background-color: green;
}```

I than created the repository and sent the work done today to Kajari, and awaiting her approval.