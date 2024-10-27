---
icon: plane-engines
description: >-
  The guide of the epic Movecraft plugin, a highly complex and flexible system
  of aircrafts, watercrafts, and weapons.
---

# Movecraft

Movecraft allows us to build classes of moveable ships on the Network. This'll be a long guide so you may need to refer to it several times. Documentation on this plugin is quite disorganized so I've tried to condense the client-side of it to one page for simplicity. You can build ships out of only the allowed blocks; anything else on the ship will prevent it from flying or moving in water. If there is a block type you want to use and it's not included in the blocks list, open a ticket in discord. You also have to be aware of the engine, fuel, speed, and how to pilot it.

## **How to build a ship**

First, check the block list of the class of craft you want to create below. Build your craft and make sure you follow the minimum and maximum size requirements. It is also advisable to build it slightly above the ground, or in the water. Another necessary component is the required blocks, meaning a certain percentage of your blocks must be a certain material in order for the ship to move. These blocks represent flight or movement in water. Ships also have a fuel requirement, meaning you must have a furnace that is filled with fuel that the ship can burn to move. It's recommended to keep a chest nearby filled with fuel. Lastly, you must use redstone blocks as the engine, and a certain percentage of your ship must be redstone blocks to move it.&#x20;

\
Each of those components will be detailed below by class. In order to allow your craft to be detected as a legitimate craft, you must place a sign on the ship with the name as the corresponding craft type, then you click the sign to begin piloting it. If there are any errors in your craft's design, it will tell you in chat. If it's successful, it will tell you that you have successfully piloted the craft.

## **How to pilot a craft**

In order to pilot your craft you have 3 options: flying tool, commands, or signs. You may find that one of these options work best for you. I personally like using the flying tool in combination with commands. Our flying tool is flint. To pilot it using a command, simply use `/pilot <class>`

## **Flying with signs**

