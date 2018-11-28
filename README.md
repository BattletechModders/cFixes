# cFixes
Community fixes to HBS BattleTech game.
Bugs fixed as reported here:
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-for-1-3.1126334/

These files are the result of the combined work of several community modders, namely:

- Amechwarrior, Hawaii, bug tracing and code review.
- Dr. Banzai, Germany, bug fixing and configuration management.
- scJazz, US East Cost, bug fixes and code review.

Credits:
Special thanks to JustinKaseToo for providing a ton of basic information we were able to built up on.
Another shout out to Ark Evensong for providing the fixes to various pilots.

The authors do not claim any intellectual or legal property on the content of these files. 
They are intended for free use and re-use.

## List of Fixes
(by directory)

### /data/chassis/
chassisdef_commando_COM-1B.json - fixed typo: "IB" changed to "1B".
chassisdef_thunderbolt_TDR-5S.json - fixed typo: "well armored and" changed to "well armed and".
chassisdef_trebuchet_TBT-5N.json - fixed value: CT max Armor 120 changed to 160.
chassisdef_zeus_ZEU-6S.json - fixed value: Jump Jets 3 changed to 4.
chassisdef_atlas_AS7-D.json - reduced CenterTorso internal structure to 155.
chassisdef_atlas_AS7-D-HT.json - reduced CenterTorso internal structure to 155.

### /data/events/
event_mw_arcadeMercenaries.json - fixed typo: "his" changed to "{TGT_MW.Gender?Male:his|Female:her|NonBinary:their}"

### /data/factions/
faction_MagistracyOfCanopus.json - fixed typo: "conservation" changed to "compensation"

### /data/mech/
mechdef_cataphract_CTF-1X.json - removed tag: "unit_jumpOK", 
mechdef_catapult_CPLT-C1.json - added tag: "unit_jumpOK", - added tag: "unit_indirectFire",
mechdef_centurion_CN9-AL.json - added tag: "unit_indirectFire",
mechdef_commando_COM-1B.json - fixed typo: "IB" changed to "1B"
mechdef_highlander_HGN-733P.json - added tag: "unit_indirectFire",
mechdef_jagermech_JM6-A.json - added tag: "unit_indirectFire",
mechdef_orion_ON1-K.json - added tag: "unit_indirectFire",
mechdef_quickdraw_QKD-5A.json - removed tag: "unit_indirectFire",
mechdef_zeus_ZEU-6S.json - added tag: "unit_indirectFire",
mechdef_atlas_AS7-D.json - reduced CenterTorso internal structure to 155.
mechdef_atlas_AS7-D-HT.json - reduced CenterTorso internal structure to 155.

### /data/movement/
movedef_crab_CRB-27 - Fixed Walk and Sprint distances.  From 120/200 to 140/240.

### /data/pilot/
The exact list of changes is long to detail see original thread...
https://forum.paradoxplaza.com/forum/index.php?threads/battletech-pregenerated-ronin-kickstarter-pilots-missing-passive-skills.1125874/
along with the additions noted by Amechwarrior for PvP pilots...
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-for-1-3.1126334/

### /data/starsystem/
starsystemdef_NewGanymede.json - fixed typo: "Concordant" changed to "Concordat"

### /data/vehicle/
vehicledef_STRIKER.json - fixed value: Turret Armor 120 changed to 110

### /data/weapon/
Weapon_LRM_LRM5_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,
Weapon_LRM_LRM10_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,
Weapon_LRM_LRM15_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,
Weapon_PPC_PPCER_0-STOCK.json - added general PPC status debuff "sensors impaired"
Weapon_PPC_PPCER_1-MagnaFirestar.json - added general PPC status debuff "sensors impaired"
Weapon_PPC_PPCER_2-TiegartMagnum.json - added general PPC status debuff "sensors impaired"
