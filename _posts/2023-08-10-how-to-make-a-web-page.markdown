---
layout: post
title:  "How to make a web page"
date:   2023-08-10 17:54:28 +0200
categories: jekyll update
---
# Make a web page with Jekyll
The first assignment is a two part task. One make a web page and that's what this post will be about, how I made a web page with *Jekyll* without having any prior knowlage about web development. We'll host the site on **GitHub**. 
 
# Befor starting
Before one starts with the page there are a couple ting that needs to be done. Not all of the  following points are mandatory, but the way i did it one will need to have instaled all the programms.
1. Homebrew
2. Ruby
3. Jekyll
4. *[VS Code](https://code.visualstudio.com/download)*
5. *[GitHub Desktop](https://desktop.github.com)*

To install Homebrew, Ruby and Jekyll, there is a step by step guide on: 
<https://jekyllrb.com/docs/installation/macos/>

# Repository from *GitHub*
Make a new repository. To make a repository for a web page one will need to name the repository a special way. *username*.github.io. For me it was *MaxThyes.github.io*. When you have made the repository, make a local copy with *GitHub Desktop*.

# Making the web page with *Jekyll*
I did not manage to get *Jekyll* to build the web page inn the folder I wanted. So I "cheated" and buldt one on my desktop and copied the files *Jekyll* made to the folder I wanted.
In the terminal navigete to the desktop. Use the following command:
**jekyll new *name the project***
I use *jekyll new ADA525*. *Jekyll* now made all files needed to make a web page, with a eksample theme. To build the page one need to navigate into the folder added by *Jekyll* and use the following command:
**jekyll serve**
One can now go to a web browser and use the following address:*localhost:4000*. This is a local host of ones web page.
In the terminal, press *ctrl-c* to stop the local host.
Now copy all the files from the folder *Jekyll* made to the folder made by *GitHub Desktop*. Commit and push all the files to ones online repository. This will take some time the first try. To make sure *GitHub* konws what file to start with. Go to **github.com/"username"/"username#.github.io** -> **Settings** -> **Pages** and check *Branch*, one wants to have selected *main* and */root*

# Adjust the templet and add posts
The page that was just made is an example page filled with example content. Go to the first post on the page and there are an instruction on how to add posts and change the content on the page. When adding new posts one must remember formatting the file name and the location to save the file. All this is mentioned in the first post. One of the advantages of *Jekyll* is that one can write the files with *markdown* and *Jekyll* converts it to HTML. When a new post is added to the *_posts* folder one will need to tell *Jekyll* a new post is added. To do this open the terminal, navigate to the folder of your page and use the following command:
**jekyll build**
Open *GItHub Desktop*, commit and push the new post.