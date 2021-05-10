---
layout: post
title: Creating the Space Invaders Game
description: 
summary: 
tags: 
---
Today, we continued the practice and began working on the Space Invaders game. The game revolves around the player trying to shoot as many invaders as they can, while avoidng the invader's lasers. [Link to the Space Invaders game](https://osvaldo178.github.io/space-invaders/)The main objective is for the player to destroy all the invaders.
We started working on the code firstly with the html file, by creating a 15 x 15 grid for the game. The 15 x 15 grid consist of 225 ```<div>``` codes, which is a fairly large grid. I created 10 ```<grid>``` codes, copied it, than pasted it multiple times until 225 ```<grids>``` were created to not waste time. I than moved on to creating a seperate tag for score display everytime the player destroyed an invader. 

```
<h3>Score:<span id="result"></span></h3>
```
I than moved on to styling the items being added into the game: Invader, Shooter, Laser, and Boom. I added the codes to add color and the raidus of the items, than created a seperate code for the width and height of the border.

```
.invader {
	background-color: purple;
	border-radius: 10px;
}
.shooter {
	background-color: blue;
}
.laser {
	background-color: yellow;
}
.boom {
	background-color: red;
```
The app.js side was very difficult, as the intructor would sometimes come back to the code ad change it up. We created code for the movement of the imvadrs and the ship the player controls. We also added code that allows collision when a player shoots a laser towards the invader. 