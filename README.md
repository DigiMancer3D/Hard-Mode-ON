# Hard Mode (ON)
Finding a way to make a progressively harder Project Zomboid Sandbox game for a "Faux Playstyle" until the team behind PZ sets HMO or "Hard Mode (ON)" as a Playstyle in PZ.

### Note:
At this point you could attempt to find the LUA timer event code to then use different code points or use a script to swap files at certian timer points but to be honest, the timer point for the first swap after the inital loading swap for <b><i>week2</i></b> is at approx 21 hours (IRL time) of gameplay. So, the majority of everyone will probably be swapping out the game settings file (<i>map_sand.bin</i>) for which ever week they are about to load into or while they are in-game. 

</br></br>
## What is Hard Mode (ON)?
<b><i>Hard Mode (ON)</i></b> is a difficultly set sandbox game that is designed to be a "Faux Playstyle" or <i>mock playstlye</i>. Where other playstyles are about a form of challenge or systematic difficulty, so <b>HMO</b> is a challenge of an overall time survived (represented as in-game reward tokens) & less by the number of zombies killed. Altough both should have a factor like tokens divided by zombie kills or just look at both metrics independently but in correlation with other. 

For each week in HMO the settings are changed. From day time to zombie population to special events & even load outs per profession (extra iteams given to player upon loading a new character). This faux playstyle is setup to be used with a specific set of mods but some of the mods used are simply for cosmetic changes to give this version a slightly different feel to the vanilla playstyles. 

</br></br>
#### 2 Ways to Play HMO
Hard Mode (ON) has essentially 2 ways to make this happen. 
<ol><li>You can load your own game with your mods, use the presets or select the settings in the sandbox options while allowing you to modify any setting easily. This can include the individual week map settings files or just the main hosting game save.</li>
<li>You can use the provided files in this repo to quickly load up and switch to the different weeks.</li></ol>
</br></br>
When you download this repo you should obtain the files which are as follows:
<ol><li>HMO [zipped folder containing starting game save]</li><li>HMO (weeks) [folder containing week-by-week map settings files]</li><li>Special Data for HMO (Self-Save) [folder containing data for setting up your own map settings files & inital game save]</li><li>modmanager-mods.txt [mods list for mods manager]</li></ol>
</br></br>
If you are wanting to use the provided data, you will drop "HMO" the folder into your Zomboid game saves folder. Then the map settings files for each week to drop in while playing is in the "HMO (weeks)" folder (with a folder for each week inside that).
</br></br>BUT</br></br>
If you are wanting to make all the game files and map settings, you'll need to use the "Special Data for HMO (Self-Save)" folder.
</br></br>HOWEVER</br></br>
If you use Mod Manager, you will need to drop the modmanager-mods.txt file into Zomboid Lua folder but if you do use mod manager, make a copy of your original modsmanager-mods.txt file and place somewhere else as a backup because this will overwrite any presave you may have setup already with mod manager. You can open up the text file and add it into your current version one but you may need to update the header number to match the new listed number in your modsmanager-mods.txt file.

</br></br></br>
To help showcase the increasing difficulty in just being able to complete a single in-game week with Hard Mode (ON). The following list is the length to complete a week in REAL LIFE TIME (IRL hours per game-day):
<li>Early Weeks:<ol>Weeks 1-3: 21 hours (3hr days)</ol>
<ol>Weeks 4-6: 28 hours (4hr days)</ol></li></br>
<li>Mid Weeks:<ol>Weeks 7-9: 35 hours (5hr days)</ol></li></br>
<li>Late Weeks:<ol>Week 10: 42 hours (6hr days)</ol>
<ol>Week 11: 49 hours (7hr days)</ol></li></br>
<li>Final Weeks:<ol>Weeks 12+: 63 hours (9hr days)</ol></li>
</br></br></br>

### Tokens VS Zombie Count
In HMO, token counts are 1 of 2 metrics used to determine better players. The tokens should only be paid out when someone survives for a specified length of time but may payout after a specified number of minutes while playing. Either way, it does limit the total possible number of tokens available from week to week which can help spot bad or untrustworthy players. By having the token payout being related to time played the players surviving while killing zombies essentially doubling the total points possible. Consider Zombie Count + Tokens the way to find a total for comparing or doing a leaderboard but you could use Tokens Divided-By Zombie-Kills for a more percentile approach to the leaderboard. Next is a list of the max number of tokens awardable per player per week.

