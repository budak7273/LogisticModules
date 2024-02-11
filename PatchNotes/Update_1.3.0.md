Improved in-inventory UI of some modules. Bugfixes.




![ModulesScreenshot](https://i.imgur.com/wMzIAYp.png)

This update brought to you by Robb.
If you enjoy my work, please consider my [completely optional tip jar](https://ko-fi.com/robb4).

## Changed Stuff

- Logistic Request, Subscribe, and Disperese module UI
  - Expand/collapse section triangle is no longer black-on-gray and doesn't resize when changing shape
- Pocket Inventory module UI
  - Added additional tooltips
  - Separated the "stack control" input from the fill percent bar
  - Switched to "factory orange" instead of "why is this blue?"
  - Fixed button shapes/colors that UE5 broke
    - Expand/collapse section triangle is no longer black-on-gray and doesn't resize when changing shape
  - Removed the warning about typing in the "stack control" input because
    the game no longer tries to activate your Equipment Shortcuts while typing
  - Changed the "stack control" input maximum value (of stacks to keep in your inventory) from 10 to 100
    - The only reason it was that low previously is so the slider would be reasonable to set by dragging,
      which was the only reliable way to set a value
    - You can only input values above 10 by typing them in directly

## Bugfixes

- The logistic subscribe module was randomly turning off for no clear reason, this may have been fixed. Please let me know if you're still running into issues with this.

## Known Bugs

- The hub's built-in storage container can't be seen by logistic modules
- The Subscriber module does not intelligently select the largest stack to pull from to supply its demands, so it could pull multiple smaller batches.

## Notice

**The balance of this mod is still being figured out. Power costs, recipes, and unlock order are all highly likely to change.**

Please leave suggestions and report issues either on the [Nog's Mods Discord](http://discord.gg/zqp6U7Y7Nu) or [as a Github issue](https://github.com/budak7273/ArmorModules/issues/new/choose).

Feedback on the current balance, performance issues, and your thoughts on the mod in general would be greatly appreciated. The [Discord](http://discord.gg/zqp6U7Y7Nu) is the best place to reach me.
