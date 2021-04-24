## DotA2 Patch Play ##

*Disclaimer: Here i publish research from my master thesis at the Rijksuniversiteit Groningen, about the influence of popular, repeated and successful combinations of hero actions on the Dota 2 patches [Link when it is online]*  

### Content ###
1. [Introduction](#introduction)
2. [Dota Basics](#dota-2-basics)
3. [Dataset Description][Dataset Describtion]

*added soon vvv* 

4. Herodata
	1. Descriptive statistics
	2. Hero performance form singlecombo data
5. Combodata 
	1. Descriptive statistics
	2. Hero performance 
	3.[Heroperformance Singlecombo + combooutlier data]
6. Combination
	1.[Heroperformance Official + Singlecombo + combooutlier data]
  
[Official Descriptive statistics]
[Heroperformance Official]


[Combodata Descriptive statistics]
[Heroperformance Singlecombo ]
[Heroperformance Multicombo]
[Heroperformance Combination]



### Introduction ###

In this project I follow DotA 2 Pro Circuit matches for five years, in order to analyze the games patch practices.
In DotA the players are foremost supplied with a set of Heroes and Items, a map and a system to connect, in order to play with teammates or random people and against other teams or random people. Different to other sports, like for example Formula 1, amateurs and professionals from the games perspective, have the same initial position, the same material with the same stats to play with, so the main difference comes down to overall mechanic and game-internal skills, training and instinct.


Around this basic supply of game utensils there are several layers to increase activity with the platform and bind players. It starts with a steam user-account, where all the progress, stats and gained trophies and cosmetic items are collected and tied to the player-id. The account becomes also part of the players social life, since it is used to team up with friends and family members. For ranked matches teams can be build beforehand or players get matched with and against others according to their previous performance.  

Next to the basic game and elementary user features, that foremost exist to make matches possible and keep them interesting there are additional services like Dota Plus and seasonal passes that allow Valve to create additional attention and revenue. For example there is every year a 'Battle Pass' that can be bought, which grants access to additional activities and features, like to collect points in order to level up and to gain special items or trophies. It also offers different mini games, and the possibility to gamble with these points. The battle passes are directed towards the International, which is the biggest tournament in Dota every year. A part of the battle pass proceeds are also added into the Internationals prize pool, so for the 2020 edition which they had to cancel in the end, this added up to a record sum of 40 Million USD [[1]].

Professional E-sports is an essential part of Dota 2, which it inherited from its predecessor, the openly developed and refined modification for Blizzards Warcraft III, where also tournaments where organized all over the world. Valve wanted to make sure that its variation of the game was taking that footsteps when they held the first International in 2011, before the game was officially launched, which had a breathtaking prize pool of one million dollar.  


With about 400.000 online players around the clock [[2]] and with an overall median of 1633 hours [[3]] a user spend playing ( which in some cases goes up to 60.000 hours [[4]] ), it is one of the most played games on steam, Valve's gaming platform. 


![Patch-AvgPlayers][img2]


### DotA 2 Basics ###
In (standard competitive) DotA two teams of five people, each controlling a hero, start with a base and defense towers on the corner of a unvaried map. One of the buildings is the Ancient and whichever team is destroying the opponents Ancient first is winning the match.

#### Lanes, Towers and Creeps ####
From one base to the other there are three main lanes. Along those there are 3 tiers of defense towers that are shooting as soon as opponents are in reach. Next to the player controlled heroes there are also Non-Player-Characters on the map, which are emerging on regular intervals: Lane creeps  are spawning  from the barrack buildings in the base and run along the three lines. If players would not attack them, they would be killed by the opponents towers. Neutral creeps are in their camps in the forest between the lane doing nothing on their own and reemerge on a specific time schedule if they get killed. Roshan is the biggest and drops the most rewards. So in a basic state the map is a form of a delicate equilibrium, if it wasn’t for the humans, again..

![DotA2-Minimap][img1]

#### Heroes ####
The Heroes have different Abilities, Attributes and Stats and therefor suit different play styles and roles. All of those can be altered within a match by leveling up or equipping items. After the game the level progress and held items are reset, so that everyone is starting every match on Level 1 with 600 gold to buy a starting set of items. A hero can only be chosen once per game or not at all if it was banned before. 

#### Gold and XP #### 
Experience Points  can be gained by destroying killing enemy creeps or heroes. Gold is earned like that as well and is additionally rewarded for destroying enemy buildings.

#### Items ####
Items are used to upgrade heroes attributes or allow different activities ( such as teleportation ). They can be bought from the different shops on the maps or the teams fountain in the very corner of the base and they are dropped by some neutral creeps when they get killed. 

#### Captains Mode ####
The standard game mode in competitive matches is the captains mode. Where both team captains are going through three phases of banning and picking heroes. If a hero gets banned it can’t be choose by neither team. Usually more then one round is played, where bans are reset for each round.

#### Game Updates ####
In order to keep all the players attentive, motivated and spending, there are game updates where next to security and gameplay fixes also the underlying attributes of heroes, items and NPCs can be changed. Every patch is acting in theory as an equalizer that gives lower ranking teams the chance to find new strategies or builds that the altered attributes allow, so to find a better *meta* and with it gaining some momentum and climb the ranks.


[2]:https://steamcharts.com/app/570#All 
[3]:https://howlongis.io/app/570/Dota+2 
[4]:https://steamladder.com/ladder/playtime/570/ 
[1]:https://dota2.prizetrac.kr/international10

[Dataset Describtion]: dataset/ "Dataset Description"



[img1]: figures/dota2_minimap.png "DotA2-Minimap Link"
[img2]: figures/patch_avgplayers.png "Patch-AvgPlayers"


