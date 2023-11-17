![Fulfillment Logo](/logo.png)
# Fulfillment
## Overview
This is a small, lightweight modpack that focuses on 

* Create Mod
* Magic Mods
* Terrain Generation
* Performance

## Mod List
Here are all the mods (hopefully) by category with a small 
description of the purpose. Additionally, the lists are 
vaguely ordered by importance. Please look up any mods that 
interest you!


<details>
    <summary> Create and Friends </summary>

* Create: Cogs and multi-block machines with a lot you can do
* Create Steam-n-Rails: more create train functionality
* Slice and Dice: Allows farmer's delight recipes in create
* Ars Creo: A few create additions themed around Ars Nouveau (see Magic Mods)
* Create Structures: create mod themed structure generation
</details>

<details>
    <summary> Magic Mods </summary>

* Ars Nouveau: spell making magic mod
* Occultism: demon summoning and cool storage systems (eventually)
* Forbidden Arcanus: magic mod that trades sanity for advancing
* Tarot Cards: collectible buff giving cards
* Ars Elemental: A.N. additions themed around elements
* Ars Instrumentum: A.N. utility additions
* Ars Ocultas: minor A.N. and Occultism integration
</details>

<details>
    <summary> Terrain Generation </summary>

* Terralith: Many more biomes, but only using vanilla blocks
* Deeper Darker: Deep Dark themed gear and more challenges in the Deep Dark
* Yungs Better Desert Temples: Yungs mods are all amazing, so I included them all.
* Yungs Better Dungeons
* Yungs Better Jungle Temples
* Yungs Better Mineshafts
* Yungs Better Nether Fortresses
* Yungs Better Ocean Monuments
* Yungs Better Strongholds
* Yungs Better Witch-huts
</details>

<details>
    <summary> Food </summary>

* Farmers Delight: more food and crops
* Spice Of Life Apple Pie Edition: penalized or rewarded for eating a balanced diet
</details>

<details>
    <summary> QOL/Minor Content </summary>

* Sophisticated Backpacks: really nice backpacks
* Gravestone: gravestones to hold items on death
* Lootr: loot chests have unique inventory per player
* Leaves Be Gone: leaves decay quickly
* Absent by Design: more stair/slab/fence etc. variants
* Another Furniture: furniture 
* Fantasy Furniture: more furniture
* Better Third Person: third person is more controllable
* Comforts: couple of items including sleeping bags
* Do a Barrel Roll: makes elytra flight more flight-sim-esque (very cool)
* Keep Curios Inventory: see bugs section for explanation
</details>

<details>
    <summary> Horses </summary>

* Realistic Horse Genetics: horses are cooler
* Craft that horse armor: craftable horse armor
</details>

<details>
    <summary> Performance </summary>

* AI Improvements: better AI that uses less cycles
* Clumps: gathers XP orbs faster
* Get it Together Drops: gathers drops together faster
* Embeddium: Better rendering engine
* Embeddium++: Embeddium improvements
* Oculus: Minor performance increase and shader support
* Chunk Sending: optimize server and client chunk traffic
* Alternate Current: better redstone engine
</details>

<details>
    <summary> UI Changes </summary>

* 3D Skin Layers: skin layers are rendered as 3d
* Nekos Enchanted Books: per-enchantment book textures
* Xaeros Minimap: mini map in upper left
* Jade: Banner displaying what you are looking at
* Jei: Searchable item list for seeing recipes and uses
* Just Enough Effect Descriptions: effect descriptions
* Just Enough Professions: villager professions added to jei
* Just Enough Resources: resource generation depths added to jei
* Polymorph: can select between conflicting crafting recipes
* Xaeros World Map: world map
* Yeetus Experimentus: removes dumb screen
</details>

<details>
    <summary> Supporting/Library </summary>
    
* Synatra Connector: An amazing mod allowing Fabric and Forge mods together (!!!!)
* Forgified Fabric API: Allows Synatra connector to work, so also amazing (!!)
* Architectury API
* Cloth Config
* Yungs API
* Cupboard
* Curios
* Fastback
* Ferrite-core
* Flib
* Patchouli
* Puzzles Lib
* Smartbrainlib
* Sophisticated Core
* Valhelsia Core
* Geckolib
* Kotlin For Forge
* Yet Another Config Lib
* Modonomicon
</details>



## Compiling Yourself!
If you want to use it for some reason, you can use `packwiz`
to compile the pack like so:
```
packwiz modrinth export
```
and then import the resulting `.mrpack` file into a minecraft
launcher like MultiMC or Prism

The java version that works for me is `1.17.2` so if you have
problems, you might want to try that. Good luck!

## Bugs
### Curios, Gravestones and Keep Inventory
Curios is one of the supporting mods and it adds extra inventory slots
for things like charms or backpacks. Unfortunately, few of the gravestone
mods account for curios when populating your gravestone on death. This
would mean that anything in your nifty curious slots would disappear 
on death. This would be incredibly annoying, so for now, the mod
`Keep Curios Inventory` is installed. This mod allows the gravestone to
hold all of your main inventory items when you die, while your curios
inventory stays with you across deaths. 

This isn't ideal, but it works for now.

