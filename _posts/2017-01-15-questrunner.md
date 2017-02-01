---
layout: post
title:  "QuestRunner"
date:   2017-01-25
excerpt: "A mobile game developed in Unity; inspired by Warcraft, inspiring runners."
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

[Inventory and Item System](#inventory)

[Level System and Main Menu UI)(#levelselect)

[Character System](#character)

[Battle System](#battle)

[Run Tracking](#run)

## Motivations

*More than two-thirds of adults are considered to be overweight or obese [(1)](https://www.niddk.nih.gov/health-information/health-statistics/Pages/overweight-obesity-statistics.aspx).
*Rewarding users may provide incentive to increase physical fitness.
*Users have a higher desire to complete an activity when reward for the activity is uncertain [(2)](http://library.fora.tv/2011/02/15/Robert_Sapolsky_Are_Humans_Just_Another_Primate#9YjA8sErOq6Ohub7.99).

## Inventory and Item System <a name="#inventory></a>

<figure>
	<a href="images/qr-inventory.jpg"><img src="/images/qr-inventory.jpg"></a>
</figure>

* Inventory holds all of the a user's acquired items
* Each item modifies the stats of the user's character
* The user can click an item and then click on an open inventory spot to move or equip the item
* A user can inspect the item by clicking it, displaying its tooltip revealing information about the item

## <a name="#levelsystem>Level Select and Main Menu UI</a>

<figure>
	<a href="images/qr-levelselect.jpg"><img src="/images/qr-levelselect.jpg"></a>
</figure>

* User progresses through the game by finishing levels
* As levels are unlocked, the difficulty of the monsters increases
* stronger monsters reward stronger items
* The user can drag the map around with touch
* User has access to five selections on the bottom panel: Adventure, Inventory, Quests, Town, and Options (some are not yet implemented)

 
## <a name="#character></a>Character System


<figure>
	<a href="images/qr-char.jpg"><img src="/images/qr-char.jpg"></a>
</figure>

* Character has stats such as health, mana, stamina, strength, intellect, and agility
* stats modify the amount of health the user has and the amount of damage the user deals
* A character's current stats are displayed and updated as different items are equipped


## <a name="#battle></a>Battle System

* User controls two characters at once, each with a separate set of abilities
* When a user clicks a character, the hotbar on the bottom of the screen changes to that of clicked character
* More than one enemy may battle the user at one time
* User can change the target of their currently selected character by clicking on an enemy

<figure>
	<a href="images/qr-combatexample1.jpg"><img src="/images/qr-combatexample1.jpg"></a>
</figure>

### Unit Frames

* Show the name, icon, health, power, and level of a unit
* Player frame is displayed on top left
* Enemy frame is displayed on top right

### Hotbar and Abilities

* Icons are colored red on the hotbar when the user does not have enough power to use it
* Icons have an image fill method of radial 360, which is filled clockwise to signify the cooldown of an ability

### Floating Combat Text

* Damage dealt to a monster is displayed on top of the monster
* Healing done is displayed in green 
* Critical hits are displayed in a larger font

<figure>
	<a href="images/qr-combatexample2.jpg"><img src="/images/qr-combatexample2.jpg"></a>
</figure>



## <a name="#run></a>Run-tracking

Runner-Up, an open-source Android application, observes and records the users run, tracking distance, pace, and duration.  
Completing a walk or run rewards the user with random items suited for their level and a scaled amount of experience points.

# Acknowledgements

Usui no kai (http://usui.moo.jp/frame2.html)

R do (http://www.geocities.co.jp/Milano-Cat/3319/)

bakenekokan (http://neko.moo.jp/)

Whitecat (http://whitecafe.sakura.ne.jp)

RTD web site (http://rtdweb.web.fc2.com/)

obane no koya (http://obane.tuzikaze.com/)

M-ART (http://mart.kitunebi.com/)

Open Game Art (http://opengameart.org/)

amacha music (http://amachamusic.chagasi.com/)

Free Sound Effects (http://taira-komori.jpn.org/)

Sound Effect Lab (http://soundeffect-lab.info/)

GoldenYak (http://goldenyak-wowfan.tumblr.com/)

World of Warcraft (https://worldofwarcraft.com/en-us/)







World of Warcraft© and Blizzard Entertainment© are all trademarks or registered trademarks of Blizzard Entertainment in the United States and/or other countries. These terms and all related materials, logos, and images are copyright © Blizzard Entertainment. This site is in no way associated with or endorsed by Blizzard Entertainment©
{: .notice}
