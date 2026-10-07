# v0.50

First standalone release of HexedPatches.

# v0.40

HexedPatches changes:
* Removed enhanced map vote menu and spawn protection timer.
* Reorganized HexedPatches settings into two sections: Fixes and Legacy 3369 Fixes.
* Fully disabled HUD replacements on OldUnreal patched versions.
* Removed validation of netspeed at every level change on OldUnreal patched versions.

# v0.30

First release aiming to be compatible wit OldUnreal patches!

HexedPatches changes:
* Added code to detect OldUnreal patches and disable conflicting changes.
  * HUD replacements are currently allowed on 3374P9 solely as a temporary fix for weapon FOV.
* Map voting: added graphical indicator for the sorting order when sorting by last played.
* Made the spawn protection timer HUD-independent, so it doesn't require HUD replacements anymore.

# v0.23.1

Hotfix for the map voting page:
* Fixed incorrect map being displayed after a player changes their vote.
* Fixed bug preventing mouse scrolling to work with the game type drop list.
* Fixed bug preventing mouse scrolling after clicking on a list header.

# v0.23

Another update focused on the map voting page.

HexedPatches changes:
* Added option to classify maps as liked/disliked.
* Fixed bug causing votes to not appear if the map voting page was closed when the vote was submitted.
* Several changes to Look and Feel.
* Converted "Seq" column to a compact column to sort by last played.

# v0.22

This update focus on further improving the map voting page.

HexedPatches changes:
* Added map description to the map preview.
* Added new column with the recommended minimum/maximum of players.
* Added search bar for each column of the map list.
* Added new button to select a random map.
* Added option to filter by source: any map, official maps or custom maps.
* Several improvements to font size, line spacing, alignments, backgrounds and colors.
* Made the map voting page persistent, allowing more intuitive behavior (e.g. sort column is remembered).

# v0.21

Very small update.

HexedPatches changes:
* Removed bold from some of the small fonts.
* Added an embedded map preview in the map voting page.

# v0.20

HexedPatches changes:
* Added modern resolutions in the settings menu.
* Increased the FOV limit in the settings menu.
* Fixed player models being cropped in the settings menu (when using a widescreen resolution).
* Added new tab in settings for all HexedPatches options (called "Patches").
* Added option to scale fonts based on screen height instead of width.
* Added HUD replacements to fix widescreen scaling.
* Added a timer to indicate spawn protection duration (requires HUD replacements).
* Added option to validate KeepAliveTimer to make sure it has the default value (0.2).
* Added option to define a persistent custom network speed (applied on every level change).
* Added a master server selector (either 333network or OpenSpy).
