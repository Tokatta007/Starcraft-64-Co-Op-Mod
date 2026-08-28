# StarCraft 64 — Campaign Co-Op Mod (V2)

*By Tokatta (if you want to reach me, message me on Discord)*

A romhack that turns StarCraft 64's single-player campaign into a **two-player**,
split-screen, shared-control co-op experience. Both players share one base, one
economy, and one army, and can play through the entire campaign together on one
console (Team Melee/Archon Mode).

<img width="632" height="478" alt="Pic 1" src="https://github.com/user-attachments/assets/39b53af7-019f-4e9d-9997-aeb0fbd3c1bc" />

---

## New in V2

- **Enemy AI now attacks in co-op.** In V1, the computer opponents would sometimes not
  do scripted AI events (like attacking in Terran Mission 3). This is now fixed in V2,
  and the missions should now behave just like the vanilla game.
- **"Dark Origins" is now a selectable mission.** The secret bonus map is now a
  normal, visible entry at the **end of the Chapter 6 mission list** (right after
  *Omega*). No cheat code needed anymore!

Everything from V1 is still here.

---

## What's included

- **Full split-screen campaign co-op.** All **60 campaign missions** are playable
  in two-player shared-control mode. Player 1 and Player 2 share the same faction,
  units, and resources, each with their own cursor and screen.
- **Every mission unlocked from the start.**
- **All cheats unlocked from the start.**
- **Every scenario map selectable**, including two hidden ones:
  - **Resurrection IV** — a secret scenario normally locked behind completing everything in the game.
  - **Mass Hysteria** — a hidden map that is rarely ever mentioned anywhere, with
    essentially no YouTube videos or online coverage. It was left in the cartridge by
    the developers but never made selectable. This mod surfaces it as a normal,
    playable entry in the Two-Player Scenario menu.
- **Dark Origins** — the secret bonus mission — is now a selectable Chapter 6 mission (new in V2).
- **Story Info** — Pre- and post-mission text, briefings, and slideshows all work as intended!
- **Hardware Ready** — You can play on both emulator or hardware. Play how you'd like!

<img width="622" height="475" alt="Pic 2" src="https://github.com/user-attachments/assets/30ee84fa-4dcf-444a-89b3-11015ddef019" />

---

## The secret maps

- **Resurrection IV** and **Mass Hysteria** appear directly in the Two-Player →
  Scenario menu. Just highlight and select them like any other map.

- **Dark Origins** is the game's hidden bonus mission. In the original game it isn't a
  menu entry at all and is only playable by finishing C6M9 with 5 or more minutes
  remaining. **V2 adds it as a normal mission at the end of the Chapter 6 list.**

<img width="796" height="597" alt="Pic 3" src="https://github.com/user-attachments/assets/2f4d5582-5758-4f65-881f-aec3dd4a8d08" />

---

## Known quirks

- **Note on controllers:** Controller 2 is detected when a mission *loads*. If you
  plug it in after the mission has already started, it might not work. Quit and then
  re-enter the mission to fix. If you unplug a controller mid-mission, it should work
  just fine once you plug it back in.
- **Loading screen:** In co-op, every mission shows the two-player "versus" loading
  screen (a Marine facing a Zealot) rather than the race/chapter-specific screens seen
  in single-player. This is purely cosmetic and does not affect gameplay.
- **Regular two-player Melee** now behaves like Team Melee (shared base). If you want
  vanilla competitive two-player, keep an **unmodified** copy of the ROM for that.
- The allied player's selection outline and some results-screen labels are cosmetic
  and may look slightly different from vanilla — this does not affect gameplay.
- In these competitive modes, you share a base, and the Player 2 slot is just an idle
  base with the worker bees endlessly collecting minerals until one team blows them up.
- **Progression/saving in co-op:** because the game treats co-op sessions as
  multiplayer internally, campaign progression is sadly **not saved** in co-op. This is
  why every mission is unlocked from the start.
- **Story Co-Op mission list (Scenario / Load Saved tabs) are disabled.** On the
  campaign (Story Co-Op) mission list, the "Scenario" and "Load Saved" tabs are
  intentionally greyed out and cannot be selected (pressing left/right just plays the
  menu beep). These screens aren't used in this mod. There's no saving, so these
  additional menus aren't selectable, to keep the menu clean. This is by design, not a
  bug.

<img width="508" height="382" alt="pic 4" src="https://github.com/user-attachments/assets/c2f35b9a-93c9-4866-95a5-f03ef6bbe232" />

---

## Applying the patch

This mod is distributed as a **patch**, not a full ROM. To use it:

1. Obtain your own legally-owned copy of **StarCraft 64 (U)** as a
   `.z64` (big-endian) file.
2. Apply the included patch to your ROM.
3. Have fun!

**Base ROM this patch expects (StarCraft 64 (U), unmodified, `.z64` big-endian):**

- MD5: `559f71b861f639b6376d891e3023414b`
- Region/format: USA (U), `.z64` (big-endian; first bytes `80 37 12 40`)

> If the patch fails to apply, your ROM is almost certainly a different dump, region,
> or byte-order (`.v64` / `.n64`). Byte-swapped or little-endian ROMs will not work.
> You need the big-endian `.z64` USA version whose MD5 matches the value above.

---

## Credits & thanks

- Original game: **StarCraft 64** (Blizzard / Mass Media / Nintendo).
- Map extraction made possible by **heinermann's BOLTextract**
  (github.com/heinermann/BOLTextract).
- Thanks to **Heinermann**, **FaRTy1billion**, **Warranty Voider**, **blackgamma7**, and the
  **staredit.net** community for tools, documentation, and reverse-engineering
  groundwork that made this possible.

---

## Legal

This is a fan-made modification distributed as a **patch** (BPS/xdelta), not as a
complete ROM. You must supply your own legally-obtained copy of StarCraft 64 to apply
it. No copyrighted game data is included in the patch itself.
