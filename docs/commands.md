---
layout: page
title: Bot Commands
parent: Documentation
---
# Getting Started
## `?verify`
Verify your wallet and get the `@Kani Owner` role.  
  

# Kani Management
## `?mykani`
View your Kani and their stats. This will also check your Algorand wallet for
new Kani NFTs. If no additional arguments are given this will display the stats
of your rumbler Kani.

This command takes one optional argument which can be any of these:

| Argument  | Description                                                | Example            |
| --------- | ---------------------------------------------------------- | ------------------ |
| Role Name | Display the stats for a Kani besides your rumbler.         | `?mykani explorer` |
| `all`     | Display the stats for all of the Kani in your wallet.      | `?mykani all`      |
| `list`    | Display a short listing of all of the Kani in your wallet. | `?mykani list`     |

## `?role`
Assign a role to one of your Kani. See [here](/docs/roles/) for more
information on the various roles which can be assigned to your kani.

This command requires two arguments in this order:

| Argument  | Description                                                 |
| --------- | ----------------------------------------------------------- |
| Asset ID  | The Algorand ASA ID of the Kani NFT.                        |
| Role Name | The name of the role which should be assigned to this Kani. |

### Example
```
?role 123456789 rumbler
```

## `?name`
Change the name of your Kani NFT on the Algorand network.

This command requires two arguments in this order:

| Argument | Description                                                                                                 |
| -------- | ----------------------------------------------------------------------------------------------------------- |
| Asset ID | The Algorand ASA ID of the Kani NFT.                                                                        |
| Name     | The name to assign to this Kani. Note, if the name contains spaces you must enclose the name in quotes `"`. |

### Examples
```
?name 123456789 Grabby
```
```
?name 123456789 "Grabby Crabby"
```

## `?reroll`
Change the special move of your Kani. See [here](/docs/specials/) for more
information on special moves.

This command requires two arguments in this order:

| Argument  | Description                          |
| --------- | ------------------------------------ |
| Asset ID  | The Algorand ASA ID of the Kani NFT. |
| `special` | The word special.                    |

### Example
```
?reroll 123456789 special
```

## `?buff`
Buff your Kani to improve his battle skills.

This command has one required argument and two optional arguments in this
order:

| Argument  | Description                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------ |
| Stat      | Required, the name of the stat to buff, one of: `power`, `wrestle`, `stamina`, `appeal`, `speed` |
| Quantity  | The number of times to buff the same stat.                                                       |
| Role Name | Buff the Kani assigned to this role.                                                             |

# Gameplay
## `?scavenge`
Collect some scum.

This command takes no arguments.

### Example
```
?scavenge
```

## `?explore`
Send your Kani to collect scum while you are away from the game. By default
this command will send out the Kani with the explorer role.

This command takes one optional argument:

| Argument  | Description                                  |
| --------- | -------------------------------------------- |
| Role Name | Explore with the Kani assigned to this role. |

### Examples
```
?explore
```
```
?explore rumbler
```

## `?recall`
Bring your exploring Kani back and collect scum.

This command takes no arguments.

### Example
```
?recall
```

## `?hunt`
Send your treasure hunter Kani out on an expedition. If no arguments are given
then this command will show the status of your treasure hunter.

This command takes two optional arguments.

| Argument  | Description                                                                  |
| --------- | ---------------------------------------------------------------------------- |
| State     | Either `start` or `end` to send or recall your treasure hunter respectively. |
| Role Name | Hunt for treasure with the Kani assigned to this role.                       |

### Examples
```
?hunt
```
```
?hunt start
```
```
?hunt end
```
```
?hunt start explorer
```

## `?pve`
Challenge a randomly generated creature with your rumbler Kani.

This command takes one optional argument:

| Argument   | Description                                                                                               |
| ---------- | --------------------------------------------------------------------------------------------------------- |
| Difficulty | An integer which increases the strength of the generated creature as well as the reward for defeating it. |

### Examples
```
?pve
```
```
?pve 2
```

