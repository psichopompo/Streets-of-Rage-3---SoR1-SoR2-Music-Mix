<p align="center">
  <img width="400" height="175" alt="Streets_of_Rage_3_Logo" src="https://github.com/user-attachments/assets/fa8b9ebb-66e2-4bc6-9baa-1601c7108b83" />
</p>



# Streets of Rage 3 / Bare Knuckle III — Streets of Rage 1 & 2 Music Hack

**Version 1.0 — Psicopompo**

This hack replaces the music soundtrack of *Bare Knuckle III* with 28 tracks from *Streets of Rage* and *Streets of Rage 2*, adapted to run natively through the game's original sound driver.

No external audio player, VGM playback or streamed audio is used.

- **Round 1:** Go Straight (SoR2)
- **Sound Test:** 36 entries, including the imported tracks, original jingles and one unused track from SoR2.
- **Sound effects, voices and the original sound driver remain unchanged.**

## Files

- `Streets of Rage 3 - SoR1+SoR2 Music Mix.ips` — IPS patch (355,016 bytes)
- `Streets of Rage 3 - SoR1+SoR2 Music Mix.bps` — BPS patch (354,875 bytes)
- `README.md` — this file
- `screenshots/` — in-game captures

Apply **one patch only**. BPS is recommended because it verifies the source ROM.

## How to Apply

### Required ROM

- **Game:** Bare Knuckle III (Japan)
- **Size:** 3,145,728 bytes
- **CRC32:** `5D09236F`

You must use the clean Japanese ROM, not *Streets of Rage 3* (USA) or an English-translated version. The patch is not intended for other ROM revisions.

Apply the IPS or BPS patch using a compatible patching tool such as Floating IPS (Flips), Lunar IPS or RomPatcher.js.

The resulting ROM is 4,194,304 bytes.

Always start a fresh game. Do not load save states created with a different ROM.

## Track List

The numbers correspond to the game's Sound Test entries.

| No. | Track | Source / Notes |
|---:|---|---|
| 01 | Player Select | SoR1 |
| 02 | Go Straight | SoR2 — Round 1 |
| 03 | Back to the Industry | SoR2 |
| 04 | In the Bar | SoR2 |
| 05 | Never Return Alive | SoR2 |
| 06 | Dilapidated Town | SoR1 — Round 2 |
| 07 | Violent Breathing | SoR1 — Round 7 |
| 08 | Expander | SoR2 |
| 09 | Moon Beach | SoR1 — Round 3 |
| 10 | Revenge of Mr. X | SoR2 |
| 11 | My Little Baby | SoR1 — Boss |
| 12 | Ready Funk | SoR2 |
| 13 | Slow Moon | SoR2 |
| 14 | Beatnik on the Ship | SoR1 — Round 5 |
| 15 | Jungle Base | SoR2 |
| 16 | Max Man | SoR2 |
| 17 | Too Deep | SoR2 |
| 18 | Alien Power | SoR2 |
| 19 | Fighting in the Street | SoR1 — Round 1 |
| 20 | Attack the Barbarian | SoR1 — Round 8 |
| 21 | Violent Breathing | SoR1 — Round 6 |
| 22 | Dreamer | SoR2 |
| 23 | Under Logic | SoR2 |
| 24 | Spin on the Bridge | SoR2 |
| 25 | Round Clear | SoR2 |
| 26 | Keep the Groovin | SoR1 — Round 4 |
| 27 | Wave 131 | SoR2 |
| 28 | Original BKIII jingle | Unchanged |
| 29 | Original BKIII jingle | Unchanged |
| 30 | Original BKIII jingle | Unchanged — plays at the end of the intro |
| 31 | Original BKIII jingle | Unchanged |
| 32 | Original BKIII jingle | Unchanged |
| 33 | Original BKIII jingle | Unchanged |
| 34 | Original BKIII jingle | Unchanged |
| 35 | Unused music | SoR2 |
| 36 | Original BKIII jingle | Unchanged |

## Why Some Original Music Remains

The short jingles and cutscene cues from *Bare Knuckle III* remain unchanged. These include the round-clear and game-over jingles, the cue at the end of the intro sequence and other short musical stings.

The imported songs were not suitable replacements for these brief cues, so the original music data and pointers have been preserved.

## Testing and Validation

The hack has undergone automated checks and in-game testing.

- All 28 imported tracks passed isolated playback tests of 20,000 frames each, with channel activity and stream pointers checked.
- A fresh boot of the patched ROM was tested, confirming that Round 1 plays the imported *Go Straight* track.
- The eight original jingle slots were compared byte-for-byte against the original ROM and found to be identical.
- Automated validation confirmed that both patches reconstruct the released ROM.
- The game has been played through most levels without encountering errors.

The hack has not yet undergone exhaustive testing across every route and gameplay situation. Feedback about any issues or specific tracks is welcome.

## Notes and Limitations

The *Streets of Rage 1* conversions may differ from the original recordings in timbre, vibrato, envelope balance and drum tuning. The first and third games use different sound drivers, so exact reproduction is not always possible. The *Streets of Rage 2* conversions are closer to their source material.

Imported background tracks loop and are cut off by the game when the scene changes.

## Credits

**Music conversion, tooling and validation:** Psicopompo.

Original games © SEGA / Ancient. All music belongs to its respective rights holders.

Free fan project. Not for sale.
