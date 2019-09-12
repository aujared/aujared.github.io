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

## Project Introduction
The Brain Controller Interface project is a part of Dr. Darren Carlson's Ambient lab, the ultimate goal of the lab is to have many different Internet of Things devices and other cutting edge technologies, interacting seamlessly in a high tech space. The equipment that we worked with is known as the Emotiv Epoc, this is an EEG, and motion tracking headset, we initially saw it being used to control video games, and thought that it would be good as an assistive tool for disabled people, controlling a claw to improve their reach.

## My Role/Responsibilities
There was an extensive existing codebase for the Emotiv Epoc, but it was difficult for us to decihper how certain functions were implemented, not to mention the fact that it was in C# which we had to begin learning. Our group had some previous experience with arduino from EE296, and had a good idea of what we needed to do to control the servos (in terms of arduino code). We split our team into two, Nate and I worked on the C# code and Epoc SDK, while Felix and Japhet worked on the Braccio Arm and Arduino integration. We determined that the best method for transferring data from the program and Arduino would be a serial port, so both teams needed to research how to open a serial connection for their programming language, setting a due date so that testing could be done. Learning C# was an interesting experience as it sits in a strange midground between C, C#, and Javascript, where elements from each are involved but there are significant differences. After learning the language, we had to look through the extensive documentation for the Emotiv Epoc to try and decipher what methods we needed to access to get our desired data, then we did some simple comparator statements with set threshholds to detect an action, then send the action via serial port to the arduino.

## Problems
We had an unfortunate mishap towards the end of the semester where some of the servos burnt out, we later learned that this was due to back current from adjusting the servos while the arm was powered off. This put us in a unique situation where we needed to obtain weaker replacement servos and change how our code worked, to account for the arm needing to move slower. These servos were barely able to carry the weight of the arm, but we managed to make it work in the end, it was a real time crunch as we were in the lead up to finals week at the time. 

Additionally, the Emotiv epoc was not as accurate or as sophisticated as we hoped, and many of our inital plans needed to be modified to fit the realistic capabilities of the device. The facial recognition functions worked fine, along with the motion tracking and gyroscope. We hoped to rely on the EEG capabilities for additional control mapping, but it proved to be almost random at some points, luckily we still had enough mappable actions to control both actions for all 6 modtors

## Lessons Learned
Out of all the projects I've worked on so far, the Brain Controller Interface project was by far the most technically complex, and time demanding. It required our team to mesh complex hardware and software designs together, to create our final product. The final time crunch we went through after burning out our servos was also a great challenge, we were under the pressure of getting this project done but also studying for finals, but managed to pull through with teamwork and time management. We also learned how to effectively understand large codebases written by others, the Emotiv Epoc had alot of pre-written software but not much documentation so we needed to do alot of prodding and testing to fully utilize its potential. This was by far the most satisfying project to see come together, as it encompassed so many different facets of engineering.

I do not currently have access to the source code, as Dr.Carlson requested the data stay within the Ambient Lab. A video of the Braccio Arm in action can be seen below:
<div class="ui embed" data-source="youtube" data-id="ennlXDwQofc" >
</div>
