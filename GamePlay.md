# GamePlay  
-----------------------------------------------------------

## Sets of Skills

### What do the Classes do?
A Class provides a bonus to exp gained to its related skills (e.g. *Scout* grants bonuses to Archery and Light Armor, and *Mystic* provides bonuses to Illusion and Alteration).  
It also grants a base perk that gets stronger whenever the Class levels up (e.g. *Rogue*: gain **+2% Attack Speed per Class Level** or *Merchant*: gain **+2% better prices per Class Level**) and afterward grants a new perk for every five Class Levels.

### How do I equip a Class?
Equipping Classes happens through the MCM Menu.  
You are free to change your Class at any given moment.  
However, be warned — you will temporarily lose a Class’s skills if it's not mastered and you equip another Class.  
Alternatively, the mod also provides a *lesser power* that lets you choose your Class. To enable this, check the box under settings.  
This lesser power uses **UIExtension**, so you will not be able to use it without that dependency.

### How do I level up a Class?
By having it equipped when the player gains a level up.  
Because of this, the mod is incompatible with any mods that remove the vanilla level-up menu (the one where you can pick between Health, Magicka, and Stamina).

### What is "mastering" a Class?
Mastering a Class means that you are now free to unequip this Class without losing its perks or related skills.

### How do I master a Class?
- **Normal mode:** Once you gain the maximum level of a Class (5, 10, or 15 depending on the Class), it is automatically considered *mastered*. You can then switch to another Class without losing its granted skills.  
- **Hardcore mode:** Classes are **not** automatically mastered. You must master them manually in the *Overview Tab* of the MCM. In this mode:  
  - You can only master a limited number of Classes.  
  - Mastering cannot be reversed, so choose carefully.  
  - The number of Classes you can master is configurable under settings (after enabling Hardcore Mode).

### How do I unlock new Classes?
Some Classes have prerequisites before you can choose them.  
For example:  
- You must level the *Mage* Class to its maximum before unlocking *Occultist*.  
- You must master both *Thief* and *Mage* before unlocking *Nightblade*.

-----------------------------------------------------------

# Leveling  

# Time Based Enemy Scaling

## How It Works + How to Use
Most mods (like *Experience*) treat the vanilla experience system as part of the player’s progression — XP gain is always good and beneficial.  
This system takes the **opposite** approach: it disconnects XP gain from the player entirely and ties it to **time**.  

With this system, **leveling up is bad for you and good for your enemies.**  
The vanilla player-leveling system is now an *enemy-scaling mechanic*.  
Having level 15, for example, tells you nothing about your abilities or stats — it only reflects how strong your enemies (and the world) have become.

You don’t gain stats from leveling anymore.  
All leveling does is make enemies stronger.  
That allows the use of vanilla enemy scaling without major overhauls — you might only want to *unlevel loot* slightly, but nothing more.

Simply put:
- You can improve skills and stats without affecting your "player level".  
- The "player level" effectively becomes the **world level** — the value that determines enemy difficulty.  
- When the game says "Player Level 9", it really means *World Level 9*.  
- This value increases over time, independently of your actions.  
- Stronger NPCs get added or replaced depending on cell resets and your installed enemy overhaul mods.

----------------------------------------------------------------

# Quests Award Perk Points

Inspired by ESO’s quest system, this mod awards perk points for completing major quests.  
This complements perk overhauls that add many new perks and provides extra motivation to complete questlines.




<style>
.columns {
  display: flex;
  justify-content: space-between;
}
.column {
  width: 48%;
}
h3 {
  font-size: 1.2em;
  margin-top: 1em;
  color: #d2b48c; /* Slight gold tint if you use it for Skyrim-themed styling */
}
</style>

<div class="columns">
  <div class="column">

### Main Quest
- Bleak Falls Barrow  
- Dragon Rising  
- Diplomatic Immunity  
- The Horn of Jurgen Windcaller  
- Alduin's Wall  
- Elder Knowledge  
- The Fallen  
- Dragonslayer  

### Companions
- The Silver Hand  
- Glory of the Dead  

### College of Winterhold
- Revealing the Unseen  
- The Eye of Magnus  

### Thieves' Guild
- Darkness Returns  
- Under New Management  

### Dark Brotherhood
- Bound Until Death  
- Hail Sithis!  
- Destroy the Dark Brotherhood *(optional, see below)*  

### Daedric Quests *(optional, see below)*
- The Black Star  
- Boethiah's Calling  
- A Daedra's Best Friend  
- Discerning the Transmundane  
- Ill Met By Moonlight  
- The Cursed Tribe  
- Pieces of the Past  
- The Whispering Door  

  </div>
  <div class="column">

### Daedric Quests (cont.)
- The Break of Dawn  
- The House of Horrors  
- The Taste of Death  
- The Only Cure  
- A Night To Remember  
- The Mind of Madness  
- Waking Nightmare  

### Bard's College
- Tending the Flames  

### Civil War
- Battle for Whiterun *(both Imperial and Stormcloaks)*  
- Liberation of Skyrim *(Stormcloaks)*  
- Reunification of Skyrim *(Imperial)*  

### Dawnguard
- Beyond Death  
- Kindred Judgment  
- Lost to the Ages  

### Dragonborn
- The Temple of Miraak  
- The Path of Knowledge  
- At the Summit of Apocrypha  

### More Vanilla Sidequests
- Kyne's Sacred Trials  
- The Blessings of Nature  
- Blood on the Ice  
- The Book of Love  
- The Heart of Dibella  
- No One Escapes Cidhna Mine  
- The Wolf Queen Awakened  

  </div>
</div>


# Buying Perks  

Buy stats (**Health**, **Magicka**, **Stamina**, **Carry Weight**, **Movement Speed**) and perk points.  
Easily enable or disable everything or change prices mid-game.  
Wide price ranges (**200–100,000 gold**).  
Compatible with everything — even mods that also modify stats.

Maximum compatibility is achieved through the way stats are applied: they’re added via (almost) infinitely upgradeable **enchanted rings**, which you can equip or unequip at any time.

You can **craft and upgrade** the rings at any forge.  
They weigh nothing and don’t occupy a body slot.

Each upgrade grants:
- **+1** Health / Magicka / Stamina / Speed  
- **+10** Carry Weight  

Each ring can be upgraded **up to 10,000 times!**

While this technically counts as crafting, you’re still spending your gold to gain stats — only instead of a merchant, you’re interacting with a forge.

You can also **buy (craft) and drink the perk point potion** to earn perk points.

---

### Notes

1. The rings and the perk potion have low vendor prices, meaning they give very little Smithing experience when crafted.  
2. Don’t forget to **equip the ring** after upgrading it.  
3. To declutter the crafting menu, recipes only appear if you have the **required amount of gold**.

---

### Advanced Upgrading

After upgrading your first ring 100 times, you’ll start crafting a second ring.  
Once you upgrade that one 100 times, you can **merge two level 100 rings** into one.  
You can then continue merging multiple rings:

- Two level 100 rings → one level 200 ring  
- Level 1000 rings can also merge  
- Eventually, you can forge a **+10,000 HP ring**, if you wish  

You don’t spend any gold when merging rings together.



