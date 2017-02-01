---
layout: post
title:  "QuestRunner"
date:   2017-01-25
excerpt: "A mobile game developed in Unity, inspired by Warcraft, inspiring runners."
tag:
- questrunner
- unity
- c#
- mobile
- game
comments: false
---

*QuestRunner* is a mobile RPG currently being developed in Unity3D using C#. It was created for educational and personal use only.


## Overview

QuestRunner is an Android application that combines the functionality of a walking and running GPS tracker with a role-playing video game. Users defeat monsters, acquire items, and progress through levels of increasing difficulty. If a user goes for a run, they are rewarded with items and XP the next time they play the game.

## Motivations
More than two-thirds of adults are considered to be overweight or obese [1](https://www.niddk.nih.gov/health-information/health-statistics/Pages/overweight-obesity-statistics.aspx).
Rewarding users may provide incentive to increase physical fitness.
Users have higher desire to complete an activity when reward for the activity is uncertain [2](http://library.fora.tv/2011/02/15/Robert_Sapolsky_Are_Humans_Just_Another_Primate#9YjA8sErOq6Ohub7.99).

## Inventory and Item System

<figure>
	<a href="https://rowin1.github.io/images/bts-game-overview.jpg"><img src="/images/bts-gameboard.jpg"></a>
</figure>

* Inventory holds all of the a user's acquired items
* Each item modifies the stats of the user's character
* The user can click an item and then click on an open inventory spot to move or equip the item
* A user can inspect the item by clicking it, displaying its tooltip revealing information about the item

## <a href="#levelselect">Level System and Main Menu UI</a>

<figure>
	<a href="images/qr-inventory.jpg"><img src="/images/qr-inventory"></a>
</figure>

* User progresses through the game by finishing levels
* As levels are unlocked, the difficulty of the monsters increases
* The user can drag the map around with touch
* User has access to five selections on the bottom panel: Adventure, Inventory, Quests, Town, and Options (some are not yet implemented)

 
## Character System

<figure>
	<a href="https://rowin1.github.io/images/bts-game-overview.jpg"><img src="/images/bts-gameboard.jpg"></a>
</figure>

## Battle System

<figure>
	<a href="https://rowin1.github.io/images/bts-game-overview.jpg"><img src="/images/bts-gameboard.jpg"></a>
</figure>

## Run-tracking

<figure>
	<a href="https://rowin1.github.io/images/bts-game-overview.jpg"><img src="/images/bts-gameboard.jpg"></a>
</figure>

Runner-Up observes and records the users run, tracking distance, pace, and duration.  Completing a walk or run rewards the user with random items suited for their level and a scaled amount of experience points.

World of Warcraft© and Blizzard Entertainment© are all trademarks or registered trademarks of Blizzard Entertainment in the United States and/or other countries. These terms and all related materials, logos, and images are copyright © Blizzard Entertainment. This site is in no way associated with or endorsed by Blizzard Entertainment©
{: .notice}
