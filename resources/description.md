#Features

Allows erasing and reprogramming of modules into other modules through "blank modules".

Inspired by the programmable modules in [Industrial Revolution 2](https://mods.factorio.com/mod/IndustrialRevolution) made by [Deadlock989](https://mods.factorio.com/user/Deadlock989).

![Demo](https://raw.githubusercontent.com/Soul-Burn/Factorio-flexible-modules/main/resources/demo.gif)

Blank modules can be created in 2 ways:

* The original module recipe, with ingredient modules replaced with a blank of the relevant level.
* Erasing an existing module.

#Settings

Startup settings to reduce clutter:

* Disable direct module recipes - Disables the original module recipes. Modules have to be created as blanks and then programmed to be used.
* Disable crafting of blank modules - Disables recipes for blank modules. Modules are created with the original recipes, but can then be erased to be reprogrammed as another module of the same level.

Both options are unchecked by default. Checking both options will remove the ability to create modules and may cause an unwinnable game. Only one option or neither should be checked at a time.

#Compatibility

This mod was tested with for compatibility the following mods:

* [Base](https://factorio.com/)
* [Space Exploration](https://mods.factorio.com/mod/space-exploration)
* [Krastorio 2](https://mods.factorio.com/mod/Krastorio2)
* [SeaBlock](https://mods.factorio.com/mod/SeaBlockMetaPack) - Blank modules are shown as level 2, 4, 6, 8, following the internal modules names.
* SeaBlock without [CircuitProcessing](https://mods.factorio.com/mod/CircuitProcessing)

Incompatible with:

* [Industrial Revolution 2](https://mods.factorio.com/mod/IndustrialRevolution) - Already has a similar programming mechanism.
* [PyAlienLife](https://mods.factorio.com/mod/pyalienlife) - Has many unique modules with special interactions.

Please note that if a module's recipe is changed by a different mod's update, the "blank module" recipes may change as well.