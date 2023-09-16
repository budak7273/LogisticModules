<!-- # Test early releases for Update 8 on the [Discord](http://discord.gg/zqp6U7Y7Nu)! -->

# PowerSuit Logistic Modules

![ModulesScreenshot](https://i.imgur.com/wMzIAYp.png)

[![PowerSuit Logo](https://i.imgur.com/ZRtYzSN.png)](https://ficsit.app/mod/7J2LyFzTakqPQ5)
[![SMART Logo](https://i.imgur.com/JtXv6NA.png)](https://ficsit.app/mod/5yGWmmB8KL2Zq8)
![Singleplayer compatibility: full](https://i.imgur.com/S8roc0Y.png)
![Multiplayer compatibility: partial](https://i.imgur.com/GJh3Lcb.png)
<!-- ![Early Access version support: full](https://i.imgur.com/1TXo5em.png) -->
<!-- ![Experimental version support: none](https://i.imgur.com/pc6D9bs.png) -->

Automatically keep your inventory stocked from the containers around you, request specific items from them, or send out excess items from your inventory!

This mod introduces a number of new modules for [PowerSuits](https://ficsit.app/mod/7J2LyFzTakqPQ5) that allow the user to transer items to and from containers and machines in the world.

**More demonstration videos coming to the mod page soon.**

Works well with the [PowerSuit Modules](https://ficsit.app/mod/BezrE8aswqXLRX/) suite of mods. _Not currently included in [Modpack: All PowerSuit Modules](https://ficsit.app/mod/ArmorModules__Modpack_All)_ because it's not fully ready for multiplayer yet.

Please leave suggestions and report issues either on the [Nog's Mods Discord](http://discord.gg/zqp6U7Y7Nu) or [as a Github issue](https://github.com/budak7273/ArmorModules/issues/new/choose).

## Notice + Multiplayer Support WIP

**The balance of this mod is still being figured out. Power costs, recipes, and unlock order are all highly likely to change.**

Feedback on the current balance, performance issues, and your thoughts on the mod in general would be greatly appreciated. The [Discord](http://discord.gg/zqp6U7Y7Nu) is the best place to reach us.

This mod has been tested in singleplayer, but limited testing has been done in multiplayer. However, **numerous users have reported no problems in multiplayer**, so I suggest you give it a shot. A few bugs probably remain, but you may not notice them.

## Mod Incompatibilities

If you try to use these mods at the same time as this mod, something will not work as expected.

- [Stack Overflow](https://ficsit.app/mod/StackOverload) can prevent the Subscribe, Disperese, and Pocket Dimension modules from working correctly.

## Modules on Offer

<video controls="" width="720" height="405">
  <source src="https://i.imgur.com/8sGOtbr.mp4" autoplay="false" controls="true" type="video/mp4">
</video>

All Modules except 'Logistics Pocket Dimension' are Unique (additional copies of the same module can't be installed)

### Functional Modules

[![VideoLink](https://i.imgur.com/tFhvRc5.png)](https://streamable.com/yuypdz)

[This video](https://streamable.com/yuypdz) demonstrates the **Logistics Build** and **Logistics Request** modules

**More demonstration videos coming soon.**

The further away the item is, the more power the module consumes, and the longer it takes to arrive. Active transfer tasks will appear above your suit HUD.

- **Logistic Builder Module**
  - Short range, instant transfer speed
  - When trying to build and lacking the required ingredients, this Module will request them from containers in range.
  - Automatically activated when you select a new Build Gun recipe and you're lacking the required items to build it.
  - Compatible with [Smart!](https://ficsit.app/mod/5yGWmmB8KL2Zq8)
- **Logistic Subscriber Module**
  - Medium range, normal transfer speed
  - Specify minimum quantities of certain items to keep in your inventory. When you are below this amount, items will be delivered from containers in range to refill you.
  - You can import/export settings for the module from your computer's clipboard.
- **Logistic Disperser Module**
  - Medium range, normal transfer speed
  - Specify maximum quantities of certain items to keep in your inventory.
  - When you are above this amount, the excess items will be sent out to valid containers in range.
  - Valid container targets are ones that already have some of that item, or have filters set via the [Inventory Filters](https://ficsit.app/mod/2gWLoXR9Rrqtvh) mod
  - You can import/export settings for the module from your computer's clipboard.
  - Press a keybind to send whatever inventory stack you're hovering over out to storage
    - [Video demo here](https://streamable.com/5osovj)
- **Logistic Requester Module**
  - Long range, normal transfer speed
  - Request specific items to be delivered to you from containers in range. You can favorite frequently used requests.
  - You can import from your computer's clipboard to request every item it specified.
  - You can also request all items you are missing to satisfy your To Do List.
- **Logistic Pocket Dimension Module**
  - Range N/A
  - An 'inventory expansion' that adds a separate compartment to your inventory
  - [Slightly outdated demo video](https://streamable.com/upyguw)
  - Specify a specific item in its filter, and one stack of that item will be kept in your inventory. Any extra will be moved to the compartment. If you fall below a full stack, the stack will be refilled from the compartment.
  - Multiple can be installed
  - Mk1: 7 slots. Mk2: 14 slots

### Enhancement Modules

- **Logistics Power Amplifier Module**
  - Increases the speed at which the accrued power cost of other Logistic modules ramps down at the expense of increased cost per operation.
- **Logistics Power Stabilizer Module**
  - Decreases the per-item power cost of logistics operations of other Logistic modules but it takes longer for the accrued power cost to ramp down.
- **Logistics Power Synchronizer Module**
  - Generates bonus Power for each unique Logistics module installed in the suit.
  - Reduces the max accrued power cost of Logistics operations.
- **Logistics Range Increaser Module Mk1**
  - Increases logistics operation range.
  - Stacks with the MK2 range increaser.
- **Logistics Range Increaser Module Mk2**
  - Increases logistics operation range
  - Stacks with the MK1 range increaser.

## Mod Compatibility

- Any mod that deletes building clearances could break this mod, as it searches for Clearances to locate buildings to interact with
- The **Logistic Build** module is compatible with [Infinite Zoop](https://ficsit.app/mod/InfiniteZoop) and [Smart!](https://ficsit.app/mod/SmartFoundations)
- The **Subscribe**, **Disperse**, and **Request** modules should be compatible with any modded building that has an inventory component that uses the buildable storage inventory component interface. Mod developers, contact us for more info.
