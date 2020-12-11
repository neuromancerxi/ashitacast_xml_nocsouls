# Example AshitaCast XMLs 
A Collection of Ashitacast XML used on Nocturnal Souls FFXI

In this repository you will find a collection of AshitaCast XMLs that I use on [Nocturnal Souls](https://nocturnalsouls.net). Most of these .xml are straight forward, and are noted with comments. Most come with rebinds for F9 to toggle your weapon (e.g. RNG between Archery and Marksmanship, PLD between Almace and Burtgang).

Some jobs have special logic included (BRD is heavily customized to allow for one button song casting), but most are just simple templates to give you a starting point (TP Set, WS Set, MACC Set, etc). There is also an examples folder with basic ashitacast examples to help beginners with basic usage.

Some examples of special use:

Most Jobs have Mode Toggles F9 and F12 to toggle between combat modes and weapon.

All Jobs have one button med use (F10) which will display your current Combat Mode/Weapon and use Echo Drops, Hallowed Water, or Panacea depending on debuffs active.

Most Jobs have level detection to scale down when below level 99 (BCNMs etc). Most Mages also have additional logic for uncapped, Level 71-98, level 51-70, and level 50.

An example for a NG+ tailored .xml is also included (webjester_noob.xml).

BRD - Has custom commands for songs to allow single button song casting (e.g. /minuet will start at Minuet 5, and work down to 4, 3, and 2, then reset to 5.)

PLD - Has some Blue Enmity generating spells in a one button /command.

THF - F9 Will toggle between Standard, Defensive, TH, and THMAX Modes depending on your use case. THMAX will TP and WS in max TH Gear.

General Questions can be directed to the [Nocturnal Souls Discord](https://discord.gg/swnTWUv) in #job_qa.

As always, .xml are provided as-is with no warranty expressed or implied. You're on your own from here. Good Luck!
