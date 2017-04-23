Dark Souls 3 Mechanics Cheatsheet
=================================

*One-stop shopping for each time you ask yourself, "How does that mechanic work again :suspect:?"*

> To be honest, I'm in a bit of a pickle.  
> -Siegward of Catarina

---

Table of Contents
-----------------

1.	[Base Power](#basepower)

	-	[HP](#hp)
	-	[Stamina](#stamina)
	-	[Equip Load](#equipload)
	-	[Prisoner's Chain vs. Ring of Favor](#pcrof)
	-	[FP and Attunement Slots](#FP)
	-	[Luck, Hollowing, and Item Discovery](#luck)

2.	[Combat](#combat)

	-	[Attack Power](#ar)
	-	[Defense and Absorption](#defenseandabsorption)
		-	[Defense](#defense)  
		-	[Absorption](#absorption)
	-	[Additional Effects and Resistances](#statuseffects)
		-	[Additional Effects](#additionaleffects)
		-	[Resistances](#resistances)
	-	[Poise and Poise-Through](#poiseandpoisethrough)
		-	[Attack Animations](#attackanimations)
		-	[Poise Frames](#poiseframes)
		-	[Poise Healthbar](#poisehealthbar)
		-	[Poise Damage](#poisedamage)
		-	[Armor Poise](#armorpoise)
		-	[Poise Health](#poisehealth)
	-	[Special Attacks](#specialattacks)
		-	[Counter Attack](#counterattacks)
		-	[Critical Attack](#criticalattacks)
	-	[Guarding](#guarding)
		-	[Stability](#stability)
	-	[Parrying](#parrying)
	-	[Rolling and Invincibility Frames](#rolling)

3.	Spellcasting

	-	Spell Buff and Spell Damage
	-	Spell Poise
	-	Casting Speed
	-	Non-Scaling spells

4.	[Appendix](#appendix)

	-	[Healing and Regeneration](#healingandregeneration)
		-	[Healing](#healing)
		-	[HP Regeneration](#hpregeneration)
		-	[HP Leech](#hpleech)
		-	[Stamina Regeneration](#staminaregeneration)
		-	[FP Recovery](#fprecovery)
		-	[FP Regeneration](#fpregeneration)
		-	[FP Leech](#fpleech)
	-	[Sources of Attack Power Increase](#sourcesofarincrease)
		-	[Flat Attack Power Increase](#flatattackpowerincrease)
		-	[Conditional Attack Power Increase](#conditionalattackpowerincrease)
		-	[Flat Elemental Attack Power Increase](#flatelementalattackpowerincrease)
		-	[Scaling Elemental Attack Power Increase](#scalingelementalattackpowerincrease)
		-	[Elemental Bonus Damage](#elementalbonusdamage)
	-	[Sources of Absorption, Resistance, and Cure](#sourcesofabsortionandresistance)
		-	[Flat Absorption Increase](#flatabsorptionincrease)
		-	[Conditional Absorption Increase](#conditionalabsorptionincrease)
		-	[Absorption Decrease](#absorptiondecrease)
		-	[Resistance Increase](#resistanceincrease)
		-	[Cures](#cures)
	-	[Sources Additional Effects](#sourcesofadditionaleffects)
		-	[Bleed](#bleed)
		-	[Poison](#poison)
		-	[Toxic](#toxic)
		-	[Frostbite](frost)
	-	[Poise Modifiers](#poisemodifiers)
		-	[Armor Poise Increase](#armorpoiseincrease)
		-	[Base Poise and Stamina Damage](#poiseandstaminadamage)
		-	[Weapons with Poise Frames](#hyperarmor)
	-	[Guard Modifiers](#guardmodifiers)
		-	[Stability Increase](#stabilityincrease)
		-	[Guard Breaks](#guardbreaks)
	-	Sources of Magic Attack Increase
		-	Spell Damage Increase
		-	Casting Speed Increase
		-	Non-Scaling Spells
	-	Weapon Infusion Scaling

---

<a name="basepower"></a>Base Power
----------------------------------

### <a name="hp"></a>![HP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_hp.png) HP

-	HP (Hit Points) is governed by VIG.
-	HP is softcapped at 1000 (27 VIG) and 1300 (50 VIG).
-	Life Ring (+1, +2, +3) grants 7% (8%, 9%, 10%) more HP.

*Cf. [Healing](#healing), [HP Regeneration](#hpregeneration), and [HP Leech](#hpleech)*.

### <a name="stamina"></a>![Stamina](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_stamina.png) Stamina

-	Stamina is governed by END.
-	Stamina has a softcap of 160 at 40 END.
-	Stamina regeneration is 45 per second.
-	Equip Load > 69.9% reduces Stamina regeneration by about 20%, to 37 per second.
-	Stamina Damage is a deduction of Stamina points that occurs upon being successfully attacked.
-	1 point of Stamina is enough to execute an action.
-	Stamina can be brought to a negative level (-60).
-	If the full Stamina cost of an action brings the players Stamina below 0, the action will lose efficacy.
-	Stamina regenerates at the same rate regardless of being negative or positive, causing a player to be unable to act until Stamina again becomes positive.

*Cf. [Stamina Regeneration](#staminaregeneration)*.

### <a name="equipload"></a>![Equip Load](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_equip_load.png) Equip Load

-	Equip Load is governed by VIT.
-	Base Equip Load is 40.
-	1 VIT grants one point of Equip Load. 40 VIT = 80 equip; 99 VIT = 139 equip
-	Havel's Ring (+1, +2, +3) grants +15% (17%, 18%, 19%) equip load.

### <a name="pcrof"></a>Prisoner's Chain vs. Ring of Favor +3 vs. Life Ring +3 vs. Havel's Ring +3

Prisoner's Chain and Ring of Favor offer similar bonuses, but are best used at different stages in the game.

**TL;DR**

```
 Start with Prisoner's Chain.  
 Switch to Ring of Favor +3 at 36/36 VIT/END.  
 If you only care about HP, use Life Ring +3 starting at 27 VIG.  
 If you only care about Equip Load, use Havel's Ring.  
 The effects of these rings stacks.
```

-	Prisoner's Chain grants a +5 bonus to the base Attributes of VIG, END, and VIT.  
-	Ring of Favor (+1, +2, +3) grants +3% HP, +8.5% Stamina, and +5% Equip Load (4.5/9.5/6; 5/10.5/7; 6/11.5/8).

| VIG / END / VIT | Prisoner's Chain    | Ring of Favor +3       | Life Ring +3     | Havel's Ring +3 |
|:---------------:|:-------------------:|:----------------------:|:----------------:|:---------------:|
|       10        |   550 / 102 / 55    |     427 / 104 / 54     |   443 / - / -    |  - / - / 59.50  |
|       15        |   764 / 112 / 60    |    583 / 113 / 59.4    |   605 / - / -    |  - / - / 65.45  |
|       20        |   947 / 122 / 65    |    809 / 124 / 64.8    |   840 / - / -    |  - / - / 71.4   |
|     **26**      | **1074** / 136 / 71 |   1035 / 139 / 71.28   | **1074** / - / - |  - / - / 78.45  |
|       30        |   1141 / 146 / 75   |   1119 / 149 / 75.6    |   1161 / - / -   |  - / - / 83.3   |
|     **36**      | **1226** / 160 / 81 | **1226** / 165 / 82.08 |   1272 / - / -   |  - / - / 90.4   |
|       40        |   1269 / 160 / 85   |    1285 / 178 /86.4    |   1334 / - / -   |  - / - / 95.2   |

-	Life Ring +3 grants greater HP than Prisoner's Chain starting at 27 VIG.
-	RoF +3 grants greater HP than Prisoner's Chain starting at 36 VIG.
-	RoF +3 always grants more Stamina than PC, substantially so starting at 36 END. This is because END is softcapped at 40 and PC hits this level virtually at 35 END.
-	Havel's Ring +3 always grants the greatest Equip Load.
-	RoF +3 grants a greater Equip Load than PC starting at 23 VIT, though the difference between the two is negligible throughout.

### <a name="FP"></a>![FP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_fp.png) ![Attunement Slots](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_attunement.png) FP and Attunement Slots

-	ATT governs FP and Attunement Slots.  
-	FP is consumed when casting spells and while performing Skills (Weapon Arts).
-	For purposes of Attunement Slots, ATT has a soft cap of 30.
-	For purposes of FP, ATT has a soft cap of 35.

| ATT   | 10 | 14  | 18  | 24  | 30  | 40  |
|:-----:|:--:|:---:|:---:|:---:|:---:|:---:|
| Slots | 1  |  2  |  3  |  4  |  5  |  6  |
|  FP   | 93 | 114 | 136 | 181 | 233 | 296 |

-	Saint's Ring and Deep Ring both grant +1 Attunement Slot.  
-	Darkmoon Ring grants +2 Attunement Slots.  
-	Dusk Crown Ring reduces FP consumption when casting spells by 25%.  
-	Farron Ring reduces FP consumption when performing Weapon Arts by 30%.

*Cf. [FP Recovery](#fprecovery), [FP Regeneration](#fpregeneration), and [FP Leech](#fpleech)*.

### <a name="luck"></a>![Luck](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-luck_22.png) ![Item Discovery](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_item_discovery.png) Luck, Hollowing, and Item Discovery

-	LUCK governs Item Discovery.  
-	Base Item Discovery is 100.
-	1 LUCK grants 1 point in Item Discovery up to the hard cap of 199.
-	Hollowing is acquired through Yoel of Londor's quest line and requires dying.
-	At 15 Hollowing or greater, holding a +10 Hollow-infused weapon grants +5 LUCK.

*Cf. [Sources of Additional Effects](#sourcesofadditionaleffects).*

---

<a name="combat"></a>Combat
---------------------------

### <a name="ar"></a>Attack Power

A player's Attack Power (Attacking Rating or AR) is compared to the target's Defense and Absorption, producing the Damage that the target suffers. Information about AR calculations can be found on [here](http://blog.mugenmonkey.com/2016/07/22/how-to-calculate-ar.html). A weapon AR calculator can be found [here](https://mugenmonkey.com/darksouls3/weapons).

**Simplified AR Formula**

```
AR = Base Damage + Physical Scaling Bonus + Magic Scaling Bonus + Fire Scaling Bonus +
Lightning Scaling Bonus + Dark Scaling Bonus
```

Hidden within Scaling Bonuses are weightings that are different for each weapon. These weightings are what determine how a player's Attributes will interact with the weapon to produce Attack Power. Not taking weighting into consideration, the following is true:  
- STR, DEX, FTH, and LUCK govern Physical Scaling Bonus.  
- INT governs Magic Scaling bonus.  
- INT and FTH govern Fire Scaling Bonus.  
- FTH governs Lightning Scaling Bonus.  
- INT and FTH governs Dark Scaling Bonus.

Scaling grades are given to show some inclination of how much weight is given to each Attribute in determining Scaling Bonus. The following example illustrates this:

```
* Fume Ultra Greatsword receives a 148.4 weighting for STR
* A Scaling in STR
* Fume Ultra Greatsword receives a 7 weighting for DEX
* E Scaling in DEX
```

-	The affect that STR and DEX have on weapons softcaps at 40 and 60.  
-	The affect that INT and FTH have on weapons softcaps at 40 and 60.  
-	Knight's, Hunter's, Scholar's, and Priestess Rings grant +5 to STR, DEX, INT, and FTH, respectively.  
-	Carthus Milkring grants +3 DEX.  
-	Two-handing a weapon grants a 1.5x multiplier to STR, improving Attack Power and decreasing any STR requirement needed to wield the weapon.
-	A list of weapons that gain S/A/B scaling from elemental infusions can be found [here](https://www.reddit.com/r/darksouls3/comments/4ii8lj/heres_a_list_of_all_weapons_that_gain_an_sa/).  
-	Heavy/Sharp/Refined infusions from the latest patch can be found [here](https://docs.google.com/spreadsheets/d/1SQ4MZANAqrfBnSjWeXUxCzv8DX8UewA3QeG6QPcx6X4/edit#gid=0).

*Cf. [Flat AR Increase](#flatattackpowerincrease), [Conditional AR Increase](#conditionalattackpowerincrease), [Flat Elemental AR Increase](#flatelementalattackpowerincrease), [Scaling Elemental AR Increase](#scalingelementalattackpowerincrease), and [Elemental Bonus Damage](#elementalbonusdamage).*

### <a name="defenseandabsorption"></a>Defense and Absorption

#### <a name="defense"></a>Defense

Defense is calculated by player Attributes, and will rise by some degree regardless of which Attribute is leveled.  
* Physical Defense is primarily governed by VIT.  
 * For purposes of Defense, VIT has a softcap of 40 VIT.  
* Magic Defense is primarily governed by INT.  
* Fire Defense is primarily governed by STR.  
* Lightning Defense is primarily governed by END.  
* Dark Defense is primarily governed by FTH.

A player's Defense is compared against a successful attacker's AR and provides a Damage reduction based on one of five different categories.

| Defense Compared to AR | Damage Reduction        |
|:-----------------------|:-----------------------:|
| DEF > ATK*8            |  90% Damage reduction   |
| DEF > ATK              | 60-90% Damage reduction |
| DEF > ATK*0.4          | 30-60% Damage reduction |
| DEF > ATK*0.125        | 10-30% Damage reduction |
| DEF < ATK*0.125        |  10% Damage Reduction   |

The follow example illustrates this calculation:

```
* Player A (60 STR) attacks Player B with FUGS +10.
* FUGS at this level has 593 AR, all Physical Damage.
* Player B has a Physical Defense level of 177.
* 177 is greater than 12.5% of 593 but lesser than 40% of 593.
* Player B receives a 10-30% damage reduction
* Player B takes somewhere between 415 and 513 damage from Player A.
```

These calculations are done separately per damage type, causing the efficacy of split damage type weapons (such as Drakeblood Greatsword, which is split between Physical, Lightning, and Magic) to vary depending on whom the player is attacking.

#### <a name="absorption"></a>Absorption

Absorption is provided by Armor and Rings, and represents a straight percentage reduction to the Damage calculated by comparing Defense to AR.

Following the example from above:

```
* Player B has 34.811 Physical Absorption, meaning they absorb 34.8% of Player A's attack.
* Player B absorbs 144 to 185 of the 415 to 513 damage from Player A.
* Player A deals 271 to 348 damage to Player B with FUGS.
```

More information about Defense and Absorption can be found [here](https://www.reddit.com/r/darksouls3/comments/59qde8/how_defense_and_absorption_work_simplified/).

*Cf. [Flat Absorption Increase](#flatabsorptionincrease), [Conditional Absorption Increase](#conditionalabsorptionincrease), and [Absorption Decrease](#absorptiondecrease).*

### <a name="statuseffects"></a>Additional Effects and Resistances

The Additional Effects (aka status effects) found on weapons and applied by spells are Bleeding, Poison, Toxic, Acid, and Frostbite. Curse is a status effect found throughout the game but one which cannot be applied by players.

#### <a name="additionaleffects"></a>Additional Effects

-	Additional Effect buildup is applied on hit.
-	100 points of buildup is required for a Status Effect to activate.
-	The Additional Effect values on a weapon indicate how much buildup the weapon applies on hit.
-	Buildup is applied on all hits, regardless of damage outcome. This applies for hits against Guarding opponents and hits against rolling opponents.
-	LUCK contributes to the Additional Effect number found on weapons with innate Bleed or Poison.
	-	For purposes of Additional Effects, LUCK has a softcap of 50.

| Additional Effect             | Damage                                                      |
|:-----------------------------:|:-----------------------------------------------------------:|
|       Bleeding (Innate)       |                     15% HP + 50 Damage                      |
|        Bleeding (Base)        |                        15% HP + 100                         |
| Bleeding (Blood Infusion +10) |                          15% + 100                          |
| Bleeding (Innate, Blood +10)  |                          15% + 200                          |
|           Poisoning           |    (7 + .07% HP) per second for 90s, or (630 + 6.3% HP)     |
|             Toxic             |     (22 +.1% HP) per second for 90s, or (1980 + 9% HP)      |
|           Frostbite           | (85 + 11% HP), -15 Stamina regen and -7% absorption for 28s |
|             Curse             |                            Death                            |

Information about calculating Additional Effect damage can be found [here](https://www.reddit.com/r/darksouls3/comments/61urxh/bleed_poison_frostbite_toxic_buildups_after_111/). Information about LUCK, Bleed, Poison, and infusions can be found [here](https://www.reddit.com/r/darksouls3/comments/66k53b/bleed_values_for_every_level_of_luck/).

*Cf. [Bleed](#bleed), [Poison](#poison), [Toxic](#toxic), [Frost](#frost).*

#### <a name="resistances"></a>Resistances

Resistances offer a boost to how long a player can stave off a Status Effect by increasing the buildup required for activation.

-	END governs Bleed resistance.
-	VIT governs Poison resistance.  
-	VIG governs Frost resistance.  
-	LUCK governs Curse resistance.  

*Cf. [Resistance Increase](#resistanceincrease), [Cures](#cures).*

### <a name="poiseandpoisethrough"></a> Poise

Poise determines whether or not a player will be able to continue attacking, or "Poise-Through", without being staggered while trading attacks with the opponent. Information about Poise calculations can be found [here](https://www.reddit.com/r/darksouls3/comments/5ckxjf/indepth_poiseguide_v108/), and a Poise calculator can be found [here](https://www.reddit.com/r/darksouls3/comments/5962gm/refined_poise_calculator_108/).

**Poise-Through Formula**

```
If the player's Poise Armor > 100*(1-Poise Healthbar*Poise Health/Opponent's Poise Damage),
then the player's attack Poises-Through.
```

#### <a name="attackanimations"></a>Attack Animations

All attack animations have three stages:  
* Startup Frames: the transition from neutral at the time of input to the beginning of the stage where a hit might register.  
* Active Frames: the time during which a hit might register or a parry might be executed.  
* Recovery Frames: the follow-through of the attack animation to neutral.

If a player is attacked at the beginning of Startup Frames, or during Recovery Frames, regardless of which weapon is used and which attack is performed, they will be staggered.

#### <a name="poiseframes"></a>Poise Frames

Some weapons do not allow a player to trade attacks without being interrupted. Put another way, some weapons do not make a check for Poise. If a weapon makes a check for Poise, that check occurs during the second half of Startup Frames and the first half of Active Frames.

```
[Startup Frames] -> [Active Frames] -> [Recovery Frames]
	 | 		|
	 [ Poise Frames ]
```

*Cf. [Weapons with Poise Frames](#hyperarmor).*

#### <a name="poisehealthbar"></a>Poise Healthbar

The Poise Healthbar is a hidden 100 point healthbar that is affected by Poise Damage. If this bar reaches 0, the player is staggered.  
* Starts at 100.  
* Is reduced by Poise Damage on each hit.  
* If below 80%, resets to 80% on each swing.  
* Resets to 100 after 30 seconds outside of combat.  
* Resets to 100 upon using a Weapon Art.  
* Resets to 100 after recovering from a stagger.

#### <a name="poisedamage"></a>Poise Damage

Each attack for each weapon has a hidden Poise Damage value. When the player attacks an opponent, the Poise Damage for each attack is subtracted from the opponent's Poise Healthbar. Those values are available [here](https://www.reddit.com/r/darksouls3/comments/58yu34/poise_damage_spreadsheet/).

For Example:

```
Fume Ultra Greatsword 1H R1 has a Poise Damage value of 31.
Fume Ultra Greatsword L2->R2 has a Poise Damage value of 65.1.
```

*Cf. [Base Poise and Stamina Damage](#poiseandstaminadamage).*

#### <a name="armorpoise"></a>![Poise](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon_res_poise.png) Armor Poise

Poise on the Character Status Sheet is better understand as "Armor Poise". It is found on certain items and heavy Armor. Armor Poise grant's a reduction to Poise Damage akin to how Absorption works for Damage.

```
	Received Poise Damage = Opponent's Poise Damage*(1-Armor Poise/100)
```

*Cf. [Armor Poise Increase](#armorpoiseincrease).*

#### <a name="poisehealth"></a>Poise Health

During Poise Frames, the Poise Healthbar is modified by a hidden value called Poise Health. Poise Health values can be found [here](https://docs.google.com/spreadsheets/d/1TmKpp2lOOcHvoDnjB9P0LGDN71Np0Gr68tPQ8BkqxZ8/edit#gid=153914695).

```
	If Poise Healthbar = 100, then Poise Health = Attack's Poise Health * 1
	If Poise Healthbar = 80, then Poise Health = Attack's Poise Health * .8
```

Poise Health values are specific to each attack of each weapon with Poise Frames:

```
Fume Ultra Greatsword 1H R1 has a Poise Health value of 24.2
If Poise Healthbar is at 100%, then Poise Health = 24.2
If Poise Healthbar is at 80%, then Poise Health = 19.36
Fume Ultra Greatsword L2->R2 has a Poise Health value of 100.
If Poise Healthbar is at 100%, then Poise Health = 100.
If Poise Healthbar is at 80%, then Poise Health = 80.
```

### <a name="specialattacks"></a>Special Attacks

#### <a name="counterattacks"></a>Counter Attack

Counter attacks are attacks that are landed while an opponent is in the Active Frames of their attack animation.  
- Counter attacks do 30% more damage than the same attack landed against a non-attacking opponent.

![Counter Attack](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_counter.png) Leo Ring grants an additional 15% to thrusting counter attacks.  
- Thrusting swords and weapons with thrusting attacks (running Katana R1, etc.) benefit from Leo Ring, as do Pickaxe, Warpick, Heysel Pick, and Immolation Tinder.

#### <a name="criticalattacks"></a>![Critical Attack](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-wp_critical.png) Critical Attack

Critical Attacks are Ripostes, Backstabs, Plunging Attacks, and Headshots. Information about calculating Critical Attack damage can be found [here](https://youtu.be/O2450bG8408).  
- Critical Attack power on a weapon serves as a multiplier for that weapon's damage when performing a Critical Attack.  
- Ripostes are attacks from the front that may be executed after an opponent's guard has been broken or their attack has been parried.  
- Backstabs are attacks of opportunity that are scored by attacking an opponent directly in the back without other inputs.  
- Daggers have a hidden bonus Critical Attack multiplier.  
- Mail Breaker outpaces all weapons < ~450 AR in terms of Critical Attack damage.

*Cf. [Conditional AR Increase](#conditionalattackpowerincrease), [Conditional Absorption Increase](#conditionalabsorptionincrease).*

### <a name="guarding"></a>Guarding

-	Guarding is the action of holding a shield or a weapon in order to defend against an oncoming attack.  
-	Guarding reduces Stamina regeneration.  
-	A shield's Guard Absorption is applied to attack damage in the same manner that Armor Absorption is applied.

#### <a name=stability></a>![Stability](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-wp_stability.png) Stability

Stability represents a flat percentage reduction of how much Stamina Damage a player will take while Guarding.

```
	Received Stamina Damage = Stamina Damage*(Stability/100)
```

-	Each weapon has a specific Stamina Damage value.  
-	If an attack's Stamina Damage > than currently available Stamina, Guarding against the attack will cause a player's Guard to be broken and the player will be staggered.

*Cf. [Base Poise and Stamina Damage](#poiseandstaminadamage), [Stability Increase](#stabilityincrease), [Guard Mitigation](#guardmitigation).*

### <a name="parrying"></a>Parrying

Parrying is accomplished by using a shield or fist weapon that has the parry action at a specific time during an opponent's attack. A list of these items can be found [here](http://darksouls3.wiki.fextralife.com/Parry).  
- Parry timings vary between weapon type and attack. A video on parry timings using fist weapons can be found [here](https://www.youtube.com/watch?v=Do5QHrLCmmY).  
- A successful parry opens up the opponent to a Riposte by staggering them for a short period of time.  
- An unsuccesful parry will result in partial damage being taken.  
- Some attacks cannot be parried. Those attacks can be found [here](https://docs.google.com/spreadsheets/d/1FNHEH4qgtiZz6xj5PVx0SoI8QfDha9lxkkjGWGOASmQ/htmlview?sle=true#gid=0) or [here](https://www.reddit.com/r/darksouls3/comments/4hrzmy/guide_to_parryable_and_unparryable_weapons/)

### <a name="rolling"></a>Rolling and Invincibility Frames

Roll speed and distance is governed by Equip Load.

| Equip Load | Roll Speed                          |
|:----------:|:-----------------------------------:|
|   < 30%    |        farthest and fastest         |
|   > 30%    |       medium roll, no penalty       |
|   > 70%    | "fat roll", penalty to Backstepping |

-	Invincibility Frames (I-Frames) are animation frames found in certain actions, such as pulling levers and rolling.

-	During I-Frames a player will not receive damage, making it possible to "roll through" many types of attacks.

-	Rolling grants 12 I-Frames, lasting .4 seconds.

![Altered Roll](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_milk.png) Carthus Bloodring grants an additional 3 I-frames, bringing the total to 15 lasting .433 seconds.

---

<a name="spellcasting"></a>Spellcasting
---------------------------------------

In order to use a weapon, a player must pass one set of Attribute checks to see if the weapon can be wielded effectively. In Spellcasting, the player must pass two sets of Attribute checks: once in order to effectively wield their chosen catalyst, and a second in order to cast the spell. The game translates these two Attribute checks into one modifier, called Spell Buff.

### <a named="spellbuff"></a>![Spell Buff](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/spell_buff.png) Spell Buff

-	Spell Buff appears on all catalysts, and differs between each catalyst.  
-	Spell Buff is best understood as being equivalent to a weapon's Attack Power.  
-	Spell Buff is affected by Upgrades, and it scales:

	-	Most Staffs scale with INT.  
	-	Most Talismans scale with FTH.  
	-	Most Chimes scale with FTH.  
	-	Pyromancy Flames scale with INT and FTH.

The factor that makes one of two similar spells more potent than the other is how it treats Spell Buff. For example:

```
Soul Arrow AR = (1.16 * Spell Buff) - 42.2
Great Heavy Soul Arrow AR = (2.84 * Spell Buff) - 111.8
At 60 INT, Court Sorcerer's Staff +10 has a Spell Buff of 238.
Soul Arrow will have an AR of 233.9 Great Heavy Soul Arrow will have an AR of 664.12
```

Spell Damage is calculated against Defense and Absorption (and Resistance, if applicable), in the same way that Weapon Damage is calculated.

#### The Wand Chooses You!

Because Spell Buff scales, some catalysts are hybrids between schools of Spellcasting, and Weapon Arts between catalysts vary, it is often difficult to determine which catalyst best suits the application of the player.

**TL; DR**

```
Heretic's Staff at 40 INT for Sorceries.
Court Sorcerer's Staff at 60 INT for Sorceries.
If not leveling FTH, Murky Longstaff at 40 or 60 INT for Dark Sorceries.
If leveling INT and FTH, Izalith Staff for Dark Sorceries.
Cleric's Sacred Chime at 40 FTH for Miracles.
If leveing FTH and INT, Crystal Chime at 40 for Miracles.
Yorshka's Chime at 60 FTH for Miracles.
Caitha's Chime at 40 FTH for Dark Miracles.
Pyromancy Flame for all Pyromancies.
```

Based on Spell Buff alone, the best catalysts are:

|                           | 1-35                              | 35-39           | 40-44                 | 45-50                 | 50+                    |
|---------------------------|:---------------------------------:|:---------------:|:---------------------:|:---------------------:|:----------------------:|
| Soul Sorceries            |          Heretic's Staff          | Heretic's Staff |    Heretic's Staff    |   Sorcerer's Staff    | Court Sorcerer's Staff |
| Pyromancies               |          Pyromancy Flame          |       ---       |          ---          |     Softcap 45/45     |          ---           |
| Miracles (FTH)            |       Cleric's Sacred Chime       | Canvas Talisman | Cleric's Sacred Chime | Cleric's Sacred Chime |    Yorshka's Chime     |
| Miracles (FTH/INT)        |           Crystal Chime           |  Crystal Chime  |     Crystal Chime     |     Crystal Chime     |    Yorshka's Chime     |
| Dark Miracles             | Caitha's Chime / Sunless Talisman |       ---       |          ---          |     Softcap 45/45     |          ---           |
| Dark Sorceries (INT)      |          Murky Longstaff          |       ---       |          ---          |          ---          |          ---           |
| Dark Sorceries (INT/FTH)  |           Izalith Staff           |       ---       |          ---          |     Softcap 45/45     |          ---           |
| Soul Sorceries & Miracles |           Crystal Chime           |       ---       |          ---          |     Softcap 45/45     |          ---           |
| Pyromancies & Miracles    |        White-Hair Talisman        |       ---       |          ---          |          ---          |          ---           |

### Spell Damage

The following data is aggregated from the following sources:  
* Reddit: [PSA: Information about best staff/chime/talisman](https://www.reddit.com/r/darksouls3/comments/4hucav/psa_information_about_best_staffchimetalisman/)  
* [Imgur Chart](http://i.imgur.com/8mYDJS0.png)  
* Gamefaqs: [testing thread](http://www.gamefaqs.com/boards/168566-dark-souls-iii/73664144)  
* Fextralife: [testing thread](http://fextralife.com/forums/t52733/how-do-i-magic-the-endall-guide-scaling-updates/?start=240)  
* Reddit: [Spell Tools and Spell Buff Explained](https://www.reddit.com/r/darksouls3/comments/5a2ow7/spell_tools_and_spell_buff_explained/)

#### Talismans vs. Chimes

-	Unfaltering Prayer is found on all Talismans but White Hair Talisman.
-	Unfaltering Prayer grants the player Spell Poise while casting Miracles, making Talismans more conducive to close-quarters combat.
-	At 40 FTH, Sunless Talisman offers the greatest Spell Poise.
-	At 40 FTH, Canvas Talisman offers comprable Spell Poise but a much larger Spell Buff (180 vs. 160).
-	Gentle Prayer is found on all Chimes but Sacred Chime of Filiaonore.
-	Gentle Prayer does not offer Spell Poise. Instead it heals the player 6 HP/s for 60s, for totaling 360 HP.

The following information was taken from Reddit: [STR/FTH PVE Guide](https://www.reddit.com/r/DkS3Builds/comments/5z08yn/strfth_pve_guide/)  
* at 40 FTH, Sunlight Talisman has the highest poise.  
* at 40 FTH, Canvas Talisman has competitive poise and grants a greater spellbuff (180 vs 146).

### Casting Speed

-	50 Virtual Dexterity is needed for maximum casting speed.
-	Virtual Dexterity is DEX + any modifiers to casting speed.
-	Sage Ring (+1, +2) gives 30 (35, 40) Virtual Dexterity.
-	15 DEX and Sage Ring will cap Virtual Dexterity at 50.
-	Witchtree Branch and Saint-Tree Bellvine provide the same effect as the Sage Ring.

---

<a name="appendix"></a>Appendix
-------------------------------

### <a name="healingandregeneration"></a>Healing and Regeneration

#### <a name="healing"></a>![Estus Healing UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_est_up.png) Healing

| Flask Level | Healing | Estus Ring (+20%) |
|:-----------:|:-------:|:-----------------:|
|      0      |   250   |        300        |
|      1      |   335   |        402        |
|      2      |   410   |        492        |
|      3      |   470   |        564        |
|      4      |   515   |        618        |
|      5      |   535   |        642        |
|      6      |   550   |        660        |
|      7      |   565   |        678        |
|      8      |   580   |        696        |
|      9      |   590   |        708        |
|     10      |   600   |        720        |

| Miracle           | Formula           | 40 FTH, Canvas Talisman +10 |
|:-----------------:|:-----------------:|:---------------------------:|
|     Heal Aid      | 150% * Spell Buff |           270 HP            |
|  Projected Heal   | 230% * Spell Buff |  414 HP (must hit target)   |
|       Heal        | 300% * Spell Buff |           540 HP            |
|     Med Heal      | 400% * Spell Buff |           720 HP            |
|    Great Heal     | 550% * Spell Buff |           990 HP            |
| Soothing Sunlight | 700% * Spell Buff |           1260 HP           |

| Source          | Healing |
|:---------------:|:-------:|
| Divine Blessing |  100%   |
|    Siegbrau     |   ? %   |

#### <a name="hpregeneration"></a>![Poise](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_regen.png) HP Regeneration

The highest theoretical rate of HP Regeneration possible is 22 HP/s for 60s, totaling 1680 HP. This is achieved by casting Gentle Prayer, casting Bountiful Sunlight, then switching to a Blessed Weapon and Shield.

| Source                     | Average Regen   | Total                  |
|:--------------------------:|:---------------:|:----------------------:|
|  Anri's Straight Sword +5  |     1 HP/s      |           \-           |
|    +10 Blessed Infusion    |     2 HP/s      |           \-           |
| Ancient Dragon Greatsgield |     2 HP/s      |           \-           |
|   Ethereal Oak Shield +5   |     2 HP/s      |           \-           |
|     Sun Princess Ring      |     2 HP/s      |           \-           |
|       Replenishment        | 5 HP/s for 60s  |          300           |
|      Bountiful Light       | 7 HP/s for 60s  |          420           |
|     Bountiful Sunlight     | 10 HP/s for 60s |          600           |
|       Gentle Prayer        | 6 HP/s for 60s  |          360           |
|           Warmth           | 35 HP/s for 60s | 2100 (must hit target) |

#### <a name="hpleech"></a>![HP Leech](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_hp_leech.png) HP Leech

| Source                  | Healing                                          |
|:-----------------------:|:------------------------------------------------:|
|     Aldritch's Ruby     |            85 HP per Critical Attack             |
|  Feast Bell (Eleanora)  |            22 HP per hit attack at +4            |
|  Lifedrain (Dark Hand)  |            ? (NPCs and Players only)             |
|     Lifehunt Scythe     |                 87% * Spell Buff                 |
|   Pontiff's Left Eye    |          30 HP with successive attacks           |
| Sharpen (Butcher Knife) | 2 HP per light attack, 11-22 HP per heavy attack |
| Ring of the Evil Eye +3 |              37 HP per enemy killed              |

#### <a name="staminaregeneration"></a>![Stamina Regeneration](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_stamina.png) Stamina Regeneration

The highest theoretical rate of Stamina Regeneration possible is 109 Stamina/s for 60s. This is achieved by equipping Chloranthy Ring +3, Grass Crest Shield, consuming a Budding Green Blossom, casting Power Within, and performing the Galvanize Weapon Art, all while under 70% Equip Load.

| Source                  | Regen Rate    | Regen Time (40 END, 160 Stamina) |
|:-----------------------:|:-------------:|:--------------------------------:|
| Base (<70% Equip Load)  | 45 Stamina/s  |               3.6s               |
|     Deep Protection     | +3 Stamina/s  |               3.3s               |
|   Grass Crest Shield    | +3 Stamina/s  |               3.3s               |
|      Green Blossom      | +5 Stamina/s  |               3.2s               |
|  Budding Green Blossom  | +9 Stamina/s  |              2.96s               |
|        Galvanize        | +10 Stamina/s |               2.9s               |
|   Chloranthy Ring +3    | +11 Stamina/s |              2.86s               |
|      Power Within       | +30 Stamina/s |              2.13s               |
| Base (> 70% Equip Load) | -8 Stamina/s  |               4.3s               |
|  Greatshield of Glory   | -20 Stamina/s |               6.4s               |

#### <a name="fprecovery"></a>![FP Recovery UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_ash_up.png) FP Recovery

Ashen Estus Flask +10 will recover 100% FP up to 27 ATT, and up to 31 ATT with Ashen Estus Ring.

| Flask Level | FP Recovered | Ashen Estus Ring (+20%) |
|:-----------:|:------------:|:-----------------------:|
|      0      |      80      |           96            |
|      1      |      95      |           114           |
|      2      |     110      |           132           |
|      3      |     125      |           150           |
|      4      |     140      |           168           |
|      5      |     150      |           180           |
|      6      |     160      |           192           |
|      7      |     170      |           204           |
|      8      |     180      |           216           |
|      9      |     190      |           228           |
|     10      |     200      |           240           |

| Source          | FP Recovered |
|:---------------:|:------------:|
| Hidden Blessing |     100%     |

#### <a name="fpregeneration"></a>![FP Regeneration](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_fp_regen.png) FP Regeneration

| Source             | FP Recovered  |
|:------------------:|:-------------:|
| Simple Infusion +0 |  1FP per 5s   |
| Simple Infusion +5 | 1FP per 2.85s |

#### <a name="fpleech"></a>![FP Leech](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_fp_leech.png) FP Leech

| Source                   | FP Recovered              |
|:------------------------:|:-------------------------:|
|    Aldrich's Sapphire    | 15 FP per Critical Attack |
| Executioner's Greatsword |   6 FP per enemy killed   |
|   Handmaiden's Dagger    |       1 FP per hit        |

### <a name="sourcesofarincrease"></a>Sources of Attack Power increase

#### <a name="flatattackpowerincrease"></a>![Attack UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_atk_up.png) Flat Attack Power increase

| Source                    | Increase                   |
|:-------------------------:|:--------------------------:|
|          Warcry           | 5-10%, depending on weapon |
|      Deep Protection      |             5%             |
| Sharpen (Butcher's Knife) |             5%             |
|      Carthus Beacon       |   7.5% base (3% in PVP)    |
|      Blessed Weapon       |            7.5%            |
|     Oath of Sunlight      |            10%             |
|        Sacred Oath        |            10%             |
|       Power Within        |            20%             |
|  Sharpen (Great Machete)  |            20%             |
|         Bloodlust         |            30%             |

#### <a name="conditionalattackpowerincrease"></a>![Attack UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_atk_up.png) Conditional Attack Power increase

| Source              | Condition                         | Increase                           |
|:-------------------:|:---------------------------------:|:----------------------------------:|
|   Carthus Beacon    |      3-5 consecutive attacks      |            7.5% to 15%             |
| Floyd's Sword Ring  |             > 99% HP              |          10% (8% in PVP)           |
| Pontiff's Right Eye |     3-15 depending on weapon      | 3% to 6% to 9% depending on weapon |
|    Flynn's Ring     | weight while under 30% Equip Load |             1% to 15%              |
| Red Tearstone Ring  |             < 20% HP              |                20%                 |
|    Morion Blade     |             < 20% HP              |    20% (can equip two for 40%)     |
|     Hornet Ring     |          Critical Attack          | varies by weapon/Riposte/Backstab  |
|      Leo Ring       |          Counter Attack           |        15% (physical only)         |

#### <a name="flatelementalattackpowerincrease"></a>Flat elemental Attack Power increase

| Source                | Increase                         |
|:---------------------:|:--------------------------------:|
|   Magic Clutch Ring   |   20% Magic attack ( ? in PVP)   |
|   Fire Clutch Ring    |   20% Fire attack ( ? in PVP)    |
| Lightning Clutch Ring | 20% Lightning Attack ( ? in PVP) |
|   Dark Clutch Ring    |   20% Dark Attack ( ? in PVP)    |

#### <a name="scalingelementalattackpowerincrease"></a>Scaling elemental Attack Power increase

| Spell                | Element   | Formula          |
|:--------------------:|:---------:|:----------------:|
|     Magic Weapon     |   Magic   | 75% * Spell Buff |
|  Great Magic Weapon  |   Magic   | 85% * Spell Buff |
| Crystal Magic Weapon |   Magic   | 96% * Spell Buff |
|    Darkmoon Blade    |   Magic   | 96% * Spell Buff |
|  Carthus Flame Arc   |   Fire    | 82% * Spell Buff |
|   Lightning Blade    | Lightning | 96% * Spell Buff |
|      Dark Blade      |   Dark    | 85% * Spell Buff |

#### <a name="elementalbonusdamage"></a>Elemental bonus damage

| Source                                 | Element   | Bonus |
|:--------------------------------------:|:---------:|:-----:|
|            Pale Pine Resin             |   Magic   |  90   |
|          Charcoal Pine Resin           |   Fire    |  85   |
|          Charcoal Pine Bundle          |   Fire    |  110  |
|            Gold Pine Resin             | Lightning |  95   |
|            Gold Pine Bundle            | Lightning |  120  |
|            Human Pine Resin            |   Dark    |  95   |
|        Ember (Demon's Greataxe)        |   Fire    |  80   |
| Falling Bolt (Dragonslayer Swordspear) | Lightning |  80   |
|            Flame of Lorian             |   Fire    |  80   |
|             Profaned Flame             |   Fire    |  80   |
|          Stance of Judgement           |   Magic   |  80   |

### <a name="sourcesofabsortionandresistance"></a>Sources of Absorption, Resistance, and Cure

The highest theoretical level of Physical Absorption possible is ?. This is achieved by equiping Catarina Helm, Smough's Armor, Smough's Guantlets, Harald Knight Leggings, Ring of Steel Protection +3, Lloyd's Shield Ring, casting Sacred Oath and Iron Flesh, all while at > 99% HP.

#### <a name="flatabsorptionincrease"></a>![Defense UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_def_up.png) Flat Absorption Increase

| Source                                | Damage Type           | Increase                                 |
|:-------------------------------------:|:---------------------:|:----------------------------------------:|
|            Deep Protection            |          All          |                   +5%                    |
|     Speckled Stoneplate Ring (+1)     | Fire, Lightning, Dark |                +5% (+7%)                 |
|           Oath of Sunlight            |          All          |                   +10%                   |
|              Sacred Oath              |          All          |                   +10%                   |
| Ring of Steel Protection (+1, +2, +3) |       Physical        | +10% (+13%, +15%, +17%) *reduced in PVP* |
|    Magic Stoneplate Ring (+1, +2)     |         Magic         |            +13% (+17%, +20%)             |
|    Flame Stoneplate Ring (+1, +2)     |         Fire          |            +13% (+17%, +20%)             |
|   Thunder Stoneplate Ring (+1, +2)    |       Lightning       |            +13% (+17%, +20%)             |
|     Dark Stoneplate Ring (+1, +2)     |         Dark          |            +13% (+17%, +20%)             |
|            Blue Bugpellets            |         Magic         |              +15% for 120s               |
|            Red Bugpellets             |         Fire          |              +15% for 120s               |
|           Yellow Bugpellets           |       Lightning       |              +15% for 120s               |
|           Black Bugpellets            |         Dark          |              +15% for 120s               |
|              Flash Sweat              |         Fire          |                   +30%                   |
|              Iron Flesh               |       Physical        |                   +40%                   |
|             Magic Shield              |          All          |                    ?                     |
|          Great Magic Shield           |          All          |                   Max                    |
|             Magic Barrier             |         Magic         |                    ?                     |
|          Great Magic Barrier          |         Magic         |                    ?                     |

#### <a name="conditionalabsorptionincrease"></a>![Defense UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_def_up.png) Conditional Absorption Increase

| Source              | Condition       | Increase           |
|:-------------------:|:---------------:|:------------------:|
| Blue Tearstone Ring |    < 20% HP     | +20% (+15% in PVP) |
| Lloyd's Shield Ring |    > 99% HP     | +25% (+15% in PVP) |
|  Dragonscale Ring   | Critical Attack |        +30%        |

#### <a name="absorptiondecrease"></a>![Defense DOWN](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_calamity.png) Absorption Decrease

| Source                | Damage Type | Decrease |
|:---------------------:|:-----------:|:--------:|
|   Prisoner's Chain    |     All     |   -4%    |
|   Magic Clutch Ring   |    Magic    |   -10%   |
|   Flame Clutch Ring   |    Fire     |   -10%   |
| Lightning Clutch Ring |  Lightning  |   -10%   |
|   Dark Clutch Ring    |    Dark     |   -10%   |
|   Carthus Bloodring   |     All     |   -15%   |
|     Crown of Dusk     |    Magic    |   -30%   |
|    Blindfold Mask     |    Dark     |   -30%   |
|     Calamity Ring     |     All     |   100%   |

#### <a name="resistanceincrease"></a>![Defense UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_res_up.png) Resistance Increase

| Source               | Effect                                | Increase                |
|:--------------------:|:-------------------------------------:|:-----------------------:|
| Bloodbite Ring (+1)  |               Bleeding                |  +90 (+140) resistance  |
| Poisonbite Ring (+1) |               Poisoning               |  +90 (+140) resistance  |
|    Chillbite Ring    |               Frostbite               |     +140 resistance     |
|    Cursebite Ring    |                 Curse                 |     +140 resistance     |
|   Deep Protection    | Bleeding, Poisoning, Frostbite, Curse |     +20 resistance      |
|    Fleshbite Ring    | Bleeding, Poisoning, Frostbite, Curse |     +60 resistance      |
|      Mossfruit       | Bleeding, Poisoning, Frostbite, Curse | +80 resistance for 60s  |
|    Profuse Sweat     | Bleeding, Poisoning, Frostbite, Curse |     +80 resistance      |
|       Siegbrau       |               Frostbite               | +150 resistance for 60s |

#### <a name="cures"></a>Cures

| Source                     | Cures                              |
|:--------------------------:|:----------------------------------:|
|    Bloodred Moss Clump     |              Bleeding              |
|     Purple Moss Clump      |             Poisoning              |
| Blooming Purple Moss Clump |               Toxic                |
|    Rime-Blue Moss Clump    |             Frostbite              |
|       Purging Stone        |               Curse                |
|      Divine Blessing       | Bleed, Poisoning, Toxic, Frostbite |
|      Caressing Tears       |   Bleeding, Poisoning, Frostbite   |

### <a name="sourcesofadditionaleffects"></a>Sources of Additional Effects

#### <a name="bleed"></a>![Bleeding](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-bleedres.png) Bleed

| Weapon                           | +10 | +10 (60 LUCK) | +10 Blood Infusion (60 LUCK) |
|:--------------------------------:|:---:|:-------------:|:----------------------------:|
|          Bandit's Knife          | 33  |               |              76              |
|      Barbed Straight Sword       | 34  |               |              82              |
|           Black Blade            | 34  |               |              82              |
|            Bloodlust             | 35  |               |              \-              |
|    Carthus Curved Greatsword     | 38  |               |             108              |
|       Carthus Curved Sword       | 35  |               |              86              |
|          Carthus Shotel          | 34  |               |              81              |
|           Chaos Blade            | 36  |               |              \-              |
|               Claw               | 34  |               |              83              |
|           Crow Talons            | 33  |               |              82              |
|            Darkdrift             | 34  |               |              \-              |
|            Flamberge             | 33  |               |              86              |
|       Great Corvian Scythe       | 36  |               |              91              |
|           Great Scythe           | 37  |               |              86              |
|          Manikin Claws           | 34  |               |              81              |
|           Morion Blade           | 38  |               |              \-              |
|           Morning Star           | 33  |               |              72              |
|           Notched Whip           | 33  |               |              75              |
|       Onikiri and Ubidachi       | 33  |               |              86              |
| Painting Guardian's Curved Sword | 35  |               |              88              |
|         Reinforced Club          | 34  |               |              74              |
|           Spiked Mace            | 33  |               |              97              |
|        Warden Twinblades         | 34  |               |              83              |
|           Washing Pole           | 33  |               |              80              |
|            Uchigatna             | 34  |               |              81              |

| Source                 | Bleed |
|:----------------------:|:-----:|
| Feast Chime (Eleanora) |  45   |
|          Gnaw          |  130  |
|      Dorhy's Gnaw      |  210  |
|         Kukri          |  35   |
|   Splintering Bolts    |   3   |
|     Carthus Rouge      |  20   |

#### <a name="poison"></a>![Poisoning](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-poisonres.png) Poison

| Weapon                   | +10 | +10 (60 LUCK) | +10 Poison Infusion (60 LUCK) |
|:------------------------:|:---:|:-------------:|:-----------------------------:|
|    Rotten Ghru Dagger    | 34  |               |              96               |
| Rotten Ghru Curved Sword | 33  |               |              108              |
|    Rotten Ghru Spear     | 34  |               |              98               |
|      Arstor's Spear      | 35  |               |              71               |
|       Spotted Whip       | 34  |               |              \-               |

| Source                              | Poison  |
|:-----------------------------------:|:-------:|
|             Poison Mist             | 15/tick |
| Poison Spores (Storyteller's Staff) | 42/tick |
|       Poison Throwing Dagger        |   25    |
|            Poison Arrows            |   30    |
|          Rotten Pine Resin          |   45    |

#### <a name="toxic"></a>![Toxic](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-poisonres.png) Toxic

| Source       | Toxic   |
|:------------:|:-------:|
|  Toxic Mist  | 12/tick |
|   Dungpie    |         |
| Rope Dungpie |         |

#### <a name="frost"></a>![Frostbite](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/icon-frostres.png) Frost

| Source                                    | Frost                   |
|:-----------------------------------------:|:-----------------------:|
|          Irithyll Straight Sword          |           55            |
|           Vordt's Great Hammer            |           110           |
|    Frost (Pontiff Knight Great Scythe)    |           55            |
| Frost Blade (Pontiff Knight Curved Sword) |           110           |
|              Irithyll Rapier              |           55            |
| Friede's Great Scythe / Elfriede's Stance | 45 / L2R1 36, L2R2 67.5 |
|               Frozen Weapon               |           48            |
|                Snap Freeze                |         15/tick         |

### <a name="poisemodifiers"></a>Poise Modifiers

#### <a name="armorpoiseincrease"></a>![Poise UP](https://raw.githubusercontent.com/yepitsfz/ds3mechanicscheatsheet/master/icons/ds3_status_poise.png) Armor Poise Increase

The highest theoretical level of Armor Poise possible is 63.75. This is achieved by equiping Havel's Armor Set, Yhorm's Greatshield, Wolf Ring +3, and Lothric Knight Long Spear.

| Source                    | Increase        |
|:-------------------------:|:---------------:|
|  Wolf Ring (+1, +2, +3)   | +4 (+6, +8, +9) |
| Lothric Knight Long Spear |       +15       |
|    Yhorm's Greatshield    |       +15       |

#### <a name="poiseandstaminadamage"></a>Base Poise and Stamina Damage

| Source               | Poise Damage        | Stamina Damage    |
|:--------------------:|:-------------------:|:-----------------:|
|       Daggers        |         10          |        25         |
|   Straight Swords    |         14          |        44         |
|     Greatswords      |         26          |        56         |
|  Ultra Greatswords   |         31          |        70         |
|    Curved Swords     |         14          |        38         |
|  Curved Greatswords  |         31          |        55         |
|   Thrusting Swords   |         11          |        37         |
|       Katanas        |         14          |        45         |
|         Axes         |         14          |        50         |
|      Greataxes       |         31          |        75         |
|       Hammers        |         25          |        56         |
|    Great Hammers     |         35          |        80         |
|        Spears        |         14          |        40         |
|        Pikes         |         14          |        40         |
|       Halberds       |         19          |        55         |
|       Reapers        |         14          |        39         |
|        Whips         |         14          |        25         |
|        Fists         | 14 (11 for Caestus) |        28         |
|        Claws         |         14          |        26         |
|        Torch         |         10          |        25         |
| Knight's Slayer Ring |         \-          |       +10%        |
|    Horsehoof Ring    |         \-          | +30% (Kicks only) |

#### <a name="hyperarmor"></a>Weapons with Poise Frames

| Weapon                      | Attacks | Weapon Art?                     |
|:---------------------------:|:-------:|:-------------------------------:|
|      Ultra Greatswords      | 1H, 2H  |               Yes               |
|      Farron Greatsword      | 1H, 2H  |               No                |
|        Great Hammers        | 1H, 2H  |               Yes               |
|         Great Axes          | 1H, 2H  |               Yes               |
|        Great Machete        | 1H, 2H  |               No                |
|     Curved Greatswords      | 1H, 2H  |               Yes               |
|         Greatswords         |   2H    |               Yes               |
|          Halberds           |   2H    |               Yes               |
| Halberd, Red Hilted Halberd |  2H R2  |               Yes               |
|           Hammers           |   2H    | Warcry, Spin Bash, Perseverance |
|            Pikes            |   \-    |             Charge              |
|       Straight Swords       |   \-    |    Stomp, Stance, Spin Slash    |
|            Axes             |   \-    |       Warcry, Chain Spin        |
|           Reapers           |   \-    |            Neckswipe            |
|     Onikiri & Ubidachi      |   \-    |               Yes               |
|            Claws            |   \-    |               Yes               |
|          Talismans          |   \-    |       Unfaltering Prayer        |

#### <a name="guardmodifiers"></a>Guard Modifiers

### <a name="stabilityincrease"></a>Stability Increase

| Source             | Increase |
|:------------------:|:--------:|
|    Magic Shield    |   18%    |
| Great Magic Shield |   35%    |

### <a name="guardmitigation"></a>Guard Mitigation

| Weapon           | Attack          |
|:----------------:|:---------------:|
|     Daggers      |    Blindspot    |
| Straight Swords  |     Stance      |
|   Greatswords    |     Stance      |
| Thrusting Swords |     Stance      |
| Thrusting Swords | Shield Splitter |
|     Katanas      |    Darkdrift    |
|      Spears      | Shield Splitter |
|      Whips       |     Impact      |
|       Bows       |    Puncture     |

### <a name="sourcesofmagicattackincrease"></a>Sources of Magic Attack Increase

#### <a name="spelldamageincrease"></a>Spell Damage Increase

#### <a name="castingspeedincrease"></a>Casting Speed Increase

#### <a name="nonscalingspells"></a>Non-scaling spells

-	Miracles

	-	Replenishment
	-	Bountiful Light
	-	Bountiful Sunlight
	-	Caressing Tears
	-	Tears of Denial
	-	Homeword
	-	Seek Guidance
	-	Sacred Oath
	-	Force
	-	Emit Force
	-	Wrath of the Gods
	-	Blessed Weapon (buff is flat 7.5%, healing scales with FTH)
	-	Vow of Silence
	-	Atonement
	-	Deep Protection
	-	Gnaw (bleed buildup only, impact damage is scaling Dark)
	-	Dorhy's Gnawing (bleed buildup only, impact damage is scaling Dark)

-	Pyromancies

	-	Poison Mist
	-	Toxic Mist
	-	Acid Mist
	-	Flash Sweat
	-	Profuse Sweat
	-	Iron Flesh
	-	Power Within
	-	Carthus Beacon
	-	Warmth
	-	Rapport

-	Sorceries

	-	Magic Shield
	-	Great Magic Shield
	-	Spook
	-	Aural Decoy
	-	Pestilent Mercury
	-	Cast Light
	-	Repair
	-	Hidden weapon
	-	Hidden Body
	-	Chameleon
	-	Twisted Wall of Light
	-	Frozen weapon
	-	Snap Freeze
