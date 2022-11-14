Fix lag caused by Subscriber module oversight. Configurable item search interval. Fix Request module To-Do list grabber skipping items.




![ModulesScreenshot](https://i.imgur.com/wMzIAYp.png)

This update brought to you by Robb#6731

## New Stuff

- The Subscriber and Disperser modules now have a progress bar on their Overview panel widgets to convey how long it will be until they next check for items to transfer.
- Configuration options for how frequently modules check for nearby buildings and check if items need to be moved

## Bugfixes

- Fixed oversight causing the Subscriber module to update nearby tracked buildings every tick, and to not go to sleep when its requests were met (thanks lilly!)
- Fixed oversight causing To-Do List requesting to not actually request anything (thanks Mughi!)
- Fixed oversight that caused Requester Module to keep searching for items at long range even when it has no more items to look for
- Fixed Request module To-Do List functionality in multiplayer (it would previously silently do nothing)

## Notice

**The balance of this mod is still being figured out. Power costs, recipes, and unlock order are all highly likely to change.**

Please leave suggestions and report issues either on the [Nog's Mods Discord](http://discord.gg/zqp6U7Y7Nu) or [as a Github issue](https://github.com/budak7273/ArmorModules/issues/new/choose).

Feedback on the current balance, performance issues, and your thoughts on the mod in general would be greatly appreciated. The [Discord](http://discord.gg/zqp6U7Y7Nu) is the best place to reach us.
