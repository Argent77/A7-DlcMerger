# DLC Merger
*Allows you to merge DLC archives into Infinity Engine Enhanced Edition games.*

## Overview
Enhanced Edition games provide a feature that lets you use self-contained DLC archives to add or modify content. Best known example is the *"Siege of Dragonspear"* expansion, which comes as a DLC archive on GOG and Steam platforms.

The downside of this distribution method is the limited ability to mod the game however, since files contained in DLC archives can't be easily accessed or further modified without recreating the whole DLC. This mod attempts to solve this restriction by merging DLCs with the main game. The mod provides three options. You can specifically merge *"Siege of Dragonspear"* with BG:EE, merge a user-defined DLC archive or all DLCs found in the search paths of the game.

*DLC Merger* is meant to be an alternative to *modmerge*. Developed by a Beamdog developer, that tool was the only way to make Siege of Dragonspear available for modding. However, unlike *modmerge*, this mod is platform-independent and fits seamlessly into the stack of other WeiDU mods. It allows you to merge any DLC archive and provides an option to revert the whole merge operation.

## Components
This mod provides three options to merge DLC archives with the game:

#### 1. Merge "Siege of Dragonspear" with BG:EE (BG:EE and the SoD DLC required)

Merges the "Siege of Dragonspear" from any of the supported DLC locations with Baldur's Gate: Enhanced Edition.

**Note:** You need to apply the [Big World Fixpack](https://github.com/BiGWorldProject/BiG-World-Fixpack) if you want to use this mod in conjunction with EET (Enhanced Edition Trilogy).

#### 2. Merge a user-defined DLC archive (Enhanced Edition game required)

Merges a single DLC archive with the game. The mod prompts for the name of the DLC archive, which can be located in any of the supported DLC paths. Supported DLC paths are (in order of application):
- Documents directory of the game
- Installation directory of the game
- "dlc" folder in install directory
- "workshop" folder in install directory (requires DLC files with .mod extension)

#### 3. Merge all available DLC archives (Enhanced Edition game required, 64-bit WeiDU installer required)

This option scans all supported DLC search paths of the game for available DLC archives. Each DLC will be merged in the same order as it would be loaded by the game, so that multiple DLC archives may safely override files from other DLCs without causing issues. Because of technical reasons, this operation is currently only successful if the mod is invoked by a 64-bit WeiDU installer.