## `?pvp`
Challenge the rumbler Kani of other players.

This command takes one required argument which can be any of the following:

| Argument      | Description                                           |
| ------------- | ----------------------------------------------------- |
| `@playername` | The `@` username of the player you wish to challenge. |
| `random`      | Challenge a randomly selected player.                 |

### Examples
```
?pvp @username
```
```
?pvp random
```

## `?raid`
Attack the raid boss. See [here](/docs/gameplay/raids) for more information on
raids. By default this command uses your rumbler Kani to attack the boss.

This command takes one optional argument:

| Argument  | Description                                 |
| --------- | ------------------------------------------- |
| Role Name | Attack with the Kani assigned to this role. |

### Examples
```
?raid
```
```
?raid powerful
```

## `?join`
Join the PVP events. See [here](/docs/pvp_events) for more information on the
PVP events. By default this command signs up your rumbler Kani.

This command takes one optional argument:

| Argument  | Description                                 |
| --------- | ------------------------------------------- |
| Role Name | Attack with the Kani assigned to this role. |

### Examples
```
?join
```
```
?join speedy
```

# Kappa Queries
## `?bal`
View your in game balance of scum, battle points, and Kani Coins.

This command takes no arguments.

### Example
```
?bal
```

## `?bag`
View your collected Blockchain Fragments and consumable items.

This command takes no arguments.

### Example
```
?bag
```

## `?shop`
List the price of buffs for your Kani. By default this command signs up your
rumbler Kani.

This command takes one optional argument:

| Argument  | Description                                     |
| --------- | ----------------------------------------------- |
| Role Name | View prices for the Kani assigned to this role. |

### Examples
```
?shop
```
```
?shop explorer
```

## `?lb`
List a leaderboard of scum holders. By default this will list the three players
with the most scum.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | Change the number of results displayed. |

### Examples
```
?lb
```
```
?lb 10
```

## `?bp`
List a leaderboard of battle points. By default this will list the five players
with the most battle points.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | Change the number of results displayed. |

### Examples
```
?bp
```
```
?bp 15
```

## `?whobuff`
List a leaderboard of most buffed Kani. By default this will list the ten
players with the most buffs on their rumbler.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | Change the number of results displayed. |

### Examples
```
?whobuff
```
```
?whobuff 20
```

## `?inspect`
View the stats of another player’s kani.

This command takes one required and one optional argument:

| Argument      | Description                                                     |
| ------------- | --------------------------------------------------------------- |
| `@playername` | Required, the `@` username of the player you wish to challenge. |
| Role Name     | View stats for the Kani assigned to this role.                  |

### Examples
```
?inspect @Calver
```
```
?inspect @Calver explorer
```

## `?lkani`
Display the base stats of any Kani. 

This command requires one argument:

| Argument  | Description                                                 |
| --------- | ----------------------------------------------------------- |
| Asset ID  | The Algorand ASA ID of the Kani NFT.                        |

### Example
```
?lkani 123456789
```

# Items
## `?blueprints`
Display the Kani Coin and Blockchain Fragement requirements to craft an item.
If no item index is given this command will list the available items.

This command takes one optional argument.

| Argument   | Description                                 |
| ---------- | ------------------------------------------- |
| Item Index | The numerical index of the item to display. |

### Examples
```
?blueprints
```
```
?blueprints 1
```

