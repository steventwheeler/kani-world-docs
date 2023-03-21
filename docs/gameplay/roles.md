---
layout: page
title: Kani Roles
parent: Gameplay
grand_parent: Documentation
---
# Kani Roles
A Kani can be assigned one of several roles which perform different functions
in the game. The three main roles are:

1. **Rumbler** - this should be assigned to your main crab. This is the crab that
   will [scavenge for scum](/docs/commands/#scavenge), battle
   [randomly generated monsters](/docs/commands/#pve), battle
   [other players](/docs/commands/#pvp), and compete in
   [PVP events](/docs/pvp_events).
2. **Explorer** - this should be assigned to your secondary crab. This is the crab
   that will be [sent out exploring](/docs/gameplay/exploring/) for longer
   periods of time to try and gather scum.
3. **Hunter** - if you have a third crab then assign this role. You can send him out
   to [hunt for treasure](/docs/gameplay/treasure/) on the sea floor.

Additionally, there are other roles which can be useful in maximizing your
damage to raid bosses. See [here](/docs/gameplay/raids) for more information on
raid bosses and their strengths and weaknesses.

- **Speedy** - Assign to a Kani with high speed or the "Rapid Strike" special
  to use in raids early in the week if the boss is weak to speed.
- **Wrestle** - Assign to a Kani with high wrestle or the "Crab Grab" special
  to use in raids early in the week if the boss is weak to wrestle.
- **Appealing** - Assign to a Kani with high appeal or the "Shell Shine"
  special to use in raids early in the week if the boss is weak to appeal.
- **Powerful** - Assign to a Kani with high power or the "Claw Crush" special
  to use in raids early in the week if the boss is weak to power.
- **Endurance** - Assign to a Kani with high stamina or the "Shell Quake"
  special to use in raids early in the week if the boss is weak to stamina.

Finally, it is sometimes useful to have a catch all role. You can use the
**alt** role for that purpose.

To assign a role to your kani you will need to first ensure that the Kani has
been linked to your account by running [`?mykani`](/docs/commands/#mykani) to
scan the blockchain and import any new Kani NFTs. Once your NFTs have been
discovered you can go ahead and use the [`?role`](/docs/commands/#role) command
to assign the desired role to your Kani.

For example to assign the **Rumbler** role to the Kani with ASA ID `394252318`
you would run this command in the
[`#mangroves-scavenge-here`](/docs/channels/mangroves-scavenge-here) channel.

```
?role 394252318 rumbler
```

[Next: Scavenge for Scum](/docs/gameplay/scavenge){: .btn .btn-blue }