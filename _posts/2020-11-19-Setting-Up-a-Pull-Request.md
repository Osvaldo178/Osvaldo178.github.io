---
layout: post
title: Setting Up a Pull Request
description: 
summary: 
tags: 
---
Kajari instructed Celeste and I to start creating a new post using pull request. Pull requests are changes you committed in a branch that are presented to viewers of your repository in github. After completing the first commands of ls-cd(Insert github name) you open up the folder with the posts structured in: _posts at this case. To initiate a new post/pull request, the following commands are necessary for committing the task. 
* Opening up the folder - allows the user to insert the following command to initiate a new post and pull request.
* git checkout -b new_post -  Allows the user to create a new post/pull request in their repository.
* git status - The ‘git status’ command allows the user to display the state of the working working directory at the application it's being run on. The first time you run this, all the files that have changes in them, should show up as red. 
* git diff - This shows all of your changes that you did on the file since your last commit. Press enter to scroll down to the end of the changes. To exit this view, type :q. 
* git add . - This adds all of the changes that you've made so you can commit them at the end.
* git status - Use this again to make sure that all of the changes have been staged (On the terminal, the file names should be green to confirm changes have been staged ready to commit)
* git commit -m "Message Here" - The ‘git commit’ command allows the user to commit an individual change to a file. In the message write what you did.
* git push - The ‘Git Push’ command allows the user to upload local repository work onto remote repositories.

After completing the necessary commands and steps, the user and other applicant assigned to the repository can view the new post created, and that applicant added in the repository can view and request changes in the post. After completing those changes, you can merge the branch and complete the post. 
