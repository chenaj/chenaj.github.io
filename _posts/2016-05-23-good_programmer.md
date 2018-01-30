---
layout: post
title:  "What makes a good programmer?"
date:   2016-05-23
desc: "What makes a good programmer?"
keywords: "chenaj,software,engineering"
categories: [Engineering]
tags: [chenaj,programming]
icon: icon-html
---

I found myself toiling on a programming assignment for days, while a classmate of mine spent a few hours on the 
same assignment. I thought to myself, "Man, that person must be a good programmer". Then, it got me thinking...what 
does it mean to be a good programmer? Does it mean being a Javascript ninja? Or know everything about how an OS works? 
Or having the ability to put together a mobile app that is cleanly architected and maintainable? Or reason about 
complex algorithms? I struggled to answer. It’s hard to define a “good programmer”.

I asked many of my peers. And it usually comes down to two categories of what comprised of being a good programmer. 
Realizing that computer science is an incredibly broad field, some agreed that to being good you’re required to be a 
generalist, having large breadth knowledge. For example, being a to be a competent full stack developer you have to be 
able to know how to use a wide variety of technologies:  HTML/CSS, Python, Django, PostgreSQL, JavaScript + jQuery, 
AngularJS, HTTP, networks/socket programming, distributed systems. On the other hand, some look at it as being a 
specialist, an expert in some specific areas of computer science. Maybe, it’s someone who is able to tell you the ins 
and outs of, say, writing an audio driver for Linux, the math principles behind cryptography algorithms, or the 
messaging queue about an asynchronous process in a web application.

Of course, there’s an infinite amount of possible programming-related knowledge out there. New knowledge keeps 
generating as the landscape of technology keeps changing. So, we need a nuanced understanding of skills. For me, 
a good programmer should be a mixture of being generalist and specialist. Software development requires all sorts of 
skills, coding is just one small part of it. We need design, communication, debugging, and other various skills. 
And in order to create high-quality product, we need to have depth in the relevant subjects about the product. 
And, I firmly believe that one can be nurtured into a good programmer.

I know a few programmers during that I have worked that I would call good. The traits I’ve observed from them 
so far are:

1.  The serious amount attention to details they give. This may mean different things depending on context: 
designing a system? The implementation details aren’t very relevant yet. Building the system? Those details 
become very important. Comparatively, I have been lazy and oftentimes accepted “good enough”. I’m working on changing 
this so that my priority is what is best for the user, not what is easiest for me to implement.
2.  They have the knack for intuitive designs. Before setting out with any new technology, they test its properties 
and use intuitive sense on if it’s a good fit for the system. They ask what is the expensive operations and if there 
is any way to optimize it.
One strong suggestion made by Jeff Dean, a Google Senior Fellow, for this is to write microbenchmarks for all the 
basic operations of the “black boxes” you’ll be using to build the system. This way, you can do quick 
back-of-the-envelope calculations to estimate the performance of the system before actually building it. You can 
explore the problem space much more quickly when you can simulate the important characteristics in your head instead 
of having to actually type them out into an editor.
3.  Being well-versed with the tools for development relevant to the process.
4.  Have a diverse range of skills and an eagerness to dive into something new at any point.
5.  Have an ability to rapidly debug problems. This requires some sense of pattern recognition for debugging and 
remembering similar problems. It is an important skill you can improve with experience. When starting out, it feels 
like I spent my mental energy all over the place. Over time, especially with conscious exercise, I am able to hone in 
on critical spots to focus.
The best programs usually have debug information built into the structure of the program itself, along with an easy 
UI for viewing that debug info so you don’t have to stare at log lines all day.

Lastly and most importantly, be curious, explore, learn, and hack.