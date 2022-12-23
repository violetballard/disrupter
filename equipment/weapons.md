# Weapons
Weapon Stats are really easy to create as well. There are 5 stats for each Weapon representing the damage they do at each Range band (See [Rule 5][rule5])

[indirect]: /rules/indirect_fire.md
[rule5]: /rules#rule5

* Target (T, #) - Damage done to target by [Indirect Firing][indirect] Weapons
* Close (C, #)
* Medium (M, #)
* Long (L, #)
* Max (#) - Longest Range the Weapon can Hit

The Stats are the least interesting part of each Weapon. The effects that you give weapons is what will make combat fun.

Individual Units are indinistinguishable; however, Weapons are what give your teams and Vehicles real character. You can assign these weapons to miniatures that you already have, or you can develop the weapons for miniatures that you already own if none of these work. Please share any weapons that you make for inclusion in the core Weapons list.

Please pay attention to the formatting of these tables if you are submitting a new Weapon. We suggest writing them without the block quotes and then adding them when you are complete. At least for our preferred VS Code Markdown Table plugin, our table tab-completion does not like the blockquotes. However, the blockquotes make these tables legible.

## **Infantry Weapons**
Many Infantry Weapons can be attached to [Vehicles][vehicles] as well.

[vehicles]: /equipment/vehicles.md

### **Revolver**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  1  |  1  |  1  |  3  |
|   |     |     |     |     |

| **Description**                                     |
| --------------------------------------------------- |
| Officer's (See [Rule 9][rule9]) side arm |

[rule9]: /rules#rule9

### **Combat Shotgun**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  3  |  1  |  0  |  2  |
|   |     |     |     |     |

| **Description** |
| --------------- |
| Tried and True  |

### **Frag Grenade**
|  T  |  C  |  M  |  L  |    Max    |
| :-: | :-: | :-: | :-: | :-------: |
|  2  |  1  |  0  |  0  | 2 (Throw) |
|     |     |     |     |           |

| **Description**                                                                                     |
| --------------------------------------------------------------------------------------------------- |
| Medium Range (See [Rule 5][rule5]) throw, automatically hits target                                 |
| Instinct Check (See [Rule 7][rule7]) for Successful throw, Failed throw targets attacker's own Team |
| 1 Wound Splash damage within Close Range                                                            |

[rule7]: /rules#rule7

### **Pulse Rifle**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  2  |  2  |  1  |  4  |
|   |     |     |     |     |

| **Description**                                                              |
| ---------------------------------------------------------------------------- |
| Standard issue Weapon for Infantry                                           |
| Can have mounted Frag Grenade launcher with Long Range (See [Rule 5][rule5]) |

### **Laser Carbine**
| T |  C  |  M  |  L  |    Max   |
| - | :-: | :-: | :-: | :------: |
| 0 |  1  |  2  |  1  | Infinite |

| **Description**                           |
| ----------------------------------------- |
| Standard issue Weapon for [Bots][bots] |

[bots]: /equipment/bots.md

### **Sniper Rifle**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  1  |  3  |  3  |  5  |

| **Description**                                                                 |
| ------------------------------------------------------------------------------- |
| Cannot Move and Fire in the same turn See ([Rule 11][rule11])                   |
| Can Fire from cover without I [-] (See [Rule 13][rule13])                       |
| Someone else can Spot an enemy to give I [+] (See [Rule 16 - Spotting][rule16]) |

[rule11]: /rules#rule11
[rule13]: /rules#rule13
[rule16]: /rules#rule16.spotting

### **Heavy Machine Gun**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  3  |  3  |  1  |  3  |
|   |     |     |     |     |

| **Description**                                                             |
| --------------------------------------------------------------------------- |
| Requires Battle Dress (See [Armor][armor])                                  |
| Cannot Move and Fire in the same turn See ([Rule 11][rule11]                |
| 1 Wound to all units within Close Range (See [Rule 5][rule5]) of the target |

[armor]: /equipment/armor.md

### **Flamethrower**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  3  |  0  |  0  |  1  |

| **Description**                                                                                              |
| ------------------------------------------------------------------------------------------------------------ |
| Burning: 1 Wound to all Units within Close Range of the target (See [Rule 5][rule5]), excluding the attacker |

### **Laser Cutter**
| T |  C  |  M  |  L  |    Max   |
| - | :-: | :-: | :-: | :------: |
| 0 |  10 |  10 |  10 | Infinite |

| Description                                                                                       |
| ------------------------------------------------------------------------------------------------- |
| Requires Battle Dress (See [Armor][armor])                                                        |
| Cannot Move and Fire in the same turn See ([Rule 11][rule11])                                     |
| Does not require an Instinct Check                                                                |
| Penetrates through targets, all obstacles ignored, every Unit in its path must make an Armor Save |
| Takes 3 Turns to recharge                                                                         |

### **Rocket Launcher**
| T  |  C  |  M  |  L  |    Max   |
| -- | :-: | :-: | :-: | :------: |
| 10 |  2  |  10 |  10 | Infinite |
|    |     |     |     |          |

| Description                                                                              |
| ---------------------------------------------------------------------------------------- |
| Cannot Move and Fire in the same turn See ([Rule 11][rule11])                            |
| Another unit can Spot the target if there is not LOS (See [Rule 16 - Spotting][rule16])  |
| Can Spot a Target that is Under Cover (See [Rule 13][rule13])                            |
| Automatically hits if target is Spotted                                                  |
| 2 Wounds to all units in Close Range (See [Rule 5][rule5]) to target                     |
| On Failed Instinct Check (See [Rule 7][rule7]), still lands 2 Wounds on all target Units |