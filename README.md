<p align="center">
  <img src="assets/vgtb-01-cover.svg" alt="Vgtb Minecraft Guess The Build by VACK STUDIO — brand cover" width="100%" />
</p>

# Vgtb

**Build the clue. Guess the word.**

**Vgtb** is a Minecraft Guess The Build minigame by **VACK STUDIO**. Build a theme while opponents race to guess its meaning through chat. The minigame includes builder turns, hints, scoring and a round timer.

> [!IMPORTANT]
> **Commercial plugin.** Vgtb is proprietary software. This public repository provides product information, not the source code or a downloadable JAR. Builds are distributed privately under authorization.

## How Vgtb works

<p align="center">
  <img src="assets/vgtb-02-plugin-info.svg" alt="Plugin information: join, select a theme, build and guess" width="100%" />
</p>

One player is selected as the builder, chooses a theme and starts placing clues. Everyone else tries to identify the theme through chat as rounds and scores advance. Vgtb supports **six manually configured arenas** in existing worlds, **4/6/8/16-player** capacities, and saved **English and Arabic** language preferences. The default minimum start thresholds are **3/5/6/12**, respectively.

## Real in-game screenshots

<p align="center">
  <img src="assets/vgtb-03-real-gameplay.svg" alt="Authentic Vgtb Minecraft gameplay: build arena, Your Turn, and Get ready" width="100%" />
</p>

These are real Minecraft screenshots captured from the minigame, not reconstructed scenes or generated Minecraft blocks.

## Configuration and tips

<p align="center">
  <img src="assets/vgtb-04-config-notes.svg" alt="Vgtb arena configuration and practical tips — no command listings" width="100%" />
</p>

Vgtb uses **existing Minecraft worlds and six manually configured arenas**. It does not generate maps or worlds. Prepare each arena with safe player locations and a clearly defined building area.

### Arena preparation

- **Choose a safe world:** Keep the play area and surrounding space ready for a complete match.
- **Define player locations:** Set separate waiting, lobby, game and spectator positions.
- **Keep build boundaries clear:** Mark the opposite corners of each intended building area.
- **Plan the match flow:** Check that players can enter, spectate and return safely.

### Helpful admin tips

- Test the arena with multiple players before opening it publicly.
- Confirm that spectators cannot interfere with the active builder.
- Check spawn safety, arena limits and the return flow after each round.
- Verify the available player capacities and waiting areas match your server setup.

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