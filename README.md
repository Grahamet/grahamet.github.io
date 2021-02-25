# CSCI 462 Blog

# Introduction

My name is Ethan Graham.
I am now a senior at Cofc. If campus opens and we can move into dorms I will be living in a historic house on Meeting St. 

# Reflections on FOSS

The premise of the article is that software development has two categories: a cathedral style and a bazaar style. According to Eric each choice has their own purposes and uses that make each unique and effective in their own way. However a majority of the article involves an anecdote about him initially discovering what is known as the bazaar style. This anecdote involves his development of the open source software fetch mail. Within the anecdote are pieces of programming wisdom provided by Eric to be used by any programmers reading the article. 
That being said the cathedral method makes code available during each software release, whereas the bazaar method develops code in full view of the Internet. In other words, people can see the project every step of the way in a bazaar development structure rather than a more limited group of people being involved in the process for a cathedral development structure.
Both Cathedral and Bazaar styles are methods of development of open-source as opposed to closed-source software. Closed source software is never released to the public, like that of Microsoft. Their code cannot be viewed or modified, just used, by the user. Open Source software benefits from more eyes looking at their product. Developers can find and fix bugs contributing to the software, and more software can be developed from the source code that is available to viewers.
There are misconceptions that open-source software cannot be profitable and cannot be secure. Just look at Red Hat or VirtualBox for successful companies based on open source. And same with security. A common phrase in cybersecurity is something “security through obscurity is not the answer.” The idea is that encryption should be secure because of the algorithm, not because people don’t know what algorithm you are using. The same can be true of open source software. Software should be secure because it is written securely, not because someone can’t look through the code and find its faults.

# Reflections on Open Source in Today's World

I chose to read an article entitled “Python for Kids helps adults teach programming to youth” (view article [here](https://opensource.com/education/13/1/python-for-kids)). The article title caught me by surprise because I came into college with little previous coding experience, and I would have greatly appreciated previous coding experiences in high school. Especially Python, since it’s the simplest to learn and many universities (including College of Charleston) teach it in their introduction to programming courses. The article is essentially a book review of Python for Kids: A Playful Introduction to Programming, a new book which the author describes is more for those who are teaching young people to program, not for the kids themselves. I could understand that. I know plenty of people who could read a book about any type of programming, even HTML, and be lost by the first few words. I definitely think it’s easier to have a good teacher show you how to program. The author also suggests that having the kids become familiar with MIT’s Scratch first, which is understandable as well. The first instance of coding that I was introduced to was Alice a game design software and it had just started to be taught at my highschool as I was a senior. Alice is similar to scrath where it is mainly a drag and drop coding language. The idea of each line of code being a puzzle piece to the next is a great visual learning technique to teach kids how code can be broken down and how each “puzzle” piece contributes to the final output. Perhaps a brief introduction to programming using Alice and once a general idea is there and understood, then they can move onto Python.

# This Bugs Me
### Chapter 6: Exercises in TOS 6.4, 6.5, 6.6, 6.7

##### **6.4. Exercise - Find the Oldest Bug. Find the oldest bug that's still open in your chosen project. Write a blog entry describing the problem, with a theory about why the bug hasn't been resolved yet. (Bonus points if you can actually resolve the bug.)**

The oldest bug in the TEAMMATES open source project was issue #4345. I sorted through the issues by filtering by oldest and with the label `bug`. This bug causes an issue when an instructor searches for students who are taking a lot of courses, this causes the query to be long and an error to occur because the query string is longer than 2000 bytes. The bug was oppened in 2015, has not resolved and has been mentioned in other issues.

#### **6.5. Exercise - Create Your Bug Tracker Account. Figure out how to create a new account on the bug tracker of your chosen project. You'll need that account very soon.**

The project we are working on is an open ource project on github called TEAMMATES. My github handle is [@Grahamet](https://github.com/Grahamet)

#### **6.6.1. Exercise - Reproduce a Bug. Go through your project's bug tracker and find a bug that you think you might be able to reproduce - and then try to reproduce it in the latest build. Take careful notes. Report your experiences as a comment to the bug. If you can reproduce the bug, great! Give as much information as you can. If you can't reproduce the bug, great! Give as much information as you can, and ask the original reporter if there are other steps you might be able to take to reproduce the bug.**

I was able to reproduce a typo, which I understand isn't a bug. In the issue there is a type in the edit questions form. It had `Save Questions` instead of `Save Question`. This type was fixed by our team member Chloe Stapleton.

#### **6.7.1. Exercise - Bug Triage. Find five bug reports in the new state, and attempt to triage them according to the rules above. Your goal is to do as much as you possibly can, in a short period of time, to make those bug reports as useful as possible to the developer to whom they are assigned.(Note: be sure to follow any triage rules that your project may have defined. If there is no set triage rules, be sure to announce your intentions on the project's mailing list, so that developers can provide you some guidelines if they choose.)**

Bug triage is a little bit of an issue at the current time as the development environment that I am working on is having some issues with properly tracking instructors being added to the development server. As a result, the ability to fix bugs in the environment is being tested. The biggest issue currently facing the fix of relevant bugs is getting the development environment restarted and getting instructors added to the program. Once that issue is resolved, work should progress significantly faster.


# What's Happening?

### Chapter 7: Exercises in TOS 7.2.2, 7.8, 7.9


