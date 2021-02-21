# 0 A.D. is Actually Before Christ
**0abc**, a modification of “0 A.D. Empires Ascendant”, version 0.0.24 “Alpha XXIV: Xšayāršā” (IPA: /xʃajaːr̩ʃaː/ Old Persian: 𐎧𐏁𐎹𐎠𐎼𐏁𐎠).



## Table of contents
* [Instructions](https://github.com/0abc/0abc-a24#instructions)
* [Overview](https://github.com/0abc/0abc-a24#overview)
* [New unit costs](https://github.com/0abc/0abc-a24#new-unit-costs)



## Instructions
* Download the zip or `git clone` this repository (`https://github.com/0abc/0abc-a24.git`).
* Place it in your `/0ad/mods/` folder:
  * GNU/Linux (e.g. Fedora) typically: `~/.local/share/0ad/mods/`
  * Apple macOS typically: `~/Library/Application\Support/0ad/mods/`
  * Microsoft Windows typically: `~\Documents\My Games\0ad\mods\`
* Launch 0 A.D., click “Settings” and “Mod Selection”.
* Select `0abc`, click “Enable” and “Save Configuration”.
* Add, remove, or move up or down any other mods, click “Save Configuration” and “Start Mods”.
* Click “Learn To Play” and “Structure Tree” to see the mod(s) implemented.
* For more detailed information, please have a look at **0abc-readme.pdf**.

[(return to table of contents)](https://github.com/0abc/0abc-a24#table-of-contents)



## Overview
* Attack damage is randomized, between 50% and 150% of the displayed value, to add a bit more unpredictability to the game.
* A new damage type, thrust, for spear- and pikemen.
* A new resource, silver:
  * Silver can't be gathered directly by workers.
  * Traders can only gain silver, no other resources.
  * Apadana, Wonders, and Catafalques have a 1 silver per second resource trickle, no other resources.
  * Mercenaries cost silver, no other resources.
  * Some technologies cost silver.
  * Espionage cost silver instead of metal.
* All support units are bribable.
* Some civilization bonuses have been removed or replaced.
* Team bonuses have been deprecated.
* Units no longer give resource loot.
* Animals are no longer visible in fog.
* Corrals are deprecated.
* Cavalry can no longer gather meat.
* Lowered unit vision ranges:
  * rams: 50
  * support units: 60
  * infantry: 70
  * cavalry: 80
  * elephants: 90
  * artillery: 100
* Unit base movement speed is slightly lowered.
* Houses no longer have technologies nor can train female workers.
* Barracks trains advanced infantry by default and is postponed to the town phase.
* Civic centres can no longer train cavalry.

[(return to table of contents)](https://github.com/0abc/0abc-a24#table-of-contents)


### New unit costs
```
                   food, metal, silver; population; time
female workers:        50 ,     ,     ; 1 ;  9 s
slaves:                   ,     ,  50 ; 0 ; 15 s
healers:               50 ,     , 100 ; 1 ; 30 s
traders:              100 ,  80 ,     ; 1 ; 15 s
all heroes:               ,     , 500 ; 0 ; 60 s

                   food, metal, silver; population; time
mercenary infantry:       ,     ,  60 ; 1 ;  8.4 s
basic infantry:        50 ,  30 ,     ; 1 ; 12 s
advanced infantry:     50 ,  50 ,     ; 1 ; 14.4 s
elite infantry:        50 ,  70 ,     ; 1 ; 17.28 s
champion infantry:     90 ,  90 ,     ; 1 ; 20 s

                   food, metal, silver; population; time
mercenary cavalry:        ,     ,  90 ; 2 ; 11.2 s
basic cavalry:        100 ,  40 ,     ; 2 ; 16 s
advanced cavalry:     100 ,  60 ,     ; 2 ; 19.2 s
elite cavalry:        100 ,  80 ,     ; 2 ; 23.04 s
champion cavalry:     150 , 100 ,     ; 2 ; 27 s

                   food, metal, silver; population; time
mercenary elephants:      ,     , 120 ; 5 ; 14 s
basic elephants:      200 ,  80 ,     ; 5 ; 20 s
advanced elephants:   200 , 100 ,     ; 5 ; 24 s
elite elephants:      200 , 120 ,     ; 5 ; 28.8 s
champion elephants:   300 , 200 ,     ; 5 ; 36 s

                   wood, metal, silver; population; time
rams:                 300 , 100 ,     ; 4 ; 30 s
bolt-shooters:        200 , 200 ,     ; 3 ; 30 s
stone-throwers:       250 , 250 ,     ; 3 ; 30 s
siege towers:         500 , 300 ,     ; 5 ; 30 s

                   wood, metal, silver; population; time
fishing boats:        120 ,     ,     ; 1 ; 15 s
merchant ships:       150 , 100 ,     ; 1 ; 20 s
fireships:            300 ,     ,     ; 1 ; 30 s
biremes:              120 ,  60 ,     ; 2 ; 20 s
triremes:             200 , 100 ,     ; 3 ; 25 s
quinqueremes:         500 , 250 ,     ; 5 ; 30 s
```

[(return to table of contents)](https://github.com/0abc/0abc-a24#table-of-contents)