## `?craft`
Attempt to craft an item. You must have the required Kani Coin in the game, you
can use [`?bal`](/docs/commands/#bal) to view your balance. You must also have
the required number of Blockchain Fragments, you can use
[`?bag`](/docs/commands/#bag) to see which fragments you have collected. See
[here](/docs/items) for more information on item crafting.

This command takes one required argument.

| Argument   | Description                               |
| ---------- | ----------------------------------------- |
| Item Index | The numerical index of the item to craft. |

### Examples
```
?craft
```
```
?craft 1
```

## `?claimable`
Display items available to claim. These could be items you have crafted, Kani
won in a KGE, or other prizes you have won on the Algorand network.

This command takes no arguments.

### Example
```
?claimable
```

## `?claim`
Send item/asa to your Algorand wallet. Note, you must have first opted into the
ASA ID of the item you are claiming.

This command takes one required argument.

| Argument   | Description                                             |
| ---------- | ------------------------------------------------------- |
| Item Index | The numerical index of the item to send to your wallet. |

### Example
```
?claim 1
```

## `?inv`
Display your current available inventory of items which can be equiped on a
Kani.

This command takes no arguments.

### Example
```
?inv
```

## `?equip`
Equips an item to a Kani's open slot. If no arguments are given then this will
equip the first item onto your rumbler.

This command takes two optional arguments in this order:

| Argument   | Description                                                                         |
| ---------- | ----------------------------------------------------------------------------------- |
| Item Index | The numerical index of the item to equip as shown by [`?inv`](/docs/commands/#inv). |
| Role Name  | Equip the item to the Kani assigned to this role.                                   |

### Example
```
?equip 2 explorer
```

## `?unequip`
Removes an item from a Kani. If no arguments are given then this will remove
the item from your rumbler.

This command takes two optional arguments in this order:

| Argument    | Description                                                         |
| ----------- | ------------------------------------------------------------------- |
| Slot Number | The numerical index of the item slot from which to remove the item. |
| Role Name   | Equip the item to the Kani assigned to this role.                   |

### Example
```
?unequip 1 explorer
```

# Kani Coin
## `?auto-dis`
Toggle auto distribution off or on of Kani Coin to your Algorand wallet
following the KGE. If you disable automatic distribution then you will need to
run [`?withdraw`](/docs/commands/#withdraw) to remove your Kani Coins from the game.

This command takes one optional argument:

| Argument | Description                                                |
| -------- | ---------------------------------------------------------- |
| State    | The desired auto distribution state, either `off` or `on`. |

### Examples
```
?auto-dis
```
```
?auto-dis off
```

## `?withdraw`
Withdraw Kani Coins from the game (minimum 50 KC) and send them to your
Algorand wallet.

This command takes one required argument:

| Argument | Description                                                |
| -------- | ---------------------------------------------------------- |
| Amount   | The desired auto distribution state, either `off` or `on`. |

# Marketplace
## `?market`
Show all of the current listings in the marketplace. Each item is given an
index number which you will need when attempting to purchase from the market.

This command takes no arguments.

### Example
```
?market
```

## `?buy`

{: .warning }
> This is where the UX is not so nice, apologies everyone!

Purchase an item from the marketplace. You will need to enter the price and
currency as a confirmation you are purchasing the correct item.

This command takes three required arguments in this order:

| Argument   | Description                                                   |
| ---------- | ------------------------------------------------------------- |
| Item Index | The numerical index of the item to purchase.                  |
| Price      | The amount of scum or Kani Coin for which the item is listed. |
| Unit       | The currency identifier for the price, either `scum` or `kc`. |

### Examples
```
?buy 1 1000 scum
```
```
?buy 2 50 kc
```

## `?sell`

{: .warning }
> Again sorry for the poor UX.

List an item on the marketplace. The item will need to be entered as it is
shown by the [`?bag`](/docs/commands/#bag) command (e.g. `fragment-0`). If the
name of the item contains a space you will need to wrap it in quotation marks.
You can ask for either `scum` or `kc` (Kani Coin).

This command takes three required arguments in this order:

| Argument  | Description                                                                       |
| --------- | --------------------------------------------------------------------------------- |
| Item Name | The name of the item as it is shown by the [`?bag`](/docs/commands/#bag) command. |
| Price     | The amount of scum or Kani Coin for which the item is to be listed.               |
| Unit      | The currency identifier for the price, either `scum` or `kc`.                     |

### Examples
```
?sell fragment-9 500 scum
```
```
?sell "Wrestle Weed" 100 kc
```

# Other
## `?roll`
Roll a die to generate a random number. By default this simulates a d20.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | The number of sides on the die to roll. |

### Examples
```
?roll
```
```
?roll 6
```
