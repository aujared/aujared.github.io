---
layout: project
type: project
image: images/epoc.jpg
title: Brain Control Interface Project
permalink: projects/BCI
# All dates must be YYYY-MM-DD format!
date: 2019-05-14
labels:
  - C#
  - Emotiv Epoc
  - Arduino
  - 6DOF Robotics
summary: This project was for EE396 (Junior Project), I used a headset with EEG contacts to control a six degree of freedom robotic arm, project carried out under supervision of Dr. Darren Carlson in the Ambient Lab.
---
<img class="ui medium right floated rounded image" src="{{ site.baseurl }}/images/claw.png">

The Brain Controller Interface project is a part of Dr. Darren Carlson's Ambient lab, the ultimate goal of the lab is to have many different Internet of Things devices and other cutting edge technologies, interacting seamlessly in a high tech space. The equipment that we worked with is known as the Emotiv Epoc, this is an EEG, and motion tracking headset, we initially saw it being used to control video games, and thought that it would be good as an assistive tool for disabled people, controlling a claw to improve their reach.

There was an extensive existing codebase for the Emotiv Epoc, but it was difficult for us to decihper how certain functions were implemented, not to mention the fact that it was in C# which we had to begin learning. Our group had some previous experience with arduino from EE296, and had a good idea of what we needed to do to control the servos (in terms of arduino code). We had an unfortunate mishap towards the end of the semester where some of the servos burnt out, we later learned that this was due to back current from adjusting the servos while the arm was powered off. This put us in a unique situation where we needed to obtain weaker replacement servos and change how our code worked, to account for the arm needing to move slower.

Out of all the projects I've worked on so far, the Brain Controller Interface project was by far the most technically complex, and time demanding, requiring our team to mesh complex hardware and software designs together, to create our final product. The final time crunch we went through after burning out our servos was also a great challenge, we were under the pressure of getting this project done but also studying for finals, but managed to pull through with teamwork and time management. We also learned how to effectively understand large codebases written by others, the Emotiv Epoc had alot of pre-written software but not much documentation so we needed to do alot of prodding and testing to fully utilize its potential. This was by far the most satisfying project to see come together, as it encompassed so many different facets of engineering.
