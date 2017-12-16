---
title:  "Places, Please! Prototype"
date:   2016-02-01
categories: [projects]
tags: [unity, prototype, gamesinstitute]
excerpt_separator: <!--more-->
---

*Places, Please!* is a 4 player co-operative mobile game designed to simulate the act of putting on a theatre production. The prototype was developed in Unity for Shawn DeSouza-Coelho, a member of the the Univerity of Waterloo's Games Institute. His thesis explored the intersection between narrative and gameplay, with this game focusing on emergent narrative. I was also invited by Shawn to join him when he pitched the prototype to the Stratford Theatre Festival, and when he demoed the prototype during the Waterloo Innovation Summit.

![Waterloo Innovation Summit]({{ site.baseurl }}/images/placesplease/wisbooth.jpg "Waterloo Innovation Summit Booth")


### *Places, Please!* - A Quick Overview

*Places, Please!* tasks 4 players with taking on the roles of 4 different departments that are essential to running a theatre production. They are Crew, Stage Manager, Actor and Tech. The game is divided into different "scenes" which act like the rounds of the game. In each scene the 4 departments are randomly tasked with timed minigames called "moments" that simulate tasks that could occur while a theatre production is going. The moments are random for each scene and are either completed solo or as a duo, trio or quartet. 

An example of a solo moment is called Dead Battery, where the tech player has to tap the dead mic, switch off the battery pack of the dead mic, and turn on the battery pack of a new mic. Things get really interesting in the duo, trio or quartet moments. The game requires the 4 players to be in the same room when playing because certain multiplayer moments require in person verbal communication to achieve. For example, one moment, Cueing, tasks the stage manager to cue the tech player to press the GO button on their screen. The only way to notify the tech player is to physically tell him in person. Moments have to be finished within the time limit and the faster a moment is finished, the more points are gained. If the player takes too long to finish, a meter representing the house lights fills, with the maximum penalty given if they are unable to finish within the time limit. If the house lights meter maxes out, the show is stopped and the players lose.  

### Moments

Some of the moments we implemented were:

+ **Wig Prep:** This moment tasks players with swiping down on the red mannequins to prepare them for the actors 

![WigPrep]({{ site.baseurl }}/images/placesplease/wigprep.png "WigPrep")

+ **Understudy Guide:** This moment involves the stage manager and the actor. The stage manager's screen is presented with a map and a series of dots that form a path that they have to trace over with their finger. As a dot is swiped by the stage manager, the actor, who is presented with the same screen but without the dots initially, is able to see the dots that form the path which must also be traced.

![UnderstudyGuide]({{ site.baseurl }}/images/placesplease/understudyguide.png "UnderstudyGuide")

+ **Costume Change:** This is also another duo moment, this time consisting of the crew and the actor. The crew gets a piece of clothing that he must "pass" onto the actor by tilting their device. To receive the piece of clothing, the actor must also tilt their device after the crew player has done so. The actor will then be presented with arrows, which they will have to swipe to signify them putting it on. 

![CostumeChange]({{ site.baseurl }}/images/placesplease/costumechange.png "CostumeChange")

### My Role:

Developer: 
* Built most of the moments(minigames), and put the game together.
* Built the underlying systems such as the scoring and penalty systems.
* Added most of the art into the game.  
 