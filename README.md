<p align="center">
  <img src="assets/vgtb-01-cover.svg" alt="Vgtb Minecraft Guess The Build by VACK STUDIO — brand cover" width="100%" />
</p>

# Vgtb <img src="assets/emoji/mini-zoiila-wave.png" alt="Mini Zoiila" width="29" height="29" />

**Build the clue. Guess the word.**

**Vgtb** is a Minecraft Guess The Build minigame by **VACK STUDIO**. Build a theme while opponents race to guess its meaning through chat. The minigame includes builder turns, hints, scoring and a round timer.

> [!IMPORTANT]
> **Commercial plugin.** Vgtb is proprietary software. This public repository provides product information, not the source code or a downloadable JAR. Builds are distributed privately under authorization.

## How the game works

<p align="center">
  <img src="assets/vgtb-02-plugin-info.svg" alt="Plugin information: join, select a theme, build and guess" width="100%" />
</p>

One player is selected as the builder, chooses a theme and starts placing clues. Everyone else tries to identify the theme through chat as rounds and scores advance. Vgtb supports **six manually configured arenas** in existing worlds, **4/6/8/16-player** capacities, and saved **English and Arabic** language preferences. The default minimum start thresholds are **3/5/6/12**, respectively.

## In-game screenshots

<p align="center">
  <img src="assets/vgtb-03-real-gameplay.svg" alt="Authentic Vgtb Minecraft gameplay: build arena, Your Turn, and Get ready" width="100%" />
</p>

These are real Minecraft screenshots captured from the minigame, not reconstructed scenes or generated Minecraft blocks.

## Configuration and tips

<p align="center">
  <img src="assets/vgtb-04-config-notes.svg" alt="Verified Vgtb admin setup commands and arena configuration guidance" width="100%" />
</p>

Vgtb uses **existing Minecraft worlds and manually positioned arenas**; it does not generate maps or worlds. Stand at the relevant position and configure the selected arena:

```text
/gb setwaiting <arena>
/gb setlobby <arena>
/gb setgame <arena>
/gb setspectator <arena>
/gb setpos1 <arena>
/gb setpos2 <arena>
```

Set waiting, lobby, game and spectator positions, as well as the two opposing corners of the play area. Administrative setup and `/gb pack` diagnostics require **`gb.admin`**.

### Player commands

| Action | Command |
| --- | --- |
| Join a specific arena | `/gb1` through `/gb6` |
| Join a capacity queue | `/gb game 4`, `/gb game 8`, `/gb game 16` |
| Join queue and arena | `/gb game 4 2` |
| Select language | `/gb language`, `/gb language en`, `/gb language ar` |
| Leave a match | `/gb leave` |

## Companion integrations

Vgtb works with its standard cosmetic inventory. Optional companion plugins add extra functionality.

| Plugin | Integration |
| --- | --- |
| **VPackEngine 1.1.0-preview.2** | Waiting/game pack profiles, arena overrides, language-specific cosmetic menus and resource cleanup |
| **VMusic 1.7.0** | Optional NBS waiting track and game cues with native fallback |
| **VHeads 1.0.1** | Optional player-head management |

When VPackEngine, its resources or menus are unavailable, the standard cosmetic inventory remains available. Its resource-pack menus require `vpack.use`.

## Compatibility and verification

| Item | Version or status |
| --- | --- |
| Vgtb | **1.8.0** |
| Target server | **Paper 26.2 build 133** |
| Java | **Java 25** |
| Arenas | **Six, manually configured** |
| Leaf / Folia / Bedrock | **Not verified** |

A previously reported private Java 25 build passed **24 automated tests** covering service integration, resource readiness, request isolation and lifecycle invalidation. These build/service tests do not prove full multiplayer acceptance, audio, resource-pack rendering or runtime cleanup, which still need live-client verification.

## Availability

**Vgtb is commercial software distributed privately by VACK STUDIO.** Contact the studio for availability and licensing terms.

<p align="center">
  <a href="https://builtbybit.com/members/vack-studio.891381/#latest-activity">BuiltByBit</a>
  &nbsp;·&nbsp;
  <a href="https://discord.gg/y45brtZBEE">Discord</a>
</p>

<p align="center">
  <img src="assets/vgtb-05-studio-signature.svg" alt="Proudly crafted by VACK STUDIO — Built by Built" width="100%" />
</p>

<p align="center"><sub>Copyright © 2026 VACK STUDIO. All rights reserved. Third-party components retain their respective rights.</sub></p>