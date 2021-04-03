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

#### **6.4. Exercise - Find the Oldest Bug. Find the oldest bug that's still open in your chosen project. Write a blog entry describing the problem, with a theory about why the bug hasn't been resolved yet. (Bonus points if you can actually resolve the bug.)**

The oldest bug in the TEAMMATES open source project was issue #4345. I sorted through the issues by filtering by oldest and with the label `bug`. This bug causes an issue when an instructor searches for students who are taking a lot of courses, this causes the query to be long and an error to occur because the query string is longer than 2000 bytes. The bug was oppened in 2015, has not resolved and has been mentioned in other issues.

#### **6.5. Exercise - Create Your Bug Tracker Account. Figure out how to create a new account on the bug tracker of your chosen project. You'll need that account very soon.**

The project we are working on is an open ource project on github called TEAMMATES. My github handle is [@Grahamet](https://github.com/Grahamet)

#### **6.6.1. Exercise - Reproduce a Bug. Go through your project's bug tracker and find a bug that you think you might be able to reproduce - and then try to reproduce it in the latest build. Take careful notes. Report your experiences as a comment to the bug. If you can reproduce the bug, great! Give as much information as you can. If you can't reproduce the bug, great! Give as much information as you can, and ask the original reporter if there are other steps you might be able to take to reproduce the bug.**

I was able to reproduce a typo, which I understand isn't a bug. In the issue there is a type in the edit questions form. It had `Save Questions` instead of `Save Question`. This type was fixed by our team member Chloe Stapleton.

#### **6.7.1. Exercise - Bug Triage. Find five bug reports in the new state, and attempt to triage them according to the rules above. Your goal is to do as much as you possibly can, in a short period of time, to make those bug reports as useful as possible to the developer to whom they are assigned.(Note: be sure to follow any triage rules that your project may have defined. If there is no set triage rules, be sure to announce your intentions on the project's mailing list, so that developers can provide you some guidelines if they choose.)**

Bug triage is a little bit of an issue at the current time as the development environment that I am working on is having some issues with properly tracking instructors being added to the development server. As a result, the ability to fix bugs in the environment is being tested. The biggest issue currently facing the fix of relevant bugs is getting the development environment restarted and getting instructors added to the program. Once that issue is resolved, work should progress significantly faster.


# What's Happening?

### Chapter 7: Exercises in TOS 7.2.2, 7.8, 7.9

I read an article called [Ryan Ripley on Making Scrum Work](https://www-computer-org.nuncio.cofc.edu/csdl/magazine/so/2021/01/09305896/1pNkshctjFe) from the ICEE Computer Society Digital Library Proceedings January/ February 2021 issue. Scrum is an agile framework for developing, delivering, and sustaining complex products with an emphasis on software development. This article was an interview between host of "Agile for humans" Kanchan Shringi and Ryan Ripley.

**Why do organizations adopt Scrum?**
According to Ryan Ripley Scrum is not the goal when organizations adopt the methodology, but rather they want delivery, customer satisfaction, consistency that comes when adopting Scrum. Adopting scrum lets them observe behaviors and outcomes in their projects and inspect what goes on through transparent work, which lets them adapt frequently as they go.

**What are Scrum prerequisites?**
Ryan Ripley states that leadership is the most important prerequisite for Scrum closely followed by "throwing out the playbook" and doing many small experiments to get started.

**What experience should a Scrum master have?**
Ryan Ripley states that there are three things that are the most important that a scrum master should have.
> 1. They love their teams and have a deep care for the people they are serving.
> 2. They want every member on this team and the collective team to be as successful as possible.
> 3. They have zero tolerance for organizational impediments.

**Conclusion**
I feel like this agile framework is incredibly efficient when it comes to product development and management. It is able to keep the team energized and focused and when something gets done the member feels more accomplished. This also makes it easier for members to ask for help in meetings when they are having issues with a problem.

# Stupid or Solid

This is my reflection on the article "[From STUPID to SOLID code](https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)." This article discusses the two ideas STUPID and SOLID. The acronym STUPID stands for Singleton, Tight Coupling, Untestability, Premature Optimization, Indescriptive Naming, and Duplication. These are all things that are considered to be bad practices for programming. The acronym SOLID stands for Single Responsiblity Principle, Open/Closed principle, Liskov Substitution Principle, Interface Segregation Principle, and Dependency Inversion Principle. These are all things that you should be doing in your code or are ways to fix STUPID code. 

#### S.T.U.P.I.D

From what I was able to understand from the article one of the biggest things to avoid when writing code was Tight coupling. Tight coupling is the "degree to which each program relies on each one of the other modules." If someone were to coding with tight coupling, and they wanted to change a single module they would then have to made a change in any module that was coupled with the one they needed/wanted to change. Due to tight coupling making it more complicated to edit or change a module in the code it is highly recommended to avoid this and it also just makes sense to avoid the type of dependencies it creates in order to help you with your code and help other developers who need to work on your code down the line.

To me the Indescriptive naming aspect of stupid is also on of the most important take aways when reading the article. Having a naming convention should be necessary in every project you work on and it should be done properly because programs are written by humans and not everybody thinks the same. Having clear and relevant names for your variables and methods makes it a lot easier down the road for both you and any future developers trying to understand why your code may stop working, or what the code does for new developers.

#### S.O.L.I.D

The most importand part of the acronym S.O.L.I.D would be Liskov Substitution Principle. This refers to the idea that "Objects in a program should be replacebale with instances of their subytpes without altering the correctness of the program." Not having Liskov's Substitution Principle in your code requires a lot of additional logic in your code. From what I understood making sure the super-type is suitable for the subtypes in all instances, you can ensure that all the needs of the program is met. 

#### Conclusion

Following the principles and ideas of S.O.L.I.D to avoid or fix the principles and ideas of S.T.U.P.I.D will be very helpful for not only your code for future developers to understand but also for you as a developer to improve as you work.

# Release Early and Often

Documentation is important for programmers to write often. Some programmers may disagree with the statement, however, by providing documentation programmers save time when needing to explain to others thier thought process, providing transparency about why they did what they did in their code or for when they they need to look back at an older section of their code. 

Their are five important steps to technical writing that help provide a strucure to write in but also a way for others to read it. Technical writing isn't quite the same as regular writing in that it differs where technical writing has more of a scientific process where the next steps require the previous steps, compared to an artistic process like regular writing. The five steps are as followed:

1. Planning
2. Content
3. Writing
4. Internalization/Localization
5. Review

# Chapter 5

This chapter focuses on Domain Class Development. There are three main activities in code development. They are coding practices, testing, and debugging . In a Co-FOSS project it is important that the domain class is the central element. 

**Coding**

Having some sort of base or starting code seems pretty useful when working on an open source project. Having a general starting point that everthing is built off of allows everyone working on it to have a general understanding of the foundation of any given piece of code. Following certain protocols and conventions to code a domain class is important as it can help make sure that it is coded correctly and the result matches the style that a client desires. It can be helpful to reuse code by finding developed classes that can be edited to fit the style required by a client. Doing so can result in retaining important instance variables and removing unimportant ones while aslo adding new instance variables to fit the style required. There are tiems where having to code a domain from scratch is also required. It is important to recognize when each of the cases will be more beneficial in terms of team development or client needs.

**Software Testing**

A test suite is a collection of unit tests and the suite shuld have one unit test for every module or class in the code base and one unit test for every use case. Each unit test should contain a group of calls that exercise all of the modules function and constructors. Each such call is written as an assertion (Boolean function that delivers "true" exactly when that call is successful and "false" otherwise).

**Debugging**

A bug refers to a "defect or a flaw" that causes your code to stop working and can be seen by either a client or user. Debugging is the process of finding and fixing these bugs to make everything work better. There are many different ways to track bugs depending on where you are coding. For our project we are using Github which allows us to see what bugs have been reported to be fixed. A key part to bugs is that they have to be reported and relies on "full participation of users and developers to keep the code base up to date and reasonably free of errors"(155). 

# 
