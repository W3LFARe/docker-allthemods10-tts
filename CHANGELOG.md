# Changelog

All notable modpack and container updates for **ATM10 To the Sky** are recorded here.
New entries are added automatically by [`.github/workflows/update-pack.yml`](.github/workflows/update-pack.yml) from the CurseForge release changelog.

## Unreleased

## 2.2.0 — 2026-10-25

NeoForge `21.1.250` · [CurseForge file](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10-sky/files/9261952)

### Changelog

### 📦 2.2.0

#### 🛠️ Mods

##### Added (4)

- Aaron (1.21.0)
- Excessive Utilities (1.11.0)
- Mama's Happy Hallows (1.21.1-4)
- Sophisticated Item Actions (0.5.17)

#### 📰 General changes and notes

Excessive utils Replaces Generator Galore, with quest swaps, unification, crusher compat, and a new quest chapter. EXU dimensions and the ender quarry are removed. A few recipes are adjusted such as in the ATM Star, Second Chance is blacklisted from pylons, and the quantum quarry is blocked from tick acceleration.

##### Github Commits

- Fix regex error in recipes_fix.js fixes #1069 (oly2o6)
- Deprecate old mods (oly2o6)
- Replace gengalore with excessiveutils (oly2o6)
- Quest replacements for excessive utilities being added (oly2o6)
- Excessive utils unification (oly2o6)
- Blacklist quantum quarry tick acceleration (oly2o6)
- Unstable ingot to JDT flight module (oly2o6)
- Exu Crusher mod compat (oly2o6)
- Modified angel ring recipe (oly2o6)
- Add sigil to wither drop (oly2o6)
- Add generator changes from aero (oly2o6)
- Exu helper tooltips (oly2o6)
- Blacklist second chance from pylons (exu) (oly2o6)
- Commit exu config (oly2o6)
- Added exu quest chapter (oly2o6)
- Removed ender quarry and exu dimensions (oly2o6)
- Added red orchid to sieving (oly2o6)
- Removed the ender marker (oly2o6)
- Update deprecated.js (oly2o6)

##### Updated (31)

- Apothic Enchanting (1.6.3) -> (1.6.4)
- BBL Routers (1.1.9) -> (1.2.0)
- Crystalix (3.0.1) -> (3.0.3)
- Easy Villagers (1.21.1-1.1.42) -> (1.21.1-1.1.47)
- Extended Industrialization (1.16.3-1.21.1) -> (1.16.4-1.21.1)
- FramedBlocks (10.6.2) -> (10.6.3)
- Fusion (1.3.15+b) -> (1.3.16)
- Growth Accelerator Tiers (2.0.0) -> (2.0.1)
- IntegratedCrafting (1.7.2) -> (1.8.0)
- IntegratedDynamics (1.38.0) -> (1.38.1)
- IntegratedTerminals (1.10.0) -> (1.11.1)
- Just Enough Items (19.57.0.450) -> (19.69.0.456)
- Just Enough Stuff (1.21.1-1.2.1) -> (1.21.1-1.3.0)
- LogisticsNetworks (1.16.4) -> (1.17.2)
- Mama's Herbs and Harvest (1.21.1-22) -> (1.21.1-24)
- Modern Industrialization (2.5.9) -> (2.5.10)
- ModernFix (5.27.24+mc1.21.1) -> (5.27.26+mc1.21.1)
- Moonlight Lib (1.21.1-3.7.0) -> (1.21.1-3.7.2)
- Neo Vitae (1.1.31) -> (1.1.44)
- Occultism (1.224.4) -> (1.224.5)
- Oritech (1.2.12) -> (1.2.13)
- oωo (0.12.15.5-beta.1+1.21) -> (0.12.15.6-beta.1+1.21)
- Placebo (9.9.2) -> (9.9.4)
- Puzzles Lib (21.1.62) -> (21.1.64)
- Railcraft Reborn (1.2.11) -> (1.2.13)
- Reliquary Reincarnations (2.0.80) -> (2.0.81)
- Sophisticated Backpacks (3.26.7) -> (3.26.13)
- Sophisticated Core (1.5.5) -> (1.5.16)
- Sophisticated Storage (1.6.1) -> (1.6.7)
- SuperMartijn642's Core Lib (1.1.24+b) -> (1.1.25)
- Tesseract API (1.12.17-1.21.1) -> (1.12.18-1.21.1)

### Container changes

- Require explicit `EULA=true` before the server will start (previously accepted by default when `EULA` was unset).
- Automate CurseForge version detection, in-CI server boot smoke test, Docker Hub publishing, git tagging, and changelog generation.
- Use atomic `.installed-<version>` marker and `exec` into the Java process for clean `docker stop` world saves.

## 1.3.1 — 2025-09-03

NeoForge `21.1.206` · [CurseForge](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10-sky)

- Baseline version on `curseforge-test` prior to automated updates.
