# [NMRiH] Team Healing

Allows survivors to share medical supplies and heal each other!


## Healing 
Equip a first aid kit or bandages and hold USE (Default: `E`) on another player to treat them. Team healing is slightly faster than self healing by default. Players can break out of healing by crouching.

<img src="https://user-images.githubusercontent.com/11559683/123883869-44b7a900-d920-11eb-821e-a109f5c0f3d0.png" height="400">


## Sharing supplies
Equip a medical supply and use secondary attack (Default: Right-click) on another player to give it to them.

<img src="https://user-images.githubusercontent.com/11559683/130325710-7889c61b-49b5-4895-85ce-866f48c0f4fd.png" height="400">


## Opting out

Players can opt out of healing or sharing via `sm_settings` -> `Medical Settings`

![image](https://user-images.githubusercontent.com/11559683/130325851-eefe4c67-dd4d-4abe-b07f-c2ee71024e65.png)

## Translations

All messages in this plugin can be translated via `translations/team-healing.phrases.txt`. See [Translations File Format](https://wiki.alliedmods.net/Translations_(SourceMod_Scripting)#File_Format)

## CVars:

Cvars are saved to `cfg/sourcemod/plugin.teamheal.cfg`, which is autogenerated when the plugin is first loaded.

- `sm_team_heal_first_aid_time` (Default: 8.1)
  - Seconds it takes for a first aid kit to heal a teammate.
- `sm_team_heal_bandage_time` (Default: 2.8)
  - Seconds it takes for bandages to heal a teammate.
- `sm_team_heal_max_use_distance` (Default: 50.0)
  - Maximum distance from a player for medical actions to work

## Unsupported features
- Modded medical weights, such as bandages that weight 40g instead of the default 35g
