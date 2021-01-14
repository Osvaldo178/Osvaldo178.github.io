---
layout: post
title: Pushing Up Our Websites
description: 
summary: 
tags: 
---
Today, we pushed our websites through the terminal and uploaded it into a new repository under our website name. We first created a new repository and used a set of commands to accomplish that task. Once we completed in creating our website's repository, we added urls of our site onto our repository. [This is my website](osvaldo178.github.io/thinkment/). Here the commands we use to upload our website and for future reference.
`git init.` -- initialise an empty repository locally (on your computer even if it's not online)
`git add .` -- add all the new files 
`git commit -m "first commit".` -- create the commit
`git branch -M main`  -- create a new main branch called main
`git remote add origin git@github.com:Osvaldo178/Thinkment.git` -- tell your local repository that it will connect to  `git@github.com:Osvaldo178/Thinkment.git` when it is pushed onto the real internet
`git push -u origin main` -- push this repository onto the real internet
in each case where you see the word origin, that means we're referring to github's knowledge of your repository