# Super Hero Sakusen — English Translation Patch (Beta)

English patch for **Super Hero Sakusen** (スーパーヒーロー作戦, Banpresto, PlayStation, 1998).
This is a **beta**. Testers and proofreaders are very welcome!

> **Heads-up: the script is AI-assisted.** The translation was produced with AI (Claude) and driven by a human project lead who chose the terminology and tested the build. It follows established English names from the source franchises and Super Robot Wars. It has not had a full human proofread yet, so expect rough lines, wrong nuances and the occasional mistake. Native or fluent Japanese speakers who want to review or correct lines are very welcome. Corrections get applied directly.

## What's translated
- Full story script and event dialogue
- Battle dialogue, battle menu, attack/weapon names, battle messages (EXP, level-up, etc.)
- Menus, status screens, item/character names, CONFIG, memory-card save title
- Staff roll (headings and character names; Japanese staff names are kept)

## Not translated (known limits)
- Text baked into FMV videos (including the credits video) can't be edited
- Company names in the "Cooperation" credits are left in Japanese on purpose
- Title logo is still Japanese

## What you need
- Your own dump of the game: **Track 1 only** (the `.bin` of the data track)
  - Expected SHA-1 of the original Track 1: `2149a9315bb4cd3786b17bc7974f145243f1b853`
  - Size: 682,040,016 bytes
- `SHS_English.xdelta`
- xdelta patcher: **xdeltaUI** (or `xdelta3`)
- Tracks 2–4 (audio) and your `.cue` file stay as they are

**No game data is included. Please don't ask for or share ROMs/ISOs.**

## How to patch
1. Make a **copy** of your Track 1 `.bin` (never patch your only copy).
2. Open xdeltaUI → Patch → select the xdelta file as *Patch*, your copy as *Source File*, and choose an output name.
3. Click *Patch*. Check the output's SHA-1: `ebce8dadde18e8446f26f18477bed20d9a95a949`
4. Edit your `.cue` so the Track 1 `FILE` line points to the patched `.bin`. Keep the Track 2–4 lines as they are.
5. Load the `.cue` in DuckStation (or another accurate emulator) and start a **NEW game**.

> Old save states and memory-card saves keep old in-game text. Start fresh when testing.

## Terminology (tell us if you disagree!)
Names follow the original franchises / Super Robot Wars where possible:
Ingram Prisken, Viletta Vadim, Ryusei, Rai, Aya, Heero, Duo, Trowa, Quatre, Zechs, Domon, Raizo, Gaia Savers, Reflection Circuit, Tenjo Tenge Cannon, Dragon Fang Crash.
"Giant of Light" is kept where the Japanese says it, rather than replaced with "Ultraman".

## Help test / proofread
Please use the report template (`BUG_REPORT_TEMPLATE.md`) and post screenshots.
Useful reports: garbled/stray characters, freezes, text cut off or overflowing, wrong names, mistranslations, typos.

## Credits
Project lead, terminology and testing: the project maintainer. Translation, reverse engineering and tools: AI-assisted (Claude).
Original game © Banpresto / Bandai Namco. This is an unofficial fan translation, not for sale.
