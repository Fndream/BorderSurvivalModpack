## 📓 Introduction

This is a vanilla border survival map series centered on **vanilla survival** gameplay. Start from a confined space, gather resources with wisdom, challenge day and night with courage, and expand the world border with experience. Suitable for players with some knowledge of vanilla mechanics.

## 📗 Before You Play

- This series is not a conventional modpack. It consists of a **dedicated map** and a **core datapack**. The modpack includes only auxiliary mods. **After installing the modpack**, you **must import the dedicated map** to play properly!
- **There is no difference from vanilla survival in this series**. The first player of this series liked the visual effect of the world border, and thus the initial version of this series was born.
- Due to the border limitation, alternative acquisition methods for biome or structure exclusive resources have been introduced. These mechanics are called **Core Features**, along with additional **Expansion Features**.
- **Core Features** enhance certain vanilla mechanics, giving them more uses. **Expansion Features** add new gameplay mechanics and world-setting lore.
- When facing difficulties, consulting vanilla mechanics described in the Minecraft wiki, as well as the **Core Features** and **Expansion Features** described below, may provide effective help.
- It is recommended to play with your preferred **resource pack** and **shader pack**.
- Supported languages: **Simplified Chinese, Traditional Chinese, Classical Chinese (Recommended), English.**
- If you switch languages in-game, you must exit and re-enter the save for some text to update correctly.
- **Note:** This document is a translation from the [Chinese version](https://github.com/Fndream/BorderSurvivalModpack/blob/master/README.md), provided by DeepseekAI. Please verify carefully.

---

## 🌊 Core Features

### 📕 About the World Border
The world border is a feature added in Minecraft 1.8. It is a translucent, dynamic, diagonal light-blue wall.

**The border has three states:**
- **Normal**: Color is blue.
- **Shrinking**: Color is red.
- **Expanding**: Color is green.

**Border properties:**
- Players cannot cross the border or interact with blocks outside it.
- Mobs will not spawn outside the border.
- Workstation blocks and certain redstone components outside the border cannot function properly.
- There is no air outside the border. If you leave the border beyond a certain distance, you will take suffocation damage.

### 🥬 Border Energy
- Border Energy is essentially the **size of the world border**.
- You can perform a **Border Upgrade** by consuming **experience levels** to increase border energy.

### 💠 Border Mode
- Contains two modes: **Locked** and **Day-Night**, switchable in-game.
> The Day-Night mode is an Expansion Feature; see the Expansion Features section.

### 📋️ Function Signs
Function sign monuments provided by the map, containing the following three function signs.

- **Upgrade**: Consumes experience levels to increase border energy.
- **Mode**: Switches between Day-Night mode and Locked mode. Cannot be used during the Eternal Night state.
- **Artificer**: Summons the Divine Artificer at the player's current location. Can only be summoned once per game day, and only one can exist in the world at a time.

> Function signs have a hardness of -1 and a blast resistance of 3,600,000.

> ❗ If a function sign is destroyed, you can obtain it via the following command and place it in Creative Mode:
> ```
> /function border_survival:get_sign
> ```

---

### 🎣 Fishing
While fishing, you may obtain some biome-specific items.

- **Added to Junk loot pool**: Seagrass, Kelp, Sugar Cane, Cactus, Bamboo, Sea Pickle, Cocoa Beans, Prismarine Shard, Prismarine Crystals, Coral, Coral Fan, Chorus Flower.
- **Added to Treasure loot pool**: Budding Amethyst, Obsidian, Ice, Packed Ice, Blue Ice.

### 🐱 Cat
- **Added to Gifts**: Leaves, Diamond.

### 🌹 Sniffer
- **Added to Digging**: Dandelion, Poppy, Blue Orchid, Allium, Azure Bluet, Tulip, Oxeye Daisy, Cornflower, Lily of the Valley, Open Eyeblossom, Spore Blossom, Dead Bush.

### 🐽 Piglin
- **Added to Bartering**: Blaze Rod, Nether Wart, Wither Skeleton Skull.

### 💎 Loot Chests
- **Added to Plains Village House**: Sunflower, Rose Bush, Peony, Lilac, Pink Petals, Wildflowers, Leaf Litter, Glow Lichen.
- **Added to Savanna Village House**: Armadillo Scute, Bush, Firefly Bush.
- **Added to Village Mason House**: Pointed Dripstone, Sulfur Spike.
- **Added to Shipwreck Supply Chest**: Pale Moss Block, Pale Hanging Moss.
- **Added to Buried Treasure**: Turtle Egg.
- **Added to End City Treasure**: Shulker Shell.
- **Added to Bastion Remnant Hoglin Stable**: Crimson Nylium, Warped Nylium.
- **Added to Trial Chamber Vault - Normal, Trial Chamber Ominous Vault - Normal**: Breeze Rod.

### ⚫ Ender Dragon
- Upon defeating the Ender Dragon, a **Dragon Head** will generate on the End Portal.
- Defeating a respawned Ender Dragon will also generate a **Dragon Egg and Dragon Head** on the End Portal.

###  ⬛ Deepslate
- When lava flows and interacts with water below Y=0, Deepslate or Cobbled Deepslate is formed.

### 💡 Crafting Recipes

> ❗ Recipes are automatically unlocked upon obtaining the corresponding materials. They can be viewed via the green book on the left side of the crafting table.

![recipe](https://files.seeusercontent.com/2026/07/30/aMg0/Snipaste_2026-07-30_19-53-54.png)

> Spawners can be obtained by mining them with a Silk Touch enchanted tool.  
> Spawn conditions for certain spawners:  
> **Spawn Range**: Horizontal radius 4 blocks, vertical radius 1 block, ignores biome.  
> **Slime**: Does not need to be in a slime chunk.  
> **Iron Golem**: A full block must exist below the spawnable location.  
> **Animals**: A grass block must exist below the spawnable location.  
> **Aquatic Hostile Mobs** (e.g., Drowned/Guardian/Elder Guardian): Water (including source/flowing water) must exist within the spawn range.  
> **Aquatic Animals** (e.g., Squid/Cod/Salmon/Dolphin): Water (including source/flowing water) must exist within the spawn range, and the water location must be within the ocean range (Y50-63).  
> **Glow Squid**: Water (including source/flowing water) must exist within the spawn range, and the water location must be within the cave range (below Y30).

### 🌿 Carpet Series (Carpet Mod & Addition)
**✅ The following features are enabled by default:**
- Large Barrels: When two barrels are connected back-to-back, the container space of both barrels can be used simultaneously.
- Better Bone Meal: Bone meal can fertilize Cactus, Sugar Cane, and Lily Pads.
- Renewable Sand: Cobblestone crushed by a falling Anvil transforms into Sand.
- Soul Sand Conversion: Mobs that die from fire on Sand transform the Sand into Soul Sand.
- Renewable Sponge: A Guardian struck by lightning transforms into an Elder Guardian.
- Renewable Wither Skeleton: A Skeleton struck by lightning transforms into a Wither Skeleton.
- Renewable Coral: Coral can be fertilized with bone meal.
- Shulker Respawn: Shulkers respawn in End Cities.
- Spider Jockeys drop Enchanted Golden Apples.
- Shulker Box Stacking: Empty Shulker Boxes on the ground can be stacked into 1 group.
- Empty Shulker Boxes Always Stackable: Empty Shulker Boxes are also stackable in the inventory.
- Fake Player Residency: Fake players are preserved when you log out.
- Fake Player Fishing: Fake players can auto-fish.
- Fake Player Backpack: Right-click to open a fake player's backpack.
- Fake Player Ender Chest: Shift-right-click to open a fake player's ender chest.

### 📙 Grindstone Enhancement (grind-enchantments mod)
- You can use a Grindstone to separate all enchantments from an item onto a book, or separate the first enchantment from an enchanted book onto another book.

## 🌙 Expansion Features
### 💠 Border Mode
- Contains two modes: **Locked** and **Day-Night**, switchable in-game.

### 🔵 Locked Mode
- The regular default mode.

### 🌗 Day-Night Mode
- Daytime in Day-Night mode is no different from Locked mode.
- During the night of Day-Night mode, the **mob cap** is increased to **140**, the **number of mobs per spawn cycle** is increased to **10**, the **chance of mobs wearing armor** is increased to (50% * regional difficulty), and mobs will spawn **regardless of light level**.
- During the night of Day-Night mode, if the border energy is at least level 50, the space is doubled in size.

### 🌙 Day-Night Mode - Eternal Night
- When night in Day-Night mode is about to transition to day, if the border energy is at least **level 100**, the Eternal Night will descend.
- After the Eternal Night descends, Eternal Night Knights from another realm will appear around the world spawn point.
- Influenced by the Eternal Night Knights, time is locked at the moment of their arrival, and the world plunges into an eternal thunderstorm.
- Only by defeating all the descending Eternal Night Knights can their influence on the world be lifted.
- Afterwards, after experiencing or sleeping through **0-4** nights of Day-Night mode, the Eternal Night will descend again.
> Switching to Peaceful mode will immediately end the Eternal Night and prevent attempts to enter it.

### 🧊 Eternal Rainy Night / Eternal Snowy Night
- After the Eternal Night descends, influenced by the Eternal Night Knights, the border may take on one of six colors: **Pale, Crimson, Dusk Orange, Radiant Gold, Deep Blue, Dark Purple**.
- Depending on the degree of influence, the world climate will become disordered.
- When the border in the Eternal Night state is **Radiant Gold, Dusk Orange, or Deep Blue**: All biomes will experience abnormal rainfall, regardless of being cold or warm. The chance of mobs wearing armor is increased to (60%/70%/80% * regional difficulty).
- When the border in the Eternal Night state is **Dark Purple, Crimson, or Pale**: All biomes will experience abnormal snowfall, regardless of being warm or cold. The chance of mobs wearing armor is increased to (90%/100%/110% * regional difficulty).
- After all Eternal Night Knights are defeated, the world climate returns to normal, the border color gradually recovers, and the color will foreshadow the arrival of the next Eternal Night.
> Observing the moon phase changes in the Day-Night mode time bar can also predict the moment of the next Eternal Night's descent.

> **❗ The Eternal Snowy Night will continuously cause snow accumulation and ice formation across all biomes. If you do not want snow to affect your save's terrain, as the first thing after entering the game, you must use the following command to set the snow accumulation height to 0 before the Eternal Night descends:**
> ```
> /gamerule max_snow_accumulation_height 0
> ```

### 🐎 Eternal Night Knights
- The maximum health of Eternal Night Knights increases with border energy.
- When no players are nearby, Eternal Night Knights continuously regenerate health.
- When an Eternal Night Knight takes damage, it disrupts the world, spawning more monsters.
- Upon being defeated by a player, an Eternal Night Knight drops a random Dimensional Treasure Chest.
- Additionally, as they are Bugs of the World (bug), all monsters seek to eliminate them.
> Eternal Night Knights only appear at the highest open-air location within a 16-block square radius around the world spawn point. For cave-type maps, the spawn location is at most Y96.  
> Eternal Night Knights are extremely dangerous. It is recommended to have adequate defense and healing before attempting armed combat.  
> Eternal Night Knights will not leave their current dimension and will not ride vehicles.

### 💥 Eternal Night Legions
- Every time you survive **3** Eternal Nights, the next Eternal Night will bring the **Undead Legion** or **Illager Legion**.
- Every time you survive **8** Eternal Nights, the next Eternal Night will bring the **Eternal Night Legion**.

### 💙 Eternal Heart
- Upon being defeated by a player, the legion leader drops an **Eternal Heart**.
> **Right-click to use** it to destroy the Eternal Heart. During the current or next Eternal Night, the Eternal Night Knights will no longer be united.  
> The Eternal Heart can also be used as a Heart of the Sea.

### 🏹 Eternal Divine Weapons
- Upon being defeated by a player, an Eternal Night Knight has a **1%** chance to drop the weapon it is holding.
- If the player holds a Looting weapon in their main hand, each level of Looting increases the plunder success rate by **6.67%**.
> Eternal Divine Weapons have the Curse of Vanishing and cannot be destroyed by fire or lava.  
> Unenchanted Eternal Divine Weapons can be purified and returned to their origin as Night Spirit Divine Weapons.

### 🍖 Drops
- Mobs defeated by **Eternal Night Knights, Wardens, Elder Guardians, Guardians, and Iron Golems** are counted as being defeated by a player.

---

### 🐈 Border Sustainer
- The Sustainer descends at the world spawn point and is responsible for maintaining the stability of the border energy.
- If no Sustainer exists near the world spawn point, border energy will continuously drain.
- If the Sustainer is too far from the world spawn point, it will attempt to return there.
- If the Sustainer dies, it will descend again at the world spawn point after some time.
- Additionally, as a Bug of the World (bug), all monsters seek to eliminate it.
> When the Sustainer is near the Divine Artificer, it provides healing to nearby players.  
> The Sustainer is a baby cat and can be tamed and given gifts normally.  
> The Sustainer will not leave its current dimension and will not ride vehicles.

### 🔆 Divine Artificer
- Has broken the laws of the world and shares a deep origin with the Eternal Night Knights. From him, you can exchange for items that transcend common sense.
- Additionally, as a Bug of the World (bug), all monsters seek to eliminate him.
> The Divine Artificer is an Armorer Villager and can breed and restock normally.  
> The Divine Artificer is not considered to exist when not in a loaded chunk.

### 🐞 Bugs of the World
- Bugs of the World targets draw the aggro of all monsters within a horizontal distance of 384 blocks.
- When a monster is above a Bug of the World target, its vertical pursuit distance is infinite blocks.
- When a monster is below a Bug of the World target, its vertical pursuit distance is 16 blocks.
- While pursuing a Bug of the World target, if a player comes within line of sight, the monster will prioritize attacking the player.
> Endermen will not naturally switch targets to players who haven't looked at them.  
> Evokers pursue Bugs of the World targets with both horizontal and vertical distances of 384 blocks.  
> When a Drowned is pursuing a Bug of the World target, if the Euclidean distance to the target is ≤16 blocks, it gains wallhack vision.  
> When a Creeper is pursuing a Bug of the World target, if the Euclidean distance to the target is ≤8 blocks and the vertical distance is ≤4 blocks, it gains wallhack vision. If its pathfinding is blocked, it will instantly ignite itself.  
> Creepers will not actively flee from Bugs of the World targets.

### 🪵 Flawless Spirit Materials
- Immortal spirit materials forged by the Divine Artificer from a Chaos Star, fused from the energies of the three dimensions. They possess the Unbreakable trait.
- Flawless Spirit Materials can be infused into the Border Upgrade function sign to increase the border energy by a certain number of levels.

### ✨ Flawless Spirit Tools
- Spirit tools forged by the Divine Artificer from Flawless Spirit Materials. They possess the Unbreakable trait.
- Some Flawless Spirit Tools provide special effects when held in the offhand:
- **Chaos Star**: Regeneration II
- **Spirit Shears**: Haste II
- **Spirit Brush**: Fire Resistance
- **Spiritguard Shield**: Absorption V
- **Spirit Lure Rod**: Speed II
- **Warped Spirit Lure Rod**: Speed II
- **Blessing of the Sea**: Conduit Power
- **Vast Sea Spirit Trident**: Dolphin's Grace
- **Whirling Spirit Mace**: Strength III
- **Soaring Spirit Wings**: Slow Falling
- **Soaring Spirit Wingplate**: Slow Falling
- **Spirit Wolf Armor**: Resistance II; when worn by a wolf, additionally provides Instant Health.
- **Spirit Flint and Steel**: The holder, Eternal Night Knights, Divine Artificer, Illagers, Witches, Wandering Traders, and Trader Llamas constantly glow.

### 📦 ? ? ?
- A treasure chest forged by the Divine Artificer from a Spirit Emerald. When placed and opened:
- High chance to open a random Structure loot chest.
- Medium chance to open a random Village loot chest.
- Low chance to open a random Treasure loot chest.

### 🍀 Spirit Emerald
- **Convert Materials**: Can be converted into a certain amount of basic building materials via a Stonecutter.
- **Gather Items**:
    - **General Spirit Emerald**: When held in the offhand or placed in any Item Frame, it gathers nearby dropped items within a `33x33x33` area to its own location.
    - **Container Spirit Emerald**: If the Item Frame containing the Spirit Emerald is attached to a Chest, Barrel, or Shulker Box, it will only gather item types that already exist in the container. If attached to an empty container, it will not gather any items.
    - When multiple **General Spirit Emeralds** are near a dropped item entity, the item is gathered by the closest Spirit Emerald.
    - When multiple valid **Container Spirit Emeralds** are near a dropped item entity, the item splits into multiple item entities, evenly distributed among those Spirit Emeralds.
    - When both **General Spirit Emeralds** and **Container Spirit Emeralds** are near a dropped item entity, the item is first gathered and stacked by the closest former, then split and distributed by the latter.
> The Spirit Emerald can also be used as an Emerald.

## 🌕 Unique Features

> ❗ The following features are unique to their respective maps and only take effect in those maps.

### 🌸 Guard - Mountain of Cherry Protection (Cherry Blossom Valley)
- <del>A Divine Artificer exists, and all monsters seek to eliminate him. When the Divine Artificer dies, border energy drains.</del> (Replaced by the Border Sustainer)

### 🌑 Eternal Night - Night Island Garden
- The world cycles only through night, with no daytime.
- Day-Night mode is locked and cannot be switched.
- Villager daily schedules are reversed; villagers and players can only sleep after tick 23000.
- <del>A Sustainer exists, and all monsters seek to eliminate it. When the Sustainer dies, border energy drains.</del> (Permanently implemented)

### 🔥 Void Portal - Persisting Worlds
- Build a portal frame using the themed block of the respective map and activate it with a fire source to travel to different dimensions.
- Unlike Nether Portals, regardless of the coordinates, a Void Portal will search for the nearest portal within a 128-block radius centered on the world spawn of the target dimension. If none is found, a portal structure will be generated near the world spawn.
- Each Persisting World dimension has independent border energy, except for the Nether and the End.
- Each Persisting World dimension has a Sustainer, except for the Nether and the End.
- Eternal Night Knights will only descend in the Overworld or Persisting World dimensions that have at least **level 100** border energy, excluding the Nether and the End.
- If multiple dimensions simultaneously have border energy above **level 100**, the Eternal Night Knights will randomly descend in one of those dimensions that has at least one non-spectator player.
- If no dimension meets the criteria, they will first attempt to descend in the Overworld. If the Overworld's border energy is below **level 100**, they will not descend.

---

## 🧭 Maps

> 1. **You must use the dedicated map save.** The game cannot be played properly if you create a new world yourself.
> 2. Maps are sorted by **type and overall difficulty from high to low**. Higher star ratings generally indicate higher survival or resource acquisition difficulty.

<details>
<summary>Click here to expand the map list</summary>

### 🔥 **Void Thirteen Worlds — Persisting Worlds**
🔆 **Type: 6th Anniversary — Void Type**  
✨ **Difficulty: ⭐⭐⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/18/jBs5/9f7e2b5.jpg" width="400">

---
> A void realm, blocks form the frame, source fire ignites, enter the persisting world...
---
### 🌑 **Cursed Eternal Night — Night Island Garden**
🥥 **Type: 5th Anniversary — Floating Island Type**  
⚡ **Difficulty: 🌟🌟🌟🌟🌟**

<img src="https://files.seeusercontent.com/2026/06/26/C9dl/36aad17.jpg" width="400">

---
> A realm forsaken by the heavens, a cycle of curses and eternal night...  
> Dance with the demons... Live with the chaos...
>
> Portal: Pale Moss Block
---
### 🌿 **Axolotl World — Lush Caves**
🛖 **Type: 4th Anniversary — Cave Type**  
✨ **Difficulty: ⭐⭐⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/zs8K/d40646d.jpg" width="400">

---
> Legend speaks of a land of axolotls...  
> Its flora was boundless, its darkness limitless...  
> Its children danced in the pools, its monsters covered the hollow earth...  
> It was a lush and magnificent cave, a barren and impoverished world...  
> A dimension of deep darkness, yet a paradise dotted with starlight...  
> —From a lost diary of a Divine Artificer
>
> Portal: Moss Block
---
### 🌺 **Hidden Paradise — Cherry Blossom Valley**
🍀 **Type: 3rd Anniversary — Vanilla Type**   
✨ **Difficulty: ⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/xfV3/29cb24f.jpg" width="400">

---
> Once, a Divine Artificer was imprisoned in a cherry blossom valley.  
> Now, when the moonlit night descends, endless chaos still arises here.  
> But what's different is, the Sustainer has taken over the guard of this realm...
>
> Portal: Cherry Wood
---
### ⛅ **Void**
🔆 **Type: Void Type**  
⚡ **Difficulty: 🌟🌟🌟🌟🌟**

<img src="https://files.seeusercontent.com/2026/06/26/3anO/da8f020.jpg" width="400">

---
> A world where both the Overworld and the Nether are void.  
> **Recommended to attempt only with ample time and thorough knowledge of vanilla and core features.**
---
### 🦠 **Painted Caverns — Sulfur Caves**
🛖 **Type: Cave Type**  
✨ **Difficulty: ⭐⭐⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/tH4c/f2bd16e.jpg" width="400">

---
> 26.2 themed map, an underground world like an ancient painted scroll.
>
> Portal: Chiseled Sulfur

---
### 🌳 **Sacred Lake and Peaks — Spruce Floating Island**
🥥 **Type: Floating Island Type**    
✨ **Difficulty: ⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/Ac4g/18eae77.jpg" width="400">

---
> A floating solitary island surrounded by spruce, a sacred ground for builders.  
> **This map's terrain was generated by kinbee's [RevampedFloatingIslands](https://modrinth.com/datapack/revamped-floating-islands) datapack!**
>
> Portal: Spruce Wood

---
### 🌿 **Land of Abundant Rain — Lush Floating Island**
🥥 **Type: Floating Island Type**  
✨ **Difficulty: ⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/kJw5/5d446c5.jpg" width="400">

---
> A rainforest island atop a massive lush floating island.  
> **This map's terrain was generated by kinbee's [RevampedFloatingIslands](https://modrinth.com/datapack/revamped-floating-islands) datapack!**
>
> Portal: Clay

---
### 🧊 **Realm of Extreme Ice — Frozen Icebergs**
💠 **Type: Amplified**  
✨ **Difficulty: ⭐⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/A6im/9e53fe7.jpg" width="400">

---
> An extremely cold region with towering mountain peaks.  
> Ceiling-piercing ice spikes, a boundless frozen ocean.
>
> Portal: Blue Ice

---
### 🌴 **Coral Rain Bamboo Land — Rainforest Island**
🍀 **Type: Vanilla Type**  
✨ **Difficulty: ⭐⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/eI5s/0d02daf.jpg" width="400">

---
> An island containing a coral sea, rainforest, and bamboo forest.
>
> Portal: Jungle Wood

---
### 🌿 **Pure Land in the Marsh — Marsh Savanna**
🍀 **Type: Vanilla Type**  
✨ **Difficulty: ⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/oH8i/dd7d1bf.jpg" width="400">

---
> 1.19 themed map, an acacia plains and plains village surrounded by a mangrove swamp.
>
> Portal: Mud

---
### 🪵 **Valley Forest Lake — Verdant Forest Lake**
🍀 **Type: Vanilla Type**  
✨ **Difficulty: ⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/hlC8/d4ae6bd.jpg" width="400">

---
> 1.20 themed map, a cherry blossom forest and a plains heart lake surrounded by steep mountains.
>
> Portal: Oak Wood

---
### 🌸 **Summit Cherry Blossom — Cherry Blossom Plain**
🍀 **Type: Vanilla Type**  
✨ **Difficulty: ⭐⭐**

<img src="https://files.seeusercontent.com/2026/06/26/zy4Q/db372d6.jpg" width="400">

---
> 1.20 themed map, a cherry blossom forest surrounded by steep mountains.
>
> Portal: Cherry Log

---
### 🌵 **Triphibious Coast — Coastal Settlement**
🍀 **Type: Vanilla Type**   
✨ **Difficulty: ⭐**

<img src="https://files.seeusercontent.com/2026/06/26/gu3P/eb05458.jpg" width="400">

---
> On a coast surrounded by three biomes, there exists a very lively seaside settlement.  
> Coral Sea biome, suitable for players who like coastal and underwater building.  
> A commemorative map for the series' first map, "Island Village".
>
> Portal: Smooth Sandstone
---
</details>

### 📕 Game Rules
- ❗ **Even with keepInventory enabled, experience is still dropped on death.**
- ❗ **Even with keepInventory enabled, the Curse of Vanishing still takes effect.**
> ❗ **The Eternal Snowy Night will continuously cause snow accumulation and ice formation across all biomes. If you do not want snow to affect your save's terrain, as the first thing after entering the game, you must use the following command to set the snow accumulation height to 0 before the Eternal Night descends:**
> ```
> /gamerule max_snow_accumulation_height 0
> ```

> ❌ The vanilla `/gamerule mob_griefing false` command is commonly used for anti-griefing, but it prevents villagers from picking up food, piglins from picking up gold, and monsters from picking up armor/tools.

>✅ If you need anti-griefing against Creepers, we recommend using the following command:  
>```/gamerule creeper_griefing false```

>✅ If you need to stop Endermen from moving blocks, we recommend using the following command:  
>```/gamerule endman_griefing false```

> ✅ If you need to stop Zombies from breaking doors, we recommend using the following command:  
>```/gamerule zombie_griefing false```

> ✅ If you need anti-griefing against Ghast fireballs, we recommend using the following command:  
> ```/gamerule ghast_griefing false```

> ✅ If you need to stop Ravagers from destroying blocks, we recommend using the following command:  
> ```/gamerule ravager_griefing false```

> ✅ If you need to stop mobs from trampling farmland, we recommend using the following command:  
> ```/gamerule farmland_griefing false```

> ✅ If you need to stop players from trampling farmland, we recommend using the following command:  
> ```/gamerule farmland_player_griefing false```

---

## 🎓 Mod Hotkeys

**Keybind configurations for some mod features within the modpack:**

| Hotkey | Function |
| :--- | :--- |
| **Right-Click** on a villager trade | One-click trade |
| **Middle-Click** on a villager trade | Pin trade to top |
| **R** | Sort inventory/chest (mouse must be over an item) |
| **Shift** | Preview Shulker Box contents |
| **G, J, ↑, ↓, ←, →** | Adjust Gamma / Night Vision values |
| **F6** | Activate Free Camera mode (Tweakeroo Soul Out) |
| **F7** | Show light level overlay |
| **F8** | View Slime Chunks (Must first bind world seed for Minihud via `/seed`) |
| **F9** | View Structure Bounds |
| **B** | View Biome Borders |
| **[** | Toggle Flexible Block Placement |
| **]** | Toggle Fast Block Placement |
| **Right Shift** | Toggle Pseudo-Sneak |
| **Scroll Wheel** | Move individual items |
| **Shift + Left-Click** | Move a stack of items |
| **Shift + Left-Click hold + Drag** | Quickly move multiple stacks |
| **Shift + Left-Click hold + Drag + Q** | Quickly drop multiple stacks |
| **Alt + Left-Click** | Move all identical items |
| **Shift + Alt + Left-Click** | Move all items |

---

## 📖 Notes

### Save Upgrades
- Most maps in this series are vanilla saves, and the modpack will not introduce any mods containing new items or blocks.
- This means you can directly upgrade an older save, e.g., Coastal Settlement from version 1.21.10, to the 26.2 version modpack for playing, as long as Minecraft itself has no issues upgrading the save version.
- ❗ **In any case, back up your save before upgrading to avoid accidents.**
- ❗ **Void-type maps have no terrain and will never have chunk upgrade issues.**

### System Requirements
- ❗ **This series requires at least Java 25 or higher to run.**
- The series mostly consists of optimization and auxiliary mods and is essentially vanilla. It should run smoothly as long as vanilla survival for that version can run smoothly.

### About Mods
- ❗ **Mods marked with the `[Core]` tag must not be removed.**
- ❗ If you wish to add your own mods, be aware that this may lead to feature anomalies, crashes, save corruption, and other compatibility issues. It is recommended to add a prefix like [Custom] to mod filenames for easier replacement when updating the modpack.
- ❗ We only recommend adding small mods that **do not affect vanilla mechanics, do not contain terrain generation, do not disrupt the combat system or numerical balance, and are decorative, display, assistance, or time-saving types.** (e.g., MusicNotification, voxy, Advancement Plaques, Litematica, Auto Fishing, FallingTree, Vein Miner)
- ❗ If you add mods containing new items, blocks, or entities, it may affect the upgradeability of your save if those mods are not updated to new versions.

> ❗ It is strictly forbidden to use entity transportation mods to move the special NPC entities of this series. It is known to cause partial data corruption for these entities.  
> (e.g., In the "Persisting Worlds" map, if the Sustainer is transported (deleting and respawning the entity), its data will be corrupted, allowing it to pass through portals and causing the border energy of its respective dimension to continuously drain)  
> (Also, if a Sustainer dies in a dimension not its own, its bound dimension will never respawn a new Sustainer)

> ❗ This series will not actively attempt to be compatible with non-natively added mods. If you encounter chemical reactions from mods you added yourself, please take on the role of the author of your own custom modpack and be responsible for it yourself.  
> ❗ Note: According to the usage agreement, modified modpacks are for your personal use only. You may not redistribute the original or modified files of this series in public settings.

---

## 📖 FAQ
**Q: How to update the modpack to get the latest features?**

**A:** Replace mods, keep the original version
1. Download the new modpack.
2. Use the launcher to install the new modpack as a temporary instance.
3. Delete the original game instance's `mods` directory files that come with the modpack. Do not delete mods you added yourself.
4. Copy all files from the new game instance's `mods` directory to the original game instance's `mods` directory.

**B:** Migrate resources, clean install new version
1. Download and install the new modpack.
2. Copy the following folders or files from the original game instance to the new game instance directory:
    - `config` (Mod configuration folder)
    - `mods` (**Only your self-added mod files**)
    - `resourcepacks` (Resource pack folder)
    - `saves` (Save folder)
    - `screenshots` (Screenshot folder)
    - `shaderpacks` (Shader pack folder)

---

**Q: How to repair a broken function sign?**

**A:** Use the following command to obtain it. Placing it requires Creative Mode.
```/function border_survival:get_sign```

---

**Q: Right-clicking a function sign does nothing?**

**A:** This is caused by mods not being loaded. Please check if the modpack is installed correctly and if the launched game version name matches the version name installed by the modpack.

---

**Q: Commands cannot be used?**

**A:** Most commands require cheats permission. Obtain command permission through the following steps:
- **Singleplayer**: Press `ESC` -> Click **Options** -> Click **World Options** -> Change **Allow Cheats: OFF** to **Allow Cheats: ON** -> Click **Done**.
- **Server**: Use the `/op <playername>` command via the server console to grant command permission to the specified player.

---

**Q: Border energy is draining abnormally?**

**A:** The chunk containing the Border Sustainer must be loaded. As of Minecraft 1.21.9, there is no longer a concept of world spawn chunks.  
**B:** You can use the Carpet mod to spawn a fake player in the Overworld and teleport it to a safe location, or use a pearl stasis chamber to create a chunk loader, ensuring the Sustainer's chunk is normally loaded.

---

**Q: Why do I die immediately upon entering the End?**

**A:** Insufficient border energy. The border hasn't expanded to cover the End's obsidian platform coordinates. When the portal transports you to the main End island, you are too far outside the border and thus die of suffocation.  
**B:** Please increase the border radius to at least 100 blocks before attempting to enter the End.

---

**Q: Why are no mobs spawning?**

**A:** Check if you are in Peaceful mode. If the map defaults to Peaceful mode, please provide the map name for a fix.  
**B:** Since mobs cannot spawn outside the border, if the border level is below 10, mob spawning efficiency will be relatively slow.

---

**Q: Block placement delay? Chunk loading lag? Piston animations not smooth?**

**A:** This might be caused by dynamic lighting. Try turning off dynamic lighting.

---

**Q: How to set up a server?**

1. Install a Fabric server for the corresponding Minecraft version yourself.
2. Install the modpack, and add all files from the `mods` and `config` directories of the modpack to the server's `mods` and `config` folders.
3. Extract the map pack to the server's root directory, and rename the map save folder to `world`, or to the value of the `level-name` setting in the `server.properties` file.
4. Read the next FAQ for server-specific mod deletion and copying Carpet configuration files into the save.
5. Setup complete, start the server.

---

**Q: The set up server fails to start normally after overwriting with modpack mods?**

**A:** The server requires deleting the **`[Advanced Connection Settings] mcwifipnp`** mod to run properly.

---

**Q: The set up server does not have any Carpet mod features enabled by default?**

**A:** The server's Carpet mod requires separate configuration for the save:
1. Copy the `config/carpet/default_carpet.conf` file to the save directory (usually `world`).
2. Rename the copied file to `carpet.conf`.
3. Restart the server.

---

> **If you encounter other issues or difficulties, or if the above steps did not resolve the problem, please post your question on the [Issues page](https://github.com/Fndream/BorderSurvivalModpack/issues).**

---

## © Version History
- If this series updates to a higher Minecraft version in the future, **older versions will no longer be maintained**.
- ❗ **This series does not preserve or recommend playing historical versions. Any secondary distribution of historical versions is prohibited.**
- ❗ **By downloading resources from this series, you agree to and abide by the [Usage Agreement](#-usage-agreement).**

## © Usage Agreement

#### Content of This Document
Unauthorized excerpts or reproductions of the text and images in this document are prohibited.

#### Resources of This Series
- ✅ Allowed: You may use this series for singleplayer, multiplayer LAN, server play, and content recording/streaming.
- ❌ Prohibited: Without authorization, you may not redistribute (upload, share, publish) the original or modified files of this series in any public setting (including but not limited to communities, websites, cloud drives, resource groups, social media, etc.).
- ❌ Prohibited: You may not use this series for any commercial purpose, including but not limited to sales, bundling, advertising, etc.
- ❌ Prohibited: This series is not suitable for server hosting as a service. You may not and cannot use this series for any server, except for personal server-style LAN connections.