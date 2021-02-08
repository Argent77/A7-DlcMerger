[![GitHub release (latest by date)](https://img.shields.io/github/v/release/Argent77/A7-DlcMerger?color=darkred&include_prereleases&label=latest%20release)](https://github.com/Argent77/A7-DlcMerger/releases/latest)
[![Github downloads (all releases)](https://img.shields.io/github/downloads/Argent77/A7-DlcMerger/total.svg?color=gold)](https://github.com/Argent77/A7-DlcMerger/releases)
[![Platform](https://img.shields.io/static/v1?label=platform&message=Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Project%20Infinity&color=informational)](https://github.com/Argent77/A7-DlcMerger/releases/latest)
[![Supported games](https://img.shields.io/static/v1?label=supported%20games&message=BG%3AEE%20%7C%20SoD%20%7C%20BG2%3AEE%20%7C%20EET%20%7C%20IWD%3AEE%20%7C%20PST%3AEE&color=indigo)](https://github.com/Argent77/A7-DlcMerger)
[![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20German%20%7C%20Brazilian%20Portuguese&color=limegreen)](https://github.com/Argent77/A7-DlcMerger)

# DLC Merger
*Allows you to merge DLC archives into Infinity Engine Enhanced Edition games.*

[![Beamdog Forums](https://img.shields.io/static/v1?label=Discussion&message=Beamdog%20Forums&color=444&labelColor=eee&style=for-the-badge)](https://forums.beamdog.com/discussion/71305 "Beamdog Forums")

## Overview
Enhanced Edition games provide a feature that lets you use self-contained DLC archives to add or modify content. Best known example is the *"Siege of Dragonspear"* expansion, which comes as a DLC archive on GOG and Steam platforms.

The downside of this distribution method is the limited ability to mod the game however, since files contained in DLC archives can't be easily accessed or further modified without recreating the whole DLC. This mod attempts to solve this restriction by merging DLCs with the main game. The mod provides three options. You can specifically merge *"Siege of Dragonspear"* with BG:EE, merge a user-defined DLC archive or all DLCs found in the search paths of the game.

*DLC Merger* is meant to be an alternative to *modmerge*. Developed by a Beamdog developer, that tool was the only way to make Siege of Dragonspear available for modding. However, unlike *modmerge*, this mod is platform-independent and fits seamlessly into the stack of other WeiDU mods. It allows you to merge any DLC archive and provides an option to revert the whole merge operation.

## Components
This mod provides three options to merge DLC archives with the game:

#### 1. Merge "Siege of Dragonspear" with BG:EE (BG:EE and the SoD DLC required)

Merges the "Siege of Dragonspear" from any of the supported DLC locations with Baldur's Gate: Enhanced Edition.

#### 2. Merge a user-defined DLC archive (Enhanced Edition game required)

Merges a single DLC archive with the game. The mod prompts for the name of the DLC archive, which can be located in any of the supported DLC paths. Supported DLC paths are (in order of application):
- Documents directory of the game
- Installation directory of the game
- "dlc" folder in install directory
- "workshop" folder in install directory (requires DLC files with .mod extension)

#### 3. Merge all available DLC archives (Enhanced Edition game required, 64-bit WeiDU installer required)

This option scans all supported DLC search paths of the game for available DLC archives. Each DLC will be merged in the same order as it would be loaded by the game, so that multiple DLC archives may safely override files from other DLCs without causing issues. Because of technical reasons, this operation is currently only successful if the mod is invoked by a 64-bit WeiDU installer.
