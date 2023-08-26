---
title: "Process of making this website"
date: 2023-08-26T09:40:01+05:30
draft: true
decription: "test"
---
A brief explanation of my journey in making this website
<!--more-->
## Figuring out what Hugo actually is
When I first saw the task statement on the document I thought this was going to be pretty easy since I already had some very beginner experience hosting a website using flask, but when I downloaded the theme I was puzzled as to where the html or css files were. 

After a bit of digging I found out that Hugo is actually a website generator and the themes are essentially templates we use to generate our websites, armed with that knowledge I started following the [quickstart guide](https://gohugo.io/getting-started/quick-start/).

## Unexpected Errors
Everything was going fine.. until it wasnt (*\*cue ominous music\**). On running the command to create a new post: `hugo new content posts/first-post.md`, I got a weird error, I thought no problem, ill just google it but to my dismay there were no stackoverflow pages for this particular error, I wasted around 30 mins googling around trying different queries but to no avail.

Finally I decided to read through the quickstart page again, and thats when I realized that in my hastiness I had glossed over a very important piece of information: The version requirement written in the prerequisites, the apt package manager had installed an older version of Hugo, I proceeded to install the newer version using snap and bingo everything was working fine.

**Moral of the story:** Read through the docs if googling fails

## Things I learned
* How to use hugo to create static webpages 
* How to import themes into hugo and customize them
* The `git submodule` command, which lets us use external repositories in our own repo's.
