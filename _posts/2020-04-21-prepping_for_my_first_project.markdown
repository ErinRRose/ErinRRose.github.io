---
layout: post
title:      "Prepping for my first project "
date:       2020-04-21 14:16:21 +0000
permalink:  prepping_for_my_first_project
---

In preparing my first project, the CLI gem with Ruby, I knew I wanted to use an API.  I had found scraping difficult and cumbersome to do and I felt I was not very effective at it.  

Early in my learning someone shared a git for a bunch of free/public API so I planned to use from the list and work there.  I had an idea to use the one for Open Library, you can search their website for books that have free digital copies to read.  I thought it would be cool to do something with that, but when looking at the API and the site I realized the depth and breadth of the website would make it challenging, especially for my first project.  

I talked with some others who were also working on their projects about what I could do with that idea, and I decided to look for a new idea.  I wanted the topic to be something I had an interest in or something I would do anyway.  LIke the book idea, I read for fun when I can and often look for free digital copies for some books I am interested in reading.  I spent some time on the git resource looking at other APIs and playing with them or their websites to find something I wanted to use and was somewhat straightforward to use. Eventually I found Launch Library.  It is a site that lists all upcoming space launches for the world, with dates, descriptions and the part that I thought was the coolest, a map url to view the launch site.  

At first I felt like I was in uncharted territory using an API and not having done much work with one before. Also this project is meant to test what you know, and get you to work on something other than from tests.  So I learned to work with an API and how to read the associated information.  Thankfully the API I chose had a lot of uses and had been worked on for a while.

My CLI pulls from Launch Library, it pulls the 10, the API only provides 10 even if there are more, most current upcoming worldwide space launches, big or small.  Then from the list you select one of the 10 to take a closer look at, then it will show you that launche's name, date and location with a brief description, and a map url that can be opened in a browser to see the location on a map of the world.  I found this part so cool, it was one reason I was so excited about this API.  

Technically my CLI will not let you enter in a select any number other than 1 through 10, or to simply exit the program, otherwise it will simply repeat the prompt nothing else.  Once inside a listing you can go back to the list or exit the program, nothing else will be accepted and it will just keep repeating the same prompt.  My thought was to keep others from going astray in the program.  

Then to finish it up I colorized it, to give it some space and differences, to keep it from looking like a block of white.  I picked colors I liked but I also wanted it to be appealing to most people. 

In all this was a big learning experience, the point of this, and it helped me learn about what I know and how to stretch myself.  

