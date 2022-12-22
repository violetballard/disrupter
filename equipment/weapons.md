# Weapons
Weapon Stats are really easy to create as well. There are 5 stats for each Weapon representing the damage they do at each Range band (See [Rule 5](broken-reference))

* Target (T, #) - Damage done to target by [Indirect Firing](../rules/indirect\_fire.md) Weapons
* Close (C, #)
* Medium (M, #)
* Long (L, #)
* Max (#) - Longest Range the Weapon can Hit

The Stats are the least interesting part of each Weapon. The effects that you give weapons is what will make combat fun.

Individual Units are indinistinguishable; however, Weapons are what give your teams and Vehicles real character. You can assign these weapons to miniatures that you already have, or you can develop the weapons for miniatures that you already own if none of these work. Please share any weapons that you make for inclusion in the core Weapons list.

Please pay attention to the formatting of these tables if you are submitting a new Weapon. We suggest writing them without the block quotes and then adding them when you are complete. At least for our preferred VS Code Markdown Table plugin, our table tab-completion does not like the blockquotes. However, the blockquotes make these tables legible.

## **Infantry Weapons**
Many Infantry Weapons can be attached to [Vehicles](vehicles.md) as well.

### **Revolver**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  1  |  1  |  1  |  3  |
|   |     |     |     |     |

| **Description**                                     |
| --------------------------------------------------- |
| Officer's (See [Rule 9](broken-reference)) side arm |

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

| **Description**                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------- |
| Medium Range (See <a href="broken-reference">Rule 5</a>) throw, automatically hits target                                 |
| Instinct Check (See <a href="broken-reference">Rule 7</a>) for Successful throw, Failed throw targets attacker's own Team |
| 1 Wound Splash damage within Close Range                                                                                  |

### **Pulse Rifle**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  2  |  2  |  1  |  4  |
|   |     |     |     |     |

| **Description**                                                                                    |
| -------------------------------------------------------------------------------------------------- |
| Standard issue Weapon for Infantry                                                                 |
| Can have mounted Frag Grenade launcher with Long Range (See <a href="broken-reference">Rule 5</a>) |

### **Laser Carbine**
| T |  C  |  M  |  L  |    Max   |
| - | :-: | :-: | :-: | :------: |
| 0 |  1  |  2  |  1  | Infinite |

| **Description**                           |
| ----------------------------------------- |
| Standard issue Weapon for [Bots](bots.md) |

### **Sniper Rifle**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  1  |  3  |  3  |  5  |

| **Description**                                                                                      |
| ---------------------------------------------------------------------------------------------------- |
| Cannot Move and Fire in the same turn See (<a href="broken-reference">Rule 11</a>)                   |
| Can Fire from cover without I [-] (See <a href="broken-reference">Rule 13</a>)                       |
| Someone else can Spot an enemy to give I [+] (See <a href="broken-reference">Rule 16 - Spotting</a>) |

### **Heavy Machine Gun**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  3  |  3  |  1  |  3  |
|   |     |     |     |     |

| **Description**                                                                                   |
| ------------------------------------------------------------------------------------------------- |
| Requires Battle Dress (See <a href="armor.md">Armor</a>)                                          |
| Cannot Move and Fire in the same turn See (<a href="broken-reference">Rule 11</a>)                |
| 1 Wound to all units within Close Range (See <a href="broken-reference">Rule 5</a>) of the target |

### **Flamethrower**
| T |  C  |  M  |  L  | Max |
| - | :-: | :-: | :-: | :-: |
| 0 |  3  |  0  |  0  |  1  |

| **Description**                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------- |
| Burning: 1 Wound to all Units within Close Range of the target (See [Rule 5](broken-reference)), excluding the attacker |
|                                                                                                                         |

### **Laser Cutter**
| T |  C  |  M  |  L  |    Max   |
| - | :-: | :-: | :-: | :------: |
| 0 |  10 |  10 |  10 | Infinite |
|   |     |     |     |          |

| Description                                                                                       |
| ------------------------------------------------------------------------------------------------- |
| Requires Battle Dress (See <a href="armor.md">Armor</a>)                                          |
| Cannot Move and Fire in the same turn See (<a href="broken-reference">Rule 11</a>)                |
| Does not require an Instinct Check                                                                |
| Penetrates through targets, all obstacles ignored, every Unit in its path must make an Armor Save |
| Takes 3 Turns to recharge                                                                         |
|                                                                                                   |

### **Rocket Launcher**
| T  |  C  |  M  |  L  |    Max   |
| -- | :-: | :-: | :-: | :------: |
| 10 |  2  |  10 |  10 | Infinite |
|    |     |     |     |          |

| Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- |
| Cannot Move and Fire in the same turn See (<a href="broken-reference">Rule 11</a>)                             |
| Another unit can Spot the target if there is not LOS (See <a href="broken-reference">Rule 16 - Spotting</a>)   |
| Can Spot a Target that is Under Cover (See <a href="broken-reference">Rule 13</a>)                             |
| Automatically hits if target is Spotted                                                                        |
| 2 Wounds to all units in Close Range (See <a href="broken-reference">Rule 5</a>) to target                     |
| On Failed Instinct Check (See <a href="broken-reference">Rule 7</a>), still lands 2 Wounds on all target Units |