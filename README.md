minetest modpack 3d Armor
===========================

ARMOR pack for your gameplay, **full all engines compatible**

## Information
--------------

This mod provides ARMORS to your gameplays, such like shields, gloves, wielded, 
helmet, chestplate, leggings and boots.

![screenshot.png](screenshot.png)

## Technical info
-----------------

This modpack must be named `3d_armor` and enables armor manage for the gameplay
Makes hand wielded items visible to other players.
Adds a chest-like armor stand for armor storage and display.

This is a **fork that unify all the 3d_armor mods.. the features on this 
repository is the simplification & compatibility game of the mod**, this means you 
will find a **more faster but less featured mod**.. if you want a minetest game with simple armors 
and faster response use this mod:

* The mods are **compatible with minetest 0.4, 5.2, 5.3, 5.4 and multicraft 2.X**
* The damage is not distributed 100% between the armor, it is only **distributed according to the height of the hit** puch from hitter
* Repairs are simplified, you will reapir using only one mod from xdecor of minenux project
* Improved **optimized reduced textures, with more colorfull aditions**
* The texture of **admin armor was improved with new desing**
* Some checks for avoid nil on game for older engines

Differences

This armor pack tracks all the upstream original Stuart ones, plus patches from mt-mods fork, 
but the only removed feature is the protected armor stand and more detailes separate damage.

### Contribution

The development is really at [https://codeberg.org/minenux/minetest-mod-3d_armor](https://codeberg.org/minenux/minetest-mod-3d_armor) you must follow minenux preferences to code!

The mods that this special fork handle are developed at [https://git.minetest.io/minenux?q=3d_armor&tab=repositories](https://git.minetest.io/minenux?sort=recentupdate&language=&q=3d_armor&tab=repositories)

### Download and requirements

It can be download from 

* https://git.minetest.io/minenux/minetest-mod-3d_armor
* https://codeberg.org/minenux/minetest-mod-3d_armor
* https://gitlab.com/minenux/minetest-mod-3d_armor

This modpack provides following mods (click on each item to get more information):

* [`3d_armor`](3d_armor/README.md)
* [`3d_armor_gloves`](3d_armor_gloves/README.md)
* [`3d_armor_stand`](3d_armor_stand/README.md)
* [`shields`](shields/README.md)
* [`wieldview`](wieldview/README.md)

Aditional this particular modpack integrates/back:

* [`3d_armor_technic`](3d_armor_technic/README.md) originally `technic_armor`
* [`3d_armor_mobile`](3d_armor_mobile/README.md) a nice way to wear for mobile play

For the inventory it provides integration for:

* [`3d_armor_sfinv`](3d_armor_sfinv/README.md) if detected `sfinv` mod
* [`3d_armor_ip`](3d_armor_ip/README.md) for `inventory_plus` but only for newer engines (MT 5.0+)
* [`3d_armor_ui`](3d_armor_ui/README.md) if detected `unified_inventory` mod

The required minetest Version: 0.4.16 + this means ALL ENGINES including recent 5.X+

Game: minetest_game and many derivatives

Depends: default (check each mod to get into aditional depends)

Adds craftable armor that is visible to other players. Each armor item worn contributes to
a player's armor group level making them less vulnerable to attack.

Armor takes damage when a player is hurt, however, many armor items offer a 'stackable'
percentage chance of restoring the lost health points. Overall armor level is boosted by 10%
when wearing a full matching set (helmet, chestplate, leggings and boots of the same material)

Fire protection has been added by TenPlus1 and in use when ethereal mod is found and crystal
armor has been enabled.  each piece of armor offers 1 fire protection, level 1 protects
against torches, level 2 against crystal spikes, 3 for fire and 5 protects when in lava.

Compatible with sfinv, inventory plus or unified inventory by enabling the appropriate
inventory module, [3d_armor_sfinv], [3d_armor_ip] and [3d_armor_ui] respectively.
Also compatible with [smart_inventory] without the need for additional modules.

built in support player skins [skins] by Zeg9 and Player Textures [player_textures] by PilzAdam
and [simple_skins] by TenPlus1.

Armor can be configured by adding a file called armor.conf in 3d_armor mod or world directory.
see armor.conf.example for all available options.

For mod installation instructions, please visit: http://wiki.minetest.org/wiki/Installing_Mods

We promoted the [http://minetest.org](http://minetest.org) site!

Adds a chest-like armor stand for armor storage and display.

## LICENSE

License Source Code: Copyright (C) 2023+ PICCORO Lenz McKAY - CC-BY-SA-NC 3.0

License Source Code: Copyright (C) 2013-2018 Stuart Jones - LGPL v2.1

Armor Textures: Copyright (C) 2017-2018 davidthecreator - CC-BY-SA 3.0

Special credit to Jordach and MirceaKitsune for providing the default 3d character model.

Changes the color of the admin armor from stupid rose 3d_armor mod to black.

License of this fork: **Creative Commons Attribution-NonCommercial-ShareAlike** CC-BY-SA-NC

