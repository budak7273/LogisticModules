Update 6 support. New Request Module features. Significant Multiplayer fixes, UI improvements, bugfixes, and code cleanup.




![ModulesScreenshot](https://i.imgur.com/wMzIAYp.png)

This update brought to you by Robb#6731

## New Stuff

- Modules now display additional status text in the Overview suit tab
- Added audio feedback to many UI interactions
- Request size config options for **Logistic Requester Module** (see Changed Stuff)
- Config options: multipliers for module passive power cost and per-item operation cost
- Debug logging configuration option, which also that makes it so that the Subscribe and Disperse modules require manual triggering to operate.

## Changed Stuff

- All modules renamed to include the text 'Module' for searchability and clarity
- Updated descriptions of most modules to better describe how they function
- In-progress transfers in the HUD have their progress bar color coded to the module requesting them
- **Logistic Requester Module**
  - 'Favorite Requests' system fleshed out
  - Alt-click a listing in the search list to favorite it, which appears in the suit Overview tab
  - Clicking now requests 1 (can edit in config)
  - Ctrl-Clicking now requests 10 (can edit in config)
  - Shift-Clicking now requests 1 Stack
  - Alt-Clicking now removes the request from favorites

## Bugfixes

- Significant internal code rewrite that still isn't done. This could have broken or fixed a number of things not listed here.
- Fixed that multiplayer clients couldn't delete listings from Subscribe and Disperse modules
- Fixed many sub-bugs that contributed to all Modules not being able to interact with a container that the player has interacted with until the save is reloaded
- Prevented numerous "items" from showing up in searches that shouldn't be (ex. scannable Hog placeholder item)
- Fixed bug causing the flying item visuals to originate and/or terminate at a location that didn't match the containers being interacted with
- Fixed rare item duplication bug caused by both the source and destination of an item transfer being full after a transfer was started
- Stopped logistic modules with no active transfers from taking up space in the HUD

## Notice

**The balance of this mod is still being figured out. Power costs, recipes, and unlock order are all highly likely to change.**

Please leave suggestions and report issues either on the [Nog's Mods Discord](http://discord.gg/zqp6U7Y7Nu) or [as a Github issue](https://github.com/budak7273/ArmorModules/issues/new/choose).

Feedback on the current balance, performance issues, and your thoughts on the mod in general would be greatly appreciated. The [Discord](http://discord.gg/zqp6U7Y7Nu) is the best place to reach us.
