# cFixes - Community fixes to HBS BATTLETECH
Bugs fixed as reported here:
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-post-1-4-0.1126334/

These files are the result of the combined work of several community modders, namely:

- Amechwarrior, Hawaii, bug tracing and code review.
- Dr. Banzai, Germany, bug fixing and configuration management.
- scJazz, US East Coast, bug fixes and code review.
- JustinKaseToo, US East Coast (living on West Coast time according to his wife), bug and formatting fixes.
- Sheepy, bug fixes and code review.

Credits:
Thanks to the community at large for helping bring these bugs to HBS's attention!

This mod is intended for free use and adaptation in other mods.

### Instructions:
    Remove older editions of cFixes. This is very important to not crash the game.
    Copy cFixes folder in to Mods folder created for ModTek.
    
### ModTek
This mod uses ModTek:

https://github.com/BattletechModders/ModTek/releases

Thanks to mpstark and the entire ModTek team for making this mod possible!

cFixes can be loaded as is by the HBS mod loader, however it will not be able to alter any files inside the DLC packages.  It is recommended you use this mod with ModTek for a complete feature set and the ability to remove this mod without affecting your saves.

## Stock Files Edited:

### StreamingAssets/data/chassis/
    chassisdef_banshee_BNC-3S.json - fixed costs
    chassisdef_battlemaster_BLR-1GB.json - fixed 1Gb from 1GB
    chassisdef_blackjack_BJ-1DB.json - fixed costs
    chassisdef_blackknight_BL-6-KNT.json - fixed variant name to BK-7-KNT
    chassisdef_blackknight_BL-6b-KNT.json - fixed reference to BK-7-KNT
    chassisdef_cicada_CDA-2A.json - fixed costs
    chassisdef_crab_CRB-27.json - fixed costs
    chassisdef_crab_CRB-27b.json - FF armor/tonnage fix, fixed 27b from 27B
    chassisdef_cyclops_CP-10-Q.json - fixed costs
    chassisdef_hatchetman_HCT-3F.json - fixed costs and base melee damage
    chassisdef_hatchetman_HCT-3X.json - fixed costs and base melee damage
    chassisdef_highlander_HGN-732b.json - fixed "732B" to "732b"
    chassisdef_hunchback_HBK-4G.json - melee DMG to 75 from 80
    chassisdef_hunchback_HBK-4P.json - melee DMG to 75 from 80
    chassisdef_javelin_JVN-10F.json - fixed costs
    chassisdef_javelin_JVN-10N.json - fixed costs
    chassisdef_marauder_MAD-2R.json - FF armor/tonnage fix
    chassisdef_phoenixhawk_PXH-1b.json - fixed 1b from 1B
    chassisdef_raven_RVN-1X.json - fixed costs
    chassisdef_urbanmech_UM-R60L.json - fixed costs
    chassisdef_urbanmech_UM-R90.json - fixed costs
    chassisdef_vindicator_VND-1AA.json - fixed costs

### StreamingAssets/data/contracts/
All Escort and Capture Base contracts have had the word "Dropship" replaced with "DropShip" as used in the BT writers guide, a list too long to put here.  Listed here are all the other contracts that have been fixed.

    Assassinate_HardTarget.json - extra space removed
    c_fp_allianceDavion_b2_fireMission.json - DropShip formatting
    c_fp_allianceKurita_a2_fireMission.json - DropShip formatting
    c_fp_allianceKurita_b2_fireMission.json - DropShip formatting
    c_fp_allianceMarik_a2_fireMission.json - DropShip formatting
    c_fp_allianceMarik_b2_fireMission.json - DropShip formatting
    c_fp_allianceSteiner_a1_fireMission.json - DropShip formatting
    c_fp_allianceSteiner_b1_fireMission.json - DropShip formatting
    c_fp_headhunting_1_battle.json - Fixed "Flack Jackal" typo
    c_fp_longHunt_c1_rescue - Fixed improper 's after "lees's"
    c_fp_scoundrel_a1_target.json - DropShip formatting
    c_fp_unwelcomeGuests_1_fireMission.json - DropShip formatting
    EscortSingle_MerchantCaravan.json - Fixed typo "loacation" in short desc
    FireMission_DataLiberation.json - typos (Reinforments and DropShip)
    FireMission_DataLiberation_Hard.json - typos (Reinforments and DropShip)
    FireMission_FireForEffect.json - typos, too many to list here
    FireMission_Fireworks.json - "WarShip" changed to "Pocket WarShip" as no true WarShips should be available.
    FireMission_Untouchable.json - DropShip formatting
    Panzyr_Attack_Default.json - DropShip foramtting
    redHunt_1_DefendBase.json - Typos "Targetted" "Commmander" and "recieved" fixed
    redHunt_2_ThreeWayBattle.json - Typos, various
    SimpleBattle_RaidingParty.json - DropShip foramtting
    SimpleBattle_RaidingParty_Hard.json - DropShip foramtting
    Smithon_Defense_Default.json - DropShip foramtting
    Story_1B_Retreat_Default.json - DropShip formatting
    Story_6B_TreasureTrove_Default - DropShip formatting
    Story_7_GunboatDiplomacy_Default.json - DropShip formatting
    succession_1_assassinate.json - typos (commision and intitial)
    succession_a1_assassinate.json - typos (commision and intitial)
    ThreeWayBattle_ClashOfTitans.json - DropShip formatting
    ThreeWayBattle_HotPursuit.json - DropShip formatting
    ThreeWayBattle_InterceptedSalvage.json - DropShip formatting
    ThreeWayBattle_BountyHunting.json - DropShip formatting

