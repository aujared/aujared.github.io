---
layout: project
type: project
image: images/simply-savory-logo.png
title: Simply Savory
permalink: projects/SimplySavory
# All dates must be YYYY-MM-DD format!
date: 2019-12-15
labels:
  - Javascript
  - Semantic-UI-React
  - Meteor
  - Galaxy
summary: This project was completed in ICS 314 Software Engineering. Simply Savory is a web application that provides a centralized site for UH Manoa students to learn and share affordable recipes that can be prepared with minimal kitchen facilities (both on and off campus) to suit local taste sensibilities.
---

## Project Objectives
<img class="<img class="ui medium right floated rounded image" src="https://i.gyazo.com/8643e073590c0f708663851258fd204b.png">
The final project for ICS 314 is meant to provide an outlet for students to combine a multitude of concepts learned throughout the class, and work in a team to produce and deploy a fully functional complex application. The original project that our group was assigned was "Toaster Oven Lovin'" a concept for a recipe application, we ended up deciding on the name "Simply Savory" and follow the general idea provided by the Toaster Oven concept. Our project statement was as follows:

*Simply Savory is a web application that provides a centralized site for UH Manoa students to learn and share affordable recipes that can be prepared with minimal kitchen facilities (both on and off campus) to suit local taste sensibilities.*

The project was built using Meteor, Semantic UI-React, Javascript, MongoDB, and was deployed using Galaxy. Version control was done via github, the organization page is found here: [https://github.com/simply-savory](link) . Our implementation stores recipes in a mongo database, then displays them to the user via cards. Users are able to like and favorite recipes, and post/edit their own recipes. If a vendor wishes to post deals & discounts on the site, they can indicate that they are a vendor during account creation, and be approved for an account.

For this project, we utilized Agile Project Management, seperating everything into 3 milestones, builduing upon funcationality, and working on individual issues that comprise larger components. For example, the implementation of recipe cards was split into database, semantic ui card configuration, and creating recipes. While we worked seperately, we communicated well, and followed common coding standards so that the others could understand what was being written.

A Link to a github.io page that summarizes the project can be found here: [https://simply-savory.github.io/](link)

## My Role
<img class="ui medium right floated rounded image" src="https://miro.medium.com/max/3200/1*DiNIG4Bfpm65_wwXf_JwMA.png">
For this project I wanted to improve my back-end database skills, so I worked on setting up the mongodb for user accounts and recipes, along with how they are accessed, modified, and displayed. This involved alot of work with simple schemas, collections, and publications to get everything interacting seamlessly. To determine who could edit a recipe, we assigned a owner property which was obtained via the Meteor Accounts.user method. Lots of troubleshooting was required as properties were being passed as null, not read correctly, or failed insertions.

Additionally I was also in charge of all content dealing with the github.io page listed above. This was another good excercies in html, and more importantly helped me practice thorough documentation and "writing for the world". This site is meant to be a record of everything pertaining to Simply Savory, and should serve as a sole summary and explaination of the application and its capabilities. Whether a potential user is reading it, an employer, or someone looking to build off of the system, the github.io page should provide them with all the information they need.

## Lessons Learned
<img class="ui medium right floated rounded image" src="https://cdn.ttgtmedia.com/rms/onlineImages/software_quality-agile_software_dev_cycle.jpg">
This project showed me that Agile project management is a very effective technique, this is the smoothest team work experience I've had on any coding project. My team and I were able to work effectively on small issues that seamlessly fit together to create a fully functional application. I was also impressed with the concept of milestones and pushing issues from milestone to milestone if they are not fully done, delivering what is available at the end of a milestone takes alot of the stress that comes from missing a delivery date and needing to rush to meet the already late deadline.

I also further improved my leadership skills, as I did majority of the organizing of our group, meetings, issues etc, along with leading the in class presentations. 

This project was a good closer to ICS 314, requiring use of skills we learned throughout the semester in a team environment, and reinforcing a new style of working (Agile) to complete the daunting task of a complex meteor application.


The full repository is found here: [https://github.com/simply-savory/simply-savory](link), a detailed guide on installation and running/using the system can be found at the github.io link.
