# Culprits Admin Client (BETA)
# To See Commands Use ;cmds
# Wait 30 Seconds Before Using!

## status: Online

## script load:
```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/conflictedtarget/Culprits-Admin-Client/refs/heads/main/Culprits-Admin.lua'))()
```
## commands:
```
		'[-] cmdbar is shown when ; is pressed.', -- (removed this)
		'[1] kill [plr] -- You need a tool! Will kill the player, use rkill to kill you and player',
		'[2] bring [plr] -- You need a tool! Will bring player to you',
		'[3] spin [plr] -- You need a tool! Makes you and the player spin crazy',
		'[4] unspin -- Use after using spin cmd and dying, so you stop loop teleporting',
		'[5] attach [plr] -- You need a tool! Attaches you to player',
		'[6] unattach [plr] -- Attempts to unattach you from a player',
		'[7] follow [plr] -- Makes you follow behind the player',
		'[8] unfollow',
		'[9] freefall [plr] -- You need a tool! Teleports you and the player up into the air',
		'[10] trail [plr] -- The opposite of follow, you stay infront of player',
		'[11] untrail',
		'[12] orbit [plr] -- Makes you orbit the player',
		'[13] unorbit',
		'[14] fling [plr] -- Makes you fling the player',
		'[15] unfling',
		'[16] fecheck -- Checks if the game is FE or not',
		'[17] void [plr] -- Teleports player to the void',
		'[18] noclip -- Gives you noclip to walk through walls',
		'[19] clip -- Removes noclip',
		'[20] speed [num]/ws [num] -- Changes how fast you walk 16 is default',
		'[21] jumppower [num]/jp [num] -- Changes how high you jump 50 is default',
		'[22] hipheight [num]/hh [num] -- Changes how high you float 0 is default',
		'[23] default -- Changes your speed, jumppower and hipheight to default values',
		'[24] annoy [plr] -- Loop teleports you to the player',
		'[25] unannoy',
		'[26] headwalk [plr] -- Loop teleports you to the player head',
		'[27] unheadwalk',
		'[28] nolimbs -- Removes your arms and legs',
		'[29] god -- Gives you FE Godmode',
		'[30] drophats -- Drops your accessories',
		'[31] droptool -- Drops any tool you have equipped',
		'[32] loopdhats -- Loop drops your accessories',
		'[33] unloopdhats',
		'[34] loopdtool -- Loop drops any tools you have equipped',
		'[35] unloopdtool',
		'[36] invisible -- Gives you invisibility CREDIT TO TIMELESS',
		'[37] view [plr] -- Changes your camera to the player character',
		'[38] unview',
		'[39] goto [plr] -- Teleports you to player',
		'[40] fly -- Allows you to fly, credit to Infinite Yield',
		'[41] unfly',
		'[42] chat [msg] -- Makes you chat a message',
		'[43] spam [msg] -- Spams a message',
		'[44] unspam',
		'[45] spamwait [num] -- Changes delay of chatting a message for the spam command in seconds default is 1 second',
		'[46] pmspam [plr] -- Spams a player in private message',
		'[47] unpmspam',
		'[48] cfreeze [plr] -- Freezes a player on your client, they will only be frozen for you',
		'[49] uncfreeze [plr]',
		'[50] unlockws -- Unlocks the workspace',
		'[51] lockws -- Locks the workspace',
		'[52] btools -- Gives you btools that will only show to you useful for deleting certain blocks only for you',
		'[53] pstand -- Enables platform stand',
		'[54] unpstand -- Disables platform stand',
		'[55] blockhead -- Removes your head mesh',
		'[56] sit',
		'[57] bringobj [obj] -- Only shows on client, brings an object/part to you constantly, can be used to bring healing parts, weapons, money etc, type in exact name',
		'[58] wsvis [num] -- Changes visibility of workspace parts, num should be between 0 and 1, only shows client sided',
		'[59] hypertotal -- Loads in my FE GUI Hypertotal',
		'[60] cmds -- Prints all commands',
		'[61] rmeshhats/blockhats -- Removes the meshes of all your accessories aka block hats',
		'[62] rmeshtool/blocktool -- Removes the mesh of the tool you have equipped aka block tool',
		'[63] spinner -- Makes you spin',
		'[64] nospinner',
		'[65] reach [num] -- Gives you reach, mostly used for swords, say ;reachd for default and enter number after for custom',
		'[66] noreach -- Removes reach, must have tool equipped',
		'[67] rkill [plr] -- Kills you and the player, use kill to just kill the player without dying',
		'[68] tp me [plr] -- Alternative to goto',
		'[69] cbring [plr] -- Brings player infront of you, shows only on client, allows you to do damage to player',
		'[70] uncbring',
		'[71] swap [plr] -- You need a tool! Swaps players position with yours and your position with players',
		'[72] givetool [plr] -- Gives the tool you have equipped to the player',
		'[73] glitch [plr] -- Glitches you and the player, looks very cool',
		'[74] unglitch -- Unglitches you',
		'[75] grespawn -- Alternative to normal respawn and usually works best for when you want to reset with FE Godmode',
		'[76] explorer -- Loads up DEX',
		'[77] reset -- Resets your character.',
		'[78] anim [id] -- Applies an animation on you, must be created by ROBLOX',
		'[79] animgui -- Loads up Energize animations GUI',
		'[80] savepos -- Saves your current position',
		'[81] loadpos -- Teleports you to your saved position',
		'[82] bang [plr] -- 18+ will not work if you have FE Godmode on',
		'[83] unbang',
		'[84] delcmdbar -- Removes the command bar completely',
		'[85] bringmod [obj] -- Brings all the parts in a model, client only, comes from ;bringobj enter exact name of model',
		'[86] shutdown -- Uses harkinians script to shutdown server',
		'[87] respawn -- If grespawn doesnt work you can use respawn',
		'[88] delobj [obj] -- Deletes a certain brick in workspace, client sided',
		'[89] getplrs -- Prints all players in game',
		'[90] deldecal -- Deletes all decals client sided',
		'[91] opfinality -- Loads in my FE GUI Opfinality',
		'[92] remotes -- Prints all remotes in the game in the console when added',
		'[93] noremotes -- Stops printing remotes',
		'[94] tpdefault -- Stops all loop teleports to a player',
		'[95] stopsit -- Will not allow you to sit',
		'[96] gosit -- Allows you to sit',
		'[97] clicktp -- Enables click tp',
		'[98] noclicktp -- Disables click tp',
		'[99] toolson -- If any tools are dropped in the workspace you will automatically get them',
		'[100] toolsoff -- Stops ;toolson',
		'[101] version -- Gets the admin version',
		'[102] state [num] -- Changes your humanoid state, ;unstate to stop.',
		'[103] gravity [num] -- Changes workspace gravity default is 196.2',
		'[104] pgs -- Checks if the game has PGSPhysicsSolverEnabled enabled',
		'[105] clickdel -- Delete any block you press q on, client sided',
		'[106] noclickdel -- Stops clickdel',
		'[107] looprhats -- Loop removes mesh of your hats/loop block hats',
		'[108] unlooprhats -- Stops loop removing mesh',
		'[109] looprtool -- Loop removes mesh of your tool/loop block tools',
		'[110] unlooprtool -- Stops loop removing mesh',
		'[111] givealltools [plr] -- Gives all the tools you have in your backpack to the player',
		'[112] age [plr] -- Makes you chat the account age of the player',
		'[113] id [plr] -- Makes you chat the account ID of the player',
		'[114] .age [plr] -- Privately shows you the account age of the player',
		'[115] .id [plr] -- Privately shows you the account ID of the player',
		'[116] gameid -- Shows the game ID',
		'[117] removeinvis -- Removes all invisible walls/parts, client sided',
		'[118] removefog -- Removes fog, client sided',
		'[119] disable -- Disables your character by removing humanoid',
		'[120] enable -- Enables your character by adding humanoid',
		'[121] prefix [key] -- Changes the prefix used, default is ;',
		'[122] ;resetprefix -- Resets the prefix to ; incase you change it to an unusable prefix. Say exactly ";resetprefix" to do this command, no matter what your prefix is set to.',
		'[123] flyspeed [num] -- Change your fly speed, default is 1',
		'[124] carpet [plr] -- Makes you a carpet for a player, will not work if FE Godmode is on',
		'[125] uncarpet -- Stops carpet player',
		'[126] stare [plr] -- Turns your character to stare at another player',
		'[127] unstare -- Stops stare player',
		'[128] logchat -- Logs all chat (including /e and whispers) of all players',
		'[129] unlogchat -- Disables logchat',
		'[130] fixcam -- Fixes/resets your camera',
		'[131] unstate -- Stops changing state',
```
