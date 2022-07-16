BGEE Leveled Spawns Mod
by AstroBryGuy (http://forum.baldursgate.com/profile/14405/AstroBryGuy)
Version 0.6

BGEE Leveled Spawns replaces the default spawns with spawns that scale in difficulty with the average level of the party or with the game difficulty setting.  Each spawn point will spawn groups of 1-8 creatures, depending on party level andcreature strength or game difficulty setting.

The user can select the time interval between spawnings as well as the probability that a triggering of a spawn point will result in that point being populated.  

The first setting is based on the "Tutu-style leveled spawns" component of the BGT Tweaks mod (http://readme.spellholdstudios.net/BGTTweakReadme.htm).  However, the spawn point scripts have been greatly simplified.  First, party-size checks have been removed.  Level checks above 12th level have also been removed.

The second setting is basically a copy of the spawn system from the easytutu mod for BG1. It's entirely based on difficulty leveled and has a set amount of enemies per level per spawn. Everything else about this setting is the same as the first, only the trigger for and amount of enemies per spawn have changed.

Additional inspiration has come from the Tutu spawn system by CamDawg and the EasyTutu Spawn Randomizer by Maccready.


OPTIONS

1. Time Between Spawn Point Resets: After a spawn point has triggered, it will not spawn again until a certain time interval has passed.  The duration of this time interval is user-selectable with the following options:

[1] 4 HOURS of game time between spawnings
[2] 8 HOURS of game time between spawnings
[3] 16 HOURS of game time between spawnings
[4] 1 day of game time between spawnings
[5] 2 days of game time between spawnings
[6] 4 days of game time between spawnings
[7] 7 days of game time between spawnings
[8] 10 days of game time between spawnings
[9] 14 days of game time between spawnings
[0] 1000 days of game time between spawnings

Notes: 
* A spawn point will not reset if the PCs are within a certain range of the spawn point.  This is to prevent spawns from suddenly appearing within the visual range of the PCs.
* A spawn point will also not reset until it is "clear" (i.e., there are none of the spawned creatures within range of the spawn point).  This is to prevent overly large groups of spawns from accumulating, especially those that are not automatically hostile (e.g., bears).
* Game default behavior is to require at least 16 hours to pass before a spawn point is reset.  Option 3 should match that timing most closely.
* 1000 days effectively ensures that each spawn point will trigger at most once during the game.

2. Spawning Probability: When a spawn point triggers, this probability controls whether or not the spawn point is populated.  If the spawn is not populated, it will not trigger again until the spawn point reset time interval has passed.  The user has the following spawning probability options:

[1] 10% chance of spawning
[2] 20% chance of spawning
[3] 35% chance of spawning
[4] 50% chance of spawning
[5] 65% chance of spawning
[6] 75% chance of spawning
[7] 85% chance of spawning
[8] 90% chance of spawning
[9] 95% chance of spawning
[0] 100% chance of spawning

Notes: 
* If you set a low spawn % and a long time between spawns, you will see very few spawns.
* Game default spawn percentages are 85% in most areas, with 100% in certain areas like Firewine Ruins.

3. Spawn system selection

[1] Spawns are based on average party level
[2] Spawns are base on game difficulty setting (easytutu style)
INSTALLATION

Windows
On successful extraction, there should be an bgeespawn folder and a setup-bgeespawn.exe file in your game folder. To install, simply double-click setup-bgeespawn.exe and follow the instructions on screen.
Run setup-bgeespawn.exe in your game folder to reinstall, uninstall or otherwise change components.

Mac OS X
If properly extracted, you should have a bgeespawn folder, setup-bgeespawn, and setup-bgeespawn.command in your game's main directory folder. To install, simply double-click setup-bgeespawn.command and follow the instructions on screen.

Linux
Download the latest version of WeiDU for Linux from WeiDU.org and copy weidu, weinstall, and tolower to /usr/bin. Then, open a terminal, cd to your BGEE installation directory, run 'tolower' and answer Y to both queries. Run 'weinstall setup-bgeespawn' in your game folder to install the mod.

If you have installation problems or encounter any bugs, please contact me at the BGEE Forums (http://forum.baldursgate.com/).


COMPATIBILITY

BGEE Leveled Spawns	Mod is coded using WeiDU and does not overwrite any files. It should be compatible with most other (WeiDU) mods. 

The mod is compatible ONLY with BGEE and EET.

+++++++++++++++Please do not translate below here ++++++++++++++++++++++++


ACKNOWLEDGEMENTS

Based on the "Tutu-style leveled spawns" component of the BGT Tweaks mod by Ascension64.

http://readme.spellholdstudios.net/BGTTweakReadme.htm

Additional inspiration drawn from the Tutu spawning system by CamDawg and the EasyTutu Spawn Randomizer by Maccready.

http://www.usoutpost31.com/easytutu/


-translations-

N/A



TOOLS USED

The BGEE Leveled Spawns Mod was created using the resources provided by the IESDP (http://iesdp.gibberlings3.net/) and with the following software:

Near Infinity			https://github.com/Argent77/NearInfinity
WeiDU					http://www.weidu.org
TextWrangler			http://www.barebones.com/products/textwrangler/
sed, awk, bash			https://www.gnu.org/software/


LEGAL INFORMATION

=============================================================================
This mod is not developed, supported, or endorsed by BioWare, Black Isle Studios, Interplay Entertainment Corp., the Wizards of the Coast, Overhaul Games or Beamdog. All other trademarks and copyrights are property of their respective owners.
=============================================================================



HISTORY

Version 0.4: Added native Baldur's Gate: Enhanced Edition Trilogy (EET) support

Version 0.3: Added notes regarding game defaults, update spawn trigger reset timings to include selection equivalent to game default, updating spawning probability values to give more options at high probabilities
Version 0.2: Install bug fixes, update spawn trigger reset timings.
Version 0.1: Initial public release
