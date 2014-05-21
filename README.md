NoBodygroups
============

![NoBodygroups](http://i.imgur.com/O4FjIBC.jpg "NoBodygroups")

NoBodygroups is a modification for Team Fortress 2 that disables all cosmetic-related bodygroups on the default Valve player models. Scout, Soldier, Pyro, Demoman, Heavy, Engineer and Sniper no longer get their default clothes and accessories removed when a player equips a cosmetic that toggles a bodygroup.

These player models are combined with another mod, which handles the removal of the cosmetics themselves. Using a 0-byte model cache file, the Source engine does not render the model, even though it may be fully intact in the game files. This keeps the mod rather space-friendly, and no "dummy" models have to be created.

Other changes are added to restore certain things to their default counterparts, such as festive weapons. The result is a Team Fortress 2 without cosmetics, unusual effects, and other things. It is similar to the original TF2 before the Sniper vs. Spy update, except for the new unlockable weapons, which cannot be removed.

**This mod is not guaranteed to improve performance, or work correctly under servers that block custom content.**

Installation
==========

*Obviously, this requires you have Steam and Team Fortress 2 installed on your operating system.*

Doing it right: `custom\no_hats\` or `custom\no_hats.vpk`

Doing it right: `custom\no_bodygroups\` or `custom\no_bodygroups.vpk`

Doing it **WRONG**: `custom\nobodygroups-master\no_hats\` or `custom\nobodygroups-master\no_bodygroups\` or `custom\nobodygroups-master.vpk`

###Microsoft Windows
Put the included folder inside the following directory: `C:\Program Files\Steam\SteamApps\common\Team Fortress 2\tf\custom`

**Note**: `C:\` may be replaced with the drive letter you installed Windows on.

**Note**: 64-bit Windows users will need to use `Program Files (x86)` instead of `Program Files`.

###GNU/Linux
Put the included folder inside the following directory: `~/Steam/SteamApps/common/Team Fotress 2/tf/custom`

###Mac OS
Put the included folder inside the following directory: `(your home folder)/Library/Application Support/Steam/SteamApps/common/Team Fortress 2/tf/custom`

**Note**: Replace `(your home folder)` with the name of your home folder.

Known Issues
==========

Servers that block content with `sv_pure` may make this mod not work correctly. While the hats will be removed regardless of `sv_pure` setting, some things may not work, such as player models and other additional content. This mod plays the best on `sv_pure 0` and `sv_pure -1` servers.

Due to Demoman's foot bodygroup being shared with weapons **and** cosmetics, I chose not to change this bodygroup. Any cosmetics that use this bodygroup will not be removed. It is possible to fix, but requires creating "dummy" models of the Demoman's original foot mesh, for every single cosmetic item that toggles this bodygroup.

Some cosmetics may be missed, like the various medals given out during competitive tournaments. Usually, this isn't much of a problem.

Credits
==========

**Snowshoe** - Main contributor.

**SergeantJoe** - Player source files for which the player models used in this modification are based on.

**Tricky X** - Original creator and contributor of NoHats Modification.
