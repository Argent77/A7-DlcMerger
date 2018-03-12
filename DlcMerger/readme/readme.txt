DLC Merger
~~~~~~~~~~

Version: 0.1-beta
Author:  Argent77


Overview
~~~~~~~~

Enhanced Edition games provide a feature that lets you use self-contained DLC archives to add or modify content.
The best known example is the "Siege of Dragonspear" expansion which comes as a DLC archive on GOG and Steam platforms.

The downside of this distribution method is the limited ability to mod the game however, since files contained in DLC 
archives can't be easily accessed or further modified without recreating the whole DLC. This mod attempts to solve 
this restriction by merging DLCs with the main game. The mod provides three options. You can specifically merge 
"Siege of Dragonspear" with BG:EE, merge a user-defined DLC archive or all DLCs found in the search paths of the game.

"DLC Merger" is meant as an alternative to "modmerge". Developed by a Beamdog developer, that tool was the only way 
to make Siege of Dragonspear available for modding. However, unlike modmerge, this mod is platform-independent and 
fits seamlessly into the stack of other WeiDU mods. It allows you to merge any DLC archive and provides an option to 
revert the whole merge operation.


Installation
~~~~~~~~~~~~

This is a WeiDU mod, that means it is very easy to install. Simply unpack the downloaded archive into your game 
directory and run "setup-DlcMerger.exe". Follow the instructions to merge the desired DLC archives.


Components
~~~~~~~~~~

This mod provides three options to merge DLC archives with the game:

1. Merge "Siege of Dragonspear" with BG:EE (BG:EE and the SoD DLC required)

Merges the "Siege of Dragonspear" from any of the supported DLC locations with Baldur's Gate: Enhanced Edition.


2. Merge a user-defined DLC archive (Enhanced Edition game required)

Merges a single DLC archive with the game. The mod prompts for the name of the DLC archive, which can be located in 
any of the supported DLC paths. Supported DLC paths are (in order of application):
- Documents directory of the game
- Installation directory of the game
- "dlc" folder in install directory
- "workshop" folder in install directory (requires DLC files with .mod extension)


3. Merge all available DLC archives (Enhanced Edition game required)

This option scans all supported DLC search paths of the game for available DLC archives. Each DLC will be merged in 
the same order as it would be loaded by the game, so that multiple DLC archives may safely override files from other 
DLCs without causing issues.


IMPORTANT: WeiDU currently fails if the path to the DLC archive contains spaces. This affects DLCs found in the 
documents directory of the game, or if the DLC archive name itself contains spaces.
To work around this issue, place DLC archives into the installation directory or one of its subfolders "dlc" or 
"workshop" and make sure their filenames don't contain spaces.


Copyright Notice
~~~~~~~~~~~~~~~~

The mod "DLC Merger" is licensed under the "Creative Commons Attribution-ShareAlike 4.0 International License" 
(http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

1.0
- Initial release
