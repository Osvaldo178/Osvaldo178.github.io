---
layout: post
title: Creating the Memory Game
description: 
summary: 
tags: 
---
Today, we began work with continuing our progress on Typing Club. After, we sent Kajari the results and she gave us a new task. The task revolves around a youtube video based on coding 7 different games to help us understand more of the variety of games to code. [Here is the video we are currently using for the tasks](https://www.youtube.com/watch?v=lhNdUVh3qCc) The video gives explanations and goes step by step on certain coding elements in order for the specific game to function. The first game we worked on is the Memory Game. [Link to the Memory Game](https://osvaldo178.github.io/Memory_Game/) I created a new folder titled Memory_Game, and added the specific files to commit the game to work. I than created an Images folder for the game and added the images provided to us by the instructor of the video. I added the html page layout and began copying the instructor's code. The instructor would teach us of what certain elements do, and how the coding functions. Here are the elements the instructor taught us about:

* push() - Allows the user to add new items at the end of the array, while also changing the length of the array.
* queryselector() - Returns the first element from the document object model that matches a group of selectors, or the specific selector.
* setAttribute() - Sets a value of an attribute on the specific element.
* getAttribute() - Gets the value of the attribute of the specific element.
* createElement() - Creates the HTML element specified by tagName.
* appendChild() - Allows you to add a node at the end of the list of child nodes of a specified parent node.
* Math.random() - Gives a random number between 2 and 12
* sort() - Sorts elements of an array in place.
* For loops - Repetition of a control structure that allows you to write loops.

In the Js file, we added an array of cards, two per image, and linked it using other coding for the cards to pop up and function. The cards all have an id, which is used for the code to respond. We set a buffer time in the functions so the check for match function doesn't respond too quickly when the player clicks on a card. We create a set of functions for flipping the card and checking for a match. We also set up other coding within those functions for the game to respond.

After adding the code, we created a new repository for the game, pushed it up, and sent it to Kajari for the approval. [Here is the final product of the Memory Game](https://osvaldo178.github.io/Memory_Game/)