BGEE Leveled Spawns Mod
by AstroBryGuy (http://forum.baldursgate.com/profile/14405/AstroBryGuy)
Version 0.1

BGEE Leveled Spawns replaces the default spawns with spawns that scale in difficulty with the average level of the party.  Each spawn point will spawn groups of 1-6 creatures, depending on party level and creature strength.

The user can select the time interval between spawnings as well as the probability that a triggering of a spawn point will result in that point being populated.  

This mod is based on the "Tutu-style leveled spawns" component of the BGT Tweaks mod (http://readme.spellholdstudios.net/BGTTweakReadme.htm).  However, the spawn point scripts have been greatly simplified.  First, party-size checks have been removed.  Level checks above 12th level have also been removed.

Additional inspiration has come from the Tutu spawn system by CamDawg and the EasyTutu Spawn Randomizer by Maccready.


OPTIONS

1. Time Between Spawn Point Resets: After a spawn point has triggered, it will not spawn again until a certain time interval has passed.  The duration of this time interval is user-selectable with the following options:

[0] 8 hours of game time between spawnings
[1] 1 day of game time between spawnings
[2] 2 days of game time between spawnings
[3] 3 days of game time between spawnings
[4] 5 days of game time between spawnings
[5] 7 days of game time between spawnings
[6] 10 days of game time between spawnings
[7] 14 days of game time between spawnings
[8] 30 days of game time between spawnings
[9] 1000 days of game time between spawnings

Note: A spawn point will not reset if the PCs are within a certain range of the spawn point.  This is to prevent spawns from suddenly appearing within the visual range of the PCs.  A spawn point will also not reset until it is "clear" (i.e., there are none of the spawned creatures within range of the spawn point). 

2. Spawning Probability: When a spawn point triggers, this probability controls whether or not the spawn point is populated.  If the spawn is not populated, it will not trigger again until the spawn point reset time interval has passed.  The user has the following spawning probability options:

[1] 10% chance of spawning
[2] 20% chance of spawning
[3] 30% chance of spawning
[4] 40% chance of spawning
[5] 50% chance of spawning
[6] 60% chance of spawning
[7] 70% chance of spawning
[8] 80% chance of spawning
[9] 90% chance of spawning
[0] 100% chance of spawning

Note that the combination of 1000 days between spawns and 100% spawning probability would populate every spawn point once.

INSTALLATION

Windows
On successful extraction, there should be an bgeespawn folder and a setup-bgeespawn.exe file in your game folder. To install, simply double-click setup-bgeespawn.exe and follow the instructions on screen.
Run setup-bgeespawn.exe in your game folder to reinstall, uninstall or otherwise change components.

Mac OS X
If properly extracted, you should have a bgeespawn folder, setup-bgeespawn, and setup-bgeespawn.command in your game's main directory folder. To install, simply double-click setup-bgeespawn.command and follow the instructions on screen.

Linux
Make sure you have the Linux version of the mod (named "lin-bgqe-vx.zip").
Download the latest version of WeiDU for Linux from WeiDU.org and copy WeiDU and WeInstall to /usr/bin. Following that, open a terminal, cd to your BG installation directory, run 'tolower' and answer Y to both queries. You can avoid running the second option (linux.ini) if you have already ran it once in the same directory. To save time, the archive is already tolowered, so there is no need to run the first option (lowercasing file names) either if you have extracted only this mod since the last time you lower cased file name. If you are unsure, running tolower and choosing both options is the safe bet.
Run WeInstall setup-bgeespawn in your game folder to install the mod.

If you have installation problems or encounter any bugs, please contact me at the BGEE Forums (http://forum.baldursgate.com/).


COMPATIBILITY

BGEE Leveled Spawns	Mod is coded using WeiDU and does not overwrite any files. It should be compatible with most other (WeiDU) mods. 

The mod is compatible ONLY with BGEE.

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

Version 0.x: Initial public release
