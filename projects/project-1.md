---
layout: project
type: project
image: images/sqfixed.png
title: EE205 Final Project (Soul Quest)
permalink: 'projects/EE205_Final'
# All dates must be YYYY-MM-DD format!
date: 2018-04-28
labels:
  - Git
  - C++
summary: My team and I developed a complex text based rpg in C++, complete with combat system, items, stats, and encounters
---
<img class="ui medium right floated rounded image" src="../images/sq2.png">
## Project Objectives
EE 205 is the second programming course available to electrical engineers, here we learn C++ to build upon the previous semester working in C. The official title of the class is "Object Oriented programming" and we are given a large degree of freedom when working on our final project, as long as we focus on utilizing the core programming concepts taught in the class. Being a group of gamers, we decided that it would be fun to work on a text based rpg, as it uses lots of elements that can be handled with classes and objects. We decided on a fantasy theme and appropriate name: "Soul Quest", after laying down our ideas for a basic combat system, player classes, items, and enemies, we set to work on programming.
## My Responsibilities
There were so many different files and modules that needed to work together to make this project work, and thus we decided to split the workload up among our team members. My workload consisted of the player classes & atributes, and the spells mechanics, the player class was made using composition, drawing the player stats from the weapon and equipment that they have, requiring a move constructor to accomplish this task. The spells class was a simple construct with various properties such as mana, damage, # of hits, element, and Name. I created 2 different spell books, one for the mage class, and one for the warrior class, these consisted of 4 spells each.
## Lessons Learned
As previously mentioned, this was my first experience working on a software development project with access control like git, our first big hurdle was to learn how to use git. Everything from creating and cloning the repository, to pushing and pulling, and eventually commiting. We needed effective communication within the team, as most of the modules depended on another module, and we had to make sure we understood how information would be passed between them. We did encounter numerous merge errors, as someone would change the file that was outside their responsibility, and create a conflict when the actual owner commited, working out these merge conflicts was one of our biggest problems. The other 3 team members were also assigned important sub systems such as; User Interface, Combat, Monsters, and Random Generation which required various programming techniques to be learned.

We were certainly not prepared for the level of complexity that this project entailed, there were so many different system interactions that we didn't anticipate, and it was difficult to test things as all modules were being worked at during different stages. We had a particularly difficult time getting the user interface to work, as it required us to learn how to use a completely new library called Ncurses. This allowed us to create a 4 option menu (attack, skills, flee, quit) similar to other traditional rpgs, and have the cursor highlight the selected option. We ended up taking over some of the other sub modules from the member working on Ncurses because it was such a difficult task, and we wanted him to be able to put his full focus into it. 

Although it was our first major software engineering project, through teamwork, time management, and a bit of ingenuity, we were able to complete all project goals, recieve an A for the class, and ended up with ~2000 lines of code.

All related files to Soul Quest can be found here: https://github.com/aujared/EE205/tree/master/Final/project
