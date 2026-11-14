# Plague Watch (early trial)

A 1 to 4 player co-op game. You and your friends are the last town guards in a plagued medieval town, and one of you might already be bitten.

Hold the town as long as you can. By day you check villagers for hidden bites, give them jobs, haul food, bar doors and set traps, and find time to sleep. By night the dead come at the gates in waves and you fight them in the streets. Every fifth night a beast comes with the horde.

A bitten guard can confess and ask for the one scarce cure, take the jail cell and come back as a fresh recruit, or hide it, listen to the voice from below, and quietly bring the town down.

Bring the beast down and the watch can ring the stand-down bell the next morning to end the run as a win. A guard who lives to win is yours again next run, with everything they learned. Skills are practised at the training yard and mastered for good by using them well.

This is a rough early trial. Expect bugs and placeholder sound.

## Download

Get the zip from the [latest release](../../releases/latest), unzip everything into one folder, and run `PlagueWatch.exe`.

- Windows 64-bit only.
- Keep `PlagueWatch.pck` next to the exe. It holds the game.
- The build is unsigned, so Windows may show a warning the first time you run it.
- `PlagueWatch.console.exe` is the same game with a log window, handy for bug reports.

## Playing together

- One player picks Host. Everyone else picks Join and types the host's IP address.
- The host needs UDP port 24680 open or forwarded on their router.
- Up to 4 players. You can also play alone.

## Controls

Keyboard and mouse. A gamepad also works.

| Key | Action |
|---|---|
| WASD | Move |
| Mouse | Look |
| Left click | Attack, hold to charge |
| Right click | Shield, or shove kick with weapons that have no shield |
| Space | Jump, press again in the air for a second jump |
| Shift | Roll, hold to sprint |
| Ctrl | Slide |
| E | Use or interact |
| F | Pick up, carry, throw (items, the fallen dead, a downed friend) |
| Q | Use the carried item, or rest when your hands are empty |
| T | Talk |
| R | Give a villager a job |
| C | Accuse a villager, or vote on a guard |
| V and B | Skills, practised at the training yard in the south-west corner |
| G | Ping for the team |
| Tab | Stats and move list |
| Esc | Pause |
| F10 | Screen filter |
| F11 | Fullscreen |

Weapons hang on the racks at the armoury, between the barracks and the workshop.

## Credits

- 3D art: KayKit by Kay Lousberg (CC0)
- Sound: Kenney (CC0)
- UI kit and fonts: Dead Revolver (Pixel UI & HUD, Pixel Font Pack)
- Made with [Godot Engine](https://godotengine.org/license) 4.7.2 (MIT licence)

This repository holds the trial build only, not the source.