You can place signs on your craft that correspond to certain actions. The sign must be named exactly as detailed in this guide or it will not function as an actionable sign. Check out this [guide](https://github.com/APDevTeam/Movecraft/wiki/Control-Signs) on signs. If you do the signs correctly, you can click on them to do different commands. A requirement of any craft is a sign with the exact name of the craft.

## **Flying Classes**

***

### **Fighter**

A small fighter jet capable of fast flight.

<details>

<summary>Allowed Blocks</summary>

```
- water
- lava
- PLAYER_HEAD
- ARMOR_STAND
- GLASS
- dispenser
- note_block
- RED_BED
- sticky_piston
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- piston
- piston_head
- sticky_piston
- piston
- piston_head
- gold_block
- bookshelf
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- cake
- repeater
- iron_bars
- brewing_stand
- cauldron
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- activator_rail
- slime_block
- coal_block
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
- GRAY_CONCRETE
- LIGHT_GRAY_CONCRETE
- CYAN_CONCRETE
- RED_CONCRETE
- "#wool"
```

</details>

A fighter has a minimum block size requirement of 10 and a maximum of 1,000. The craft must have at least 2 redstone blocks. A fighter is small, so it must have a way to generate lift using wool, of which 25% of the craft must contain.

***

### **Airship**

A large flying ship that is very versatile.

<details>

<summary>Allowed Blocks</summary>

```
- water
- lava
- GLASS
- lapis_block
- dispenser
- note_block
- RED_BED
- sticky_piston
- piston
- piston_head
- gold_block
- iron_block
- "#slabs"
- bricks
- bookshelf
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- clay
- netherrack
- glowstone
- cake
- repeater
- iron_bars
- nether_brick
- enchanting_table
- brewing_stand
- cauldron
- end_stone
- dragon_egg
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- quartz_block
- chiseled_quartz_block
- quartz_pillar
- smooth_quartz
- activator_rail
- dropper
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- slime_block
- coal_block
- end_stone_bricks
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
- PLAYER_HEAD
- ARMOR_STAND
- "#wool"
```

</details>

An airship has a minimum block size requirement of 1,000 and a maximum of 5,000. The engine requires at least 10 redstone blocks. 10% of the craft must be made out of wool to generate lift.

***

### **Voyager**

A large craft capable of flying that moves slowly but domineers over its enemies.

<details>

<summary>Allowed Blocks</summary>

```
- PLAYER_HEAD
- ARMOR_STAND
- water
- lava
- GLASS
- lapis_block
- dispenser
- note_block
- sticky_piston
- piston
- piston_head
- gold_block
- iron_block
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- bricks
- bookshelf
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- clay
- netherrack
- glowstone
- cake
- repeater
- iron_bars
- nether_brick
- enchanting_table
- brewing_stand
- cauldron
- end_stone
- dragon_egg
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- quartz_block
- chiseled_quartz_block
- quartz_pillar
- smooth_quartz
- activator_rail
- dropper
- slime_block
- coal_block
- end_stone_bricks
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
- GRAY_CONCRETE
- LIGHT_GRAY_CONCRETE
- CYAN_CONCRETE
- RED_CONCRETE
- GREEN_WOOL
- BLACK_WOOL
```

</details>

A voyager has a minimum block size requirement of 10,000 and a maximum of 20,000. This craft requires 15 redstone blocks to function. 10% of this craft must be made of wool to generate lift.

***

### **Dreadnought**

The hallmark destroyer craft of the Artorian aliens. This was featured flying across the SMP during the Alien Invasion Event on November 26, 2023. It is now located above the Shopping District. This craft requires permission to pilot, due to its significance on the network. This may be added as an event reward in the future.

<details>

<summary>Allowed Blocks</summary>

```
- MAGMA_BLOCK
- PLAYER_HEAD
- ARMOR_STAND
- POLISHED_DIORITE
- POLISHED_DIORITE_SLAB
- POLISHED_DIORITE_STAIRS
- POLISHED_ANDESITE
- POLISHED_ANDESITE_STAIRS
- ANDESITE_WALL
- CHISELED_DEEPSLATE
- DEEPSLATE_TILES
- DEEPSLATE_TILE_WALL
- DEEPSLATE_TILE_STAIRS
- DEEPSLATE_TILE_SLAB
- POLISHED_DEEPSLATE
- POLISHED_DEEPSLATE_STAIRS
- POLISHED_DEEPSLATE_SLAB
- WATER
- LAVA
- OAK_LOG
- OAK_WOOD
- OAK_LEAVES
- GLASS
- DISPENSER
- NOTE_BLOCK
- RED_BED
- STICKY_PISTON
- PISTON
- PISTON_HEAD
- WHITE_WOOL
- GOLD_BLOCK
- IRON_BLOCK
- STONE_SLAB
- BOOKSHELF
- OBSIDIAN
- TORCH
- FIRE
- OAK_STAIRS
- CHEST
- BARREL
- SEA_LANTERN
- LANTERN
- CRIMSON_NYLIUM
- REDSTONE_WIRE
- DIAMOND_BLOCK
- CRAFTING_TABLE
- JUNGLE_SIGN
- OAK_SIGN
- OAK_DOOR
- LADDER
- FURNACE
- BLAST_FURNACE
- LEVER
- STONE_PRESSURE_PLATE
- IRON_DOOR
- OAK_PRESSURE_PLATE
- REDSTONE_TORCH
- STONE_BUTTON
- CLAY
- OAK_FENCE
- NETHERRACK
- GLOWSTONE
- CAKE
- REPEATER
- WHITE_STAINED_GLASS
- OAK_TRAPDOOR
- STONE_BRICKS
- IRON_BARS
- GLASS_PANE
- OAK_FENCE_GATE
- STONE_BRICK_STAIRS
- NETHER_BRICK_FENCE
- NETHER_BRICK_STAIRS
- ENCHANTING_TABLE
- BREWING_STAND
- CAULDRON
- DRAGON_EGG
- REDSTONE_LAMP
- ENDER_CHEST
- TRIPWIRE_HOOK
- EMERALD_BLOCK
- SPRUCE_STAIRS
- BIRCH_STAIRS
- JUNGLE_STAIRS
- BEACON
- COBBLESTONE_WALL
- FLOWER_POT
- OAK_BUTTON
- ANVIL
- TRAPPED_CHEST
- LIGHT_WEIGHTED_PRESSURE_PLATE
- HEAVY_WEIGHTED_PRESSURE_PLATE
- COMPARATOR
- DAYLIGHT_DETECTOR
- REDSTONE_BLOCK
- HOPPER
- QUARTZ_BLOCK
- QUARTZ_STAIRS
- ACTIVATOR_RAIL
- DROPPER
- WHITE_CARPET
- TERRACOTTA
- COAL_BLOCK
- POLISHED_DEEPSLATE_WALL
- STONE
- CHISELED_DEEPSLATE
```

</details>

This vessel has a minimum size requirement of 15,000 blocks and a maximum size of 100,000. 10% of this vessel must contain chiseled deepslate due to its intricacies and alien origin. This craft requires an engine consisting of at least 18 redstone blocks.

***

### **Ship**

The most basic water-class, the Ship is the most versatile water vessel.

<details>

<summary>Allowed Blocks</summary>

```
- lava
- GLASS
- PLAYER_HEAD
- ARMOR_STAND
- lapis_block
- dispenser
- note_block
- RED_BED
- sticky_piston
- piston
- piston_head
- gold_block
- iron_block
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- bricks
- bookshelf
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- clay
- netherrack
- glowstone
- cake
- repeater
- iron_bars
- nether_brick
- enchanting_table
- brewing_stand
- cauldron
- end_stone
- dragon_egg
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- quartz_block
- chiseled_quartz_block
- quartz_pillar
- smooth_quartz
- activator_rail
- dropper
- slime_block
- coal_block
- end_stone_bricks
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
- ACACIA_BUTTON
- ACACIA_DOOR
- ACACIA_FENCE
- ACACIA_FENCE_GATE
- ACACIA_HANGING_SIGN
- ACACIA_LOG
- ACACIA_PLANKS
- ACACIA_PRESSURE_PLATE
- ACACIA_SIGN
- ACACIA_SLAB
- ACACIA_STAIRS
- ACACIA_TRAPDOOR
- ACACIA_WALL_HANGING_SIGN
- ACACIA_WALL_SIGN
- ACACIA_WOOD    
- OAK_BUTTON
- OAK_DOOR
- OAK_FENCE
- OAK_FENCE_GATE
- OAK_HANGING_SIGN
- OAK_LOG
- OAK_PLANKS
- OAK_PRESSURE_PLATE
- OAK_SIGN
- OAK_SLAB
- OAK_STAIRS
- OAK_TRAPDOOR
- OAK_WALL_HANGING_SIGN
- OAK_WALL_SIGN
- OAK_WOOD
- BIRCH_BUTTON
- BIRCH_DOOR
- BIRCH_FENCE
- BIRCH_FENCE_GATE
- BIRCH_HANGING_SIGN
- BIRCH_LOG
- BIRCH_PLANKS
- BIRCH_PRESSURE_PLATE
- BIRCH_SIGN
- BIRCH_SLAB
- BIRCH_STAIRS
- BIRCH_TRAPDOOR
- BIRCH_WALL_HANGING_SIGN
- BIRCH_WALL_SIGN
- BIRCH_WOOD
- CHERRY_BUTTON
- CHERRY_DOOR
- CHERRY_FENCE
- CHERRY_FENCE_GATE
- CHERRY_HANGING_SIGN
- CHERRY_LOG
- CHERRY_PLANKS
- CHERRY_PRESSURE_PLATE
- CHERRY_SIGN
- CHERRY_SLAB
- CHERRY_STAIRS
- CHERRY_TRAPDOOR
- CHERRY_WALL_HANGING_SIGN
- CHERRY_WALL_SIGN
- CHERRY_WOOD
- CRIMSON_HANGING_SIGN
- CRIMSON_HYPHAE
- CRIMSON_NYLIUM
- CRIMSON_PLANKS
- CRIMSON_PRESSURE_PLATE
- CRIMSON_SIGN
- CRIMSON_SLAB
- CRIMSON_STAIRS
- CRIMSON_STEM
- CRIMSON_TRAPDOOR
- CRIMSON_WALL_HANGING_SIGN
- CRIMSON_WALL_SIGN
- DARK_OAK_FENCE
- DARK_OAK_HANGING_SIGN
- DARK_OAK_LOG
- DARK_OAK_PLANKS
- DARK_OAK_PRESSURE_PLATE
- DARK_OAK_SIGN
- DARK_OAK_SLAB
- DARK_OAK_STAIRS
- DARK_OAK_TRAPDOOR
- DARK_OAK_WALL_HANGING_SIGN
- DARK_OAK_WALL_SIGN
- DARK_OAK_WOOD
- JUNGLE_BUTTON
- JUNGLE_DOOR
- JUNGLE_FENCE
- JUNGLE_FENCE_GATE
- JUNGLE_HANGING_SIGN
- JUNGLE_LOG
- JUNGLE_PLANKS
- JUNGLE_PRESSURE_PLATE
- JUNGLE_SIGN
- JUNGLE_SLAB
- JUNGLE_STAIRS
- JUNGLE_TRAPDOOR
- JUNGLE_WALL_HANGING_SIGN
- JUNGLE_WALL_SIGN
- JUNGLE_WOOD
- MANGROVE_BUTTON
- MANGROVE_DOOR
- MANGROVE_FENCE
- MANGROVE_FENCE_GATE
- MANGROVE_HANGING_SIGN
- MANGROVE_LOG
- MANGROVE_PLANKS
- MANGROVE_PRESSURE_PLATE
- MANGROVE_SIGN
- MANGROVE_SLAB
- MANGROVE_STAIRS
- MANGROVE_TRAPDOOR
- MANGROVE_WALL_HANGING_SIGN
- MANGROVE_WALL_SIGN
- MANGROVE_WOOD
- SPRUCE_BUTTON
- SPRUCE_DOOR
- SPRUCE_FENCE
- SPRUCE_FENCE_GATE
- SPRUCE_HANGING_SIGN
- SPRUCE_LOG
- SPRUCE_PLANKS
- SPRUCE_PRESSURE_PLATE
- SPRUCE_SIGN
- SPRUCE_SLAB
- SPRUCE_STAIRS
- SPRUCE_TRAPDOOR
- SPRUCE_WALL_HANGING_SIGN
- SPRUCE_WALL_SIGN
- SPRUCE_WOOD
- STRIPPED_ACACIA_LOG
- STRIPPED_ACACIA_WOOD
- STRIPPED_BAMBOO_BLOCK
- STRIPPED_BIRCH_LOG
- STRIPPED_BIRCH_WOOD
- STRIPPED_CHERRY_LOG
- STRIPPED_CHERRY_WOOD
- STRIPPED_CRIMSON_HYPHAE
- STRIPPED_CRIMSON_STEM
- STRIPPED_DARK_OAK_LOG
- STRIPPED_DARK_OAK_WOOD
- STRIPPED_JUNGLE_LOG
- STRIPPED_JUNGLE_WOOD
- STRIPPED_MANGROVE_LOG
- STRIPPED_MANGROVE_WOOD
- STRIPPED_OAK_LOG
- STRIPPED_OAK_WOOD
- STRIPPED_SPRUCE_LOG
- STRIPPED_SPRUCE_WOOD
- STRIPPED_WARPED_HYPHAE
- STRIPPED_WARPED_STEM
- WARPED_BUTTON
- WARPED_DOOR
- WARPED_FENCE
- WARPED_FENCE_GATE
- WARPED_HANGING_SIGN
- WARPED_HYPHAE
- WARPED_NYLIUM
- WARPED_PLANKS
- WARPED_SIGN
- WARPED_SLAB
- WARPED_STAIRS
- WARPED_STEM
- WARPED_TRAPDOOR
- WARPED_WALL_HANGING_SIGN
- WARPED_WALL_SIGN
- "#wool"
- "#planks"
- "#wooden_slabs"
```

</details>

The Ship is a good choice if you lack redstone, as it's not a requirement. It can be driven without an engine. It also doesn't have requirements of certain blocks other than the ones above. It also contains every wood type, so you can build a classic wooden pirate ship. The minimum size requirement is 100 blocks and the maximum is 10,000.

25% of this craft must be made of wooden planks, and 5% must be made of wool (for the mast.)

***

### **Cruiser**

A mid-size water vessel.

<details>

<summary>Allowed Blocks</summary>

```
- PLAYER_HEAD
- ARMOR_STAND
- lava
- GLASS
- lapis_block
- dispenser
- note_block
- RED_BED
- sticky_piston
- piston
- piston_head
- gold_block
- iron_block
- bricks
- bookshelf
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- clay
- netherrack
- glowstone
- cake
- repeater
- iron_bars
- nether_brick
- enchanting_table
- brewing_stand
- cauldron
- end_stone
- dragon_egg
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- quartz_block
- chiseled_quartz_block
- quartz_pillar
- smooth_quartz
- activator_rail
- dropper
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- slime_block
- coal_block
- end_stone_bricks
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
```

</details>

A cruiser must have 5% iron blocks to represent ballasts. It will not be able to move under the water. If it's sinking, there's a problem! The minimum size requirement is 1,000 blocks and maximum is 5,000. This craft requires 10 redstone blocks to function.

***

### **Submarine**

The only craft class that can sink below the water.

<details>

<summary>Allowed Blocks</summary>

```
- PLAYER_HEAD
- ARMOR_STAND
- lava
- GLASS
- lapis_block
- dispenser
- note_block
- RED_BED
- sticky_piston
- piston
- piston_head
- gold_block
- iron_block
- bricks
- bookshelf
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- clay
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- netherrack
- glowstone
- cake
- repeater
- iron_bars
- nether_brick
- enchanting_table
- brewing_stand
- cauldron
- end_stone
- dragon_egg
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- quartz_block
- chiseled_quartz_block
- quartz_pillar
- smooth_quartz
- activator_rail
- dropper
- slime_block
- coal_block
- end_stone_bricks
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
```

</details>

This craft does not fly, and can sink below the water when operated. It has to be at least 15% iron blocks. The minimum block requirement is 500 and the maximum is 100,000. This vessel requires [Astronaut Rank](https://torrent.tebex.io/package/6420753) to pilot!

***

### Frigate

A large scale water vessel.

<details>

<summary>Allowed Blocks</summary>

```
- PLAYER_HEAD
- ARMOR_STAND
- lava
- GLASS
- lapis_block
- dispenser
- note_block
- RED_BED
- sticky_piston
- piston
- piston_head
- gold_block
- iron_block
- bricks
- bookshelf
- gray_concrete
- light_gray_concrete
- cyan_concrete
- red_concrete
- green_concrete
- torch
- fire
- redstone_wire
- diamond_block
- crafting_table
- furnace
- blast_furnace
- smoker
- ladder
- lever
- redstone_torch
- redstone_wall_torch
- clay
- netherrack
- glowstone
- cake
- repeater
- iron_bars
- nether_brick
- enchanting_table
- brewing_stand
- cauldron
- end_stone
- dragon_egg
- redstone_lamp
- ender_chest
- tripwire_hook
- tripwire
- emerald_block
- beacon
- flower_pot
- comparator
- daylight_detector
- redstone_block
- hopper
- quartz_block
- chiseled_quartz_block
- quartz_pillar
- smooth_quartz
- activator_rail
- dropper
- slime_block
- coal_block
- end_stone_bricks
- smooth_stone
- bell
- cartography_table
- composter
- fletching_table
- grindstone
- lantern
- lectern
- loom
- smithing_table
- stonecutter
- GRAY_CONCRETE
- LIGHT_GRAY_CONCRETE
- CYAN_CONCRETE
- RED_CONCRETE
- iron_bloc
```

</details>

This craft is a huge water vessel capable of traveling long distances. This is essentially a battleship. This craft requires [Starlord Rank](https://torrent.tebex.io/package/6460925) to pilot it.
