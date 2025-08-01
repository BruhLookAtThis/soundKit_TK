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

For soundMod_TK v2.0.0
- Added Fahkumram to the Codenames list
- Added latest TXTPs

- REMINDER: Written instructions are NOT yet updated. Will update when I...well, when I feel like it tbh

-----------------------------------------------------
-----------------------------------------------------