### StreamingAssets/data/descriptions/Lore/
    LoreGreatHouses.json - ordered Houses "Around the Sphere"
    LoreSuccessorState.json - ordered Houses "Around the Sphere"

### StreamingAssets/data/events/
    event_mw_dubiousIntentions.json - "You" replaced with "You're" in results error
    event_mw_leadershipMoment.json - added contextual words to fix "they rises" error
    event_mw_nobleBonds.json - Fixed the gender reference instead of defaulting to their
    event_mw_smugglingOnPurpose.json - Missing space between "report[s]that" in option3 result
    event_mw_spotlight_dekker.json - Typo "recupterating", even dekker's event is injured...
    event_mw_triage.json - missing commas
    
### StreamingAssets/data/factions/
    faction_KellHounds.json - Demonym fixed missing space between "KellHounds"

### StreamingAssets/data/hardpoints/
    hardpointdatadef_phoenixhawk.json - Fixed MG underslung mount to always show
    
### StreamingAssets/data/heatsinks/
    Gear_HeatSink_Generic_Bulk-Bank.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Improved-Bank.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Standard-Bank.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Thermal-Exchanger-I.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Thermal-Exchanger-II.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Thermal-Exchanger-III.json - fixed [AMT] value in StatusEffect Description Details

### StreamingAssets/data/mech/
    mechdef_annihilator_ANH-1A.json - given Lance - Support tag
    mechdef_archer_ARC-2R.json - given Lance - Tank/Support tags
    mechdef_archer_ARC-2S.json - given Lance - Tank/Support tags
    mechdef_assassin_ASN-21.json - given Role - Scout and Lance - Assassin tags, duh
    mechdef_assassin_ASN-101.json - given Role - Scout and Lance - Assassin tags, duh
    mechdef_banshee_BNC-3S.json - fixed costs
    mechdef_battlemaster_BLR-1GB.json - Fixed 1Gb from 1GB
    mechdef_blackjack_BJ-1DB.json - fixed costs
    mechdef_blackknight_BL-6-KNT.json - fixed variant name to BK-7-KNT
    mechdef_blackknight_BL-6b-KNT.json - fixed reference to BK-7-KNT and 6b, moved DHS, fixed costs
    mechdef_bullshark_BSK-M3.json - given Lance - Support tag
    mechdef_cicada_CDA-2A.json - fixed costs
    mechdef_crab_CRB-27.json - given Role - Brawler and Lance - Tank tags, fixed costs
    mechdef_crab_CRB-27b.json - FF armor/tonnage fix, fixed 27b from 27B
    mechdef_cyclops_CP-10-HQ.json - given Lance - Support tag, removed duplicate IDF tag
    mechdef_cyclops_CP-10-Q.json - given Lance - Support tag, removed duplicate IDF tag, fixed costs
    mechdef_cyclops_CP-10-Z.json - given Lance - Support tag, removed duplicate IDF tag, fixed costs
    mechdef_flea_FLE-4.json - given Lance - Vanguard tag
    mechdef_flea_FLE-15.json - given Lance - Vanguard tag
    mechdef_griffin_GRF-4N.json - fixed JJ from Leg to Torso, moved DHS from illegal Leg slots to torsos to match "Greed"
    mechdef_griffin_GRF-4N_fp_greed.json - fixed JJ from Leg to Torso
    mechdef_hatchetman_HCT-3F.json - given Lance - Assassin tag, removed duplicate jumpOK tag, fixed costs
    mechdef_hatchetman_HCT-3X.json - given Lance - Assassin tag, removed duplicate jumpOK tag, fixed costs
    mechdef_highlander_HGN-732b.json - Adjusted Torso Front Armor to match Record Sheets, 1b from 1B typos
    mechdef_highlander_HGN-733.json - Adjusted Center Torso Front Armor to match Record Sheets, allocated "spare" armor point to CTR
    mechdef_highlander_HGN-733P.json - Adjusted Torso Front Armor and HS+ammo locations to match Record Sheets
    mechdef_javelin_JVN-10A.json - given Role - Sniper tag
    mechdef_javelin_JVN-10F.json - Removed "Fire" from UIname for sorting, given Lance - Assassin/Vanguard tags, removed duplicate jumpOK tag, fixed costs
    mechdef_javelin_JVN-10N.json - given Lance - Assassin/Vanguard tags, removed duplicate jumpOK tag, fixed costs
    mechdef_marauder_MAD-2R.json - FF armor/tonnage fix, put ERPPC hardpoint on top of MLs
    mechdef_marauder_MAD-3D.json - given Lance - Tank/Support tags, put PPC hardpoint on top of MLs
    mechdef_marauder_MAD-3R.json - given Lance - Tank/Support tags, put PPC hardpoint on top of MLs
    mechdef_phoenixhawk_PXH-1.json - given Role - Scout and Lance - Assassin/Vanguard tags
    mechdef_phoenixhawk_PXH-1b.json - fixed 1b from 1B
    mechdef_phoenixhawk_PXH-1K.json - given Role - Scout and Lance - Assassin/Vanguard tags
    mechdef_rifleman_RFL-3C.json - given Role - Sniper and Lance - Support tags
    mechdef_rifleman_RFL-3N.json - given Role - Sniper and Lance - Support tags
    mechdef_rifleman_RFL-4D.json - given Role - Sniper and Lance - Support tags
    mechdef_urbanmech_UM-R60L.json - given Lance - Tank tag
    mechdef_vulcan_VL-2T.json - given Lance - Vanguard tag
    mechdef_vulcan_VL-5T.json - given Role - Scout and Lance - Assassin/Vanguard tags
    mechdef_warhammer_WHM-6D.json - given Lance - Tank/Support tags
    mechdef_warhammer_WHM-6R.json - given Lance - Tank/Support tags
    
