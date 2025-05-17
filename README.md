16/05/2025 - First Release

Hello, Just wanted to let you know which versions of things I used to get here I what I can remember editing (It was a lot of trial and error and I have ADHD so I probably forgot stuff)

I didn't do this with the expectation of sharing it so there may be things leftover from me just playing the game.

Hopefully this way if something breaks you have at least some idea where to look!
LOBOTs is disabled by default I think to remember to activate it in the option menu.

I've also have a version of Arulco Folding Stock that can be found here https://github.com/Megamimed/Arulco-Folding-Stock-MM and is compatable with the latest (16/05/2025) experimental. Not tested it as much though.


Installation
--------------------------------------------------------------------------
Like 1.13, requires a legal Copy of JA2.

The 1.13 mod itself, found Here https://github.com/1dot13/source/releases/tag/latest

You will also need a copy of the Data file from the orginal Urban Chaos, renamed to Data-UC (DON'T OVERWRITE The Existing Data Files)

Once you have those installed, unzip my version of UC113 into your Jagged Alliance 2 Folder

Launch the INI editor and set your mod to vfs_config.UC113.ini and use the JA2.exe from the 1.13 mod

That SHOULD be it.

NOTE RE Data-Graphics:
If you have a Data-graphics folder from AFS or something then either update the bigitems, interface and tilesets found there with my versions (May break AFS/DL, not tested it) or move the old versions into their own mod folders and then remove the three files from the Data-Graphics folder entirely.


Versions and stuff - Going by the ZIP file names in my downloads folder:
--------------------------------------------------------------------------

1.13 Version used - tested on JA2_113-v2-G3519Ld827-English (V2) and JA2_113-v2-15-g11caa65-Ga9baLd827-English (Experimental)

UC-1.13 Version - Urban Chaos-1.13 Full Experimental 12 v4.6x 20190510

UC - Urban_Chaos (the original installer, not very descriptive I know)


Changes made to STI (haha) Files:
--------------------------------------------------------------------------

I tore BIGITEMS, INTERFACE and TILESETS out of Data-Graphics which came with UC113 and moved them into the UC113 folder itself. this was done at some point during my trail and error for reasons I can't fathom.

I copied P1item909 through to P1item921 from 1.13 bigitems and pasted it in UC113's bigitems folder
I REPLACED SMP1Items, SMP2Items and SMP3Items in UC113's Tilesets 0 with the ones in 1.13's Tilesets 0 Folder

This was also done with MDP1 2 and 3 in the interface Folder

whether this screws anything up remains to be seen (BY YOU!)


TABLEDATA:
--------------------------------------------------------------------------
LOBOTs - or LogicalBodyTypes:

They work! There is a filter added to UC113, this was a pain in the ass to put together and I haven't really checked it beyond seeing whether Camo, Vanilla Armour, and A weapon shows (Note not whether the specific weapon is correct just that the aren't using invisible weapons)

ITEMS:

I added the Berets, a couple hats, Urban, desert and Woodland Trousers and a version of the woodland BDU that fits in the armour slot (since UC made it a Vest). this means there are two versions of the woodland BDU and no I'm not messing around with that, they both work and I named them different.

ARMOURs:
Appended new entries from 1.13 because the game kept crashing when I opened a bobby rays box and I thought this might fix it (it stopped crashing after I did this so maybe?)


SETTINGS:
--------------------------------------------------------------------------
JA2_Options
I gave the Ja2_Options in UC113 a once over (mostly commented these) to include entries it was missing from the 1.13 version I used. I also modified some settings according to my own prefereces, notably Imp initial points which I changed from 500 to 700 because I'm not very good at this game. So you may want to make your own adjustments (which I don't need to tell you, I think everyone does this anyway)

SKILLS and TAUNTS:

So these two kept throwing up errors because they were being read from the orinal UC folder, it annoyed me enough that I went in and copied the Skills_Settings and Taunts_Settings from UC to UC113 and added the missing entries

APBPConstants:
Changed from 20AP to 100AP as a personal preference.

Please also note, I may have also changed the CTHConstants to suit my preference but I can't for the life of me remember that was for UC113 or another mod I was playing so if stuff feels off that may be why.

I think that's everything. If you notice something egregious that I've missed please let me know on the Bearpit Discord, Username is Megamimed

If you make any changes to fix this in the future I strongly suggest you add your own timestamped notes to this changelog so that future generations don't have to put up with the headache I had to endure, also so that I don't get blamed if YOUR update breaks something.
