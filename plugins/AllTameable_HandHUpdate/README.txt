Installation Instructions:
-Download the main file with a mod manager or manually place the DLL file in the plugins folder
-Download one of the TameList in the optional files section and place in the config folder
-Open the TameList file and modify to your hearts content, including adding creatures that are added by mods as long as it follows the correct format

Note: The new TameList is optional, if you already have the original config file you do not need to download any extra files. The TameList file with override if it is found when loaded, otherwise the "meldurson.valheim.AllTameable.cfg" is used.

The descriptions of the options in the config are as follows:

name: This is where you put the ID of the creature you are adding
commandable: This sets the ability to order them to follow you or not
tamingTime: This is the time it will take to tame the creature (in seconds)
fedDuration: This is how long a creature will be full for after it eats (in seconds)
consumeRange: This is the max range the creature can be at to eat food
consumeSearchInterval: This is how often the creature checks to see if food is in range to decides whether it needs it (in seconds)
consumeHeal: This is how much health each food provides
consumeSearchRange: This is the range the creature can detect food from
consumeItems: This is where you put the ID's of the items you want the creature to eat, put a : symbol in between each food (doesn't need to be a food item)
changeFaction: This is whether the creature will change faction when tamed (If set to on it will attack/get attacked by anything that attacks you)
procretion: This is whether the creature can breed to produce offspring
maxCreatures: This is the max amount of creatures within 30m you can have of the creature ID typed in, if it exceeds this they will stop breeding
pregnancyChance: This is the chance the creature has of becoming pregnant, Lower number = higher chance (scales from 0.00 to 1.00)
pregnancyDuration: This is how long the creature is pregnant for (In seconds)
growTime: This is how long it takes for offspring to grow into an adult (In seconds)

Example:
Deer,true,900,150,2,10,30,20,Raspberry:Blueberries:Carrot:Turnip:Mushroom:Cloudberry:OnionSoup:Onion,true,true,10,0.66,150,300

To make a creature not tameable you set the line to the creature name plus a -1 such as:

Wolf,-1

This will not allow for wolves to be tamed
Note: This should be used on servers to set creatures you don't want tamed