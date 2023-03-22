---
layout: page
title: Player vs. Environment
parent: Gameplay
grand_parent: Documentation
---
# Player vs. Environment (PvE)

## PvE - common
There are 2 forms of common PvE, a challenge event and a random event. The base
mechanics for the creature generation are the same for both events. The battle
mechanics are basically the same as any Kani vs Kani battle.

Every encounter spawns a new random creature. Each creature has a power,
wrestle, stamina, appeal, and speed stat similar to a Kani, but these stats
scale with the difficulty of the creature. The base (level 1) creature will
have a random (power, wrestle, stamina, appeal) stat between 5-10, and a speed
stat between 1-15. All of the base stats then increase for each level of
difficulty. A level 2 creature has twice the power of a level 1 creature, while
a level 3 has three times as much power. 

The PvE rewards are based on the power, wrestle, and stamina of the creature.
The higher the roll on the main battle stats, the harder the creature will be
and therefore, the more scum as a result of beating them. As the difficulty of
the creature increases so does the base battle stats(power, wrestle, stamina),
providing more rewards for the winner. In addition, the appeal of the attacking
Kani also increases the amount of scum the player will get as a reward. 

Launching an attack will cost you 10 scum, so make sure you choose an
appropriate strength for your opponent.

### Reward Calculation Example
A basic monster with stats `(P = 5, W = 10, S = 5)` is created and beaten by a
Kani with `(P = ?, W = ?, S = ?, A = 10)`. The reward will be monster stat
value `(5 + 10 + 5) + Kani appeal (10)` giving a reward of 30 scum. 
