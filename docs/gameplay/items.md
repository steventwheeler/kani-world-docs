---
layout: page
title: Items
parent: Gameplay
grand_parent: Documentation
---
# Items
Items will primarily be available through crafting. Some items will be reserved
for prizes and other in game rewards. Items will be released in sets with each
set having a different equip and embed bonus, different fragment requirements
and an increased crafting cost. 

## Equip
Equipping an item adds the equip bonus to your Kani as long as the item remains
equipped. This bonus is not reset after the KGE. Initially, there will only be
1 slot that items will be able to be equipped to. After the 2nd item set is
released the 2nd item slot will be unlockable.

## Embed (Future Update)
Embedding will allow a player to permanently embed the item into the Kani,
destroying the item in the process. An embedded item give the Kani both the
equip and the embed bonus and frees up the equipment slot. Embedding will be
very expensive and you may find you have to sacrifice some of your least
favorite Kani in order to complete the embed procedure.

## Item Crafting
There will be multiple items released. The initial series is a Kani World based
item. Crafting has a three day cooldown.

Currently when players damage raid bosses or get lucky in a scavenge they will
get a [blockchain fragment](/glossary/#blockchain-fragment). To see what
fragments you have you can use the [`?bag`](/docs/commands/#bag) command. These
fragments are used to craft items that Kani can either equip or embed (future
update). 

To craft an item will require a set of fragments that correspond to the item
being crafted and a Kani Coin crafting fee. Each item will have 1 of 5 rarities
associated with it, common, uncommon, rare, epic, and legendary.

### Crafting Commands
- [`?blueprints`](/docs/commands/#blueprints) - Blueprints allows you to see
  what items can be crafted. Each item has an index next to the name and to
  find out more about that particular item you can use `?blueprints <index>`.
  For example `?blueprints 1`
- [`?craft <index>`](/docs/commands/#craft) - Craft allows you to craft the
  item provided you have the correct fragments in your bag and enough Kani coin
  in your game account. Once crafted the item will be placed into your
  claimable assets. The index is the index from the blueprints command and is
  required.
- [`?claimable`](/docs/commands/#claimable) - View assets you have available to
  claim. This list allows you to see the asa of the asset, opt in if you
  haven't already. 
- [`?claim <index>`](/docs/commands/#claim) - Attempt to send an asset to your
  wallet. This command only sends 1 asset at a time and the index is required.
  You can find the item index by using ?claimable. note If you have multiple
  items to claim and a transaction fails the index will be updated so you might
  have to run `?claimable` again to get the correct index.

## Item Management
Once an item is claimed to your wallet your item will be added to your account
and you can equip it to 1 of your Kani. 

- [`?inv` or `?inventory`](/docs/commands/#inv) - Shows all the items you
  currently have available to equip to a Kani. Each item will have an index
  number next to it (1, 2, 3) which you can use to identify which item you want
  to equip. 
- [`?equip`](/docs/commands/#equip) - Equip an item to a Kani. This command
  attempts to add an item from your inventory to your Kani. The index is
  available by using ?inv and if an item is already equipped this command
  will swap the items returning the previously equipped item to your
  inventory. By default this command uses index 1 and the rumbler role. 
- [`?unequip`](/docs/commands/#unequip) - This will remove an item from an
  equipment slot of a Kani with a role. This returns the item to your
  inventory. 

{: .note }
> [`?inv`](/docs/commands/#inv) triggers a data update with new data from your
> wallet, similar to how [`?mykani`](/docs/commands/#mykani) updates the Kani
> in your game account. This update will remove equipped items from your Kani
> if the item isn't in your wallet. 

## Item Slots
 Each Kani has 2 item slots. The first item slot is available at the moment. The second item slot will be unlockable (with KC) in a future update. 