### StreamingAssets/data/milestones/
    All 144 milestone files have cost, rarity and purchasable lines removed for loading/logging readability.
    
### StreamingAssets/data/movement/
    movedef_PACKRAT.json - max walk 210 from 200
    movedef_GALLANT.json - slowed down Gallant to TT speeds

### StreamingAssets/data/pilot/
The pilot files below had missing passive traits per their skill points.  Any missing passive traits have been added to conform to the standard progressions.  Story pilots with more than the normal amount of abilities/traits have been retained, but their passive traits have been brought up to standard.

    pilot_contract_TheProfessional.json
    pilot_cvs1_bullhorn.json
    pilot_cvs2_gargoyle.json
    pilot_cvs3_myrmidon.json
    pilot_cvs4_overload.json
    pilot_d10_BL_myrmidon.json
    pilot_d10_skirmisher.json
    pilot_d10_striker.json
    pilot_d10_vanguard.json
    pilot_fp_Beta.json
    pilot_fp_Diva.json
    pilot_fp_DominikZhao.json
    pilot_fp_KellHound_1.json
    pilot_fp_KellHound_2.json
    pilot_fp_MorganKell.json
    pilot_fp_OrchidZhao.json
    pilot_fp_StienerLongRoad.json
    pilot_fp_Talon.json
    pilot_fp_Valravn.json
    pilot_fp_steelBeast.json
    pilot_privbeta_gn2-pl8-gt4-tc2.json
    pilot_privbeta_gn3-pl5-gt3-tc5.json
    pilot_privbeta_gn4-pl4-gt4-tc4.json
    pilot_privbeta_gn4-pl4-gt6-tc6.json
    pilot_privbeta_gn5-pl3-gt5-tc3.json
    pilot_privbeta_gn5-pl5-gt5-tc5.json
    pilot_privbeta_gn8-pl2-gt4-tc2.json
    pilot_sim_starter_behemoth_d4.json
    pilot_sim_starter_behemoth_d6.json
    pilot_sim_starter_medusa_d4.json
    pilot_sim_starter_shoe.json
    pilot_sim_starter_trigger.json
    pilot_story_KameaGuard1.json
    pilot_story_KameaGuard2.json
    pilot_story_SLDFAI.json
    pilot_story_VictoriaEnd.json
    pilot_story_kamea.json
    pilot_story_kamea_end.json
    pilot_story_mastiff.json
    pilot_uw_siegebreaker1.json
    pilot_uw_siegebreaker2.json
    pilot_uw_siegebreaker3.json
    pilot_uw_siegebreaker4.json

