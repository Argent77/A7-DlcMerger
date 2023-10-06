DLC Merger
~~~~~~~~~~

Version:    1.5
Author:     Argent77

Download:   https://github.com/Argent77/A7-DlcMerger/releases
Discussion: https://forums.beamdog.com/discussion/71305


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

3. Merge all available DLC archives (Enhanced Edition game required, 64-bit WeiDU installer required)

This option scans all supported DLC search paths of the game for available DLC archives. Each DLC will be merged in
the same order as it would be loaded by the game, so that multiple DLC archives may safely override files from other
DLCs without causing issues. Because of technical reasons, this operation is currently only successful if the mod is
invoked by a 64-bit WeiDU installer.

IMPORTANT: WeiDU currently fails if the path to the DLC archive contains spaces. This affects DLCs found in the
documents directory of the game, or if the DLC archive name itself contains spaces.
To work around this issue, place DLC archives into the installation directory or one of its subfolders "dlc" or
"workshop" and make sure their filenames don't contain spaces.


Credits
~~~~~~~

Coding and testing: Argent77

Brazilian Portuguese translation: Felipe

Spanish translation: ElGamerViejuno


Copyright Notice
~~~~~~~~~~~~~~~~

The mod "DLC Merger" is licensed under the "Creative Commons Attribution-ShareAlike 4.0 International License"
(http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

1.5
- Added Spanish translation (thanks ElGamerViejuno)
- Fixed typo in Brazilian Portuguese translation

1.4
- Added Brazilian Portuguese translation (thanks Felipe)
- Added component labels for Project Infinity
- Improved detection and handling of invalid DLC archives

1.3
- Added German translation
- Added Project Infinity metadata
- Added WeiDU SUPPORT information
- Fixed potential display issues with component names in WeiDU.log and Project Infinity
- Improved description of components (thanks ALIEN)

1.2
- Removed information regarding EET and Fixpack from readme because it's not needed anymore

1.1
- Added information regarding EET and Fixpack to readme

1.0
- Initial release
