---
title:  "Board Game Project - Castle Clashers"
date:   2016-01-08
categories: [projects]
tags: [project]
---

One of my favourite courses this term (and increasingly becoming one of my favourite courses I've taken in my undergraduate career) is the introduction to game design course taught by Dr. Lennart Nacke. The is the first formal game design course that I've taken and I've been learning alot about fundemental game design concepts. The concepts are quite intersting and very much in line with the kinds of jobs that I want to eventually get since I want to become a game designer.

The first project I had to do for the course was design and build a protoype for a territorial acquisition board game in our group of 5. The idea that was eventually chosen by our group was initially brought up by one of our members which was inspired by many games such as Risk or Valkyria Chronicles. The game supports 2-4 players however it is recommended that it be played with 4. The goal of the game is essentially to capture as many castles as possible, and after 12 rounds whoever has the most castles wins. 

### Game Rules

Here is a quick overview of the final iteration of rules:

Each player selects a starting castle located on one of the 4 corners of the board. The yellow castles denote neutral castles on the board. A castle is captured and controlled by they are the only player that has at least one unit inside the castle. If another player's unit is present in the castle, it is considered contested.

![Game Board]({{ site.baseurl }}images/map.png "Game Board")


Each player's turn is divided into 2 dfferent phases, the upkeep phase and the action phase.

During the upkeep phase, the player:

+ Collects a number of power tokens based on the amount of castles he/she controls. These power tokens are then used to perform actions during the action phase or can be saved up for use on later turns.
+ Place units that were bought the previous turn from the reserve onto the board.


The Action phase allows the player to:

+ Upgrade all units of a certain type.
+ Buy units which go into their reserve that cannot be placed until the next turn (costs 0 power tokens)
+ Command a unit on the board to move and/or attack another unit within range.

Different actions cost different amounts of power tokens, buying a unit costs 3 tokens while commanding a unit costs 1 token. Any subsequent commands issued to a unit that has previously moved that turn, increases the cost to do so exponentially with each command for the remainder of the turn. For example, if I commanded a particular footmen once, it would cost 1 token. If I was to command him again on the same turn, it would cost 2 tokens, and if I decide to do it again it would cost 4, etc.

When a player attacks another unit, a 6 sided dice (D6) is rolled. The number rolled is added to the damage modifier of that particular unit and is compared to the defense of the unit being attacked to see if it survives or not. If the unit survives, he may roll a dice to launch a counter attack on the unit that attacked it.

There are 3 unit types, knights, archers and footmen. Each have their own attributes like movement range, attack range, damage modifiers, and defense.


If all players are still in the game after 12 rounds, where each player player gets to go once per round, the player that controls the most castles wins!


### Reflection

I thoroughly enjoyed the process of designing and building the board game for this project. Discussing with the group members what mechanics were working, suggesting new mechanics or modifications to current mechanics during our multiple playtests was so much fun!

We went through many iterations of the rules, and spent a lot of time discussing how to balance the stats of the different units. For example, the counter attack mechanic wasn't initially present. During our playtests, we noticed that there was no consequence for attacking another player's unit. This meant that players being attacked were helpless and it gave the attacking player too much power. So to balance this, if the unit being attack survived, it was allowed to retalitate against the attacker. This made the attacking mechanic into a risk/reward decision, where the player had to decide if attacking another unit was worth the risk of a counter attack.

Another example of how the rules changed over our playtests, was how many power tokens a player would receive per castle. Initially, each player collected a base amount of 2 tokens, plus one for every player in the game, and then one for every castle the player controlled. We noticed that the number of castles held by each player remained very constant throughout the rounds. A player would lose one castle one round, and then get it back the next round, hold it for another round, and then lose it again. This led to the winner being decided on the very last player's turn. To combat this, we reworked the resource collection mechanic with a better positive feedback loop to help snowball the game. To those who don't know, a positive feedback loop is where positive effects in a game are reinforced in some way. An example would be, if in a game, whenever a player receives a point, they would get another reward, creating an advantage. This helps accelerate the game and makes players who are doing well get better even faster. For our game, we changed the base amount of power tokens a player would get and then upped the amount received for each castle under control. This allowed players who held more castles to take more actions than previously allowed if they were doing well, giving them more of an advantage and making the general experience of the game much more fun.

All in all it was a great experience designing this boardgame and I am looking forward excitedly to the next project for this course!

