Update 8 support. Bugfixes. No longer requests tiny stacks from machine output slots.




![ModulesScreenshot](https://i.imgur.com/wMzIAYp.png)

This update brought to you by Robb#6731

## Changed Stuff

- Temporary change: Logistic modules will now only interact with buildings that inherit from FGBuildableStorage
  - This means: Storage Containers, Industrial Storage Containers, and Personal Storage boxes in the base game
  - This is to avoid the fact that changes to the base game's inventory handling means I can't easily prevent the modules from stealing power shards out of machines' overclocking slots
  - Also, people were getting annoyed with modules taking small quantities of items from building output slots. This will bandaid fix that issue.
  - I will eventually™ change this back, but I would like to get the mod out for Update 8 rather than wait on this
- Logistic Build module now produces a sound when it requests items for you

## Bugfixes

- Fixed that the Request module could no request items from the to-do list (it was still looking at the deprecated data from past versions of the game)
  - Thanks NightWinder (nightwinder) and others for the report!
- Fixed that the Subscribe module did not save its WIP building filters
  - Thanks Taco (blacotaco) for the report!

## Known Bugs

- The hub's built-in storage container can't be seen by logistic modules
- The Subscriber module does not intelligently select the largest stack to pull from to supply its demands, so it could pull multiple smaller batches.

## Notice

**The balance of this mod is still being figured out. Power costs, recipes, and unlock order are all highly likely to change.**

Please leave suggestions and report issues either on the [Nog's Mods Discord](http://discord.gg/zqp6U7Y7Nu) or [as a Github issue](https://github.com/budak7273/ArmorModules/issues/new/choose).

Feedback on the current balance, performance issues, and your thoughts on the mod in general would be greatly appreciated. The [Discord](http://discord.gg/zqp6U7Y7Nu) is the best place to reach me.
