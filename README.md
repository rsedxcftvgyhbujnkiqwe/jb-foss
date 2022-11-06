# jb-foss
A free and open source jailbreak map, utilizing heavy optimization, with self imposed restrictions. Developed by blank and gusic.

See [the license](LICENSE) for information about reusing any vmfs in this repository.

## Things to know
This map was created using the following. 
- Hammer++
- Spud FGD

This map was compiled using the following. (NOTE!: add compile flags here once map releases
- (?)Ficool2 modded VBSP
- (?)Slammin VVIS
- (?)VRAD multithreading patch

## Goals
- Allow the map to be free, open source, and customizeable. All minigames are separated into instances and in their own vmfs. This way, anyone who wants to remix the map can easily change the minigames out, or simply download a vmf for a specific game without having to decompile the map.
- Make minigames as interactive as possible
- Save as many edicts as can be saved, and use as few logic entities as possible. Games should achieve their intended purpose as efficiently as possible, using the minimum number of required edicts.
- All games are limited to use a maximum of 50 edicts, games must be templated to prevent edict consumption when not in use, and games should have proper vis optimization. Minigames exceeding 50 edicts go to minigames_big.
- Utilize no custom materials whatsoever. No custom textures, sounds, or props. This way, the map is accessible to anyone.

