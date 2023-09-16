New "send out the item I'm hovering" keybind for quick trashing. Improved HUD display of large numbers of logistic transfers occurring at once. Improved request module favorites display. Fixed that Disperse module would sometimes now allowing 0 as a stock-keep quantity.




![ModulesScreenshot](https://i.imgur.com/wMzIAYp.png)

This update brought to you by Robb#6731

## New Stuff

- **Disperse anything on demand!**
  - Requires a Logistic Disperse module installed
  - Hover over a stack in your inventory and press the keybind (Alt+D by default) to send it out as if it was part of your disperse requests
  - [Video demo here](https://streamable.com/5osovj)

## Changed Stuff

- Logistic transfer information in your HUD now had a maximum size and will turn into an auto-scrolling scrollbox if you have a lot of them
  - They would previously grow too large and bleed into other sections of the HUD
  - [Video demo here](https://streamable.com/uds0ik)
  - Thanks leatherneck6017 for bringing this to my attention
- Made the displayed range in the Overview round to one decimal place instead of displaying all of them
- Made the displayed power cost in the Overview round to 1 decimal place instead of 3

## Bugfixes

- Fixed that Disperse module would sometimes now allowing 0 as a stock-keep quantity.
  - Previously if you set the "amount to keep" to 0, it would not be saved when you close the screen
  - Thanks Terrulin and leatherneck6017 for bringing this up
- Fixed that Favorite logistic request items wrapped terribly when you had more than 4. They now fill the full row before wrapping, and if they eventually get too numerous, they will be put in a scrollbox.
  - Before:
    - ![Before](https://cdn.discordapp.com/attachments/922902098344042526/1152382944351092736/image.png)
  - After:
    - ![Scrollbox](https://cdn.discordapp.com/attachments/922902098344042526/1152389379084533841/image.png)
  - Thanks leatherneck6017 for sending me a test save that had enough favorites for me to notice this
- Fixed improper coloration on the expand/contract section icon for the Request module's Extended display

## Known Bugs

- The hub's built-in storage container can't be seen by logistic modules
- The Subscriber module does not intelligently select the largest stack to pull from to supply its demands, so it could pull multiple smaller batches.

## Notice

**The balance of this mod is still being figured out. Power costs, recipes, and unlock order are all highly likely to change.**

Please leave suggestions and report issues either on the [Nog's Mods Discord](http://discord.gg/zqp6U7Y7Nu) or [as a Github issue](https://github.com/budak7273/ArmorModules/issues/new/choose).

Feedback on the current balance, performance issues, and your thoughts on the mod in general would be greatly appreciated. The [Discord](http://discord.gg/zqp6U7Y7Nu) is the best place to reach me.
