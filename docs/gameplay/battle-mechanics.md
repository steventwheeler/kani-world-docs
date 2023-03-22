---
layout: page
title: Battle Mechanics
parent: Gameplay
grand_parent: Documentation
---
# Battle Mechanics

Battle stats are derived from a Kani’s base and buffed stats. The different
stats are for different parts of the battle. At a high level the attributes of
power, wrestle, stamina, and speed relate to battle stats of attack, defense,
hit points, and special frequency. However, as a battle progresses some of
these stats change and depending on the event, may or may not be reset after
each battle. 

## Basic Battle
At the start of a battle all Kani have the following stats, attack, defense,
hit points, special charge, and fatigue. Attack is direct from power, one for
one. Defense is similarly taken from wrestle. Hit points come from stamina, for
every 1 stamina a Kani has 3 hit points. Finally, special charge and fatigue
are both set to 0 initially. 

The battle consists of rounds with each Kani taking turns to hit until one of
them no longer has hp left. For every hit the opponent has a chance to block.
The value of the hit is derived from a roll (usually d6) and the Kani’s attack
value. The defender's block is calculated by a roll (usually d6) and their
defense value. If the hit is greater than the block, the difference is taken
from the defender's hp. Each hit and block incurs attack and defense fatigue if
the value of the attack/defense is greater than the Kani’s stamina - the theory
being they don’t have the stamina to consistently hit/block at such a level.
This fatigue reduces the value of attack or defense over a number of rounds by
a percentage of the difference between attack and stamina or defense and
stamina. 

The fatigue formula is: 

```
fatigue = (def - stam) * ((def - stam)/100).
```

For example if a Kani has defense 50, stamina 20 - On blocking the defense
fatigues.
```
fatigue = (50 - 20) * ((50 - 20)/100)
```
The defense is reduced by the fatigue amount and in the next round the stats
should be, defense 41, stamina 20. On the next block the defense will fatigue
again.
```
fatigue = (41 - 20) * ((41 - 20)/100)
```
Resulting in a new defense of 37. This continues each round until the defense
is at a level sustainable by the stamina value. 

{: .note }
> Older battles will show an additional penalty on overall fatigue if the
> defense blocked all incoming damage. However, this has been removed from the
> game now. 

At the end of each round, both Kani receive general fatigue which is a random
number between 10 and the number of the round. For battles that last longer
than 5 rounds, an additional fatigue stack is added each round. Once the
fatigue counter reaches 100, the Kani is fatigued and misses a hit chance, or
blocks for a reduced amount. The final part of the basic battle is a special
charge which is added to each attack that isn’t a special move. For every hit a
Kani’s speed value is added to the special charge and once the value of the
special charge is greater than 100 at the start of an attack the Kani will use
its special to hit, dealing standard damage plus the value of the stat that is
connected to the special move.
