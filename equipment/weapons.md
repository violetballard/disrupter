# **Weapons**
Weapon Stats are really easy to create as well. There are 5 stats for each Weapon representing the damage they do at each Range band (See [Rule 5][rule5])
- Target (T, #) - Damage done to target by [Indirect Firing][indirect] Weapons
- Close (C, #)
- Medium (M, #)
- Long (L, #)
- Max (#) - Longest Range the Weapon can Hit

[rule5]: /rules/core/main.md#rule5
[indirect]: /rules/core/indirect_fire.md

The Stats are the least interesting part of each Weapon. The effects that you give weapons is what will make combat fun.

Individual Units are indinistinguishable; however, Weapons are what give your teams and Vehicles real character. You can assign these weapons to miniatures that you already have, or you can develop the weapons for miniatures that you already own if none of these work. Please share any weapons that you make for inclusion in the core Weapons list.

Please pay attention to the formatting of these tables if you are submitting a new Weapon. We suggest writing them without the block quotes and then adding them when you are complete. At least for our preferred VS Code Markdown Table plugin, our table tab-completion does not like the blockquotes. However, the blockquotes make these tables legible.

## **Infantry Weapons**
Many Infantry Weapons can be attached to Vehicles as well.
<br>

>## **Revolver**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>| 0   |  1  |  1  |  1  |  3  |
>|     |     |     |     |     |
>
>| Description          |
>| -------------------- |
>| - Officer's side arm |
<br>

>## **Combat Shotgun**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>|  0  |  3  |  1  |  0  |  2  |
>|     |     |     |     |     |
>
>| Description      |
>| ---------------- |
>| - Tried and True |
<br>

>## **Frag Grenade**
>
>|  T  |  C  |  M  |  L  |    Max    |
>| :-: | :-: | :-: | :-: | :-------: |
>|  2  |  1  |  0  |  0  | 2 (Throw) |
>|     |     |     |     |           |
>
>| Description                                                                                                                         |
>| ----------------------------------------------------------------------------------------------------------------------------------- |
>| - Medium Range throw, Automatically hits target<br> - Instinct Check (See [Rule 7][rule7]) for Successful throw, Failed throw targets attacker's own Team<br> - 1 Wound Splash damage within Close Range |
<br>

[rule7]: /rules/core/main.md#rule7

>## **Pulse Rifle**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>| 0   |  2  |  2  |  1  |  4  |
>|     |     |     |     |     |
>
>| Description          |
>| -------------------- |
>| - Standard issue Weapon for Infantry<br> - Can have mounted Frag Grenade launcher with Long Range |
<br>

>## **Laser Carbine**
>
>| T   |  C  |  M  |  L  |   Max    |
>| --- | :-: | :-: | :-: | :------: |
>| 0   |  1  |  2  |  1  | Infinite |
>|     |     |     |     |          |

>| Description                      |
>| -------------------------------- |
>| - Standard issue Weapon for Bots |
<br>

>## **Sniper Rifle**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>| 0   |  1  |  3  |  3  |  5  |
>|     |     |     |     |     |
>
>| Description          |
>| -------------------- |
>| - Cannot Move and Fire in the same turn See ([Rule 11][rule11])<br> - Can Fire from cover without I [-] (See [Rule 13][rule13])<br> - Someone else can Spot an enemy to give I [+] (See [Rule 16 - Spotting][spot]) |
<br>

[rule11]: /rules/core/main.md#rule11
[rule13]: /rules/core/main.md#rule13 

>## **Heavy Machine Gun**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>| 0   |  3  |  3  |  1  |  3  |
>|     |     |     |     |     |
>
>| Description          |
>| -------------------- |
>| - Requires Battle Dress (See [Armor][armor])<br/> - Cannot Move and Fire in the same turn See ([Rule 11][rule11])<br> - 1 Wound to all units adjacent to target |
<br>

[armor]: ./armor.md

>## **Flamethrower**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>| 0   |  3  |  0  |  0  |  1  |
>|     |     |     |     |     |
>
>| Description          |
>| -------------------- |
>| - Burning: 1 Wound to all Units within Close Range of the target, excluding the attacker|
<br>

>## **Laser Cutter**
>
>| T   |  C  |  M  |  L  |   Max    |
>| --- | :-: | :-: | :-: | :------: |
>| 0   | 10  | 10  | 10  | Infinite |
>|     |     |     |     |          |
>
>| Description          |
>| -------------------- |
>| - Requires Battle Dress (See [Armor][armor])<br/> - Cannot Move and Fire in the same turn See ([Rule 11][rule11])<br> - >Penetrates through targets<br> - Takes 3 Turns to recharge |
<br>

>## **Rocket Launcher**
>
>| T   |  C  |  M  |  L  | Max |
>| --- | :-: | :-: | :-: | :-: |
>| 10  |  2  | 10  | 10  |  Infinite  |
>|     |     |     |     |     |
>
>| Description          |
>| -------------------- |
>| - Cannot Move and Fire in the same turn See ([Rule 11][rule11])<br><br> - Another unit can Spot the target if there is not LOS (See [Rule 16 - Spotting][spot])<br> --Can Spot a Target that is Under Cover<br> --Automatically hits if target is Spotted <br><br> -2 Wounds to all units in Close Range to target<br><br> - On Failed Instinct Check, still lands 2 Wounds on all target Units |
<br>

[spot]: /rules/core/main.md#rule16.spot