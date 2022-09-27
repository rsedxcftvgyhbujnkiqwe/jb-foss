# Usage guide
This page contains all the minigame vmfs. Since games are not intended to be compiled on their own, if you wish to solo test a game you will need to ensure the game is cordoned, and at least one info_player_teamspawn entity exists (most likely in blue side).

Many games with buttons will not function unless players are in the playable area, for optimization purposes. If you wish to test a game, ensure that any logic related to this is hidden/removed before compiling.

# Game creation requirements 
- All logic should be prefixed with mg_<game name>, to make templating easier
- Filters prefix with fil_name
- Templates prefix with mg_template_<game name>
- Minigame door/entry side should be divisble by 128. Recommended: 512, 640, 768, 896, 1024 ...
- Red side door texture should be transparent, blue side opaque (if blue side door required)
- Don't include the announcer countdown ambient_generic, just make the logic for it (name: mg_countdown_3, Trigger input)
- Texture ideally should be set to World and Shift to 0. If possible, scale 0.25 as well
- (optional) light color: 254 210 152, brightness: 100 to 1600
- (optional) avoid teleports for blue side
- 50 edicts/minigame max so fitting the list above is possible
- Optimize brushwork for vvis
- Minimize lights so vrad doesn't take too long 
