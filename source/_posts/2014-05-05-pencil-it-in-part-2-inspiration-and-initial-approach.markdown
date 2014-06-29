---
layout: post
title: "Pencil it In Part 2: Inspiration and Initial Approach"
date: 2014-05-05 22:03:25 -0400
comments: true
categories: [Pencil it In, Android Design, Development Process]
---
In the previous article, we covered the problem I had faced regarding my options for lifestyle management. While the specific problem was purely one about organizing college classes, dinners, contacts, and assignments, the discussion provided in the previous post gives general cautions to be wary of when using any type of organizer. This post will further discuss the progress of development by looking at <em>iStudiez Pro</em> and <em>Google Now</em>, two of some of my main inspirations for this app. Furthermore, we will discuss my initial approach to designing a solution to this problem.

<!-- more -->

In my search for the correct app, I came across one MAC alternative. At least...sort of. It was <a href="https://itunes.apple.com/us/app/istudiez-pro/id402989379?mt=12">iStudiez Pro</a>, an in-depth, content-wealthy application that employs heavy use of forms, guises itself in a skeumorphic calendar-like interface, while it primarily functions as a content management system. Here is an app that does everything that I want, except it neither automatically generates my data, nor does it make content management digestible. Now those are huge exceptions, when looked at the number of times the student would access the app per day. For instance, take a look at a situation when the user would need to add some sections and exams.

<br>

{% img center /images/istudiez_class_addition.png %}

{% img center /images/istudiez_exam_addition.png %}

Here, there are so many fields the user is forced to fill and so many buttons to check and interpret. Even if a few of these could be alleviated or assumed, the experience would be better.

{% img center /images/istudiez_course_addition.png %}

Here is <b>another</b> instance in the application where the user has to yet again click something to arrive at another screen.

With all of these extra layers of action between the conception of the idea and the goal, the frustration of the user increases along with the number of extra layers. Therefore, while there is a great emphasis on the control and flexibility of your schedule, in the ideal application, there should be a greater tradeoff between the number of features provided and a seamless and smarter user experience.

Now comes my greatest source of inspiration, and that is Google Now. I think the entire idea of Google Now comes from the right ideal. Here is an assistant that gets out of my way and literally takes **away** navigation, all because it has made the effort to learn to use patterns and data to better serve the user. It brings to you the right information when you need it (such as by location), and nothing more. It collects data about your upcoming events from your email! It encourages simple gestures for its interactions, and provides the option to undo any particular action.

{% img center /images/google_now_intel.png %}

Google Now recognizes patterns of the locations you travel and the shows you your local weather even before you ask. Isn't that neat?

{% img center /images/google_now_swipe.png %}

Here is an example of the swipe affordance for dismissing a card.

What we learn from these lessons is that we need to focus on the details as well. The details include teaching gestures in a subtle fashion, reducing navigation efforts while making the content digestible, and gathering relevant data in pleasingly abstract ways.

<h2>My Approach</h2>

With all of this in mind, we come to my initial approach to creating a student organization app. It's easy to say that an app needs to be perfect, but to actually design off of that is quite challenging. I started off doing some sketches and writings about the app on paper. Note: What you see here was after a couple of iterations. Notice that there's more writing than actual drawing. I believe that simple sketching is fine for ideating initially, but once you've gone through a couple of iterations, you should be able to express the reasons for decisions in your designs, clearly in words. This will also make you a more effective communicator to others on your team. I'm going to leave you to decipher my egregious handrwriting in my designs, because my train of thought is fairly easy to follow.

{% img center /images/hero_screen_1.jpg %}

{% img center /images/sub_screen_1.jpg %}

So what do you think? Do you think any of the possible concerns are accurate? If so, how should I address them? Let's have a discussion in the comments section below. In the next article, if I don't do some more design iterations by then, we'll take a look at my higher fidelity mockups. In addition, at the end of the article, we'll discuss the recently popular development practice I'll be using for this project, managing product development with individual, vertically integrated scopes. 