# Heart Gold Inspired Into

A completely standalone HeartGold-inspired opening experience for Pokémon Gold Recomp.

## Included
- Custom HeartGold-inspired intro movie
- Celebi opening sequence
- Bell Tower rooftop sequence with Gold/Ethan walking toward Ho-Oh
- Johto location scenes
- HeartGold-style PRESS START screen
- Centered HeartGold logo and Ho-Oh fly-in
- HeartGold-inspired main-menu presentation
- Embedded HeartGold intro music playback

## Standalone
This mod has **no dependency on CROSSS UI** and does not install the CROSSS pause menu, Pokédex, Pokémon menu, Trainer Card, Pack, Pokégear, naming screens, options UI, mod menu, or any other CROSSS in-game UI changes.

You can use this mod by itself with the game's normal UI.

## Version 0.1.0
First standalone release, separated from CROSSS UI v0.22.1.

## v0.1.1 — Mod Manager Install Fix
- Fixed Gen1Recomp++ installation error: `invalid mod manifest: unknown profile "cosmetic"`.
- Changed the manifest profile to the supported `overhaul` profile.
- The mod remains completely standalone with no CROSSS UI dependency.
- No intro visuals, music, title screen, or menu behavior were changed.

## v0.1.2 — Cartridge Launch Crash Fix
- Fixed the crash that occurred immediately after selecting the Gold cartridge.
- The standalone split was missing the shared pixel-font loader that the intro renderer uses.
- Added a self-contained font loader directly to Heart Gold Inspired Into.
- Added a defensive fallback so an unavailable engine font cannot crash the intro renderer.
- Remains fully standalone with no CROSSS UI dependency.
- No intro artwork, animation, title layout, or music was intentionally changed.

## v1.0.0 — Initial Public Release
- Promoted the tested standalone build to v1.0.0 for release.
- No functional changes from v0.1.2.
- Fully standalone; CROSSS UI is not required.
