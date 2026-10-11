# Super Hero Sakusen — English Translation Patch (Beta)

💬 **Discord** (testing, bug reports, discussion): https://discord.gg/eaNH8qJfVh

English patch for **Super Hero Sakusen** (スーパーヒーロー作戦, Banpresto, PlayStation, 1998).
This is a **beta**. Testers and proofreaders are very welcome!

**Current version: v0.4.1-beta**

> **Heads-up: the script is AI-assisted.** The translation was produced with AI (Claude) and driven by a human project lead who chose the terminology and tested the build. It follows established English names from the source franchises and Super Robot Wars. It has not had a full human proofread yet, so expect rough lines, wrong nuances and the occasional mistake. Native or fluent Japanese speakers who want to review or correct lines are very welcome. Corrections get applied directly.

## What's new in v0.4.1-beta
- Character limit extended: English lines are no longer limited to the length of the Japanese text. Longer lines are moved and resized so they fit, in story and battle scenes.
- Full retranslation (story, battle quotes, etc).
- Fixed stray overflow dialogs.

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
- `SHS_English_v0.4.1-beta.xdelta`
- xdelta patcher: **xdeltaUI** (or `xdelta3`)
- Tracks 2–4 (audio) and your `.cue` file stay as they are

**No game data is included. Please don't ask for or share ROMs/ISOs.**

## How to patch
1. Make
