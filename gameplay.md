# ⚠️ READ THIS FIRST

This modlist is **not plug-and-play** and **not a power fantasy**.

* **All core systems start automatically on a new game**
* Progression is **slow, deliberate, and consequence-driven**
* Ignoring survival, time pressure, or preparation **will get you killed**
* Many systems are **interconnected** and assume others are active

📌 **Before playing, modifying, or troubleshooting**, you are expected to read this entire document.

If you attempt to disable or replace systems without understanding how they interact, instability and balance issues are expected.

---

# Gameplay Overview – Nymphs Savage Symphony

Nymphs Savage Symphony restructures Skyrim’s gameplay into a **survival-driven, progression-focused RPG** where preparation, time, and decision-making matter more than raw player level.

📌 **Important New Game Behavior**

* **All gameplay systems start automatically on a new game**
* You begin with **+3 perk points** to establish an early build direction
* A **Custom Skills Framework** is integrated for extended, modular progression
* A **custom-made Creature AI patch** combining **SkyTEST** and **Animallica** creates a dense, reactive ecosystem — a true **hunter’s paradise** where wildlife behavior, danger, and opportunity feel alive

Rather than scaling the world around the player, the player must grow **into** the world.

This document explains how the major gameplay systems interact, in the order they are experienced during play. Each section includes a reference link to the original mod author’s description page on Nexus for further details.

---

## 1. Survival Begins in the Wild

### **Campfire – Complete Camping System**

Before anything else, living off the land becomes a central theme.

Campfire provides a rich, standalone **camping and outdoor survival system**:

* Build campfires to cook, rest, and avoid exposure
* Craft tents, bedrolls, backpacks, and tools
* Interact with followers around fires
* Collect wood and supplies in the environment

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/667](https://www.nexusmods.com/skyrimspecialedition/mods/667)

---

## 2. Harsh Environments Shape Gameplay

### **Frostfall – Hypothermia Camping Survival**

Environmental conditions become a threat, not background flavor.

Frostfall tracks temperature, weather, and exposure in real time:

* Hypothermia and cold water survival mechanics
* Gear and heat sources matter for survival
* Weather and terrain influence your state
* Deep immersive survival effects without excessive tedium

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/671](https://www.nexusmods.com/skyrimspecialedition/mods/671)

---

## 3. The Hunt Defines the Early Game

### **Hunterborn – Hunting, Skinning, and Survival Expansion**

Hunting is transformed into a deep, skill-driven survival activity:

* Field dress and skin animals manually
* Harvest resources based on tools and skill
* Hunting takes time, preparation, and awareness
* Animal remains persist in the world

Hunterborn integrates directly with survival, economy, and crafting systems, making wildlife a core pillar of progression rather than background content.

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/7900](https://www.nexusmods.com/skyrimspecialedition/mods/7900)

---

## 4. Wildlife Becomes an Ecosystem

### **SkyTEST + Animallica – Custom Creature AI & Population Overhaul**

The world’s wildlife is no longer static or predictable.

**SkyTEST** introduces advanced animal AI:

* Pack behavior and predator logic
* Territorial responses
* Fleeing, stalking, and ambush behavior

**Animallica** expands creature variety and distribution:

* New species and variants
* Denser wilderness populations
* More organic encounters

A **custom AI patch** blends both mods into a unified ecosystem, creating a dangerous, rewarding, and reactive wilderness — ideal for hunters, travelers, and survival-focused playstyles.

**References:**

* [https://www.nexusmods.com/skyrimspecialedition/mods/1104](https://www.nexusmods.com/skyrimspecialedition/mods/1104)
* [https://www.nexusmods.com/skyrimspecialedition/mods/20456](https://www.nexusmods.com/skyrimspecialedition/mods/20456)

---

## 5. Early Progression — Identity Over Levels

### **Disparity – Player Character Class and Race Overhaul**

Your character’s identity meaningfully shapes progression from the start:

* Racial traits matter long-term
* Attribute distribution affects survivability
* Builds feel distinct early
* Power curves are flattened and intentional

Disparity ensures the early game is defined by **who you are**, not just what level you’ve reached.

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/110789](https://www.nexusmods.com/skyrimspecialedition/mods/110789)

---

## 6. Develop Your Abilities — Skills With Purpose

### **Set of Skills + Custom Skills Framework**

Skill progression rewards deliberate investment:

* Skills improve through meaningful use
* Custom skills expand progression paths
* Builds specialize instead of converging

The Custom Skills Framework allows future expansion without destabilizing core systems.

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/55535](https://www.nexusmods.com/skyrimspecialedition/mods/55535)

---

## 7. Quests Become Progression Drivers

### **QAPP – Quests Award Perk Points**

Narrative progression now drives mechanical growth:

* Perk points are awarded through quest completion
* Story engagement replaces grind-based leveling
* Major decisions carry tangible rewards

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/33081](https://www.nexusmods.com/skyrimspecialedition/mods/33081)

---

## 8. Power Has a Price — Economy and Crafting

### **Complete Crafting Overhaul Remastered**

Crafting is rebalanced into the survival economy:

* Crafting progression is slower and deliberate
* Equipment value is restructured
* Resource management matters
* Crafting supports survival, not dominance

Crafting is a strategic choice, not a shortcut to power.

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/28608](https://www.nexusmods.com/skyrimspecialedition/mods/28608)

---

## 9. The Cost of Power

### **Corruption – Artifacts and Consequences**

Powerful artifacts extract a toll:

* Using certain items causes corruption
* Effects persist and evolve over time
* Long-term consequences shape your character

The temptation of power becomes a narrative and mechanical risk.

**Reference:** [https://www.nexusmods.com/skyrimspecialedition/mods/167331](https://www.nexusmods.com/skyrimspecialedition/mods/167331)

---

## 10. Time Shapes the World

### **Time-Based Enemy Scaling**

The world evolves independently of the player:

* Enemies grow stronger as time passes
* Delays and stagnation increase danger
* Preparation becomes mandatory

Progression is measured in **time survived**, not levels gained.

---

## Visual Pipeline & Modlist Infrastructure

### **Root Builder & ReShade Support**

The list uses **Root Builder** and **ReShade** for clean visual management.

You may use your **own preferred ReShade preset**:

1. Create an empty mod
2. Inside it, create a folder named **ROOT**
3. Place your ReShade files inside the ROOT folder
4. Disable the **Nymphs ReShade preset mod**
5. **Keep the base ReShade mod enabled**

This allows full customization without breaking the list structure.

📘 **Technical Reference**  
For installation structure, Root Builder usage, ReShade customization, save requirements, and troubleshooting expectations, see **[TECHNICAL.md](./TECHNICAL.md)**.

Gameplay systems assume the technical structure described there is intact.


---

## Resulting Experience

Together, these systems create a gameplay loop where:

* Survival defines the early journey
* Wildlife feels alive and dangerous
* Progression is intentional and earned
* Crafting and economy reinforce restraint
* Power always carries consequences

Nymphs Savage Symphony does not ask *“What level are you?”*
It asks *“Are you prepared?”*

---

## Design Intent Summary

Nymphs Savage Symphony aims to deliver:

* A **true survival-driven Skyrim experience**
* Deep hunting and ecosystem gameplay
* Reduced artificial scaling
* Long-term character consequence
* A stable foundation for expansion

This is not a power fantasy.
It is a **living, reactive RPG foundation**.
