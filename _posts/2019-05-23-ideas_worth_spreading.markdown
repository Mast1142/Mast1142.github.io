---
layout: post
title:      "Ideas worth spreading"
date:       2019-05-23 22:59:52 +0000
permalink:  ideas_worth_spreading
---

#### CLI Project

After playing around with Ruby for a while, learning the basis of Object Oriented Programming, other ups and downs, our cohort finally reached our first project. To create a CLI Data Gem Application.

"What's that?"

Command Line Interface, basically it's where the program will accept input from the user to execute the functions of the application. Looks something like below.



![](https://cdn-images-1.medium.com/max/1000/1*2Pw7--evUBCs5IJVTuqI2A.png)


We need to scrape data off a website of our choosing and create the CLI database with the scraped data. At first glance this project seems daunting for new developers. 

"Why?"

The blank screen, the unknown.

>Unsure where to begin, like other times when we don't know something, we use Google and it usually goes like this... 
- 'How to create CLI Ruby'
- 'CLI Ruby'
- '9gag'
- 'reddit'
- 'CLI Ruby guide'

With a video guide and Google, the hollowed CLI started to form.
Next was to choose a site to scrape.

The first site I chose was something that my SO uses on a daily basis. [Slickdeals](https://slickdeals.net/). 
For those of you that may not be familiar, slickdeals is a site that shows current deals on products ranging anywhere from clothes to food to electronics. The plan was to scrape the front page deals, the name of the product, price, store and link.

![](https://slickdeals.net/blog/wp-content/uploads/2015/08/fp-copy.png)

Unfortunately, slickdeals uses Javascript which could still work but it's a bit harder for a newbie or maybe just me. My stubborness and pride made me push forward, hitting a wall after wall.

* "How do I reference 'href', 'data-href'?"

* "How do I get rid of extra spacing and added lines?"

* "Why is the code returning an empty array?"

After hours of searching through Google, video tutorials and scraping the right and wrong data (mostly wrong). I got all the data I needed, or so I thought. 
The scraper would only scrape the first row of the front page deals, it would stop and crash after the first row. I was **stuck**. Running out of time, I decided to start from the beginning, for now Slickdeals has defeated me. 


I took a short break from coding and browsed Youtube. I started with a music video and an hour later ended up watching a TED Talk about master procrastinators by Tim Urban. For those of you interested [Inside the mind of a master procrastinator | Tim Urban](https://www.youtube.com/watch?v=arj7oStGLkU).

That's when I decided to scrape the [TEDTalk site](https://www.ted.com/talks). Luckily, the hollow CLI is still useable and on the brighter side of things, there were many things that I have learned from hitting all those walls. The new plan is to get the speaker, title, date posted, length of the talk and link. 

When I took a peek at the page elements, a smile appeared on my face. Ideas worth scraping. Scraping would be a lot easier this time around. Within an hour, the data needed was scraped. 

The last step is to link the CLI to the data. Using the past lessons from the course as a guide, I connected the two and my CLI project is complete! 

```
Welcome to TEDTalk CLI - Ideas worth spreading
Most Recent Ted Talks
1.What surviving the Columbine shooting taught me about pain - Austin Eubanks
2.A new way to define self-worth - Liz Powers
3.Why I ask strangers to draw their memories - Janne Willems
```

It is basic and limited in function for the time being. In the future, I would like to revisit my first project and apply all of the knowledge that I will have learned and expand this. I might also tackle scraping Slickdeals again!


