---
layout: post
title: Overview of My Intership For the Year
description: 
summary: 
tags: 
---
Today, we began work with Typing Club one final time for the year. After completing the task, we met with Kajari to discuss about the presentation we gave to the company about the projects and learnings we worked on for the year. The projects were based on the Html and Javascript work we did: Catch Monsters, Working on creating 7 javascript games, and creating our own website to name a few. On my part, I presented some of the code we used, primarely with Github in pushing pull requests, creating repositories, and uploading our blog posts. I also presented some additions I did to a few projects such as adding images, a search bar, and pages to my Html website, and messing with the monster positions from Catch monsters. I believe the presentations went well but there were some issues with my presentation. I wasn't as prepared to present to the company, I felt that I should have rehearsed my lines a couple more times, and should have added less text to my presentations. I should have prepared some speaker notes also to not always read out from my presentation, a skill I will use for future presentations. 

After the meeting with Kajari, she gave us one final task, to revert the Monster positions from Catch Monsters to be random positions, instead of still positions. I went ahead and completed the task by making Monster positions to be random again.

I deleted the following code string since the code made the positions to be still:

```
monster1.x = 0 
  monster1.y = 0 

  monster2.x = 466 
  monster2.y = 0 
```
I replaced the code string with the following which allowed the monsters to spawn in random positions:

```
  monster1.x = 32 + (Math.random() * (canvas.width - 64));
  monster1.y = 32 + (Math.random() * (canvas.height - 64));

  monster2.x = 32 + (Math.random() * (canvas.width - 64));
  monster2.y = 32 + (Math.random() * (canvas.height - 64));
};
```
I created a pull request after for Kajari to look over and approve. I enjoyed this year since we were tasked with understanding coding further such as Html and Javascript. The tasks weren't easy, but  working on projects and writing notes allowed us to not always have such a difficult time, knowing that coding doesn't get easy. I had fun working on projects such as creating our own Html website and also on creating 7 different games, my favorite projects overall. For next year, I hope to continue working with Html.