# StarCraft 64 Co-Op Mod V2 — Complete Byte Changes (vs Vanilla)

Every ROM edit in this mod, relative to a clean **StarCraft 64 (U)** ROM
(MD5 `559f71b861f639b6376d891e3023414b`). Offsets are file offsets. Always edit a copy.

## Single-byte changes

|Offset|Vanilla|Modded|What it does|
|-|-|-|-|
|`0x03EB35`|`57`|`46`|P2 shares P1's control slot (shared-control co-op)|
|`0x03EB49`|`D0`|`D7`|P2 gets its own selection context|
|`0x07B055`|`40`|`43`|P2 split-screen viewport|
|`0x0D0D59`|`01`|`0B`|Chapter 6 count +1 — Dark Origins selectable|
|`0x0D0D62`|`00`|`78`|Enable-all-cheats mask (unlocks Resurrection IV)|
|`0x0D0D63`|`00`|`1E`|Enable-all-cheats mask (low byte)|
|`0x0D16E8`|`0B`|`0C`|2P scenario list count +1 — shows Mass Hysteria|
|`0x0D1701`|`0A`|`0B`|Chapter 6 draw count +1 — Dark Origins visible|
|`0x0D1B39`|`72`|`65`|Menu label text → "Team Melee"|
|`0x0DAB7F`|`08`|`09`|Mission-select list sizing|
|`0x0DCF59`|`40`|`00`|Block left/right scroll on mission-select|
|`0x0DD6F7`|`0B`|`0C`|Map/list count +1 (pairs with Mass Hysteria)|
|`0x9D20BB`|`00`|`40`|Fix Mass Hysteria highlight freeze|

## Multi-byte changes

|Offset|Vanilla|Modded|What it does|
|-|-|-|-|
|`0x00002D`|`20 20 20 20 20 20 20`|`43 4F 2D 4F 50 76 32`|Internal ROM name → "CO-OPv2"|
|`0x0235B4`|`92 42 FE FC 10 40 00 02`|`24 02 00 01 A2 42 FE FC`|Force 2P-active at campaign load (co-op master switch)|
|`0x0D0D54`|`03 01 01 01 01`|`0C 0A 0A 0A 0A`|Unlock-all-missions table|
|`0x0D1B21`|`69 6E 67 6C 65 2D 50 6C 61 79 65 72 00 00 00 54 77 6F 2D 50 6C 61 79 65 72`|`74 6F 72 79 20 43 6F 2D 4F 70 00 00 00 00 00 54 65 61 6D 20 4D 65 6C 65 65`|Menu labels → "Story Co-Op" / "Team Melee"|
|`0x0D8D04`|`8C 65 00 00 AC 45 00 00`|`24 05 01 01 A4 45 FD 98`|Stamp Resurrection IV unlock flags|

## 

