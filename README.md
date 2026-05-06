# reflect.codes / ecstasy.vip
reflect.codes ai larp fixed src

fixed inject crash because of steam game overlay hooking
rest is unfixed, like:

- Legitbot not selecting target 50% of the time
- Auto align pixel surf not working
- Local animation fix is broken
- Cheat crashing on loading skins
- Cheat crashing on updateClientsideAnimations
- Ragebot does not properly select targets in free for all mode
- Tickbase causes prediction errors
- Hideshots does not work as intended
- Animation resolver does not select proper side
- Lag compensation does not re-calculate some networked variables properly
- LUA is extremely prone to crashing especially while drawing
- Compiler error in Recorder.cpp world_circle lambda expression
- Jumpbug does not work properly 90% of the time
- Keybinds constantly changing when selected
- Leaking handles on thread creation
- Autowall trash

greetz to voidzero666 and the rest of the reflect/ecstasy team for the original src.
