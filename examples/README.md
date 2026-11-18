# Vgtb — Configuration examples

These are **illustrative, partial YAML examples** for people evaluating how Vgtb can be customized. They document selected configuration keys, not the full plugin files.

| Example | What it demonstrates |
| --- | --- |
| [Gameplay & UI](config.example.yml) | Queue sizes, round timing, scoring, plot dimensions, HUD colors and silent audio |
| [Manual arena](manual-arena.example.yml) | Manual arena provider under `arenas.<id>` without fabricated world coordinates |
| [Messages](messages.example.yml) | English text and color/argument placeholders |
| [Menus](menus.example.yml) | Inventory layout and theme-choice slots |

## How to use the examples safely

1. Install a **licensed Vgtb build** and use the configuration files it generates as the authoritative starting point.
2. Back up your existing YAML and saved arena/world data. Compare the example with your version before copying **individual settings**, not whole files.
3. Keep all actual waiting, lobby, game and spectator locations, build-region boundaries and existing player data unchanged.
4. Only apply changes during a safe idle period, following the instructions for your licensed build.

**Important:** These files are **not complete configurations**, not installers, and not guaranteed to match every historical/private preview version. The public README describes Vgtb 1.8.0; the examples reflect a verified internal configuration layout and must be checked against the particular licensed release. `config-version: 2`, where supported, identifies that schema.

Vgtb uses **`config.yml`** for arena configuration: there is **no standalone runtime `arenas.yml`**. The manual arena example is a snippet to place under the matching `arenas` section, never a replacement for real stored locations. `messages.yml` and `menus.yml` examples likewise omit keys the running plugin still needs.

The audio example intentionally defaults to `silent`; it contains no premium resource-pack identifiers, hashes, or private integration credentials. No source code, plugin binaries, database files, player information or real-world arena coordinates are published here.

**Vgtb remains commercial and closed source.** The implementation and complete release-specific configuration are maintained privately by VACK STUDIO.
