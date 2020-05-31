# CK2PGGMod

**Not Ironman Compatible**

**Checksum in 3.3.3 - BEBS**

Main focus is changes in defines.lua values (PGG locally sourced)
and integration of the Community Patch (3.3.2.1) by LaTuer and other contributors. In the launcher it will be called .CK2 PGG Mod (at the top).

In v2 MTR was integrated

**Community Patch forum link**
https://forum.paradoxplaza.com/forum/threads/mod-community-patch.1274314/

**MTR - Medieval Trade Routes 4 Vanilla v2.22** 
https://www.moddb.com/mods/mtr-medieval-trade-routes-4-vanilla/downloads/mtr-4-vanilla

# 1.0 PGG defines.lua changes

"#D x" - means the original value

## NMilitary 

CRUSADE_MAX_POT_SHARE = 0.1, #D 0.2
It is not possible to receive more than this from the Crusade pot. If there's too few qualifying participants to distribute the full pot, any remainder goes to the Crusader King

WAR_CONTRIBUTION_OCCUPATION_PER_DAY = 18, #D 10
Occupying a Holding gives this Contribution score per day 

WAR_CONTRIBUTION_BATTLE_PER_DAY = 0.14, #D 0.20
Every day in battle, a participant gets this. 

WAR_CONTRIBUTION_PROVINCE_WITHOUT_SETTLEMENT_OCCUPATION_PER_DAY = 5, #D 3
Occupying a province without settlements gives this score per day, multiplied by the number of empty holdings

NOMAD_PROVINCE_WAR_CONTRIBUTION_MULTIPLIER = 2, #D 3
War Contribution multiplier for occupied provinces without holdings from nomad holders

CAPITAL_WARSCORE_MULTIPLIER = 1.5, #D 1
Warscore multiplier for capital(this is scaled with SETTLEMENT_WARSCORE_MULTIPLIER)

SETTLEMENT_WARSCORE_MULTIPLIER = 0.5, #D 0.3
Warscore worth for occupied private demesne

ARMY_MOVEMENT_SPEED = 5, #D 3
Base movement speed of land units

CRUSADER_KING_ARTIFACTS = 3 #D 2
The Crusader King gets this many artifacts

CRUSADERS_GET_EXTRA_ARTIFACTS = 5 #D 2
The top <NUM> participants get one extra artifact each

## NTechnology 

BASE_NEIGHBOUR_SPREAD_BONUS = 0.06, #D 0.03
Bonus for each neighbour with the tech

## NAI #
STATECRAFT_THREAT_THRESHOLD = 45.0, #D 50
If threat from realm is greater or equal to threshold then Chancellor will be assigned to Statecraft job

