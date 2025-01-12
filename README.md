![LeadBot](https://repository-images.githubusercontent.com/188332969/93320b00-7d8a-11e9-95ab-8ec570917423)
## :robot:Player AI Bots to revive obscure gamemodes in Garry's Mod:robot:
#### Current State: Alpha
### Installation
Download LeadBot from [here](https://github.com/LeadKiller/leadbot/archive/master.zip), and drop leadbot-master into the addons folder.
### Currently Supported Gamemodes:
 - Sandbox
 - [nZombies Unlimited](https://github.com/Zet0rz/nZombies-Unlimited)
 - [Darkest Days](https://steamcommunity.com/sharedfiles/filedetails/?id=823262022)
 - [Stop it, Slender!](https://steamcommunity.com/sharedfiles/filedetails/?id=171728689)
 - [DOGFIGHT: Arcade Assault](https://steamcommunity.com/sharedfiles/filedetails/?id=288399121)
 - [Hover Gear Legacy](https://steamcommunity.com/sharedfiles/filedetails/?id=104516229)
 - [Zombie Plague](https://github.com/Nicholas-Fuchs/zombieplague)
 - [Assassins](https://steamcommunity.com/sharedfiles/filedetails/?id=834782562)
 - [Super Cooking Panic](https://steamcommunity.com/sharedfiles/filedetails/?id=2180715133)
 - [Cave Fight](https://github.com/Tripperful/cavefight/)
 - [The Hidden](https://steamcommunity.com/sharedfiles/filedetails/?id=443458575)
 - [Slashers](https://steamcommunity.com/sharedfiles/filedetails/?id=1092007703)
 - [Slave of GMod](https://steamcommunity.com/sharedfiles/filedetails/?id=249207064)
 - [Team Fortress 2 Gamemode](https://github.com/moddage/tf2-gamemode)
 - [Cinema](https://steamcommunity.com/workshop/filedetails/?id=143148073)
 - [Quake 3](https://steamcommunity.com/sharedfiles/filedetails/?id=160207505)
 - [Slayer](https://steamcommunity.com/sharedfiles/filedetails/?id=1336605119)
 - [Other Gamemodes](https://github.com/LeadKiller/leadbot/projects/1)
 
 This fork adds:
 - [Five Nights at Freddy's](https://steamcommunity.com/sharedfiles/filedetails/?id=408243366) (Still being worked on)
 - [Alien: Isolation](https://steamcommunity.com/sharedfiles/filedetails/?id=473858472) (Still being worked on)
### Commands/Convars
 - leadbot_add [1-128]
 - leadbot_afk
 - leadbot_kick _[name/all]_
 - leadbot_quota _[0-128]
 - leadbot_strategy _[0/1]_
 - leadbot_afk_timetoafk _[0-300]_
 - leadbot_fakeping _[0/1]_ *Using this outside of Singleplayer/LAN/nomaster servers could get you banned/blacklisted!*
 - leadbot_name_prefix _[prefix]_
 - leadbot_names _[name1,name2]_
 - leadbot_voice _[voiceset]_
 - leadbot_fov _[75-100]_
 
This fork adds:
( Note: some of the convars will only work on Sandbox, unless if the gamemode was made by me! Futurely might work on some gamemodes made by the LeadBot creators. )
 - leadbot_stop _[0/1]_ (Bots stops thinking.)
 - leadbot_move _[0/1]_ (Bots won't move and shoot but will still think.)
 - leadbot_weapons _[weapons name]_ (Inserts each weapon name per comma for the bots to select randomly between them. (Ex.:leadbot_weapons 'weapon_crowbar,weapon_pistol,weapon_ar2,weapon_frag'))
 - leadbot_forceWeapon _[0/1]_ (Force bots to keep a weapon that you was holding if you went AFK) (NOTE:This was experimental and still not working as it should.)
 - leadbot_tp _[1 = Teleports them into your exact pos, 0 = Teleports them near you with a couple of distance]_ (Teleports all the Leadbot bots near your position) (Ex.: leadbot_tp 1)
 - leadbot_test (Experimental/Testing/Debugging when working with the bots. It was intended to list all entities running in the game for when I was coding.)
 - leadbot_test2 (Experimental/Testing/Debugging when working with the bots. It was intended to show which type of weapon is the one you're holding, like ar2, shotguns, pistol, grenades, knife, etc. to let me know some weapons hold type.)
  - leadbot_separatebyteams (Experimental/Fun when I was trying to work on teams. I'd highly recommend https://steamcommunity.com/sharedfiles/filedetails/?id=2311549692 now though if you wish to do team battles with them.)
  - leadbot_movetome _[Team index]_ (Makes all bots from specific team move into your current position. (Ex: leadbot_movetome 1)
  
 ### Issues
You can submit issues on the [Discord](https://discord.gg/PJByEaPgTq) or through [issues](https://github.com/LeadKiller/leadbot/issues)
