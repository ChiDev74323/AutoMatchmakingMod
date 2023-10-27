# Auto Matchmaking Mod
**A mod for Titanfall 2 that makes matchmaking a lot easier!**

## How To Install And Setup The Auto Matchmaking Mod
You can install the mod by downloading the `AutoMatchmakingModInstaller.bat` from the latest release and running it in your Titanfall 2 installalation location. This can be found through Steam/Origin/EA Desktop. After that just launch the `Titanfall2Launcher.bat` file created in your Titanfall 2 installation location and you're good to go!

## What The Auto Matchmaking Mod Does
Once you have the Auto Matchmaking Mod installed, it will automatically reconnect you to the multiplayer matchmaking menu when you freeze in it and if you were matchmaking when you froze then it'll start matchmaking as soon as you reconnect.

## How to matchmake in parties
To matchmake in a party with the mod, you'll first have to ensure that you and the people you are stacking with are all using the same network/community/clan. After that, you'll also want to ensure you're all set to the same region in the main menu, this way network invites show up for everyone in your party. Now you have to set the convar `am_enabled` to either `2` or `3` depending on whether you plan on being the party leader or a party member. If you are going to be the party leader, set `am_enabled` to `2`, if you are going to be a party member then set `am_enabled` to `3`. After this, you can launch multiplayer at the same time as your friends. If everything was setup correctly, then you'll all end up matchmaking in a party.

If someone leaves the party manually or gets disconnected because they're in a different mp_lobby instance, then the mod will recreate the party.

<hr>

**Keep in mind that if the mod disconnects you from the multiplayer matchmaking menu and doesn't appear to be reconncting you that's normal.** Just wait and make sure you don't click any buttons in the main menu while you're waiting and it'll reconnect you eventually. If you do click any buttons in the main menu while you're waiting for it to connect you it will stop trying to connect you and you'll have to click the launch multiplayer button yourself (so it's best to just wait for it to connect for you since it'll take the same amount of time either way)

## ConVars
- `am_enabled` - This ConVar is just whether to automate matchmaking or not. If it's set to 1 then when you get reconnected the mod will restart matchmaking for you if you were matchmaking when you got reconnected. If it's set to 2, then you are set as a party leader. When you connect to an mp_lobby the mod will send a network invite. If it's set to 3, then you are set as a party member. When you connect to an mp_lobby the mod will attempt to join a network invite.
- `am_matchmaking` - This ConVar is just how the mod is able to remember if you were matchmaking or not when you get reconnected to the multiplayer matchmaking menu. The mod **should** handle changing this itself so you shouldn't ever need to change it yourself.
