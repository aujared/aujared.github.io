---
layout: essay
type: essay
title: "Final Project Idea"
date: 2019-11-05
labels:
  - Software Engineering
  - Meteor
---
Group Members: Nate Chu & Jared Au

<h1> Gaming Buddy Application </h1>

<h2> The Problem & Solution </h2>
Finding people in the gaming community can be difficult on a campus as large as UH Manoa, particularly for hobbies & games that require physical meet ups such as card games & sports. With this app we hope to create a platform that simplifies these meetup and allows more fun interactions at UH, with the opportunity to make a new friend.

<h2>Basic Concept</h2>
User logs in and is able to choose what games they're interested in (including video games, board games, card games like Magic the Gathering etc). Users can choose to indicate they are "Looking for a Game", we're unsure how we want to implement this, but either it will give them a notification that someone else is looking to play a game they are interested in, or it connects the two and allows them to send messages to each other. If this is a online game like League of Legends, it will allow them to share their in game usernames. The "special sauce" here comes into play when the user wants to meetup for a physical card/board game, we can make use of the google maps api to show where users are around UH Manoa "looking for a game", perhaps someone wants to play Monopoly at HolmesHall, but you don't wanna walk that far, so you settle for a game of Exploding Kittens at Hamilton.

Alternatively, we can implement it such that the Looking for a Game status lists you on a directory that people can browse and choose from. This requires less interaction (doesn't feel like tinder) and may be the better choice. If we implement it this way, we can have users choose a "location" with all the popular buildings and hangout spots at Manoa as default choices, mainly using the google maps api as an alternate display method for the number & location of meetings. For some activities like juggling, slacklining, or LARPing (all things we've seen going on in random spots around campus), we would not have a preset location listed but would rely on the google maps API or our built in message system to allow users to find each other. 


<h2>Mockup Page Ideas </h2>
<list>
  <ul>-Landing Page </ul>
  <ul>-Admin Page </ul> 
  <ul>-User Home Page </ul> 
  <ul>-Create a Meetup </ul> 
  <ul>-Edit profile/interests </ul> 
  <ul>-Previous Gaming Buddies </ul> 
  <ul>-"Looking for Game" Directory </ul>
  <ul>-"Looking for Game" Google Map Implementation </ul> 
</list>

<h2>Use Case Ideas</h2>
<list>
  <ul>-User Creates an account, chooses what games they are interested in, and their homepage displays currently active "Looking for Game" requests </ul>
  <ul>-Current user logs in, creates a Looking for Game request for League of Legends (they are not currently on campus, this is a online use case)</ul>
  <ul>-User recieves a message from someone with the same game/sport interest, they schedule a meetup via message system </ul>
  <ul>-User logs in, opens up the google map page to see what activities are going on near them (not particularly looking for a single type of game) </ul>
 </list>

<h2> Beyond the Basics </h2>
<list>
  <ul>-After implementing the basic framework, we will then look to utilize Google Maps to create a more visual representation of meetups </ul>
   <ul>-Slack/discord bot to notify users of when a meetup is created for one of their interests </ul>
   <ul>Review system to rate the person that you gamed with </ul>
</list>
