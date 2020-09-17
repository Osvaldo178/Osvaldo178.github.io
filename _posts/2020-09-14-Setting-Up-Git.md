---
layout: post
title: Setting Up Git
description: 
summary: 
tags: 
---
Today, Kajari helped us finalize seeting up git through the terminal. We used 

* git clone - The ‘git clone’ command allows the user to pull down the repository from github onto your local machine. This shows up as a folder on your machine. The folder will have the same name as the repository on github.
* git pull - The ‘git pull’ command allows the user to fetch and download content from a remote repository and immediately update the local repository to match that content.
* git status - The ‘git status’ command allows the user to display the state of the working working directory at the application it's being run on. The first time you run this, all the files that have changes in them, should show up as red. 
* git diff - This shows all all of your changes that you did on the file since your last commit. Press enter to scroll down to the end of the changes. To exit this view, type :q. 
* git add . - This adds all of the changes that you've made so you can commit them.
* git status - Use this again to make sure that all of the changes have been staged (On the terminal, the file names should be green to confirm changes have been staged ready to commit)
* git commit -m "Message Here" - The ‘git commit’ command allows the user to commit and individual change to a file.
* git push - The ‘Git Push’ command allows the user to upload local repository work onto remote repository.

The flow of using git follows the order above from git pull to git push. After you do git pull, you should make your changes in sublime txt or your favorite editor. Make sure to save your work on sublime text or the editor. Then, use git status and git diff to make sure that the changes are correct. Use git add to stage all your changes and git commit to save all your changes and git push to push all your changes to the cloud or github.
