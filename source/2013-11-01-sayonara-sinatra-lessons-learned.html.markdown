---
title: Sayonara Sinatra! Lessons learned
date: 2013-11-01 15:17 UTC
tags:
---

####Clone Wars Project  

This week we completed the group project [Clone Wars](http://tutorials.jumpstartlab.com/projects/clone_wars.html). Groups of 3-4 took a local business's website and scraped the html, CSS and content to rebuild the site and add features such as admin autorization for editing the site, dynamic banners, user input forms, etc. 

[Original site](http://www.thebikedepot.org/) and
[Our new site](http://bikedepot.herokuapp.com/)

During this project we used Sinatra, SQL, HTML/CSS and the Web/HTTP. If I had to describe the most important aspect of each I learned this past week, id' say:

* HTML/CSS: View Page Source allows you to see the HTML/CSS of any website with links to stylesheets. If a website has a cool style feature you want to copy, View Page Source to see how they implemented it. Stylesheet links are provided, as well.

* SQL: It's pretty intuitive, and if you have experience with excel, think of it in terms of V-lookups when you're writing queries. 

* Sinatra and Web/HTTP: Understanding the basic ideas of GET, PUT, POST and DELETE isn't just trivial. Knowing the basic action of each of these requests makes building a website faster and easier. 
  1. GET = fetches information/a page
  2. POST = posts/stores information on a page
  3. PUT = updates/changes information on a page
  4. DELETE = deletes something on a page

Working in a group of three was great. We used Github tasks to organize our workflow and keep track of parts of the project we were each working on, so as not to duplicate work and make sure everything got done. One drawback of working in a bigger group was merging our work together. We ran into some merge conflicts and at one point, after merging and deleting branches, we lost a small amount of code which I had to redo. Using Git for one project with multiple people was a necessary learning experience, but a frustrating one at that.

Another great thing about this project was that I really got a handle on [Capybara testing](http://www.sinatrarb.com/testing.html). Basically, Capybara tests the user experience by mimicking the user and clicking through the site, filling out forms, and verifying each page appears with the expected content. When building a site, it gets very tedious rebooting the site and clicking through each page to verify the site works as you intended it to. Once in place, Capybara can do that for you.

Next week we jump into Rails!

