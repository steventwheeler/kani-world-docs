---
layout: page
title: FAQ
nav_order: 998
---
# FAQ
Frequently asked questions.

## What is Kani World?
Kani World is an evolving NFT game. It uses NFTs on the Algorand network as
player characters in the game that is constantly developing and, in its current
state, is playable through commands on the Kani World discord. 

## What is the goal of the game?
The goal of the game is to become King Kani. Each week there is a
[Kani Generating Event](/docs/gameplay/kani-generating-event) where all Kani
battle it out for the opportunity to become King Kani and mate with one of the
Queen Kani and produce baby Kani. Winners have a chance to win one of the baby
Kani, potentially adding a new crab to their cast.

## How does a player become King Kani?
To win the KGE, Kani need to be battle-ready. They need to survive multiple
rounds of combat to become King Kani, and as more players join the game, the
competition will only get more challenging. The current plan is for 2
Queens/2 winners each week except on the full moon of the month, in which case
all four queens are available. Making it through to King Kani isn't, so the
Kani will need all the help they can get.

FIXME: the answer here seems outdated.

## What is scum?
[Scum](/glossary/#scum) is the primary resource Kani collect to improve their
attributes and participate in Kani World events. Any Kani can collect scum in
several ways. The first way is a player and Kani can
[scavenge](/docs/gameplay/scavenge) for some scum together. Scavenge results
in instant rewards but has a 10-hour cooldown. Another way is by sending the
Kani out to [explore](/docs/gameplay/explore) passively. When the player
returns to check on the Kani, it might have a nice big pile of scum to be used.
Kani can collect a good amount of scum in 10-20 hours, but don't leave them out
exploring too long. You can also earn scum by challenging other players or
monsters with [PvE](/docs/gameplay/pve), [PvP](/docs/gameplay/pvp), and
[raids](/docs/gameplay/raids).

## How can I improve my Kani?
Players can use the [scum](/glossary/#scum) they collect to temporarily improve
their power, wrestle, stamina, appeal, and speed. The Kappa Bot that runs the
Discord game likes scum and [buffs](/glossary/#buff) Kani in return for scum.
These buffs last until the end of the current KGE. After the KGE, the buffs end
and stats return to their original value. 

## How are the Kani attributes generated?
All Kani have attributes generated randomly at creation. The four base
attributes (power, wrestle, stamina, and appeal) are generated from random
numbers between 5 and 15, equaling 40. These attributes govern both the Kani's
ability in battles and its appearance. Most of the Kani's appearance is based
on the parents' traits. The Kani is allocated a color at random between the
mother and father's color. There is also a 2% chance of a mutation. The
possibility of a mutation increases because of several factors:
- the number of offspring
- the similarity in the parents' colors, and 
- if one or both parents have a mutation.

## What are the stats, and what do they do?
There are four main stats, power, wrestle, stamina, and appeal. The power stat
is an attack stat used when calculating a Kani's attack. Wrestle is a defensive
stat used when calculating defense. Stamina is health; it serves as the amount
of damage a Kani can withstand in battle and impacts the number of offspring it
can produce. Appeal increases the chance of winning a baby Kani and avoids
conflicts in random PVP encounters. 

## What about speed and special moves?
Speed is calculated at generation and is connected to the Kani's power and
wrestle. The higher the total power and wrestle, the slower the Kani will be.
Speed is used in battles to determine how often a special move occurs. Special
moves are an attack that deals additional damage. The current number is a
placeholder for the stat of the special move, i.e. 1 is connected to power, 2
is connected to wrestle, etc.

## What other factors affect battles?
There are four regions in Kani World, currently called "North", "South",
"East", and "West". Each Kani is assigned an area at birth based on their base
color. Kani inherits an advantage against Kani from the region of their
parents. If they are battling a Kani from the area of their father, they get an
attack bonus. Similarly, if their opponent is from the region of their mother,
they get a defense bonus. 

## Can I attack other players?
You can [challenge](/docs/gameplay/pvp) any player on the Discord server. You
will need a bit of scum to power your expedition, and success is not
guaranteed. The goal of the challenge is to take a bit of scum from the
opponent. There are three possible outcomes for a challenge. 1. If the player's
Kani is out exploring, the attacker has a free shot at the scum pile,
guaranteed success and more significant rewards. 2. The player has a Kani
defending the scum pile, but the attacker is victorious. The challenger is
successful, but a slightly reduced amount of scum is stolen. 3. Like 2, the
scum pile is being defended, but the attacker cannot beat the defender and
returns with no scum. 

## What is Kani Rumble?
[Kani Rumble](/docs/gameplay/kani-rumble) is a biweekly event that Kani must
join if they want to participate in it. Joining requires a scum fee. The fees
are then pooled together and awarded as the prize. The Kani rumble is a royal
rumble like elimination battle. 2 Kani will square off, one will win, the other
is out. The event is a random elimination event. To participate in the event,
the Kani must not explore when the event takes place. Signing up for each event
is necessary, and the event uses the "rumbler" role.

## What are the Kani roles?
The [roles](/docs/gameplay/roles) are a way to keep track of multiple Kani. If
a player has more than 1 Kani, setting up roles helps establish which Kani the
player wants to use for the Discord commands. For example, when buffing a Kani,
a player most likely wants to focus on a specific Kani to improve, so buffing
that specific Kani is critical. Another situation is if one player wants to
challenge another player, they most likely want to use a particular Kani to
attack. Adding roles makes this possible on Discord. Most commands use the
rumbler role by default, so that role is recommend for your first Kani.

## What about PvE?
[PvE](/docs/gameplay/raids) currently exists in the form of a server raid
against a selected enemy. Inspiration for the enemy is related to various
events that have taken place in the Algorand ecosystem. The event requires
players to attack the enemy and defeat it before the enemy inflicts too much
damage on all Kani in Kani World. This event will occur 2 or 3 times a week,
and participating players receive [scum](/glossary/#scum) and
[blockchain fragments](/glossary/#blockchain-fragment).

## What is the other PvE?
A [PvE](/docs/gameplay/pve) challenge, similar to
[scavenge](/docs/gameplay/scavenge) and [PvP](/docs/gameplay/pvp) challenge can
be launched with the [`?pve`](/docs/commands/#pve) command. Players can battle
a random sea creature every 10 hours or so. Beating the creature rewards the
player with scum and there is a small chance to win a blockchain fragment. The
player can choose from 3 difficulties with increased rewards as the difficulty
increases.

## What are blockchain fragments?
The setting for Kani World is the mythical waters of the Algorand ecosystem.
[Blockchain fragments](/glossary/#blockchain-fragment) are rare game assets
that Kani acquire over time. The blockchain fragments are numbers (0, 1, 2, …,
7, 8, 9). These fragments will be used to assemble items connected to ASAs. To
build an ASA, a player will need to collect all the number fragments contained
in the ASA. 
