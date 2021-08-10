# Diablo II Text Mods

This is a collection of simple text mods for Diablo II

### Included Mods

- Stack Size
  - Key stack size increased from 12 to 50
  - Tome stack size increased from 20 to 80
  - Arrow and bolt stack size increased to 500
  - Enables mana potions to be sold by vendors
  - Supports 1.00, 1.05b, 1.07, 1.08, 1.09b, 1.13c

### Installation

1. Copy the data folder for any mods you would you would like to use into your
   Diablo II folder. Select merge if prompted due to an existing data folder.
   Make sure to copy the correct data folder for the version you play.

   Note: Some mods may work with versions not officially supported. This is
   more likely if they are similar patches. For example, 1.09b and 1.09d, or
   1.13c and 1.13d. However, mods have only been tested and confirmed to work
   with the officially supported versions.

2. Add `-direct -txt` to the shortcut you use to launch the game. You can do
   that by right clicking on the shortcut, selecting `Properties`, typing
   ` -direct -txt` at the end of the file path in the `Target:` text box, and
   then clicking `Apply` or `OK`. Make sure you leave a space after the file
   path and between `-direct` and `-txt`.

   If you use PlugY you can also achieve this by adding `-direct -txt` after
   `Param=` in your PlugY config file (PlugY.ini) so that it looks like this:
   `Param=-direct -txt`.

   If you are using Lutris to play the game on Linux you can do this by right
   clicking on the game in Lutris, selecting `Configure`, clicking on the
   `Game options` tab, adding `-direct -txt` to the `Arguments` text box,
   and then clicking `Save` in the bottom right corner.
