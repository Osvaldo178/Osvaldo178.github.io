---
layout: post
title: Setting Up a Pull Request
description: 
summary: 
tags: 
---
Today we started working with Pull Requests. Pull requests are changes committed in the branch that are presented to viewers of the users repository on Github. The purpose of pull request is to allow others to view your work and make comments on it so that you can make changes before pushing your changes to the main code base. To initiate a new post/pull request, the following commands must be used to complete the task.

* git checkout -b new_post - the purpose of checkout -b is to create a new branch with the name new_post. The branch can have any name, and is usually a reference to the content of the new post with the information of the user that created the post.

* git push ' --set-upstream origin edit_pull_request_post' - The purpose of this command is to get github to recognize your local new branch and push it up to the cloud.
[This is the post of reference of other git commands after creating a new post](https://osvaldo178.github.io/2020/09/14/setting-up-git)

After completing the necessary commands and steps, the user and other collaborators assigned to the repository can view the new post created, and the collaborator added in the repository can view and request changes in the post. After completing those changes, you can merge the branch and complete the post.To make sure you completed the pull request correctly, a yellow banner will pop up in the user's github.io with a green button named:Compare and Pull Request.[Image of yellow banner popping up if succesful with creating a pull request.](image/new_branch_banner.jpg) After clicking on the button, it will take you to the next step, and there's a button with the named:Create Pull Request.[Image of yellow banner popping up if succesful with creating a pull request.](image/new_branch_pull_request.jpg) 
