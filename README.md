# HexedUT2k4 - HexedPatches

This package provides QoL improvements to Unreal Tournament 2004. With the launch of OldUnreal patches, most of the features of this package are deprecated.

The following QoL improvements are provided for any game version:
* Better font scaling for higher resolutions (may cause some font cropping/overflow, since some background elements are not properly scaled).

The following QoL improvements are provided for the legacy 3369 version of the game:
* Modern resolutions available in the settings menu.
* Small cursor to compensate absurd scaling when using high resolutions.
* Correct widescreen scaling for default HUDs.
* Higher FOV limit in the settings menu.
* Player models are no longer cropped in the settings menu (when using a widescreen resolution).
* Persistent custom network speed (applied on every level change).
* Master server selector (either 333network or OpenSpy).

For previous releases, check the main [HexedUT2k4 repository](https://github.com/hexengraf/HexedUT2k4/releases).

## Installation

Download the [latest release](https://github.com/hexengraf/HexedUT2k4-Patches/releases/latest) and extract it inside the root directory of your UT2004 installation, merging the `System` directory when asked.

To enable HexedPatches, open `System/UT2004.ini` and replace the default value of `GUIController` with `HexedPatches.HxGUIController`:
```ini
; GUIController=GUI2K4.UT2K4GUIController
GUIController=HexedPatches.HxGUIController
```

> [!CAUTION]
> **DO NOT** change the `GUIController` if you plan to join servers running AntiTCC, otherwise you will most likely be **BANNED**.

All configuration can be changed through a new tab called "HexedPatches" in the settings.
