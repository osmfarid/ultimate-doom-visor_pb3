# 2.13 CHANGES 2018-11-25

- Fixed issue with armor display during invisibility.
- Changed color of Smart Medi Kit to an orange cross.
- Fixed issue with startup message not displaying on level start.
- Updated to support all current BDv21 weapons and changes.
- Major changes to support the BDv21 vehicles. 10:50 PM 12/17/2018
- Fixed long standing bug with Tactical mode not working correctly. 11:09 PM 12/17/2018
- Removed Aiming Momentum options - recommend using Immerse mod by Josh771, since it is much better. 11:10 PM 12/26/2018
- Removed auto walk speed limiter when playing UDV Hardcore difficulty. 11:10 PM 12/26/2018
- Added new option to enable walk speed limiter at any time in UDV Gameplay Options (requires map restart). 11:10 PM 12/26/2018
- Removed Damage Factor from UDV Hardcore difficulty. 4:34 PM 12/27/2018
- Added new option to change damage factor in UDV Gameplay Options. 4:35 PM 12/27/2018
- Added Fast Monsters option in UDV Gameplay Options (requires map restart). 4:35 PM 12/27/2018
- Added option to play warning sound when near or on damaging floors. (No more wondering if it will hurt you to stand on things!) 1:57 PM 1/6/2019
- Added new option for Automatic EMS. Defaults to off. 3:59 PM 1/10/2019
- Updated Radar script code to make UniqueTIDs - more reliable. 11:45 PM 1/11/2019
- Fixed bug with EMS running after death. 9:53 PM 1/12/2019
- Fixed bug with Mugshot not appearing on armor greater than 100. 11:06 PM 5/25/2019
- Fixed bug with walk speed carrying over into UDV Hardcore difficulty. 11:06 PM 5/25/2019

# 2.12b CHANGES -- 2018-01-21

