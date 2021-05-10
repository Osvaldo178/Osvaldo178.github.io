---
layout: post
title: Creating the Whack-a-Mole Game
description: 
summary: 
tags: 
---
Today, I worked on typing club for 30 minutes, and sent my progress to Kajari after. Then, I continued my progression on the game exercises I began, continuing to game three, Whack-a-Mole. The game consisted of the player trying the whack the mole in a specific amount of time, while also trying to get the highest score. [Link to the Whack-a-Mole Game](https://osvaldo178.github.io/WHACK-A-MOLE/) While listening to the instructor explain certain codes, she gave a list of codes necessary for the game to work.

* setinterval() - Executes a specific funtions countless times at set time intervals specified in milliseconds
* classlist - Returns the class name of an element as DOMTokenList. ClassList also adds, toggles, and removes CSS classes of an element, and can only be modified with add() and remove().
* Example of classlist - In this code, the word mole is removed from each square the mole pops up from. 
	```square.forEach(className => {
    className.classList.remove('mole')
  })
  ```
* forEach() - Executes the callback function once for each array element, by returning the value as undefined.
* randomSquare - Places a set time in a square. 
* Example of randomSquare - In this code, the mole is moving every 500 seconds, which is fast and prevents the player from sometimes hitting the mole. If we increased the number to 800 seconds, it slows the mole's movement, therefore, giving the player more time to whack it. The higher the number, the slower the movement, the lower the number, the faster the movement.
	```function moveMole() {
  let timerId = null
  timerId = setInterval(randomSquare, 500)
}
moveMole()
``` 
After writing the code, I pushed the website by creating a new repository named under Whack-A-Mole, and sent it to Kajari to approve the code.

