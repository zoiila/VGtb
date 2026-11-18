<p align="center">
  <img src="assets/vgtb-01-cover.svg" alt="Vgtb by VACK STUDIO with Mini Zoiila hanging below the lower-right banner edge, original top-05-hanging-mirrored pose" width="100%" />
</p>

# Vgtb <img src="assets/emoji/mini-zoiila-wave.png" alt="Mini Zoiila waving" width="29" height="29" />

**Build the clue. Guess the word.**

**Vgtb** is a turn-based Minecraft **Guess The Build** minigame by **VACK STUDIO**. One player builds a secret theme while the others race to identify it in chat. Builder rotation, timed theme selection, hints and scoring keep each match moving.

> [!IMPORTANT]
> **Commercial plugin.** Vgtb is proprietary software by **VACK STUDIO**. This public repository provides product information only. Source code and installable builds are distributed privately with authorization.

## How the game works

**What happens in a Vgtb round?** <img src="assets/emoji/mini-zoiila-thinking.png" alt="Mini Zoiila thinking" width="24" height="24" />

<p align="center">
  <img src="assets/vgtb-02-plugin-info.svg" alt="Vgtb gameplay flow: choose an arena, take a builder's turn and build while others guess" width="100%" />
</p>

<table>
  <tr>
    <td width="23%"><strong>Join a match</strong></td>
    <td>Choose an arena or join a capacity queue. Vgtb supports <strong>six manually configured arenas</strong> in existing Minecraft worlds, with <strong>4, 6, 8 or 16-player</strong> game sizes.</td>
  </tr>
  <tr>
    <td><strong>Build the clue</strong></td>
    <td>The active builder selects a theme, then uses blocks to represent it. Other players watch the build as the round progresses.</td>
  </tr>
  <tr>
    <td><strong>Guess and score</strong></td>
    <td>Players submit guesses in chat. Hints and scoring provide feedback, and builder turns rotate between rounds.</td>
  </tr>
</table>

The default start thresholds for the 4, 6, 8 and 16-player sizes are **3, 5, 6 and 12 players**, respectively. Players can save their **English or Arabic** language preference.

## In-game screenshots

<p align="center">
  <img src="assets/vgtb-03-real-gameplay.svg" alt="Three genuine Vgtb Minecraft screenshots: the building arena, Your Turn and Get ready" width="100%" />
</p>

These are genuine Minecraft captures from Vgtb, not reconstructed or generated game scenes. You can also inspect the original <a href="assets/screenshots/building-arena.jpg">building arena</a>, <a href="assets/screenshots/your-turn.jpg">Your Turn</a> and <a href="assets/screenshots/get-ready.jpg">Get ready</a> images.

## Arena preparation and tips

<p align="center">
  <img src="assets/vgtb-04-config-notes.svg" alt="Vgtb arena preparation: world selection, player spawn locations, build boundaries and safe match flow" width="100%" />
</p>

Vgtb uses **existing worlds**; it does not generate maps. The administrator defines each arena's essential locations and building boundaries.

<table>
  <tr>
    <td width="25%"><strong>World and play area</strong></td>
    <td>Prepare an existing world with enough space for the build area and the surrounding match activity.</td>
  </tr>
  <tr>
    <td><strong>Player locations</strong></td>
    <td>Keep waiting, lobby, gameplay and spectator positions distinct, accessible and safe.</td>
  </tr>
  <tr>
    <td><strong>Boundaries</strong></td>
    <td>Mark both opposing corners of the intended play area so the arena limits are clear.</td>
  </tr>
  <tr>
    <td><strong>Match flow</strong></td>
    <td>Plan the entry, spectator experience and return to the lobby before opening the arena.</td>
  </tr>
</table>

### Before inviting players

A good first test uses multiple players: check spawn safety, spectator separation, build boundaries and the return to the lobby after a round. Avoid unsafe drop points or blocked spawn positions. <img src="assets/emoji/mini-zoiila-teacher.png" alt="Mini Zoiila sharing a setup tip" width="24" height="24" />

## Companion integrations

Vgtb includes its standard cosmetic inventory. Optional companion plugins can extend presentation, audio and player-head features.

| Companion | What it adds |
| --- | --- |
| **VPackEngine 1.1.0-preview.2** | Waiting/game pack profiles, per-arena overrides, language-specific cosmetic menus and resource-context cleanup |
| **VMusic 1.7.0** | Optional NBS waiting-room track and in-game cues, with native audio fallback |
| **VHeads 1.0.1** | Optional player-head management |

If VPackEngine, its assets or a menu are unavailable, the standard cosmetic inventory remains accessible. VPackEngine resource-pack menus require the `vpack.use` permission.

## Compatibility and verification

| Component | Version or status |
| --- | --- |
| Vgtb | **1.8.0** |
| Target server | **Paper 26.2 build 133** |
| Java | **Java 25** |
| Arena model | **Six, manually configured in existing worlds** |
| Leaf / Folia / Bedrock | **Not verified** |

### Verification status

A previously reported private Java 25 build passed **24 automated tests**, covering service integration, resource readiness, request isolation and lifecycle invalidation.

**Live multiplayer acceptance is still pending.** Automated checks do not establish full multiplayer behavior, resource-pack visuals, audio or end-to-end runtime cleanup.

## Availability

Vgtb is **commercial software** by VACK STUDIO. Contact the studio for private build availability and written licensing terms.

---

<p align="center">
  <img src="assets/vgtb-05-studio-signature.svg" alt="Proudly crafted by VACK STUDIO, BuiltByBit and Discord links, with Signature #02 — Zoiila chases Chick" width="100%" />
</p>

<p align="center">
  <a href="https://builtbybit.com/members/vack-studio.891381/#latest-activity"><img src="assets/builtbybit-mark.svg" alt="BuiltByBit" width="20" height="20" /> BuiltByBit</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://discord.gg/y45brtZBEE"><img src="assets/discord-mark.svg" alt="Discord" width="20" height="20" /> Discord</a>
</p>

<details>
<summary><strong>License &amp; rights — VACK STUDIO</strong></summary>

Copyright © 2026 VACK STUDIO. All rights reserved.

The plugin, documentation and original artwork are proprietary. Redistribution, modification or publication require written authorization from VACK STUDIO. Third-party components retain their respective rights.

</details>
