---
title: Intro to Git and Github
description: This is a post on My Blog about Git and Github.
date: 2023-02-22
tags:
  - number 2
---
## Version Control
Version control is also known as source control. This is the practice of trackiing and managing changes to sofware code. Version control systems are software tools that help software teams manages changes to source code over time. 

Version control software keeps track of every change to the code in a special kind of database. If there is any error in the code, developers can go back and compare previous versions of the code to help fix the error.

<a href="/blog/firstpost/">First post</a>
<a href="/blog/thirdpost/">Third post</a>


There are many alternatives, I am going t o focus on just Git.

Git is an open source version control system that manages and keeps track of your code.
Github is a service that let you host, share and manage your code files on the internet.
Git comes preinstalled on Macs and Linux systems. You can confirm this by;

git version.
{% image "./git_version.jpg", "image of git version on terminal %}

You can install it from the git site and verify it by typing git version 

create a github account if you do not have one.
you can do this with the Github desktop app or on the terminal.

I feel the desktop interface is pretty straighforward and boring, wheras the terminal is morefun. So I will do this from the terminal.

You will need to set your git username and git email. This can be done by typing the following commands on the terminal:

 git config --global user.name "AS Manor"

this command is used to set the username

 git config --global user.email "abdulsamedmanor@gmail.com"

this command is used to set the email.

to confirm your details, type;
git config --list
{% image "./git_list.png", "image of git details" %}

## Common Git commands to know
git init lets you initialise Git in your local folder
git add 'file_name' lets you add only 'file_name'
git add . lets you add all files in the folder.
git commit stores the added files. use -m for the message. for instance;
git commit -m 'added a new image'
git push uploads to your github account