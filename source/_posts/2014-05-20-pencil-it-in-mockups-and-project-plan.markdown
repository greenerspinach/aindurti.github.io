---
layout: post
title: "Pencil it In Part 3: Mockups and Project Plan"
date: 2014-05-20 14:31:20 -0400
comments: true
categories: [Pencil it In, Android Design, Development Process, Project Planning]
---
In the last article, we discussed my inspirations, such as iStudiez Pro and Google Now, in the design of the app. I also showed you my initial approach and wireframes for it. We learned that an app that simplifies the achievement of specific goals should focus on the details as well, delighting and surprising the user for the right information when he or she needs it. This post will further go into the progress of development by taking a look at the mockups I've made over a few design iterations. Finally, I will give you my insight into how I will plan this project with <a href="http://37signals.com/">37signals'</a> idea of <a href="http://feltpresence.com/articles/16-managing-product-development-by-integrating-around-concerns">Managing Product Development by Integrating Around Concerns</a>.

<!-- more -->

Here is a storyboard I put together from some of the screens from the wireframes. As you can see, the mockups don't differ much from the wireframes. However, I did add an empty state to the design, because I felt that the user would need to be greeted with a meaningful post-install screen. There is also a form screen to show you what kind of forms I'd be providing, for the worst case where the user actually has to give manual input.

{% img center /images/storyboard.png %}

Note that these higher-fidelity mockups exist to more easily portray a story in a person's head. By leaving all of the clutter of paper wireframes behind, these let the viewer digest the app better. A story is just as, if not more important than features. If you can convince someone that your app solves for a specific use case, you can more easily convince them to use your app.

<h2>The Plan</h2>

Designing a project plan for this app was tricky, until I came across a methodology defined by Ryan Singer, a designer and product manager at Basecamp. Obviously, I came about this whole process the wrong way since I should've decided on a practice first before I went in and started designing the app. But since I did not know about this process beforehand, I had to adapt my plan to include my already completed designs.

As the idea puts it, using individual, vertically integrated scopes of work is a good way to go. But what does that mean, exactly? You can read more about it in Singer's <a href="http://feltpresence.com/articles/16-managing-product-development-by-integrating-around-concerns">post</a> and watch a <a href="http://vimeo.com/68342874">video</a> about it. I highly recommend looking at his content on this topic at <a href="http://feltpresence.com/">feltpresence.com</a>. As Singer starts off, the <em>individual</em> implies separation based on different features or parts of your application, rather than thinking of the entire app as just one big <em>scope</em>, or <em>feature</em>. 

Each separate scope is made up of different parts such as the <b>User Interface</b> (this could either be what the user sees/interacts with or the methods of an API), <b>Application Code</b> (the front-end/back-end code for your application that uses different frameworks to create complex apps), <b>Frameworks</b> (focuses infrastructure code to accomplish goals, such as libraries), and <b>Infrastructure</b> (the basic services a platform provides). Finally, the <em>vertically integrated</em> part refers to how the different scopes interact with each other. You'll notice that certain scopes require parts of other scopes to be finished in order to be complete. In this case, complete as much as logically possible in this scope and then move onto the parts of the other scope that need to get done. 

{% img center /images/projectplanmine.png %}

So this is how I divided my application into scopes. What do you think about this methodology? While you're at it, tell us what you think of the mockups above. By the next article, I will have finished the <em>Course Management</em> scope, and will keep you posted on my progress. It will also be the first time I show code on this blog.