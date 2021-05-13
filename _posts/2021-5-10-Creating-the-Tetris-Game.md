---
layout: post
title: Creating the Tetris Game
description: 
summary: 
tags: 
---
Today, I worked on the final game for the practice entry, Tetris. Tetris is a game that revolves on the player completing a puzzle within a grid. The player must avoid stacking the tetrominos (the blocks) and instead must make combinations with the tetrominos to avoid stacking.Creating the file for the game was a bit different. [Link to the completed Tetris Game](https://osvaldo178.github.io/Tetris/) Besides creating a Js, css, and html file, I had to create a JS folder, css folder, and and images folder. I would than add the images necessary for the game and than drag the JS and css files to there respected folders.
On the app.js file, I added the code 'addEventListener'. I added the heigh and width of the tetrimino squares, placing them with a 10 square width and 20 height grid. From there, I added 200 ```div``` for the tetromino squares 
```
//The Tetrominoes
  const lTetromino = [
    [1, GRID_WIDTH + 1, GRID_WIDTH * 2 + 1, 2],
    [GRID_WIDTH, GRID_WIDTH + 1, GRID_WIDTH + 2, GRID_WIDTH * 2 + 2],
    [1, GRID_WIDTH + 1, GRID_WIDTH * 2 + 1, GRID_WIDTH * 2],
    [GRID_WIDTH, GRID_WIDTH * 2, GRID_WIDTH * 2 + 1, GRID_WIDTH * 2 + 2]
  ]
```
I wrote the following code that avoids the tetromino from escaping the grid. Any tetromino that gets into a div block, the tetromino should move to the left. For a tetromino to function, there should be 2 codes. A code to for the tetromino to rotate, and a code for the tetromino movement.
```
//move left and prevent collisions with shapes moving left
  function moveright() {
    undraw()
    const isAtRightEdge = current.some(index => (currentPosition + index) % width === width - 1)
    if (!isAtRightEdge) currentPosition += 1
    if (current.some(index => squares[currentPosition + index].classList.contains('block2'))) {
      currentPosition -= 1
    }
    draw()
//Rotate the Tetromino
  function rotate() {
    undraw()
    currentRotation++
    if (currentRotation === current.length) {
      currentRotation = 0
    }
    current = theTetrominoes[random][currentRotation]
    draw()
  }
