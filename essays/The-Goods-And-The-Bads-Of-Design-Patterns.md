---
layout: essay
type: essay
title: "The Goods and Bads of Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2022-12-01
published: true
labels:
- Webpages
- UI
- Design Patterns
---
## Wikipedia - the Most Used Design Pattern
<p align="center">
    <img width="300px" class="rounded" src="https://i.kym-cdn.com/entries/icons/original/000/001/711/Wikipedia_Logo.png">
</p>

<a href="https://en.wikipedia.org/wiki/Software_design_pattern">Wikipedia</a> (I know, I know...Wikipedia is not a reliable source) says "a software design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design. It is not a finished design that can be transformed directly into source or machine code. Rather, it is a description or template for how to solve a problem that can be used in many different situations."

In an abstract sense, Wikipedia can be considered a research design pattern.  Academia states that Wikipedia is unreliable because it relies on open source editing.  While there are many people who dedicate working on information accuracy and sourcing, I could go in and edit this page to say design patterns are a type of cheese.  But even academics can agree that Wikipedia is a good starting point when you are just starting your research.  Consider the Wikipedia page as a template. You first read about the topic and gain a general sense of what is going on.  Then you look at the plethora of sources Wikipedia lists to back up it's claims.  Using this information and these sources, you can then pivot and delve further into a specific subtopic.  Several days and pots of coffee later, your paper is done and you have greatly expanded on the basics you first read on Wikipedia.

## Recreating the Wheel vs Using a Design Pattern
So now that we have defined a design pattern as an introductory template that one can use to solve a problem, let us apply it to software engineering.  At its core, software engineering is finding the answers to a series of problems.  If you are creating a calculator program, some of the problems you might have to solve are input, output, addition function, multiplication function, clear screen, etc.

Once you have identified the problems that need to be solved, your next task is to implement the solutions.  Here, you have two options.  You could use the knowledge you have and try to implement a solution.  While this may seem like a good idea and definitely shows of your coding prowess, the second option of utilizing the wheel design pattern is probably the better idea.  Take the addition function.  All languages implement some method of handling addition.  Why waste the time and effort attempting to make your own addition function when you could take the working one adjust it to your needs?

<p align="center">
    <img width="500px" class="rounded" src="https://miro.medium.com/max/640/1*4WpIB7SzfGwfRIlbP_7u6Q.webp">
<br>
Taken from bastrakof.livejournal.com
</p>

## Design Patterns will Improve Your Quality of Life
Stackoverflow is my friend, your friend, everybody's friend.  <a href="https://galenchang.github.io/essays/Writing-Smart-Questions.html">Ask smart questions, get smart answers.</a>  At my beginner level, there really isn't a software engineering problem out there that I would encounter that hasn't already been extensively answered and a design template already created for it.  This is a very simple example, but a problem I ran into recently was trying to figure out how to read binary from a file, store it in as hex characters in an array, and parse it for certain tidbits of information.  The design pattern I found was very simple - <a href="https://www.ibm.com/docs/en/zos/2.5.0?topic=functions-fopen-open-file"> read about fopen</a>.  A very basic function that can be used to solve my problem.

Another example would be the current project I am working on.  My group and I are trying to make an application that allows users to find clubs that interest them at the University of Hawaii Manoa.  We are watching the lecture videos to understand how certain features are implemented and integrating it into our application.  How do we create users with certain properties like interests or name?  Well, we could take the schema used in lecture for something entirely different, treat it as a design pattern, and modify it to fit our end goals.

There are other design patterns that you will probably encounter and use throughout your life.  Algorithms are a prime example.  For example, learning how to use the various sorting and searching algorithms to fit your needs.  Or using dynamic programming to solve complex problems repeatedly quicker.  Design patterns are extremely helpful, and you are probably using them without even knowing (like I was).