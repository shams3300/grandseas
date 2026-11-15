# Map names

English names from `Client/scripts/table/mapinfo.txt`. Map files are in `Client/map/`, server scripts in `server/GameServer/resource/<file>/`.

## Maps with an in-game name

| File | ID | English name | Notes |
|---|---|---|---|
| `07xmas.map` | 27 | Chirstmas Villag |  |
| `07xmas2.map` | 29 | Xmas Arena |  |
| `DreamIsland.map` | 33 | Dream Island |  |
| `PKmap.map` | 32 | PKmap |  |
| `abandonedcity.map` | 8 | Forsaken City |  |
| `abandonedcity2.map` | 9 | Forsaken City 2 |  |
| `abandonedcity3.map` | 10 | Forsaken City 3 |  |
| `ctf.map` | 40 | Capture The Flag |  |
| `darkblue.map` | 3 | Deep Blue |  |
| `darkswamp.map` | 7 | Dark Swamp |  |
| `eastgoaf.map` | 5 | Eastern Goaf |  |
| `garner.map` | 1 | Ascaron |  |
| `garner2.map` | 15 | Chaos Argent |  |
| `heilong.map` | 49 | Black Dragon Lai |  |
| `hell.map` | 16 | Purgatory | Abaddon 5, 6, 7, 8 (zones 113-116) |
| `hell2.map` | 17 | Drown | Abaddon 9 (zone 117) |
| `hell3.map` | 18 | Hades | Abaddon 10-17 (zones 118-125) + Abaddon Haven (zone 128) |
| `hell4.map` | 19 | Gate of Despair | Abaddon 18 (zone 126) |
| `hell5.map` | 20 | Abaddon Eternal | Abaddon Eternal (zone 127) |
| `jialebi.map` | 14 | Pirate Hideout |  |
| `leiting2.map` | 22 | Thundoria Mirage |  |
| `lobby.map` | 39 | Lobby |  |
| `lonetower.map` | 4 | Lone Tower |  |
| `magicsea.map` | 2 | Magical Ocean |  |
| `mjing1.map` | 35 | 1st Aurora Area |  |
| `mjing2.map` | 36 | 2nd Aurora Area |  |
| `mjing3.map` | 37 | 1st Dark Area |  |
| `mjing4.map` | 38 | 2nd Dark Area |  |
| `prisonisland.map` | 31 | Prison Island |  |
| `puzzleworld.map` | 11 | Demonic World |  |
| `puzzleworld2.map` | 12 | Demonic World 2 |  |
| `sdBoss.map` | 28 | Converse Chirstm |  |
| `shalan2.map` | 23 | Shaitan Mirage |  |
| `teampk.map` | 13 | Arena |  |
| `winterland.map` | 34 | Winter Island |  |

Spelling kept as in the game table ("Chirstmas Villag", "Black Dragon Lai" are cut off there).

## Abaddon floors

Abaddon 5-18 are not separate files. They are zones inside the `hell` maps: each tile's zone ID is the "island" byte, and zone names are in `Client/scripts/table/areaset.txt`. Abaddon 1-4 (zones 107-110) are listed in areaset.txt but are not in any of the hell maps.

## Map files with no name in the game tables

These files exist but have no entry in mapinfo.txt and no server folder in this repo:

- `chaosicicle.map`
- `ctflobby.map`
- `kyjj_1.map`
- `kyjj_2.map`
- `kyjj_3.map`
- `l4map.map`
- `moneyisle.map`
- `room.map`
- `sandbagisle.map`
- `starena13.map`
- `starena23.map`
- `starena33.map`
- `starwalkway.map`
- `temple.map`
- `tribulation.map`
- `volcanoisle.map`
- `woodxp.map`

## Names with no map file

Listed in mapinfo.txt but no `.map` file is in the repo:

- `secretgarden` (ID 6, Garden of Edel)
- `guildwar` (ID 21, Sacred War)
- `binglang2` (ID 24, Icicle Mirage)
- `guildwar2` (ID 25, Mini Sacred War)
- `yschurch` (ID 26, Church)
- `darkhouse` (ID 30, Dark House)
