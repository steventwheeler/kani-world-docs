---
layout: page
title: Kani Coin
parent: Documentation
---
# Kani Coin
Kani Coin is accumulated passively by holding Kani in your wallet and actively
through playing the game. In-game Kani Coin rewards are distributed in the
weekly [PVP](/docs/gameplay/weekly-events) and [raid](/docs/gameplay/raids)
events. The in-game Kani Coin is sent to your wallet at the end of the week
after the [KGE](/docs/gameplay/kani-generating-event).

The Kani Coin asset id is `638594993`. Please add this asset if you want to
receive Kani Coin distributions to your wallet.

{: .pro-tip }
> If you want to keep the Kani Coin in your game account (not your wallet), you
> can turn off the automatic distribution with the
> [`?auto-dis`](/docs/commands/#auto-dis) command you can then manually
> withdraw the Kani Coin at any time using the
> [`?withdraw`](/docs/commands/#withdraw) command.

## In Game Utility
Kani Coin has 3 primary uses in the game. To use Kani Coin in game, it must be
in your game account, not your wallet. To send Kani Coin to in game account
send the Kani Coin to this Algorand address.
```
KAPPAONZDABE5CJI4JL6NWFUP4WDHBBKIOAOHIANH57K3CPXKSPKTLADWI
NFD: kappa.kaniworld.algo
```

### Name Change
You can use Kani Coin to change the name of your Kani. This will change the
display name in game as well as update the ARC69 metadata with your name in the
NFT description. The fee for changing a name is 10 KC. Use the
[`?name`](/docs/commands/#name) command to update your Kani's name.

### Special Move Reroll
Sometimes Kani are generated with undesirable
[special moves](/glossary/#special-move), i.e. a Kani has the *Claw Crush*
special, but a power of 5. You can use Kani Coin to reroll your special to a
different one that better suits your build and your Kani's base stats. The fee
starts at 10 KC and increases by 10 for each use to a maximum of 50 KC. Each
roll will give you an equal chance at any of the special moves excluding your
current special. Use the [`?reroll`](/docs/commands/#reroll) command to change
your Kani's special move.

### Item Crafting
You need Kani Coin in the game in order to craft an item. The fee for each item
will vary. You can use [`?blueprints`](/docs/commands/#bludprints) to view the
fee for each item. See [item crafting](/docs/gameplay/items) for more details.

## Kani Coin Shotengai
Kani Coin Shotengai is a shopping arcade for all your Kani related shopping.

## Kani Shuffle
Bi-weekly shuffles to get one of the new babies from the KGE. There are usually
around 5 babies available in the shuffles, winning the Kani Shuffle gives you
access to the ALGOxNFT shuffle for the week. To enter, in the `#kani-shuffle`
channel, the shuffle use `!enter` for registered players or `!enter <wallet>`
for non registered players. I collect the wallet up front as it saves time in
creating the WL for the ALGOxNFT shuffle.

## Kani Traders
This is a place to sell/request/trade Kani. If new players are looking to pick
up a Kani this is a great place to ask. 

## Kani Coin Auctions
Kani Coin Auctions is a channel for any auction in Kani Coin. Community members
are welcome to list anything they like in this channel and moderate the
auctions themselves. Please be careful when using this channel as all
auctions/sales/trades are the responsibility of the parties involved in the
auction. When completing trades I recommend using
[Swapper Tools](https://app.swapper.tools) or
[Nexus App](https://app.nexusasa.com) to stay safe.

## Bounty Hunters
This channel is where community members are welcome to post bounties. Please
keep the bounties appropriate and to the rules of the server.

## Kappas Craft House
This is where you can attempt to craft an item by trading, you will need to
bring your [blockchain fragments](/glossary/#blockchain-fragment) and your Kani
Coin. See [here](/docs/gameplay/items#item-crafting) for more details.

## Kappas Marketplace
The marketplace is a place to trade
[blockchain fragments](/glossary/#blockchain-fragment) and
[consumable items](/glossary/#consumable-item) with other players. Each player
is limited to one listing at a time. Creating a new listing will overwrite your
existing listing.

{: .warning }
> The marketplace is very basic and has had limited testing. Use at your own
> risk.

### Marketplace Commands
- [`?market`](/docs/commands/#market) shows all current listings. Each item is
  given an index number which you will need when attempting to purchase from
  the market.
- [`?buy`](/docs/commands/#buy) this is where the UX is not so nice, apologies
  everyone! You will need to enter the price and currency as a confirmation you
  are purchasing the correct item.
- [`?sell`](/docs/commands/#sell) again sorry for the poor UX. The item will
  need to be entered as it is in your [`?bag`](/docs/commands/#bag) (e.g.
  `fragment-0`). You can ask for either `scum` or `kc`.
- [`?cancel`](/docs/commands/#cancel) this will remove your current listing
  from the market.
