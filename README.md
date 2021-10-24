## Diablo II Text Mods

This is a collection of simple text mods for Diablo II

### Included Mods

- Stack Size

  - Key stack size increased from 12 to 50

  - Tome stack size increased from 20 to 80

  - Arrow and bolt stack size increased to 500

  - Enables mana potions to be sold by vendors

  - Supports 1.00, 1.05b, 1.07, 1.08, 1.09b, 1.13c

- Town Cast

  - Enable additional spells to be cast in town

    - Teleport, Thunderstorm, Armageddon, Hurricane

    - Charge, Leap, Shout, Battle Orders, Battle Command

  - Allow some spells to be cast in Werewolf and Werebear

    - Teleport, Shout, Battle Orders, Battle Command

  - Supports 1.00, 1.07, 1.13c

- Quest Bug

  - Always get quest drops from Andariel

  - Even if you forget to talk to Warriv

  - Supports 1.13c

- Unsocket

  - New cube recipe for unsocketing

  - Town Portal Scroll + Socketed Item

  - Does not destroy the item or the gems

  - Supports 1.13c

### Installation

1. Backup your characters and the game folder before making any changes.

2. Download the most recent release from the [releases page](https://github.com/cyhyraethz/d2-text-mods/releases) and extract the files.

3. Copy the extracted data folders for any mods you would like to use into the game folder, which should be located in `C:\Program Files (x86)\Diablo II`, and select merge if prompted.

4. Add the parameters `-direct` and `-txt` to the shortcut you use for launching the game. You can do that by right clicking on the shortcut, selecting `Properties`, typing ` -direct -txt` after the file path in the `Target:` text box, and clicking `OK`. Make sure to leave a space after the file path and between `-direct` and `-txt`.

   If you use PlugY you can also achieve this by adding `-direct -txt` after `Param=` in the PlugY config file, PlugY.ini, so that it looks like this: `Param=-direct -txt`.

   If you use Lutris to play the game on Linux you can do this by right clicking on the game in Lutris, selecting `Configure`, clicking on the `Game options` tab, adding `-direct -txt` to the `Arguments` text box, and clicking `Save` in the bottom right corner.

5. If you are adding new mods to an existing data folder, delete the .bin files in `Diablo II\data\global\excel` before launching the game so that new ones can be generated from the text files.

### Additional Notes

Some mods may work with versions that are not listed as being supported. This is most likely with versions that are very similar (e.g. 1.09b and 1.09d, 1.13c and 1.13d). However, only supported versions have actually been tested.

If your cursor is on top of an NPC when casting Teleport in town it will register as you clicking on them and your character will move toward them normally. You can get around this by holding down the Show Items hotkey to prevent your character from targeting the NPC, allowing you to Teleport right next to them.

Hurricane and Armageddon can be precast in town but will not display their animations until you leave town.

Shout, Battle Orders, and Battle Command only affect the caster, not party members, when used in town.
