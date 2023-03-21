---
layout: page
title: Bot Commands
---
# Getting Started
## `?verify`
Verify your wallet and get the `@Kani Owner` role.  
  

# Kani Management
## `?mykani`
View your Kani and their stats.  

If no additional arguments are given this will display the stats of your
rumbler Kani.

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
Attack the raid boss. See [here](/docs/raids) for more information on raids. By
default this command uses your rumbler Kani to attack the boss.

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
- `?shop` | `?shop <role>` - List the price of buffs for your Kani
- `?lb` | `?lb <number>` - List a leaderboard of scum holders
- `?bp` | `?bp <number>` - List a leaderboard of Battle Points
- `?whobuff` | `?whobuff <number>` - List a leaderboard of most buffed Kani
- `?inspect <player>` - Shows the player’s rumbler kani
- `?lkani <asset-id>` - Display the base stats of any Kani. 

# Items
- `?blueprints` | `?blueprints <number>` - Display the requirement to craft an item.
- `?craft <item number>` - Attempt to craft an item
- `?claimable` - Display items available to claim
- `?claim <claimable number>` - Send item/asa to your Algorand wallet
- `?inv` - Display your current available inventory
- `?equip <inv number> <role>` | `?equip` - Equips an item to a Kani
- `?unequip <item slot number> <role>` | `?unequip` - Removes an item from a Kani

# Kani Coin
- `?auto-dis off` | `?auto-dis` - Toggle auto distribution off and on
- `?withdraw <coins>` - Withdraw Kani Coins from the game (minimum 50 KC)

# Other
- `?roll <number>` - roll a random number
