---
layout: page
title: Kani Generating Event
parent: Gameplay
grand_parent: Documentation
---
# Kani Generating Event
This is where all Kani battle it out for the opportunity to become King Kani
and mate with one of the Queen Kani and produce baby Kani. Winners have a
chance to win one of the baby Kani, potentially adding a new crab to their
horde.

The Kani from all active players will battle it out in randomly matched rounds
until only four Kani are left standing. Those four Kani are crowned king and
mate with a queen to generate the next generation of Kani. Each of the winning
players then has a chance to win one of the new babies. If they are lucky
enough to pry one away from the queen it will be added to their account and can
be retrieved with the [`?claim`](/docs/commands/#claim) command.

{: .pro-tip }
> You can carry over up to 500 scum from one week to the next. This can give
> you a head start on buffing for the next week.

## Kani Generation
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

## Mutations
Sometimes when Kani are generated a mutation occurs. The mutations can be
either positive or negative and affect 1 of the Kani's primary attributes. The
stat modifications are added or deducted from the Kani's base stat roll.

Every Kani has a 1% chance of generating a mutant baby. However, a mutant Kani
has an increased (+25%) chance of producing a mutant baby.

Mutants that produce mutants also have a 20% chance to pass on their mutation
to their mutant baby, making a double mutant baby Kani. 

There are currently 6 types of mutants available, the final 4 will be added in
the future.

### Mutation Types

| Name          | Modifier | Stat    | Description                                               |
| ------------- | -------- | ------- |---------------------------------------------------------- |
| Grippy Claw   | +3 Buffs | Wrestle | The kani has additional grip on the top half of its claw. |
| Slippery Claw | -3 Buffs | Wrestle | The Kani has is less grippy claw.                         |
| Power Claw    | +3 Buffs | Power   | The kani has an enlarged claw.                            |
| Weak Claw     | -3 Buffs | Power   | The kani has a smaller claw.                              |
| Spotted Claw  | +3 Buffs | Appeal  | The kani has different marking on its claw and body.      |
| Plain Claw    | -3 Buffs | Appeal  | The kani has no markings on its claw or body.             |