- Fixed issue with enemy healthbar disappearing after demon transformations in Project Brutality. 10:46 PM 7/8/2017
- Updated to fix broken menu options for various commands. 11:17 1/21/2018
- Updated to support current BDv21 Beta weapons and monster changes. 11:17 1/21/2018
- Fixed issue with HUD not reappearing after exiting level during demon transformation in Project Brutality. 5:19 PM 1/22/18
- Updated to support current Project Brutality 3.0 Test weapon lists. 9:23 PM 1/22/18
- Added Unmaker to Project Brutality weapon script. (Will not show in weaponlist due to being secret, like Hitler's Buzzsaw) 10:35 AM 1/23/18
- Added UDV font portable health kit graphics. 6:08 PM 1/23/18

# 2.12 CHANGES -- 2017-06-03

- Added BD64 stamina meter to BASE. 12:28 AM 5/29/2017
- Changed item spawner script to 5 tics after map start to avoid spawning with monsters in Project Brutality. 9:03 PM 6/1/2017
- Added BD64 stamina meter to ALT2. 11:34 AM 6/3/2017
- Updated Equip Helmet on Armor Pickups to match new PB Medium armor of 150. 5:12 PM 6/3/2017
- Added new UDV compatible multiplayer CoopLives script to gameplay options. 5:17 PM 6/3/2017
- Fixed dual ammo display on 4:3 mode for BASE and Alt 1. 5:53 PM 6/3/2017
- Removed EMS Min Armor option. 12:54 PM 6/4/2017
- Added new Min Armor for all tools slider in Tools Menu. 12:54 PM 6/4/2017
- Added Lives indicator for UDV CoopLives mode. 1:02 PM 6/4/2017
- Fixed bug where Player indicator on radar remained after respawn if radar was off. 1:33 PM 6/4/2017
- Added new AI Voice "Rallinth" - Thanks Samarai1000! 10:48 PM 6/5/2017
- Fixed a bug with autosave that would load during multiplayer games. 10:09 AM 6/11/2017
- Fixed bug with Project Brutality Demon Rune Transformations not resetting visor after wearing off. 6:57 PM 6/16/2017
- Increased health display for Demon Rune Transformations to show 4 digits. 6:57 PM 6/16/2017
- Fixed bug with extcam not clearing correctly. 6:58 PM 6/16/2017
- Fixed bug with air hole showing on automap. 11:51 PM 6/17/2017
- Changed color of smart medikits to blue to differentiate them from regular. 9:41 PM 6/24/2017
- Fixed bug with Enemy Healthbar disappearing after using Project Brutality Guided Rockets. 11:03 PM 7/1/2017
- Fixed bug with HEV Suit freezing all players when equipping. 11:08 AM 7/4/2017
- Fixed bug with armor warning playing during Baron/Revenant transformations in Project Brutality. 11:35 AM 7/4/2017
- Fixed bug with Critical/Energized showing during transformations in Project Brutality. 11:35 AM 7/4/2017
- Fixed bug with "DUAL" showing for Carbine Rifle when option wasn't enabled in Project Brutality. 10:56 PM 7/4/2017
- Fixed Alt2 "DUAL" display. 11:34 AM 7/5/2017
- Fixed issue with mod not loading on anything other than Project Brutality because of previous "DUAL" fix. 4:35 PM 7/5/2017


# 2.11 CHANGES -- 2017-05-12

- Bleeding damage no longer takes armor and has custom obituary. 9:17 AM 5/9/2017
- Air Loss damage no longer makes pain grunts, and has custom obituary. 9:17 AM 5/9/2017
- Radar should now track friendly marines. 1:46 PM 5/9/2017
- Radar should now track other players in multiplayer. 1:46 PM 5/9/2017
- Updated Bleeding damage to no longer be affected by skill level (Thanks Blue Shadow!!!) - requires ZScript - GZDoom 3.0 or higher required. 12:04 PM 5/10/2017
- Fixed issue with Explosive Barrels getting a TID assigned and showing up on the map. 5:05 PM 5/10/2017
- Fixed issue with mods changing UDV Assigned Player TID necessary for Radar. 6:16 PM 5/10/2017
- Added new options to customize Critical/Energized health amounts. 2:10 PM 5/12/2017
- Updated Autosave script to leave screen more quickly during external camera views. 5:18 PM 5/12/2017
- Added faint non-invasive UDV version number at bottom left of screen for debug and tracking purposes. 5:19 PM 5/12/2017
- Re-worked Ambient "C" module to be much smaller, moved script from BASE to "C" module and added new cave style background track. 12:58 AM 5/13/2017
- Clarified some menu options. 1:39 AM 5/13/2017
- Emergency Patch - fixed issue with PB weapons and things using a static TID. Radar now should adapt to mods that change the TID. 10:02 AM 5/13/2017
- Fixed PB TID issue again. 5:07 PM 5/13/2017
- Fixed Radar not showing enemy height icons correctly. 5:08 PM 5/13/2017
- Added new height icons in Radar for Players. 5:08 PM 5/13/2017
- Changed the TID stuff again. You know what? F- TID stuff. 7:21 PM 5/13/2017
- Added new logic to not change TID while dead. 7:29 PM 5/13/2017
- Added DoomED Numbers to UDV Items. 11:13 PM 5/13/2017
- Removed random spawner items and made ACS script to add UDV items if enabled. 9:18 PM 5/17/2017
- Added separate option to choose Accessory Battery spawns. 10:09 PM 5/17/2017
- Removed GLDEFS for removed UDV_ArmorBonus. 7:54 AM 5/18/2017
- Fixed bug with random spawner causing extra spawns at origin coordinates. 7:54 AM 5/18/2017
- Added CVARs to choose max amt of random spawn items per level. 5:03 PM 5/18/2017
- Updated Ambient addon to not play default music if off. Allows for other music mods to work. 6:56 PM 5/20/2017
- Fixed some EnemyHB code to address bug. 4:12 PM 5/21/2017
- Updated EnemyHB with ability to disable assigned names. 4:54 PM 5/21/2017
- Fixed bug with radar power not working. 5:27 PM 5/21/2017
- Updated HEV Suit to protect against air loss damage when equipped. 9:38 PM 5/23/2017
- Increased MAX amount for Accessory Battery spawns in Menu from 10 to 20. 9:06 AM 5/24/2017
- Added startup graphic during GZDoom loading.  1:41 PM 5/24/2017
- Fixed bug with Radar spawner during timefreeze events. Fixes issue with WeaponWheel mod. 12:02 PM 5/26/2017
- Added menu option for choosing starting battery amount. 12:25 AM 5/27/2017
- Changed Radar TID assignment to run every second instead of every tic. Should greatly increase performance. 12:58 AM 5/27/2017
- Added menu option to disable Radar TID assignment completely. Possible performance increase at loss of radar tracking. 12:58 AM 5/27/2017

# 2.10 CHANGES -- 2017-05-08

- Fixed long standing bug with Fog that I wasn't aware of, that was preventing from changing density. 5:40 PM 5/7/2017
- Fixed bug where "Cortana" voice wouldn't play sound for scanner disabled. 6:11 PM 5/7/2017
- HUGE CHANGE - Radar no longer requires "B" Module. All monsters should now be tracked via radar, always. Holy crap. 11:37 PM 5/7/2017
	- All of this is thanks to The Zombie Killer's 10x Universal monster spawning mod. Took the idea behind how it works, applied it to Radar... and BOOM! It works(with some modifications)... INSANITY! 11:43 PM 5/7/2017
- HUGE CHANGE - And... "B" Module no longer needed to capture fatalities!!! 12:03 AM 5/8/2017
- HUGE CHANGE - "B" Modules GONE! No longer needed at all - Critical Bleeding will now take a random 1-2 damage... so when near death, you have a slight chance of surviving a bit longer if you're lucky... 1:37 PM 5/8/2017
- Fixed Bleeding/Critical to work in multiplayer, as well as updating instantly on option change instead of requiring script restart. 12:12 PM 5/8/2017
- Screen Shake option will now update instantly instead of requiring script restart. 12:18 PM 5/8/2017
- Aiming Momentum option will now update instantly instead of requiring script restart. 12:27 PM 5/8/2017
- Moved visor inventory graphics for PB items into main UDV BASE file. Separate "B" module no longer required. 1:39 PM 5/8/2017
- Added LQ version of armor hole graphic. 3:01 PM 5/8/2017
- Now can choose default radar mode at map start. 3:02 PM 5/8/2017
- Removed sae_deathcam checks from BASE and Alt2 visor since they are no longer needed. 5:07 PM 5/8/2017

# 2.01 CHANGES -- 2017-05-07

- HEV Suit will replace all Radsuits again if enabled. Tweaked the equipping freeze delay to give foot protection while equipping, thus you will not take damage. This fixes the issues with replacing Radsuits in maps. 10:47 PM 5/2/2017
- Added new Extended Accessory Battery - gives 25 Accessory Battery, lower chance of spawn, but balances out energy a bit better. Don't have to be QUITE so conservative with your tools anymore. 5:45 PM 5/4/2017
- Updated PB 3.0 Test Module with some missed enemy names. 7:07 PM 5/4/2017
- Added "Cortana" AI voice, and converted some audio to OGG to further reduce file size. 8:44 PM 5/4/2017
- Renamed armor hole option to be less confusing. 11:18 AM 5/5/2017
- Fixed bug with "hole" showing in armor even if dynamic damage was turned off. 11:31 AM 5/5/2017
- Fixed bug with Reserve Ammo list not showing up unless you enabled Weapon List. 12:38 PM 5/5/2017
- Added new option to disable all battery power. 11:10 AM 5/6/2017
- If battery power options disabled, accessory batteries will no longer spawn. 11:10 AM 5/6/2017
- Fixed bug with Alt 2 visor disabling blood splatter when armor damage was off. 11:22 AM 5/6/2017
- Changed to only one UDV Difficulty instead of two and Individual gameplay settings can be enabled in Gameplay Options for any difficulty. 11:52 AM 5/6/2017
- Fixed bug with bleeding not being disabled if changed during game. 11:52 AM 5/6/2017
- Slightly increased transparency for final two armor levels of Alt 2. 12:48 PM 5/6/2017
- Fixed bug where Radar would not turn off if battery was drained. 1:30 PM 5/6/2017
- Fixed bug where flashlight wasn't turning on if battery was zero, even if power requirement was turned off. 1:36 PM 5/6/2017

# 2.00 CHANGES -- 2017-04-27

- Fixed animated face not working from 1.85
- New animatied faces for berserk/invulnerability.
- Menudef options updated
- Fixed runaway script 4278 in saehud
- Updated external camera check script to be more universal and reliable.
- Integrated saeweap modules into BASE module. No longer required for weapon warnings.
- Fixed EMS being able to be activated after death.
- Cleaned up mugshot code, much more efficient.
- Fixed Bleeding/Critical/Energized being carried over on respawn in multiplayer.
- Added Helmet Animation on start/new armor.
- New visor graphics for armor during invisibility.
- "Active Camo" counter during invisibility.
- Alt2 flashing icon when less than 30 armor.
- New "Accessory Battery" items, and display.
- Flashlight can now use Accessory Battery instead of Armor.
- EMS can now require Accessory Battery instead of Armor.
- Radar can now require Accessory Battery.
- Separate blood splatter generated from total damage taken.
- Ability to "clean" blood splatter manually by holding "forward+back" at the same time.
- Optional "Air Loss" damage when armor is under a certain level when in an "outside" zone.
- Optional warning beep when armor is below "air loss" armor level.
- Goggles and HEV Suit timers now carry over to subsequent levels instead of resetting.
- Recoded Health and Armor in SBARINFO. Much more efficient.
- Optional red tint on low health to reduce vision and add difficulty.
- Integrated HEV Suit/Goggles/SmartMedikit as options in UDV.
- Berserk/Demon Strength limiter option added.
- Choose starting armor amount, 0-200 instead of only 80.
- Fixed Enemy Healthbar horizontal amount display being incorrect.
- Increased enemy health from 1.0 to 1.5 on UDV Hardcore difficulty.
- Optional additional crack in Alt2 Visor.
- Menu Spacing reduced to 9 so that menus do not go off screen on some smaller displays.
- Recoded all options/tools to support multiplayer.
- HEV Suit/Goggles will spawn with Armor Bonuses at a low chance if enabled.
- Revamped darkdoom code to be more efficient.
- Fixed UDVReset command.
- Option to disable weapon scripts and use generic in case of mod incompatibility.
- New independent battery script that can be called from any tool that uses battery.
- Re-coded radar and brought back all 3 modes.
- New option to display default class name of monster instead of "Class X Entity" for Enemy Healthbar.
- Updated Flashlight to use DarkDoom Flashlight 2.0.
- Ambient Music/Sound can now be toggled individually.
- Fixed Ambient Music/Sound not resetting if changed midgame. 1:27 PM 4/28/2017
- Modified Vanilla_Revenant_UDV, Vanilla_DNImpVariant1_UDV, and Vanilla_DNImpVariant2_UDV in the PB 3.0 module to fix issue with radar overflow. 1:28 PM 4/28/2017
- Changed Medikit and Armorbonus pickup sounds. 4:13 PM 4/28/2017
- Added special handling for Brutal Doom 64 Tactical mode to disable Critical/Energized so sprinting still works. 5:23 PM 4/28/2017
- Added 15 new sound effects to UDV Ambient while still reducing overall file size by around 15Mb. 9:46 PM 4/28/2017
- Fixed small bug with Dark Doom effects not clearing variables if disabled. 10:59 AM 4/29/2017
- Fixed bug with UDV Helmet animation not playing the equip sounds. 7:35 PM 4/29/2017
- Modified dark doom to remove unneeded CVAR and replaced with script variable. 10:57 PM 4/29/2017
- Added back LQ Flashlight Option for those that need it. 11:21 PM 4/29/2017
- Added auto cleaning option to remove blood from visor. 12:17 AM 4/30/2017
- Extra Crack for Alt2 Visor menu option now only visible if loading Alt2 visor module. 12:18 AM 4/30/2017
- Fixed Apply All Changes option to call correct UDVReset script. 12:20 AM 4/30/2017

# 1.85 CHANGES -- 08-23-2016

- **IMPORTANT** Moved all menu options into HUD options from the main menu. This should remove the need for a separate MENUDEF for every mod. 08-24-2016
- New fog effects! Customizable in UDV menu - adds atmospheric fog to any level. Overrides any other similar effects, so it can be disabled entirely in options if you need to.
- New "D" Ambient SFX module. Replaces all music with droning factory noise with random other creepy sounds. Make sure to enable it in options if you load it!
- New "B" Module for Brutal Doom 64 Aug 08 Patreon Alpha. All current BD64 weapons and enemies are supported.
- Revamped Bleeding/Critical/Energized speed code. Should be more efficent and more compatible with other mods.
- UDV Brutal and UDV Hardcore Difficulty code changed to be more compatible with other mods.
- New OPTIONAL add-in compatible with any mod - Any door that normally closes by itself will now stay open until you decide to close it.
- Fixed bug with Energize/Fatigued message staying during death/external cam views. 08-24-2016
- Fixed bug with enemy health bar not showing after fatalities. 08-24-2016
- Fixed bug with GZDoom beta and UDValt message. 08-24-2016
- Added support for BDv20BFNT mod. 08-24-2016
- Added reserve ammo counts for BD64 C2 Visor. 08-24-2016
- Separated ambient background sound and sound effects. Can be loaded independently of each other for those that want music, but random creepy noises too, or vice versa. 08-24-2016
- Added Light Color options! Change the colors of the lighting in a level. Options for manual, random, and also match the fog color! **Thanks to Iddqd_Idkfa_Idclip for creating it!** 08-25-2016
- Fixed bug with GZDoom beta versions and ACS errors. 08-25-2016
- Fixed bug with Standalone_Doors_Stay_Open.pk3 that caused certain switches not to work. 08-25-2016
- Added Save/Load function for Fog and Light effects. Great if you happen to find a setting that you really like! 08-26-2016
- Fixed weapon loadout order in weapon list for Project Brutality. 08-26-2016
- Added icon for Sgt. Mark IV's Brutal Friends Teleport Beacon. 09-02-2016
- Added new Random Light Level option 09-02-2016
- Fixed broken C2 Fullscreen Visor not working correctly. 09-02-2016
- Decreased door open speed for Standalone_Doors_Stay_Open.pk3 09-03-2016
- Moved Doors mod to UAC Survival Pack 09-07-2016
- Fixed flashlight bug during time freeze. 09-07-2016


# 1.84 CHANGES

- Optional Screen Shake when damaged! Can be turned on in options, or is automatic on UDV Hardcore mode. The harder you are hit, the longer and more intense the shake.
	- If you have 15 or more Armor, shake duration will be reduced by 1/3.
- Changed to new font that supports Uppercase and Lowercase. New optional add-in to restore original font if you don't like it.
- Changed "XXX Celsius" display to "XXX- C".
- Fixed bug where DUAL wasn't displaying for DualRifles on BDv20.
- Fixed various things that were not capitalized correctly.
- Fixed bug with reflection continuing to show during fatalities and executions.
- Changed timing for face animation to a random time for a bit more realistic animation.
- Fixed font issue when using NoMenuFont add-in. 02-26-2016
- Fixed reserve ammo display on 16:10 resolutions. 02-26-2016
- Fixed bug where wrong font was used if using NoMenuFont add-in 02-26-2016
- Fixed bug with Default AI voice playing wrong Critical Health warning. 02-26-2016
- Screen Shake now depends on Armor level. 80+ is 75% absorbed, 50+ is 50% absorbed, 20+ is 25% absorbed. 02-26-2016
- New UDVReset console command. Resets UDV in case things stop working when using cheats like 'resurrect'. Can also be activated through the menu with "Apply Changes Now" 03-01-2016

# 1.83 CHANGES

- Face reflection now animated!
- New option to ALWAYS have face reflection on screen (if you're into that sort of thing.) Off by default.
- New option to set reflection transparency level. For those that want it more noticeable, or less noticeable.
- Fixed issue with face reflection continuing to display on external camera death.
- Fixed issue with headshot recognition on Project Brutality. Also improved code to catch further changes and display Boss hitboxes.
- Changed "Temp. XXX" display for headshots to "XXX Celsius" to better emphasize "temperature" reading of hitbox.
- Added support for my new UAC Survival Pack Satchel Charges in weapons display on supported mods.
- Bugfix for Project Brutality add-in not showing correct secondary weapon function names. 02-22-2016
- Bugfix for Vanilla add-in keycards not working correctly. 02-22-2016
- Forgot to update the version number in the startup display. 02-23-2016


# 1.82 CHANGES

- Graphics can now be changed between HQ and LQ in the options. No more loading LQ or HQ packs!
- Greatly reduced the size of the face reflection graphics while still maintaining the same look. Should run better on lower systems.
- Updated the Knee Deep in ZDoom keys add-in, including a new one for the C2 visor.
- New add-in for loading lower resolution screen effects (cracks and bulletholes in glass when shot/blown up). Should run better on lower systems.
- Renamed add ins for better clarity and ease of loading... (hopefully).
- Restored BDJ add-in to current BDJ release version until new BDJ version is released to avoid further confusion.
- New add-in for the Fearrific Project Brutality Nightmare monster variant for radar tracking. 02-18-16
- Lowered resolution of Low Quality visor graphics to help performance on lower end systems. Also renamed some images and tweaked SBARINFO. 02-18-16
- Fixed bug with radar not working correctly after reloading a save. 02-18-16


# 1.81 CHANGES

- New Feature! Face "reflection" in visor! Every few minutes Doomguy face will flash in the visor glass. Of course this is toggleable off or on in the UDV options! Defaults to OFF.
- Health can now adjust to additions from the Stamina property to show total overall health percentage correctly.
- Cleaned up Menus - separated into multiple smaller sections.
- New Toggle for Player Name display, ability to toggle stats and time serparately.
- New toggle to enable radar at map start. This can cause performance issues on slower systems, so by default it is turned off.
- Clip warning will now be disabled if you turn off AI Alerts.
- Update BDJ Add-In to support new BDJ version.
- New compatible add-in for Brutal Pack 8.
- Fixed Project Brutality add-in bug with guided rockets. 02-15-16
- Fixed speed issue when carrying barrel on BD Realism Difficulty and UDV difficulties. 02-15-16

# 1.80 CHANGES

- Added completely new alternate visor pack. It is a C2 module and has HQ and LQ versions. Load it after A and B modules, and have fun! Has some new display features that the regular visor does not.
- Two new AI voices, both male! One is a computerized TTS voice I created, the other was a user made voice pack. Try them out!
- Health warnings now calculated by percentage of health. 100%+, 100%, 50%, 25%, 0%. This will make it more accurate for mods that modify the player max health.
- Added new startup messages. Some are for flavor, others will specify the current UDV settings and display your player name. More immersion!
- Added new option in UDV Options to specify source port you are playing: (G)Zdoom or Zandronum. If you are playing multiplayer, MAKE SURE THIS IS ACCURATE! Otherwise you WILL have problems with certain features.
- Added some new damage resistance to the HEV.

# 1.71 CHANGES

- Fixed speed issues with bleeding options. All difficulties should use the correct speed now.
- Added new Low Quality Alternate Graphics pack for slower systems.
- Added Startup Message when loading level.
- Fixed a few incorrect coding mistakes I caught.

# 1.70 CHANGES

- Added armor power drain when using flashlight if minimum power requirement is set. Drops by 1% for every 10 seconds. Use it wisely!
- Added new indicator under mugshot for UDV - Hardcore mode. Now shows "Energized" for >180 Health, and "Fatigued" when hobbled from <20 health.
- New menu option to toggle critical bleeding/energized on any difficulty!
- New menu option to toggle realistic aiming mode on any difficulty!
- New menu options to control EMS Minimum Health/Armor!
- Changed blood loss timing to random between 5 and 15 seconds for UDV - Hardcore. You'll never know exactly how long till you bleed out, so you better hurry!
- Fixed bug with EMS that would permanently lower your speed on difficulties less than UDV - Hardcore.
- Possibly enhanced performance with Radar. Still will slow down on abnormally large maps like Memorial and Doom:One. Will start out fine, but after awhile you will notice slow down.
- Fixed bug with Radar Enable sounds not playing.
- Removed Visible Radar Scanner due to being overly complicated and resource intensive, while being fairly pointless.
- Updated HEV add-in to correctly protect against fire damage for certain special fire damage sectors. (Specifically BDv20b Starter Pack maps.)
- Fixed HEV and Goggles add-ins flashing when low. Will flash on and off correctly when at 15% battery.
- HEV and Goggles add-ins now droppable when partially used. They will be unable to be picked back up, but if they are really low and you find a replacement, now you don't have to turn it on and wait for it to drain!
- Optional Alternate Graphics add in now included! Created by user "Lightsource". He is amazing!!
- Fixed Player name display for Multiplayer.
- Disabled Radar and Flashlight in Multiplayer due to many bugs (WIP for any fixes I can figure out).
- Updated some Inventory Icons.

# 1.61 CHANGES

- Removed optional pk3 for low quality flashlight, integrated LQ flashlight into UDV options. Now toggleable on/off.
- Fixed bug with UDV difficulties that was affecting non UDV difficulties.
- Combined UDV AI voice toggle into one option.

# 1.60 CHANGES

- New UDV - Hardcore difficulty. All the difficulty of UDV - Truly Brutal, with blood loss of 1 HP per 15 seconds at 20 or lower health and 50% slower movement speed. BUT at 180+ health, you get a 50% speed boost!
- Added new Emergency Medical System(EMS). Mainly for use with UDV - Hardcore, but available on all skill levels.
	- When under 20 health, and over 80 armor - you can activate it for a heal over time that will randomly heal your HP from 21-40 at the cost of 40 armor.
	- Default key is "N", and configurable in controls.
- New lower quality flashlight add-in. For those having performance issues, you can load this up and lose slight brightness for a performance boost.


# 1.51 CHANGES

- Re-did radar icons for displaying enemy height. Now shows upward pointing arrow for above, downwards pointing arrow for below.
- Bugfix for some shadows/lighting effects affected by the mod.
- Added new optional add-in to remove DoomVisor font from menus. This will also remove it from on screen pickup messages, so use if the menu font really bothers you.

# 1.50 CHANGES

- Now requires add-in for full functionality in mods. If you only load the BASE file, it will technically "work", but you will not have full advanced functionality. See HOWTOUSE.TXT for details.
- New UDV Difficulty added when starting a new game. If you want a challenge on any mod, try out "UDV - Truly Brutal" when you choose your skill. "Realistic" aiming, slower movement, faster and harder hitting enemies.
- Supports Brutal Doom v20 via add-in!
- Now supports Brutal Doom J 20 via add-in!
- UDV now has a built-in flashlight! But be careful, the hellspawn aren't completely idiotic... while it's on, they WILL notice it and be alerted to your presence! Default bind is "Y", available to set in control config!
- Flashlight can be set to shut off if armor is below a certain level. Defaults to always available, but configurable through UDV Menu.
- Flashlight can be used in two positions: Center, and Shoulder. Choose your favorite and light up your path! Available in UDV Menu.
- Ability to darken the default lighting levels in WAD from UDV Menu. Choose between Dark, Darker, and Pitch Black levels. Great with the flashlight! 
- New radar tracking system! For v19, you will need to load the Radar add in separately. For all other mods, it will be built in. Configure controls via in game control menu. Can display all movement, or all visible monsters/items(WIP).
	- Radar will show all lower tier monsters position relative to player.
		- Red is on same level as player.
		- Orange is above player.
		- Olive is below player.
	- Monsters with 1000 or more health will show up as gold.	
- Enemy health bar display! Defaults to on, shows up in top center of visor. Can show just the bar, or bar and numerical health. Toggle in UDV options.
- Enemy name display! Human type enemies will display a random rank and last name if toggled in health bar display. All other unknown monsters will be shown as a "Class X Entity" ranking 1-8 depending on their level of health. As always, toggle off or on under the healthbar display options inside UDV.
- Weapons display in top left of visor. Keep track of what weapons you do or don't have! Never wonder "Do I have the plasma rifle?" again! Toggle it in UDV options.
- Visor will display "DUAL" underneath the weapon name if you have two of the same weapon on certain mods! Never forget again that you are carrying two rifles or plasma guns!
- Added "Engagement Time" (level time) to level stats display. Displays in the top middle of visor. Great for speedrunners! Disable level stats in the menu to remove it.
- Added Combat Recorder timer display. Counts down until the next autosave. Displays at bottom left of visor. Useful in a firefight to know how long until your next autosave!
- Keys will now display a double icon when carrying two of the same color (card, skull) instead of 6 separate images.
- New Inventory add-ins for Radiation Suit and Light Amp goggles. If you load these add-ins, you can carry these items with you, two at a time and toggle them on and off with a key! Never waste that precious power again!
	- Light amp goggles default key is (K), configured through in game control menu.
	- Radiation Suit is now HEV suit. Halves damage from fire and fce, quarters damage from electricity, and nullifies poison and acid. Default key is (J), configure through in game control menu.
	- When toggling HEV suit, there is a 2 second delay that will freeze you in place as you "put on" the suit. This balances having a persistent suit with damage reduction and makes it more realistic.
- Integrated display for my other add-on Pipebombs, Jawbones, and Flares. They will now show up in all supported mods by default, if you are using them without the need for an extra UDV add-in.
- MANY new crosshairs to choose from.
- HUD no longer requires screen size to be set to 11. Will work on all sizes.

# 1.43a CHANGES

- Font fix(yet again) - Made the fonts in the menus and intermission screens smaller. Hopefully this will fix the issues people have been having.
- Updated some sounds with some higher quality versions made by the amazing Quaker540!

# 1.43 CHANGES

- New low clip warning chime. When clip ammo gets below 20% and the clip capacity is greater than 2, a short warning chime will play(does not play for SSG, and other weapons with low clip capacity counts.). Helps to know when you are nearing the end of a clip, or like me forget you are not using a full clip when switching between weapons.
- Visor display will turn off during external camera sequences! This should work for any rolls, deaths, fatalities, etc. that switch out of first person view. This was a tough one to figure out and work around, it might be buggy - let me know!
- New flatline sound on death. Now when you die, you will hear a flatline sound.
- Ammo low warnings increased from 15% to 20%.
- Fixed bug with low ammo and depleted warnings going off at the same time when switching to a weapon with no ammo.
- Fixed display bug with primary ammo count on 16:9 displays.

# 1.42a CHANGES

- Fonts are fixed! (For the last time hopefully) I re-did the fonts, and everything should work now WITHOUT having to set scale text to DOUBLE or ON. You can have no text scaling, and everything should be readable now.
- Unknown weapons will now show "-----" instead of "UNKN".
- New fonts mean slight tweaks to the locations of the ammo counters.
- Menus are now in DoomVisor colors.
- Meatshields now display correctly on Visor!

# 1.42 CHANGES

- New reserve ammo display! Enabled by default, this will display in the right side of the visor and have a running count of all ammo available. Option to toggle this in DoomVisor Options.
- Combat Recorder (Autosave) mode! Disabled by default, this allows you to enable an autosave every 1-10 minutes. Very helpful if you are like me and forget to save, then lose tons of progress. You'll never be further than 10 minutes from where you left off! Shows a red recording light on the bottom left of visor when enabled.
- Weapon names now shown on visor display instead of boring AMMO.
- Found a workaround for the annoying audio bombardment when starting a new game. Armor depleted warning should now no longer play until you have gotten at least 1 armor, then lost it.
- Higher quality AI sounds thanks to Quaker540! He optimized and re-did my audio tracks, changed some of the warning beeps, and increased volume!
- New option to Toggle off/on Visor on screen messages. Available in DoomVisor Options.

# 1.41 CHANGES

- New high resolution damage graphics for bullet holes and explosion damage on visor.
- New toggle option for disabling auto switching weapons on pickup. This is just a personal preference of mine, and I have made it an option for anyone else who wants it.
- Re-did damage graphics and the way they are loaded. Should improve performance overall. Unfortunately this increases the overall size of the HUD, but the performance increase should be worth it.
- Changed ammo warning levels from 50% and 25% to 40% and 15%. This seems like an overall better option so it isn't constantly whining about low ammo.

# 1.40b CHANGES

- Bugfix for menus. Certain mods lost their special menu functions with the last version, those should be fixed now. Thanks Alex-Wolfenstein97 for finding this!
- Bugfix for ammo depleted count. I noticed that on some weapons, the ammo depleted warning would go off with 1 bullet left. Changed the way it works, now should only go off for truly empty ammo counts!

# 1.40a CHANGES

- Bugfix for melee weapons. There was a bug that would show a low ammo warning for melee weapons that would show up randomly. This has been fixed.
- All options have been moved to the main Options screen. It is now located at Options -> Ultimate DoomVisor HUD.
- You can now set all options necessary for the HUD to display correctly directly from the Ultimate DoomVisor Options screen. Set these options to their recommended settings, and everything should display perfectly!
- PA1NKI113R's Add-In has been updated to support the new V7.

# 1.40 CHANGES

- Brand new warning sounds! HUD now has an "AI" (and I use the term intelligence very loosely) system. Warning beep and voice will play under the following conditions: When health is critical, Armor is zero, Ammo is critical, and Ammo is empty. Thanks to killbotvii for inspiring me to do this, and his friend Kate for recording the voices!
- Warning text! In addition to the warning sounds, text will show on screen to warn you of the same conditions.
- Warning sounds are on by default, but are a toggle option under Options -> HUD Options -> DoomVisor HUD -> Enable Sounds.
- Foolproof Ammo display! A basic Ammo display will always be shown, even if a weapon is not fully supported. This will show up in white and show "UNKN" instead of "AMMO". For example, if Quaker540 updates his submod and adds a new weapon - you will now be able to continue to use my HUD until an update is available. All supported weapons will be unaffected. This serves three purposes, the first being adapting to new weapons. The second purpose is that the HUD should now partially support ANY mod. The third purpose is to help out those that still can't figure out load order. Even if you load things in the wrong order, you will still have a semi-functional Ammo display.
- Warning sounds/text will not function with unsupported weapons.

# 1.35e CHANGES

- Option to toggle mugshot damage off! For those that always want to see that beautiful Doomguy mugshot, you now will have the option to always display it, no matter how little armor you have. Just go into the DoomVisor HUD options and turn "Dynamic Mugshot Damage" to OFF.
- New font! I made a new font. It is more uniform, and supports more characters.
- All messages on screen will now display in DoomVisor digital font. This makes it less jarring when finding secrets, picking up items. Now it is more connected to the total experience. Because of this change, you need to make sure Options -> HUD Options -> Message Options -> Scale Text In High Res is set to DOUBLE or ON. If you do not do this, you might be unable to read any on screen messages.
- All menus (except for the title screen and end of level) display in DoomVisor digital font.

# 1.35d CHANGES

- Option to toggle damage! Due to a few requests, I went ahead and added a new option in the DoomVisor HUD option menu for disabling the damage graphics. I personally don't prefer it this way, as it takes away half of what makes this HUD immersive - but hey, if the damage gets on your nerves and you just want the rest of the counters, colors, etc... then here you go!
- Bugfix for damage on resolutions other than 4:3 when showing damage. Due to a coding fail on my end, when the armor hit 20%, it only drew one damage level instead of the four it should have. Once you hit 10%, it would show the full damage again. This has been fixed, and damage should show consistently as it was meant to!
- Separated the ACS scripting into two modules. This is to make it easier for me to update it in the future with other submod weapon layouts. This will unfortunately break loading current savegames you might have because it will be a different number of ACS modules. If you are doing a playthrough and loading from save games, I highly recommend you either wait until you finish that run before using the new version of my HUD, or just go all out and be prepared to start fresh. :D

# V1.35c CHANGES

- New indicator for when you have berserk strength (berserk pack, demon strength rune). The UAC logo in the bottom left corner will now light up and pulse slowly to remind you that you have berserk strength. I find that I forget I have that from time to time, and this serves as an non-intrusive reminder.
- Hand Grenade ammo no longer displays if you are completely out. This was originally how it was meant to be, but I apparently left that code out at some point and didn't realize it. Anyway, it is fixed now.
- Slight tweak for my persistent Radiation Suit / Light Amp mod. The Light Amp goggles will no longer count toward your item counts for the level. I changed this because with my mod you can't always pick up every Light Amp you come across. This allows you to still get 100% items, but enjoy saving your Light Amps for a dark day.

# v1.35b CHANGES

- Fatalities should now properly remove HUD from view consistently. No more keybar/grenade counters staying on screen during those beautiful deaths!
- Ammo counter for Pa1n's V6C new weapon Compact SMG now supported.
- Automap Inventory bar should now work properly again. Got broken in one of the previous updates, and I just noticed it.

# v1.35 CHANGES

- New bar graphics for health and ammo. Cleaned up and sharper, looks much better now. Also new graphics for stats display, also sharper and cleaner.
- Support for PA1n's new inventory items for v6. They will show up in the inventory bar on the bottom left display for easy access.
- 4:3 support now back to old method. No cut off edges, everything is scrunched but you can see everything now.
- A few new armor damage levels. The more damage your armor takes, the worse off it is. Some new cracks, some new blood, some scuffs... nothing too intrusive, but here's another reason to keep your armor in good condition!
- Weapons that don't use a secondary ammo clip (chaingun, bfg, etc.) will only show one ammo display and will not show the / separator.
- Support for bdpv24.
- Support for Vanilla Doom.

# v1.34 CHANGES

- Newly optimized, should work with absolutely any resolution! While researching information on making this work with Zandronum, I discovered I had been doing more work than necessary for different resolutions. Every resolution should work now, and I have removed all redundant graphics for the old method. Filesize reduced by about 4MB!
- 4:3 mode no longer looks squished, and supports all functions! Because of the new way to handle resolution scaling, everything fits. 4:3 users rejoice!
- Zandronum 2.0 support! Now supports Zandronum 2.0 via optional add-in pk3. Just load it after the main pk3, and you should be good to go! Minor downside is there is no way for me to easily set things like Stats, Mugshot, or the inventory display as a toggle with Zandronum. They are always on in Zandronum, until a way to toggle is available. Also, I am working on making it compatible with the stable version of Zandronum 1.2.2, but it might be heavily stripped down in terms of features due to lack of advanced functions.
- Visor HUD turns off during fatalities! Awesome suggestion, and I found a way to implement it. Now you aren't looking through a visor watching yourself perform one of those beautiful fatalities! Much better immersion this way.

# v1.33 CHANGES

- Light Amplification Visor battery level! When you pick up a Light Amplification Visor, a battery icon will appear in your right display. It will drain as your Visor runs out of power.
- Radiation Suit level! When you pick up a Radiation Suit, a biohazard icon will appear on your right display and slowly disappear as your suit runs out of protection.
- Keys have been moved slightly left on the display to make room for the new icons.
- Inventory! An inventory bar has been added to the automap display, if you have any items in your inventory. For those of you that play WADs that use inventory, this is for you!
- Inventory on Visor! You can show your current inventory on the bottom left side of the right display in 16:9 and 16:10 resolutions, 4:3 is too squeezed to fit it. This is made mainly for PA1N's submod and the Sentry Gun inventory item. I have created a custom graphic for the Sentry Gun to show there. Other items may not work as well, as their icon will not scale well or fit the theme. For now this is a toggle option, and only for those that want it.
- Optional add in that changes the Radiation Suit and Light Amplification Visor to inventory items that can be used on demand. You can carry 2 Light Visors, and 1 Radiation Suit. This is totally optional, but I like it better than use on pickup versions, it feels more strategic and real. I have created custom graphics for those two items to work with the Inventory on Visor capability, and when used together, the visor becomes even more dynamic and useful!
- Minor change to visor damage graphics. I noticed a smudge on the visor that was really only visible in bright environments. I have removed it. If you noticed it and it bugged you, it is gone!


# v1.32b CHANGES

- All PNG files have been optimized for a smaller overall file size. The optimization is lossless, so it should not have any effect on the look, just saves space, and makes for quicker loading for the engine!

# v1.32 NEW FEATURES

- Full 16:10 support up to at least 1920x1200! Higher resolutions should work in theory, but I have no way to test myself.
- New keybar location resides below the Ammo display at the bottom right.
- New key graphics to better integrate into the overall look of HUD.
- New FONT! Thanks to Nikulas' effort in designing some new high resolution fonts, the numbers and lettering have never looked better!

# v1.31 NEW FEATURES

- Full 4:3 support up to at least 1600x1200! Higher resolutions should work in theory, but I have no way to test it since I have no monitors that support higher resolution than that.

# v1.3 NEW FEATURES

- Now replaces the full screen HUD, to make it possible for the main new feature...
- Full 16:9 support up to at least 1920x1080! Higher resolutions may work, but I have no way of testing.
- 4:3 support has been removed temporarily until I can get it optimized and fully working with all the features. If you play in 4:3, don't bother downloading right now.
- Level stats and mugshot can now be turned on or off independently from the HUD Options menu. Just look for DoomVisor HUD, toggle your preference and viola!
- Air supply display will show up at bottom of screen as a semi-transparent bar over the respirator mouthpiece. For those of you playing WADs that go underwater, you can now avoid drowning! (Dark7 being my favorite so far!)