</br>
<ol><ol>Week 1: 21</ol><ol>Week 2: 21</ol><ol>Week 3: 21</ol><ol>Week 4: 28</ol><ol>Week 5: 28</ol><ol>Week 6: 28</ol><ol>Week 7: 35</ol><ol>Week 8: 35</ol><ol>Week 9: 35</ol><ol>Week 10: 84</ol><ol>Week 11: 98</ol><ol>Weeks 12+: 1134</ol></ol>



</br></br></br>
The current list of Non-Cosmetic Mods for HMO (as named by internal files) & why that mode was used are as follows:
<ol><li>15xp - To add a flat rate to Workout Experience (comes in handy Weeks 10+)</li>
<li>UBPropFix - Fixes Known Bugs & Issues with some Mods</li>
<li>25WRFIX - Allows for better wood carry but mostly a quality of life upgrade</li>
<li>AutoReload - Needed in Late & Final Weeks</li>
<li>AutomaticGateMotors - Adds Automated Services for Unit Protection (so to speak)</li>
<li>autotsartrailers - More Container Type Materials</li>
<li>tsarslib - Car & Trailer Library</li>
<li>AxeOverhaul - Allows for more useful axe use</li>
<li>BecomeBrave - Allows for extras after high kills</li>
<li>Better Belts - Attempts to get better use out of belts</li>
<li>FasterTraining - Mostly Quality of Life Upgrade</li>
<li>BetterFlashlightsFixed - Mostly Quality of Life Upgrade</li>
<li>BetterSortCC42 - Mostly Quality of Life Upgrade</li>
<li>BrutalHandwork - Helpful Malee Combat</li>
<li>FancyHandwork - Additional Combat Options</li>
<li>isoContainers - More Loot Spots</li>
<li>BB_DaysGone_Counter - Lore Related Add-On</li>
<li>IMWSEnergyDrinks - Lore Related Add-On</li>
<li>EngineKeeper - Needed in late & final weeks</li>
<li>ExerciseWithGear - Quality of Life Upgrade</li>
<li>ExerciseWithCorpses - Quality of Life Upgrade</li>
<li>FWOBenchPress&Treadmill - Quality of Life Upgrade</li>
<li>FitnessGains - Quality of Life Upgrade</li>
<li>FixedLongLifeBulbs - Used to manipulate players by allows infinate lights until the late & final weeks</li>
<li>improvedbuildmenu41 - Quality of Life Upgrade</li>
<li>ItemTweakerAPI - Quality of Life Upgrade</li>
<li>jumpThroughWindows - Needed in late & final weeks</li>
<li>Ladders - Quality of Life Upgrade & Allows for a specific game style (world-war-z kill-mode)</li>
<li>ModManager - Easier Access to Mod List for Selecting</li>
<li>MoreBuilds - Quality of Life Upgrade</li>
<li>MoreBuildAppliances - Quality of Life Upgrade</li>
<li>LabItemsZFS - Quality of Life Upgrade</li>
<li>MPOZ - Quality of Life Upgrade</li>
<li>MoreSmokes - Creator's Personal Choice</li>
<li>MoreSmokesEasyPacking - Creator's Personal Choice</li>
<li>nattachments - Quality of Life Upgrade</li>
<li>ReadFasterWhenSitting - Quality of Life Upgrade</li>
<li>ReloadAllMagazines - Quality of Life Upgrade</li>
<li>ServerPoints - Used for considering sucessful survival sections per week</li>
<li>tailoringfix41 - Quality of Life Upgrade</li>
<li>KI5trailers - Quality of Life Upgrade</li>
<li>GetUpQuick - Quality of Life Upgrade</li>
<li>P4HasBeenRead - Quality of Life Upgrade</li>
<li>BB_CommonSense - Quality of Life Upgrade</li>
<li>ssr-core - Helps some Mods work better/correctly</li>
<li>MoodleFramework - Helps some Mods work better/correctly</li>
<li>DropRollMod - Quality of Life Upgrade</li>
<li>TsarcraftCache2 - Helps some Mods work better/correctly</li>
<li>VehicleRepairOverhaul - Quality of Life Upgrade</li>
<li>VanillaOpenAmmoWalk - Quality of Life Upgrade</li>
<li>[COS] Clipping animation Fix - Seems to Help with some Mods</li>
<li>custItemsforProf - Special Loadouts</li>
<li>diveThroughWindows - Extra Attempt to get Dive-through-windows to work</li>
<li>Buttstroke - Extra Attacks</li>
<li>RepairAnyMod - Quality of Life Upgrade</li>
<li>RepairAnyClothes - Quality of Life Upgrade</li>
<li>VanillaMuzzleflashEnhanced - Needed in Final Weeks (12+)</li></ol>
</br></br></br>

 The current list of Cosmetic Mods for HMO (as named by internal files) are as follows:
 <ol><li>4ColorBicPen</li><li>blkt_invtrack</li><li>Authentic Z - Current</li><li>ATA_Mustang</li><li>ATA_Jeep</li><li>ATA_Luton</li><li>ATA_Petyarbuilt</li><li>VISIBLE_BACKPACK_BACKGROUND</li><li>Brita_2</li><li>BCGRareWeapons</li><li>BCGTools</li><li>modurl=https://steamcommunity.com/sharedfiles/filedetails/?2565273421</li><li>CleanDirt</li><li>CloseVehicleDoor</li><li>damnlib</li><li>FixCraftingContextMenuStutter</li><li>DIY_Vehicle_Parts_Ford_F350UK</li><li>DIY_Vehicle_Parts_ATA_MustardUK</li><li>DIY_Vehicle_Parts_Halo_M12_WarthogUK</li><li>DIY_Vehicle_Parts_Base_Vanilla_CraftingUK</li><li>DylansTiles_Elysium</li><li>DylansTiles</li><li>EasyEngineRebuild</li><li>EasyPacking</li><li>FixTooltipLag</li><li>fuelsideindicator</li><li>GeneratorTimeRemaining</li><li>GlassHats</li><li>NoLighterNeeded</li><li>IMightNeedALighter</li><li>Improved_Blood_Ffects_Optimized</li><li>Improved_Blood_Ffects</li><li>Improved_wearbable_cigarettes</li><li>invisibledenimpatches</li><li>invisibleleatherpatches</li><li>invisiblesheetpatches</li><li>qdx_item_condition</li><li>KillCount</li><li>ModGlassHats</li><li>modoptions</li><li>noirrsling</li><li>RainCleans</li><li>BloodRainWash</li><li>ReduceLagofCraftingMenu</li><li>sleeponit</li><li>SID3404</li><li>TMC_TrueActions</li><li>fhqExpVehSpawn</li><li>fhqExpVehSpawnNoVanilla</li><li>Wearable_Cigarette</li><li>WorkingMasks</li><li>FC4WT</li><li>[ADDON]TMC_TrueActions</li><li>tkTiles_01</li><li>BigZombieMonkeys_tile_pack</li><li>MezzHairColors</li><li>esIC</li><li>FantaStreetTiles_01</li><li>axolotl</li><li>RotatorsLib</li><li>truemusic</li><li>Threads</li><li>ATA_Dadge</li><li>ATA_Mustang_x2</li><li>ATA_Jeep_x2</li><li>QNW_QNWLibrary</li><li>wringclothesnostr</li><li>fshk_ghostmask</li><li>animeshader</li><li>SchoolbagBundleAlice</li><li>DONDAVest</li><li>SpnHair</li><li>FH</li><li>MilPackChestRigWebbingBlack</li><li>Gasmaskwithbalaclava</li><li>AnimeTV</li><li>BlackSatchels</li><li>TombBodyTex</li><li>TombBody</li><li>81deloreanDMC12BTTF</li><li>81deloreanDMC12</li><li>Video_Game_Consoles</li><li>TombBodyTexDOLL</li></ol>
</br></br></br>

There is a file named, "modmanager-mods.txt", that may help you auto select these mods if you: (A) have these mods installed (check Steam List [steam list no yet available]) & (B) are using "Mod Manager". Each mod that can be configured from the sandbox configuration section has been pre-configured and those files are in the folder, "Sandbox Presets" within the folder, "Special Data for HMO (Self-Serve)". You can copy and paste the presets to your project zomboid "Sandbox Presets" folder to have them usable from within your game when creating a new game.
