# Technical Overview – Nymphs Savage Symphony

This document explains the **technical structure, tooling, and expected user behavior** for Nymphs Savage Symphony.

It is intended for:

* Players troubleshooting issues
* Users customizing visuals or UI
* Modlist authors extending the foundation

---

## Modlist Architecture

Nymphs Savage Symphony is built with **long-term stability and extensibility** as the primary goal.

Core principles:

* Clean separation of **gameplay**, **visuals**, and **infrastructure**
* Minimal overwrite chains
* Deterministic load and file behavior
* Safe customization without touching core mods

The list assumes **Mod Organizer 2** usage.

---

## Root Builder

The list uses **Root Builder** to manage files that must exist in the Skyrim root directory.

### Why Root Builder Is Used

* Prevents direct root pollution
* Allows profiles to remain portable
* Makes visual and tool swaps reversible
* Keeps the game directory clean

Anything placed inside a mod folder under a directory named **ROOT** will be deployed to the game root at runtime.

---

## ReShade Integration

ReShade is treated as **infrastructure**, not a visual preference.

### Default Behavior

* A **base ReShade mod** provides binaries and hooks
* A **Nymphs ReShade preset mod** provides the default look

### Using Your Own ReShade Preset

You may safely replace the preset without breaking the list:

1. Create an **empty mod** in MO2
2. Inside the mod, create a folder named **ROOT**
3. Place your ReShade files and preset inside **ROOT**
4. **Disable the Nymphs ReShade preset mod**
5. **Leave the base ReShade mod enabled**

This preserves compatibility with updates and avoids root conflicts.

---

## Shader & Rendering Stack

Visuals are built around:

* **Community Shaders**
* **Physically Based Rendering (PBR)** assets
* No ENB dependency

Expectations:

* Lighting is physically grounded, not cinematic
* Materials respond consistently across weather and interiors
* Performance scales predictably with hardware

This stack is chosen to support **gameplay readability**, not screenshots.

---

## Save Safety & New Games

⚠️ **New Game Required**

Because:

* Gameplay systems auto-start
* Perk distribution occurs at game start
* Custom skills initialize on first load
* Time-based systems begin tracking immediately

**Existing saves are not supported.**

Attempting to load this list mid-playthrough will result in broken progression.

---

## Custom Patches & AI Behavior

The list includes **hand-authored patches**, including:

* SkyTEST + Animallica creature AI integration
* Survival and economy balancing patches
* Conflict resolution across gameplay systems

These patches are **intentional and load-order sensitive**.

Disabling one system may have cascading effects.

---

## Safe Customization Guidelines

You may safely customize:

* ReShade presets
* UI mods (with care)
* Audio replacers
* Controller layouts

Avoid removing or replacing:

* Survival frameworks
* Progression systems
* Economy or scaling mods
* Time-based mechanics

When in doubt: **assume a system is required**.

---

## Troubleshooting Philosophy

Before reporting issues:

1. Confirm you are on a **new game**
2. Re-read **GAMEPLAY.md** expectations
3. Verify no core systems were disabled
4. Test without additional mods

Most issues arise from **expectation mismatch**, not bugs.

---

## Design Intent (Technical)

Nymphs Savage Symphony is designed to be:

* Deterministic
* Extendable
* Resistant to user error
* Clear in responsibility boundaries

This is not a sandbox modlist.
It is a **structured foundation**.

Respect the structure, and it will remain stable.
