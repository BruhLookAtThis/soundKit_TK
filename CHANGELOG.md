-----------------------------------------------------
-----------------------------------------------------
UPDATE 1 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

- Initial Release

-----------------------------------------------------
-----------------------------------------------------

UPDATE 1.0.1 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For soundMod
- Added Anna (KGR) to codenames list
- Added Season 2 TXTP files

-----------------------------------------------------
-----------------------------------------------------

Update 1.0.2 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For soundFinder
-Updated script to no longer give errors when processing

-----------------------------------------------------
-----------------------------------------------------

Update 1.0.2b (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For soundMod
-Updated Codenames txt

-----------------------------------------------------
-----------------------------------------------------

Update 1.0.3 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For soundMod
-Updated Script to automatically append "_9999999_P" to the end of custom mods folder names
(This is to override update .paks, which could prevent your audio mods from playing ingame)
-Updated script to be able to process subfolders and loose wems in the 4-Put-Custom-Wems-Here folder simultaneously.
(Missed this in the initial releases)

-----------------------------------------------------
-----------------------------------------------------

UPDATE 1.1.0 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For soundMod
- Integrated soundFinders abilities into soundMods script (Options 3, 4).
- Added new folder to soundMods directory that specifically says IGNORE it. So DONT DELETE IT. 
- Added "Info" selections to explain how each Option of the script works
 (These descriptions are not particularly fleshed out currently, Ill get around to making them more detailed later)
- Written Instructions in the .txt are NOT updated. Will get to this later.

General
- Removed soundFinder
- Removed "NOTES.txt" out of the OLD TOOLS folder, added its contents to the zz_READ_THIS_FIRST.txt file.
- Added instructions for creating your own TXTP files in the zz_READ_THIS_FIRST.txt file.

-----------------------------------------------------
-----------------------------------------------------

UPDATE 1.1.1 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For General
- Will now be adding tool version # to subheader
- Removed Txtp-Searcher_v1, as this is now integrated into soundMod_TK
- Updated TXTP Creation instructions to recommend AGAINST checking the Generate Duplicates option

For soundMod_TK 1.1.1
- Changed "z1_RunMeInPowershell_SoundMod.ps1" to "z1_RunMeInPowershell_SoundMod_TK.ps1"
- Changed "z2_DoubleClickMe_SoundMod.bat" to "z2_DoubleClickMe_SoundMod_TK.bat"
- Changed "x1-(OPTIONAL)-Put-Wems-To-TEST-Here" to "x1-Put-Wems-To-TEST-Here-(OPTIONAL)"
- Changed "x3-(OPTIONAL)-Put-Wems-To-SILENCE-Here" to "x3-Put-Wems-To-SILENCE-Here-(OPTIONAL)"
- Changed "z0-(IGNORE-THIS)-TESTs-Folder" to "0-Ignore-This-Folder-(TESTs)"
- Merged "5-Wems-With-No-Txtp-Match-Copied-Here" & "6-Skipped-Txtps-Are-Copied-Here" into "5-Wems-And-Txtps-With-Issues-Are-Copied-Here"
- Wems that were generated in "5-Wems-With-No-Txtp-Match-Copied-Here" are now placed in "5-Wems-And-Txtps-With-Issues-Are-Copied-Here\Wems-With-No-Txtp-Match"
- Subfolders that were generated in "6-Skipped-Txtps-Are-Copied-Here" are now placed "5-Wems-And-Txtps-With-Issues-Are-Copied-Here"
- (When executing Option 1) Txtp files that share a wem ID(s) are now placed into "5-Wems-And-Txtps-With-Issues-Are-Copied-Here\Txtps-Skipped-Due-To-Duplicate-Wem-ID(s)"
- (When executing Option 1) Txtp files that share a wem ID(s) are also now listed in "5-Wems-And-Txtps-With-Issues-Are-Copied-Here\List-Of-Txtps-That-Share-A-Wem-ID.json"
  Inside this .json are lines displaying which TXTP was used for the renaming for that share wem ID, and which one(s) were Skipped
- Added (DEVELOPER) Option 100: This Option lets you search a wem ID, and will scan all TXTPs for any that contain that wem ID
- Any matching TXTP files will be placed into "6-TXTPs-With-Matching-WEM-IDs-Are-Here-(DEV)"
  (If you have already executed Option 1, you can also just search that wem ID number in the List-Of-Txtps-That-Share-A-Wem-ID.json file)
- Replaced TXTP batch with a smaller version. My testing shows this had no detrimental effect to modding
- That being said, I kept the old, larger TXTP batch in the '.OLD-FULL-TXTP-FILES' folder inside of '.OLD-TOOLS-ONLY-USE-IF-NECESSARY'
  Use that batch IF you run into issues with the new, smaller batch
  (Also please notify me on Discord what file you ran into an issue with)
  (Additionally, let me know if even the large batch did not help you)
  (So far, we know Clive x Reina interations, OKM & ZBR, simply dont exist within the game files in a manner that lets me edit them with this tool)
- Added Play_SE_Glocky_Start:  SOUND - Combat to the Codenames.txt
  (Play_SE_Glocky_Start.txtp contains the same wem ID as Play_SE_Heat_Burst_Start_EFX.txtp does, along with a couple more)
  
-----------------------------------------------------
-----------------------------------------------------

UPDATE 1.2.0 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For General
- Changed CHANGELOG file format from txt to json just because I can
- Added latest Tekken .usmap file in 0_Extras

For soundMod_TK v1.2.0
- Added ability for script to rename BGM wem files found in 3-Renamed-Media-Wems-Will-Be-Here to their DebugName counterparts

i.e. '661589587' is first renamed to 'Play_BGM_Container (1964107455=54782393)(1608193273=normal)_Wem2.txtp' which is itself then renamed to 'T4_13_Touch_and_Go_lp.wem'

- Added ability for script to rename these new DebugName wems back to their ID name for placement in the appropriate, pak-ready folder structure
- Added a Play_BGM_Container.json file (extracted right out of FModel btw, in case you need to update it yourself for new songs) inside of 1_Extras
  This is crucial for the new BGM renaming function to work so dont remove it from 1_Extras
- Moved 0-Ignore-This-Folder-(TESTs) inside of 1_Extras
  (Adjusted script to factor in this move)

- REMINDER: Written instructions are NOT yet updated. Will update when I...well, when I feel like it tbh
    
-----------------------------------------------------
-----------------------------------------------------

UPDATE 1.2.1 (NOT AVAILABLE. LOGGING FOR LEGACY REASONS)

For soundMod_TK v1.2.1
- Increased the speed for processing multiple folders during Option 2

- REMINDER: Written instructions are NOT yet updated. Will update when I...well, when I feel like it tbh
     
-----------------------------------------------------
-----------------------------------------------------

UPDATE 1.2.2

Initial Github release

For soundMod_TK v1.2.2
- Added Fahkumram to the Codenames list
- Added latest TXTPs

- REMINDER: Written instructions are NOT yet updated. Will update when I...well, when I feel like it tbh
       
-----------------------------------------------------
-----------------------------------------------------

UPDATE 2.0.0 (NOT RELEASED YET)

For General
- Removed '.OLD-TOOLS-ONLY-USE-IF-NECESSARY' folder, no longer necessary
- Changed '0_Extras' to '3_XTRA'
- Renamed 'soundMod_TK_v1.2.2' to 'SMT_TK'. This folder will no longer have its own version
- Chnaged 'zzz_CHANGELOG.json' to 'CHANGELOG.md'
- Changed 'zz_READ_THIS_FIRST.txt' to 'README.md'

For SMT
- Overhauled UI (Is now consistent with my other tools, soundKit_MR and soundKit_SB)
- Changed '1_Extras' to '0_XTRA'
- Changed '1-Put-Media-Wems-Here' to '0-MEDIA', moved it inside of '0_XTRA'
- Changed '2-Put-TXTP-Files-Here' to '0-JSONS', moved it inside of '0_XTRA'
- Adjusted script to accomodate subfoldered files in '0-JSONS' and '0-MEDIA'

- Changed all functions to work with extracted .json files instead of generated .txtp files
  1. This makes it simpler to extract the information needed to rename .wem files,
     as these .jsons can be obtained directly from FModel itself
  2. Simply go to 'Polaris/Content/WwiseAudio/Event' in FModel
  3. Then extract the entire 'Event' folder as .jsons
  4. Place these .json files into the '0-JSONs' folder

- Adjusted Option 1 to generate a 'WEM-ID-CHART.txt' file in the '0-TOOLS' folder
  This file contains all renamed wem IDs matched up to their original numerical wem IDs
  Useless for...something lol. Tired af writing this
  Oh, Option 102 can reference this to find...stuff (again, tired af)
- Improved processing capability of Option 2 (Creating A Mod Folder)
  1. In older versions of the script, some .wem files would not be properly processed
  2. These cases have been fixed, though more may reveal themselves later
  3. They will also be patched when it is brought to my attention
- Adjusted Option 2 to output into '3-Your-MOD-FOLDERS-Are-Here'
  1. If Option 2 is executed consecutive times with no change to folder structure in '2-Put-CUSTOM-WEMs-Here',
     then subsequent 'z_(Name)_9999999_P' outputs folders will be renamed incrementally
  i.e: 'z_(Name)_9999999_P', 'z_(Name)_1_9999999_P', 'z_(Name)_2_9999999_P', etc.
- Adjusted Option 2 to move error wem files to the error folder(s) instead of merely copying them
- Adjusted Option 2 to be able to process wem files that are already renamed to the numerical ID

- Changed '4-Put-Custom-Wems-Here' to '2-Put-CUSTOM-WEMs-Here'
- Created 'x100-XTRAs-Are-Here' folder
  Inside of there, created 'x103-TEST-Wem-Stuff' and 'x104-SILENT-Wem-Stuff'
  
- Changed 'x1-Put-Wems-To-TEST-Here-(OPTIONAL)' to 'A-Put-Wems-To-TEST-Here'
- Changed 'x2-Your-New-TEST-Wems-Are-Here' to 'B-Your-New-TEST-Wems-Are-Here'
  Moved both of these inside of 'x103-TEST-Wem-Stuff'
- Changed 'Option 3' to 'Option 103'
- Changed Option 103 to accomodate the new folder paths

- Changed 'Option 100' to 'Option 102'
- Changed '4-TXTPs-With-Matching-WEM-IDs-Are-Here-(DEV)' to 'x102-SEARCHED-Wem-Stuff'
  Moved this inside of 'x100-XTRAs-Are-Here'
- Moved 'Play_BGM_Container.json' to '0-TOOLS'  
- Changed Option 102 to accomodate the new folder path
- Added 'Play_BGM_Container.json' support
  1. Now, wem IDs that are found in this file (likely for music) can be searched
  2. A 'Play_BGM_Container-######.json' file will be output into 'x102-SEARCHED-Wem-Stuff'
  3. It will contain the .wem ID as well as the interal music track name (and other, currently irrelevant data)
- Added support to search renamed wem file names
  Not sure what this will be useful for, but I added it anyway lol
  You can search the names and get a json with the correspodning wem ID in its name
 
- Changed how Option 103 functions
  1. Previously, test file creation was limited to the amount of test wems available in the Tests folder
  2. Now, the script will reuse Test wems if there are more source wems than test wems
  3. "_test#" was changed to "-test#"
 
- Changed 'x3-Put-Wems-To-SILENCE-Here-(OPTIONAL)' to 'A-Put-Wems-To-SILENCE-Here'
- Changed 'x4-Your-Newly-SILENCED-Wems-Are-Here' to 'B-Your-New-TEST-Wems-Are-Here'
  Moved both of these inside of 'x104-SILENT-Wem-Stuff'
- Changed 'Option 4' to 'Option 104'
- Changed Option 104 to accomodate the new folder paths

- Changed '3-Wems-And-Txtps-With-Issues-Are-Copied-Here' to 'x200-ERROR-FILEs-Are-Here'
- Changed 'Txtps-Skipped-Due-To-Duplicate-Wem-ID(s)' to 'x202-JSONs-With-DUPE-WEM-IDs-Here'
  A '.List-Of-JSONs-That-Share-A-Wem-ID.json' file will be generated here
  This file will show exactly which jsons shared wem IDs, and which jsons were USED or SKIPPED during Option 1
- Changed 'Txtps-With-No-WEM-References' to 'x203-JSONs-With-NO-WEM-REFERENCE'
- Changed 'Wems-With-No-Txtp-Match' to 'x204a-BASE-Wems-With-NO-JSON-MATCH-Here' and 'x204b-CUSTOM-Wems-With-NO-JSON-MATCH-Here'
  No JSON Match Wems found during Option 1 processing will go into the 'x204a' folder
  No JSON Match Wems found during Option 2 processing will go into the 'x204b' folder
- Changed 'Txtps-Skipped-Due-To-Other-Errors' to 'x205-JSONs-With-OTHER-ERROR-Here'

- Added '0-Put-CUSTOM-WAVS-Here' folder
- Added Option 0
  1. This option allows users to convert wav files to wem files
  2. Simply place the wav files into '0-Put-CUSTOM-WAVS-Here' then choose option 0 of the script
  3. Wem files will be output into '2-Put-CUSTOM-WEMs-Here'

-----------------------------------------------------
-----------------------------------------------------
