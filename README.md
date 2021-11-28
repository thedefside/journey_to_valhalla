# Description
The goal of this set up is to simply complete the game without straying too far from vanilla. It is based off of monsternomicon, with weapons from Huntardy's Valheim Additions, and some new enemies and metals from DoDMonsters.

# Click the image for a short video preview
[![Journey To Valhalla](https://img.youtube.com/vi/nzWcYK7BIyQ/0.jpg)](https://www.youtube.com/watch?v=nzWcYK7BIyQ)

# Features
 - The first 5 biomes are largely untouched. 1 or 2 enemies were added per biome, some friendly NPCs, and some new weapons
 - 5 New metals and 3 complete weapon sets for unfinished biomes
 - Elemental swords
 - Boss altars for Mistlands, Ashlands, and Deep North
 - 7 top tier armor sets each with special characteristics
 - Storm Wolves and Drakes that spawn during rain storms

# Installation

## Manual (Recommended)
 1. Download all dependencies first
 2. Extract contents to the appropriate folder (i.e. if the download has a config folder, put all the files in that config folder in your BepInEx\Config folder. If there is a plugins folder, put those files in you BepInEx\plugins folder.)
 3. Download Journey To Valhalla
 4. Extract to BepinEx folder

## Mod Manager
 1. Install all dependencies first
 2. Install Journey To Valhalla to over-write the default configs for the dependencies
 3. Manually move the files from `BepInEx\plugins\thedefside-Journey_To_Valhalla\DasSauerkraut-Terraheim` to `BepInEx\plugins\DasSauerkraut-Terraheim`. If you skip this step the armor recipes will be wrong.


# Biomes
```
Meadows:
 - Add butterflies (MonsterLabZ)
 - Add Chickens (ChickenBoo)
```
```
Black Forest:
 - Add Ghost Warrior (MonsterLabZ)
```
```
Swamp:
 - Add Molluscan (MonsterLabZ)
```
```
Mountains:
 - Add Obsidian Golem (MonsterLabZ)
```
```
Plains:
 - Add Berserker random spawns
 - Add New Fulings (MonsterLabZ)
 - Add Groozer (Tar Oozer)
```
```
Mistlands:
 - Dark Elves, Dark Elder, Dark Spiders, Darksquitos (Monsternomicon)
 - Voidling (DoDMonsters)
 - Minable FelMetal deposits (DoDMonsters)
 - Makes ancient root destructable with new wood drop (HundardysValheimAdditions)
 - Heavymetal Scale drops (HundardysValheimAdditions)
 - Mother Darkspider miniboss (Monsternomicon)
```
```
Deep North:
 - Frozen Corpses, Frost Serpents, Boreal Spirits, Polar Lox, and Jotunn (Monsternomicon)
 - Ice Golem, Dire Wolf, Frostling (DoDMonsters)
 - Dvergr NPC (Monsternomicon)
 - FrometalOre deposits (DoDMonsters)
 - Makes iceberg destructable with new drop (HundardysValheimAdditions)
 - Frost Giant (MonsterLabZ)
 - Forgotten One miniboss (Monsternomicon)
```
```
Ashlands:
 - Burned Bones, Elder Surtling, Ash Neck, Swollen Body, and Fire Drake (Monsternomicon)
 - Living Lava (DoDMonsters)
```
```
Ocean:
  - Add Kraken (Disabled) (MonsterLabZ)
 ```

# Armor
There are 7 new sets of armor. All are top-tier with identical armor stats, but each provides different strengths and weaknesses
```
 - Plate Armor: Mistlands - resistent to poison damage
 - Dragon Slayer Armor: Deep North - resistent to frost damage
 - Mistlands Armor: Ashlands - resistent to fire damage
 - Barbarian Armor: Faster movement speed, weak to frost and fire
 - Nomad Armor: Weight carry bonus
 - Wanderer's Armor: resistent to lightning, frost damage; weak to fire
 - Chaos Warrior Armor: Increased health and stamina regen, slow movement
```

# Known issues
 - The boss altars don't work for Servers. For clients you may need to log out (not quit) and log back in to your world to summon the boss.

# Roadmap
 - Lock progresion to Mistlands -> Deep North -> Ashlands through boss drops
 - Replace Forgotten Biomes with a JVL based solution

# Change log
v0.1.0
 - Remove dependency on Nexus mods and replace with my own forks
 - Fix the movement speed modifier on weapons
 - Replace Sage Robes with Sage Vault
 - Update Cahos Warrior T1-T2 stats and recipes
 - Fixed an issue in MonsterNobs.dll where it was trying to load the prefabs again on log out

v0.0.9
 - Updated the look of the Dark Elves
 - Disabled the dark elf raids

v0.0.8
 - Mourning Queen event can only happen in the Mistlands
 - Fixed the drops for Mourning Queen and court
 - Updated dependency for Forgotten Biomes

v0.0.7
 - Added everything back to the Mistlands world generation
 - Balance all Huntardy's weapons to be in line with vanilla

v0.0.6
 - Removed Goblin ships (causing errors and severe FPS drops)
 - Removed Silver Golem and added Polar Lox to Deep North
 - Changed the name of the 'Mistlands' armor, since it has nothing to do with the Mistlands
 - Changed the prefabs for the Thunder Drake and Fire-Breathing Drake to the new DoD prefabs (Thanks Horem!)
 - Reworked Storm Fenring encounter
 - Made the Dark Elf raids scale as you progress (instead of adding them all after Bonemass)
 - Fixed Frost Giant's Damage
 - Removed ValheimPlus config
 - Dvergr doesn't despawn at night

v0.0.5
 - Fixed custom textures not loading on dedicated servers
 - Toned down the Dark Elves a bit
 - Added Goblin ships to the Ocean
 - Added Kraken to the Ocean, but disabled by default. Enable at your own risk.

v0.0.4
 - Dark Elves always drop Heavyscale
 - Update Forgotten Biomes dependency
 - Storm enemies no longer spawn in the mountains

v0.0.3
 - removed OdinPlus-Digitalroots_GoldBars-1.2.0 dependency
 - update ChickenBoo
 - Add Groozer (Tar Oozer) to Plains
  
v0.0.2
 - Update Jude's equipment
 - Rework armor recipes
 - Increase Voidling Core drop rate
 - Made Growths re-spawn
 - Decrease Mother Darkspider spawn rate

v0.0.1
 - Combined DoD, MonsterLabz, and Monsternomicon files together under the JTV (Journey To Valhalla) folder
 - Add Gold Bars mod. 
 - Jude's Equipment:
   - fixed the forge levels
   - changed the recipe for Barbarian armor to use Steel and Gold instead of Black Metal
   - increase Simple Backpack durability and made it so it's not destroyed when it breaks
 - Terraheim - Disabled most of the Flametal items
 - Added Valheim Additions mod