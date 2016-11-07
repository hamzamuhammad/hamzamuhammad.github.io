---
layout: post
title:  "MAKE SURE YOU GO OUT AND VOTE"
date:   2016-11-6
categories: jekyll update
---

<img src="/assets/profpic.JPG" width="300">

What did you do this past week?

- Got destroyed by both OOP and algo. I'm just trying to cop my degree and swag out of here into some dank job where I can meme hard all day. Honestly, taking 3 CS classes was sort of a mistake (because of the stupid workload) but then again my GPA can take a beating.

What's in your way?

- Start on OOP as well as take care of some minor obstacles (homework and what not). I haven't lifted for like 3 days so I have to get back in the gym before my muscle literally starts deteriorating from my bones.

What will you do next week?

- Enjoy the week of free time. The semester is just about to end, so I have to really go hard and get over with these classes and really do the crunch time necessary. 

Tip of the week

- "The only thing necessary for the triumph of evil is for good men to do nothing."

Darwin was an interesting project to finish, partly because it required extensive knowledge of how to design an object-oriented system. Now, the prescence of setters and getters isn't necessarily a bad thing, but limiting the use of these items is very beneficial for the system in general. 

With my first iteration of the project, I was accessing data members of objects (which were mistakenly made private) and this in turn made all of the code very confusing and non-functional. I then realized that in order to make the project more fluent and cohesive I would have to redesign the system by making the Creature do most of the heavy lifting. This has 2 advantages - one, Darwin just has to deal with the 'business logic' and the Creature can make moves based on it's own environment. 

I believed that making Darwin analyze the environment FOR the Creature was sort of a mistake, since if Darwin were to change than the entire back and forth between Darwin and the Creature would have to be modified as well. Therefore, I thought it is beneficial to make each object as independant as possible and to delegate responsiblity instead of doing half the job in one object and finishing it in the other. Although the notion of keeping data private and separate is hindered by this methodology, I found that reasoning about this concept as a whole is easier when the environment is given to the creature instead of getting bits and pieces from Darwin regarding the environment.

Each methodology has pros and cons, but the bottom line is this: design a system that has modular parts you could easily replace if you chose to. If an object relies heavily on a certain model (such as a Creature exisiting as part of a 2d grid), then of course changing the entire system to 3d would require modifying Creature as well. However, this may make things easier for Darwin, since Darwin does not have to deal with exploring the environment.

At the end of the day, each design is best suited to a certain problem. Using certain principles does not guarantee code reusage or easy refactoring, but it surely does point us in the right direction!
