# cFixes
Community fixes to HBS BattleTech game.
Bugs fixed as reported here:
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-for-1-3.1126334/

These files are the result of the combined work of several community modders, namely:

- Amechwarrior, Hawaii, bug tracing and code review.
- Dr. Banzai, Germany, bug fixing and configuration management.
- scJazz, US East Coast, bug fixes and code review.
- JustinKaseToo, US East Coast (living on West Coast time according to his wife), bug and formatting fixes.

Credits:
Special thanks to Ark Evensong for providing the fixes to various pilots.

The authors do not claim any intellectual or legal property on the content of these files. 
They are intended for free use and re-use.

## List of Fixes
(by directory)

### /data/chassis/
chassisdef_atlas_AS7-D.json - reduced CenterTorso internal structure to 155, max CT armor to match.

chassisdef_atlas_AS7-D-HT.json - reduced CenterTorso internal structure to 155, max CT armor to match.

chassisdef_commando_COM-1B.json - fixed typo: "IB" changed to "1B".

chassisdef_thunderbolt_TDR-5S.json - fixed typo: "well armored and" changed to "well armed and".

chassisdef_trebuchet_TBT-5N.json - fixed value: CT max Armor 120 changed to 160.

chassisdef_zeus_ZEU-6S.json - fixed value: Jump Jets 3 changed to 4.

### /data/contracts/
DefendBase_Bodyguards.json - removed redundant "the" in dialogs.

### /descriptions/Lore/
LoreGreatHouses.json - Ordered Houses "Around the Sphere"

LoreSuccessorState.json - Ordered Houses "Around the Sphere"

### /data/events/
event_mw_arcadeMercenaries.json - fixed typo: "his" changed to "{TGT_MW.Gender?Male:his|Female:her|NonBinary:their}"

### /data/factions/
faction_MagistracyOfCanopus.json - fixed typo: "conservation" changed to "compensation"

### /data/mech/
mechdef_atlas_AS7-D.json - reduced CenterTorso internal structure to 155.

mechdef_atlas_AS7-D-HT.json - reduced CenterTorso internal structure to 155.

mechdef_cataphract_CTF-1X.json - removed tag: "unit_jumpOK", 

mechdef_catapult_CPLT-C1.json - added tag: "unit_jumpOK", - added tag: "unit_indirectFire",

mechdef_centurion_CN9-AL.json - added tag: "unit_indirectFire",

mechdef_commando_COM-1B.json - fixed typo: "IB" changed to "1B"

mechdef_highlander_HGN-733P.json - added tag: "unit_indirectFire",

mechdef_jagermech_JM6-A.json - added tag: "unit_indirectFire",

mechdef_orion_ON1-K.json - added tag: "unit_indirectFire",

mechdef_quickdraw_QKD-5A.json - removed tag: "unit_indirectFire",

mechdef_zeus_ZEU-6S.json - added tag: "unit_indirectFire",

### /data/movement/
movedef_crab_CRB-27 - Fixed Walk and Sprint distances.  From 120/200 to 140/240.

### /data/pilot/
pilot_backer_Brown - Typo in bio "ambivalence" corrected to "ambivalent."

pilot_kbeta_apex - Added missing "TraitDefWeaponHit7"

pilot_kbeta_arclight.json - Removed Piloting 7 Sprint Bonus, added Piloting 6 Evasive Charge Max +1

pilot_kbeta_ozone.json - Removed Piloting 7 Sprint Bonus, added Piloting 6 Evasive Charge Max +1

pilot_kbeta_showboat.json - Removed Piloting 7 Sprint Bonus, added Piloting 6 Evasive Charge Max +1

### /data/simGameConstants
SimGameConstants.json - Various extra commas, missing comma after "uixSvgIcon_contract_Travel"

### /data/starsystem/
starsystemdef_Camadeirre.json - fixed typo: "Camadeirre" change to "Camadeierre"

starsystemdef_MacLeodsLand.json - fixed typo: "Concordant" changed to "Concordat"

starsystemdef_NewGanymede.json - fixed typo: "Concordant" changed to "Concordat"

starsystemdef_NewVandenburg.json - fixed typo: "Concordant" changed to "Concordat"

starsystemdef_Renfield.json - fixed typo: "Concordant" changed to "Concordat"

starsystemdef_Samantha.json - fixed typo: "Concordant" changed to "Concordat"

starsystemdef_Taurus.json - fixed typo: "Concordant" changed to "Concordat"

### /data/vehicle/
vehicledef_BULLDOG.json - added Front MG and ammo

vehicledef_DEMOLISHER.json - added missing 4th ton of AC/20 ammo

vehicledef_SCORPION.json - moved MG from Turret to Front

vehicledef_STRIKER.json - fixed value: Turret Armor 120 changed to 110

### /data/vehicleChassis/
vehiclechassisdef_SCORPION - moved AP hardpoint from Turret to Front

### /data/weapon/
Weapon_LRM_LRM5_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,

Weapon_LRM_LRM10_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,

Weapon_LRM_LRM15_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,

Weapon_PPC_PPCER_0-STOCK.json - added general PPC status debuff "sensors impaired"

Weapon_PPC_PPCER_1-MagnaFirestar.json - added general PPC status debuff "sensors impaired"

Weapon_PPC_PPCER_1-MagnaFirestar.json - added weapon bonus description

Weapon_PPC_PPCER_2-TiegartMagnum.json - added general PPC status debuff "sensors impaired"

Weapon_PPC_PPCER_2-TiegartMagnum.json - added weapon bonus description

Weapon_Gauss_Gauss_1-M7.json - added weapon bonus description

Weapon_Gauss_Gauss_2-M9.json - added weapon bonus description

Weapon_Laser_LargeLaserER_1-Blankenburg25.json - added weapon bonus description

Weapon_Laser_LargeLaserER_2-BlazeFire.json - added weapon bonus description

Weapon_Laser_LargeLaserPulse_1-Thunderbolt12.json - added weapon bonus description

Weapon_Laser_LargeLaserPulse_2-Exostar.json - added weapon bonus description
 
Weapon_Laser_MediumLaserPulse_1-RakerIV.json - added weapon bonus description

Weapon_Laser_MediumLaserPulse_2-Magna400P.json - added weapon bonus description

Weapon_Laser_SmallLaserPulse_1-Maxell.json - added weapon bonus description

Weapon_Laser_SmallLaserPulse_2-Magna200P.json - added weapon bonus description
