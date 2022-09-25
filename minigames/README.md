-all logic should be prefixed with mg_name, to make templating easier
-filters prefix with fil_name
-templates prefix with template_mg_name
-minigame door/entry side should be divisble by 128. Recommended: 512, 640, 768, 896, 1024 ...
-red side door texture should be transparent, blue side opaque
-don't include the announcer countdown ambient_generic, just make the logic for it (name: mg_countdown_3, Trigger input)
-only default assets should be used for the public .vmfs, custom could be included in the released .bsp
-texture ideally should be set to World and Shift to 0. If possible, scale 0.25 as well
-door height: 128 hu
-(optional) light color: 254 210 152, brightness: 100 to 1600
-(optional) avoid teleports for blue side
(Decided against using editor_text for explanations, less time consuming for players to just figure out the logic on their own or contact the mapping group with questions)
 

Goals:
-50 edicts/minigame max so fitting the list above is possible
-optimize brushwork for vvis
-minimize lights so vrad doesn't take too long 

