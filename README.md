# timeConsumer
This MWSE mod passes time when enchanting, repairing, performing alchemy, making and learning spells, bartering, talking, and looting. Can be used alone for immersion or with other mods that introduce time sensitive mechanics such as hunger and thirst. Each feature is modular and can be toggled on or off through the MCM.

Below I will break down how exactly this mod passes time and what events trigger it to do so.
<br>
<br>
<br>
## Enchanting:

Whenever the player attempts to enchant an item either themselves or through an NPC, time will pass. I like to think of enchanting as a time consuming project, so the default values will reflect that. The time consumed will decrease with higher enchanting skill.

A successful enchantment attempt will take 5 hours of in game time before enchant skill is considered. Once skill is considered, the time consumed can be roughly the same as base or as low as 60% of base time, in hours.

A failed enchantment attempt will take 2.5 hours of in game time before enchant skill is considered. This is less time than a successful enchant because when an enchantment fails, it could be assumed that something went wrong during the process that stops the project short, breaking the soul gem. Once skill is considered, the time consumed can be roughly the same as base or as low as 60% of base time at level 100.

Enchanting through an NPC will also consume 4 hours of in game time before their enchant skill is considered. Once skill is considered, the time consumed can be roughly the same as base or as low as 60% of base time at level 100.

Recharging an enchanted item will consume .5 hours of in game time before enchant skill is considered. Once skill is considered, the time consumed can be roughly the same as base or as low as 33% of base time at level 100.

Each of the above enchanting features can be toggled on/off or have their base time values changed.
<br>
<br>

## Repairs:

Whenever the player attempts to repair an item, time will pass for each attempt. Gone are the days of mindlessly spamming your repair hammer. Since time is consumed for each attempt, I kept the base values fairly low as with low skill, repair times could become quite inflated. The time consumed will decrease with higher armorer skill.

An attempted repair will take .3 hours per attempt before armorer skill is considered. Once skill is considered, the time consumed can be roughly the same as base or as low as 20% of base time at level 100.

Repairing through an NPC will also take .4 hours per piece repaired, but since NPCs repair pieces fully each time, this can take considerably less time than doing it yourself if you have low armorer skill. The time consumed will decrease with higher NPC Armorer skill, down to 20% of base time at level 100.

Both of the above repair features can be toggled on/off or have their base time values changed.
<br>
<br>
## Alchemy:﻿

Whenever the player either successfully or unsuccessfully creates a potion, time will pass. By default, both success and failure will consume the same amount of time. I like to think that in most cases, one would only know if their potion was successful or not at the end of the refining process. The time consumed will decrease with higher alchemy skill.

A successful potion will take 1 hour to make before alchemy skill is considered. Once skill is considered, the time consumed can be roughly the same as base or as low as 33% of base time at level 100.

An unsuccessful potion will take 1 hour to make before alchemy skill is considered as well. Once skill is considered, the time consumed can be roughly the same as base or as low as 33% of base time at level 100.

Both of the above alchemy features can be toggled on/off or have their base time values changed.
<br>
<br>
## Spellmaking / Spell Learning:

Whenever the player employs the services of a spellmaker, time will pass. Like enchanting, I like to think the process of creating an entirely new spell to be a time consuming project. The default time will reflect that. Time consumed will decrease with higher NPC and player intelligence.
<br>
<br>
Also, when purchasing a spell from an NPC, I envision the NPC teaching you how to cast the spell itself. So by default, time will be consumed for each spell purchase, allowing your character to take time to learn the spell. Time consumed will decrease with higher NPC and player intelligence.
<br>
<br>
The process of creating a new spell takes 6 hours before intelligence is considered. Once intelligence is considered, the time consumed can be roughly the same as base or as low as 60% of base time at NPC and player intelligence 100.
<br>
<br>
The process of purchasing a pre-made spell from a vendor will take 1 hour to learn before intelligence is considered. Once intelligence is considered, the time consumed can be roughly the same as base or as low as 30% of base time at NPC and player intelligence 100.

Both of the above spell learning features can be toggled on/off or have their base time values changed.
<br>
<br>
## Bartering:

Whenever the player selects an item to buy, regardless of quantity, 1 minute will pass. 1 minute will also pass when making an offer. This is really just to simulate time passing while negotiating prices at a vendor.

The bartering time feature can be toggled on/off.
<br>
<br>
## Talking:

Whenever the player asks about a topic, attempts persuasion, gives a response to a question, or is denied service, 1-3 minutes pass. This is to simulate time passing while conversing with NPCs.

The talking time feature can be toggled on/off.
<br>
<br>
## Looting:

Whenever the player searches a non-empty container or corpse, 1 minute will pass to simulate the player rummaging through a container.
