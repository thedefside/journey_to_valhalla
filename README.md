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
Mod Manager (Preferred)
 1. Install JTV and all dependencies
 2. Start the game. This will copy all config files to the correct place.
 3. Exit the game and re-start to reload the config changes.

Manual
 1. Download all dependencies and copy to your BepInEx folder
 2. Download JTV last and copy all files to the BepInEx folder

## Information
For help requests, suggestions, bug reports, or to just follow the development, join the discord! https://discord.gg/vSEjCNF48K

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
 - Add Rancid Remains
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
 - Makes ancient root destructable with new wood drop (HundardysValheimAdditions)
 - Heavymetal ore deposits (HundardysValheimAdditions)
 - Mother Darkspider miniboss (Monsternomicon)
 - The Mourning Queen boss and altar (HundardysValheimAdditions)
 - New crafting table: Dark Forge
```
```
Deep North:
 - Frozen Corpses, Frost Serpents, Boreal Spirits, Polar Lox, Silver Golem (Monsternomicon)
 - Frostling (DoDMonsters)
 - Dvergr NPC (Monsternomicon)
 - Frometal Ore deposits (HundardysValheimAdditions)
 - Makes iceberg destructable with new drop (HundardysValheimAdditions)
 - Frost Giant (MonsterLabZ)
 - Arctic Wolf
 - Forgotten One miniboss (Monsternomicon)
 - Jotunn boss and altar (Monsternomicon)
 - New crafting table: Cold Forge
```
```
Ashlands:
 - Burned Bones, Elder Surtling, Ash Neck, Swollen Body, and Fire Drake (Monsternomicon)
 - Living Lava (DoDMonsters)
 - Minable FelMetal deposits (DoDMonsters)
 - Damned One boss and Altar (HundardysValheimAdditions)
 - New Crafting Table: Thor's Forge
```
```
Ocean:
  - Add Kraken (Disabled) (MonsterLabZ)
 ```

# Armor
There are 7 new sets of armor.
```
 - Plate Armor: Mistlands - resistent to poison damage
 - Dragon Slayer Armor: Mountains - resistent to frost damage
 - Ashlands Armor: Ashlands - resistent to fire damage
 - Barbarian Armor: Mistlands - Faster movement speed, weak to frost and fire
 - Nomad Armor: Plains - Weight carry bonus
 - Wanderer's Armor: Deep North - resistent to lightning, frost damage; weak to fire
 - Chaos Warrior Armor: Increased health and stamina regen, slow movement
```
***Terraheim armor changes are disabled

# Known issues
 - None.

# Roadmap
 - Sync the weapon configs with server

# Change log
v0.2.3
 - Update the ragdolls for the Monsternomicon mobs so the textures match
 - New Mistlands food: Liver and Onions
 - Replaced Dire Wolf with Arctic Wolf and added pelt and trophy drops
 - Remove custom recipes for Flametal weapons

v0.2.2
 - Lock progression to Mistlands -> Deep North -> Ashlands through boss drops and crafting stations
   - Dark Forge (Inscription Table) - Requires Yagluth drop to craft. Used to craft Heavy metal weapons and armor.
   - Cold Forge (Armorer's Bench) - Requires Misltands boss drop to craft. Used to craft Frometal weapons and armor.
   - Thor's Forge - Requires Deep North boss drop to craft. Used to craft Flametal weapons and armor.
 - Add new food: Banana Bread
 - Improve the appearance of the Dire Wolves and lowered the drop rate of the pelts
 - Add teirs to the Jude's Equipment armors 

v0.2.1
 - Revert change to Dark Elf drops
 - Add boss summoning drops to Deep North and Ashlands mobs
 - Disable random boss events for Deep North and Ashlands (Altars must be used to summon them)
 - Increase Dire Wolf pelt drop rate
 - Increase Frostling Core drop rate
 - Fix 'Forgotten One' Deep North miniboss spawning
 - Adjust Heavymetal, Frometal, and Flametal Pickaxe damages
 - Adjust Flametal Bow damage
 - Reduce the drop rate on frometal ore
 - Add unique item drops to the bosses to unlock the next tier progression (WIP)
 - chickens can only lay 1 egg at a time

v0.2.0
 - Update Epic Valheim Additions mod
   - Boss altars are fixed for all users and are created during world gen instead of having to build them
   - This requires the Deep North to switch back to Forgotten Biomes vegetation
   - DoDMonsters Frometal has been replaced by Huntardy's Frometal
   - Dark Elves will drop Infused Gemstones instead of scales
   - Felmetal deposits moved to Ashlands
   - Frometal recipes updated to use Huntardy's Frometal
 - Molluscan should no longer avoid water
 - Make Thor's Forge, Inscription tabel, and Armorer's Bench un-crafable
 - Add Rancid Remains to the Swamp
 - Update Chaos Warrior Armor. Unfortunately, you can no longer configure the armor values

v0.1.3
 - Remove the DoD spawner and drop files

v0.1.2
 - Use DoD Monsters Deep North Veg instead of Forgotten Biomes
 - Fix Swedish Chef and Molluscan damages
 - No more manual installation steps required thanks to ASharpPen's 'This Goes Here' mod

v0.1.1
 - Fix Obsidian Golem not doing any damage
 - Fix Kursed not loading on dedicated servers
 - Include config for latest DoDMonsters (thanks Horem!)
 - Move the Forgotten Biomes files to the config folder (thanks Alree!)
 - Turn off Storm enemies spawning in the Mountains

v0.1.0
 - Remove dependency on Nexus mods and replace with my own forks
 - Fix the movement speed modifier on weapons
 - Replace Sage Robes with Sage Vault
 - Update Chaos Warrior T1-T2 stats and recipes
 - Fixed an issue in MonsterMobs.dll where it was trying to load the prefabs again on log out

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