### StreamingAssets/data/regions/
    regionDef_Positive.json - typo (Positve)

### StreamingAssets/data/starsystem/
    starsystemdef_Camadeirre.json - fixed typo: "Camadeirre" change to "Camadeierre"
    
### StreamingAssets/data/turrets/
    turretdef_Standard_Laser.json - renamed "Standard Laser Turret" from "Light Standard Turret"
    
### StreamingAssets/data/upgrades/
    Gear_General_Enhanced_Missilery_System.json - Corrected displayed SRM bonus to 50% STB DMG per stat value

### StreamingAssets/data/vehicle/
    vehicledef_BULLDOG.json - added Front MG and ammo
    vehicledef_DEMOLISHER.json - added missing 4th ton of AC/20 ammo
    vehicledef_GALLANT.json - fixed armor to TT values, LRM hardpoint slot adjustment
    vehicledef_MOBILEHQ_ARMORED.json - fixed armor to match TT values
    vehicledef_SCORPION.json - moved MG from Turret to Front
    vehicledef_STRIKER.json - fixed value: Turret Armor 120 changed to 110, fixed IS to 20 from 10
    vehicledef_STRIKER_Narc.json - fixed IS to 20 from 10
    vehicledef_SWIFTWIND_ARMORED.json - fixed tonnage and armor to match possible TT config

### StreamingAssets/data/vehicleChassis/
    vehiclechassisdef_GALLANT.json - fixed weight class to Heavy
    vehiclechassisdef_MANTICORE.json - fixed armor and internals
    vehiclechassisdef_SCORPION - moved AP hardpoint from Turret to Front
    vehiclechassisdef_STRIKER.json - fixed armor and internals
    vehiclechassisdef_STRIKER_Narc.json - fixed IS to 20 from 10
    vehiclechassisdef_SWIFTWIND.json - fixed armor and internals
    vehiclechassisdef_SWIFTWIND_ARMORED.json - fixed Tonnage and armor and internals

### StreamingAssets/data/weapon/
    Weapon_Gauss_Gauss_1-M7.json - tag fixes
    Weapon_Gauss_Gauss_2-M9.json - tag fixes
    Weapon_Laser_LargeLaserER_1-Blankenburg25.json - tag fixes
    Weapon_Laser_LargeLaserER_2-BlazeFire.json - tag fixes
    Weapon_Laser_LargeLaserPulse_1-Thunderbolt12.json - tag fixes
    Weapon_Laser_LargeLaserPulse_2-Exostar.json - tag fixes
    Weapon_Laser_MediumLaserER_1-MagnaVI.json - tag fixes
    Weapon_Laser_MediumLaserER_2-BrightBloom.json - tag fixes
    Weapon_Laser_MediumLaserPulse_1-RakerIV.json - tag fixes
    Weapon_Laser_MediumLaserPulse_2-Magna400P.json - tag fixes
    Weapon_Laser_SmallLaserER_1-Diverse_Optics.json - tag fixes
    Weapon_Laser_SmallLaserER_2-BlazeFire.json - tag fixes
    Weapon_Laser_SmallLaserPulse_1-Maxell.json - tag fixes
    Weapon_Laser_SmallLaserPulse_2-Magna200P.json - tag fixes
    Weapon_PPC_PPCER_1-MagnaFirestar.json - tag fixes
    Weapon_PPC_PPCER_2-TiegartMagnum.json - tag fixes
