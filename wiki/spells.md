# Spells

Player-character spells use spell levels 1-9. Spell level 10 is reserved for epic magic and is not currently available to player characters.

## Spell-Level Access

Full casters gain access to spell levels according to the shared progression in [Classes](classes/index.md#full-spell-level-progression): spell level 1 at class level 1, increasing by one every two class levels, through spell level 9 at class level 17. The Paladin and Ranger use their class-specific limited spell-level progressions. Class-level access does not grant every spell at that level; known spells, spellbooks, schools, bloodlines, and other class restrictions still apply.

## Class Spell Lists

The [Cleric](spell-lists/cleric.md), [Druid](spell-lists/druid.md), and [Wizard](spell-lists/wizard.md) lists cover spell levels 1–9. The [Paladin](spell-lists/paladin.md) and [Ranger](spell-lists/ranger.md) lists cover spell levels 1–4. A spell page lists every class spell list and the spell level for each class. Each listed spell links to its own page with its casting rules and effect. Use the standard [damage types](game-mechanics.md#damage-types) throughout spell effects.

## Bonus Spell-Slot Progression

A caster gains the bonus spell slots shown below from their spellcasting ability score. The slots apply only to spell levels the caster can cast; scores below 12 grant no bonus slots. Cantrips do not receive bonus slots. A bonus slot gained from an increase to the primary spellcasting ability, including an Enhancement bonus from an item, persists through rests and is not lost if that increase later ends. It is expended and recovered like any other spell slot.

| Ability score | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
| ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| 8-11 | - | - | - | - | - | - | - | - | - |
| 12-13 | 1 | - | - | - | - | - | - | - | - |
| 14-15 | 1 | 1 | - | - | - | - | - | - | - |
| 16-17 | 1 | 1 | 1 | - | - | - | - | - | - |
| 18-19 | 1 | 1 | 1 | 1 | - | - | - | - | - |
| 20-21 | 2 | 1 | 1 | 1 | 1 | - | - | - | - |
| 22-23 | 2 | 2 | 1 | 1 | 1 | 1 | - | - | - |
| 24-25 | 2 | 2 | 2 | 1 | 1 | 1 | 1 | - | - |
| 26-27 | 2 | 2 | 2 | 2 | 1 | 1 | 1 | 1 | - |
| 28-29 | 2 | 2 | 2 | 2 | 2 | 1 | 1 | 1 | 1 |
| 30-31 | 2 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| 32-33 | 2 | 2 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| 34-35 | 2 | 2 | 2 | 1 | 1 | 1 | 1 | 1 | 1 |
| 36-37 | 2 | 2 | 2 | 2 | 1 | 1 | 1 | 1 | 1 |
| 38-39 | 2 | 2 | 2 | 2 | 2 | 1 | 1 | 1 | 1 |
| 40-41 | 2 | 2 | 2 | 2 | 2 | 2 | 1 | 1 | 1 |

For scores above 41, continue the pattern: each additional 2 points adds one bonus slot to the next spell level, cycling from 1st through 9th. When the progression cycles back to 1st, add another slot at each spell level as the score increases by 2.

**CL** means caster level. A duration written as `X/CL` lasts for X multiplied by the caster's CL; for example, `1 minute/CL` lasts 1 minute per caster level. Damage written as `1d6/CL` means one d6 per caster level. Caster-level damage progressions have no maximum damage-dice cap; when a progression grants one or more dice per multiple caster levels, round down unless the spell says to round up. Each spell's rate is set for its class and level, target count, area, damage type, attack or saving-throw interaction, and whether it can deal damage repeatedly; some repeated or weapon-like effects therefore retain fixed damage. A spell's individual formula controls. For a spellcasting class, caster level equals the character's level in that class unless a rule modifies it. Multiclass levels do not combine. [Practiced Spellcaster](feats/practiced-spellcaster.md) can increase caster level, but does not alter spell progression.

## Spell Attacks and Save DCs

A spell attack bonus is **base attack bonus + spellcasting ability modifier + other applicable bonuses**. Use it for ranged spell attacks and touch spell attacks.

The saving-throw DC for a spell is **10 + spell level + the caster's primary spellcasting ability modifier + any applicable bonuses to the DC**. Apply bonus stacking as described in [Attributes](attributes.md#bonus-types-and-stacking); each class identifies its primary spellcasting ability.

Any spell that changes AC must identify the affected AC component, bonus type, and amount. If it changes a creature's size, specify the size change and apply the corresponding Size AC adjustment. Resolve stacking using [Armor Class Components](game-mechanics/armor-class.md).

When a spell or other magical effect is subject to a target's spell resistance, make a caster-level check (**1d20 + caster level**) against the target's spell resistance. The check succeeds if the result equals or exceeds the target's spell resistance. Spell Penetration feats add their listed bonuses to this check.

## Summoning

Unless a spell says otherwise, summoned creatures appear in unoccupied spaces within range, act immediately after the caster, and understand the caster's spoken commands. The caster can issue them a brief command as a Free Action once per turn. They can move up to 30 feet on their turn, or use the speed listed by the spell, and can take the attacks and special actions the spell describes. If no command is given, they defend themselves. A summoned creature cannot cast spells or activate magic items, and vanishes when the spell ends or it is reduced to 0 hit points.

There is no general cap on the number of summoned creatures or undead creatures a character can have active or controlled at one time. Each spell's duration, per-casting creature limit, control rules, and other restrictions still apply; this does not change limits on animal companions.

### Beast Call I-IX

The Roman numeral is both the Druid spell level and the maximum Challenge Rating (CR) of a single beast it can summon. The caster chooses either one beast with CR equal to the spell's numeral or rolls `1d4` to summon that many beasts, all with the same lower CR. Use an appropriate animal stat block selected with the GM. All other summoning rules above apply.

## Counterspell

Any spellcaster can use a Reaction when they see a creature within 60 feet begin casting a spell. To counter it, the caster must expend the same spell or a spell explicitly designated as a native counter to it. A matching spell interrupts the casting. The countering spell is expended using its normal casting resource.

Instead, a caster may expend an applicable Dispel spell to counter the casting. Resolve the attempt using the Dispel rules.

## Casting in Combat

Casting a spell with a Standard Action or Full-Round Action while within an enemy's reach provokes an Attack of Opportunity from each enemy in reach that can take one. Resolve these attacks before the spell resolves; each attacker spends its Reaction. Casting with another action type does not provoke an Attack of Opportunity under this rule.

If an Attack of Opportunity deals damage to the caster while the spell is being cast, the caster must succeed at a Concentration check with a DC of **10 + damage dealt + spell level**. Resolve a separate check for each damaging hit. If any check fails, the spell fails and its casting resource is expended. [Combat Casting](feats/combat-casting.md) improves these checks, while [Improved Combat Casting](feats/improved-combat-casting.md) prevents casting from provoking these attacks.

## Metamagic

When casting a spell, you may apply any number of different [metamagic feats](feats.md#spellcasting-feats) you know, provided their effects can all apply to that spell. Each feat can be applied only once to a casting. Add their spell-level adjustments together; the adjusted spell level cannot exceed 9. The adjustment increases the spell slot required or the Sorcery Point cost, but does not change caster level. The spell's save DC continues to use its original spell level unless Heighten Spell is applied.

A slot-based caster expends a slot of the adjusted spell level to cast the modified spell. A Sorcerer pays the Sorcery Point cost for the adjusted spell level shown in the Sorcerer class rules, in addition to any other Sorcery Point costs of the spell. A metamagic-modified cantrip is no longer cast at will: it requires a slot of its adjusted spell level or the corresponding Sorcery Point cost. Heighten Spell increases the spell's effective level, including its save DC, by the chosen amount.

Cantrips known by a character are always prepared and can be cast at will without expending spell slots or Sorcery Points. They do not count against a class's prepared-spell limit.

## Wizard Spell Slots

Wizards prepare a number of distinct spells from their spellbook equal to Wizard level + Intelligence modifier (minimum 1), choosing any spell level they can currently cast. Preparation is separate from spell slots: casting a prepared spell expends a slot of its level. The [Wizard class page](classes/base-classes/wizard/index.md#spellbook-and-daily-preparation) defines preparation; its [spell-slot table](classes/base-classes/wizard/index.md#spellcasting) lists base daily slots by spell level. Add Intelligence bonus slots using the [bonus spell-slot progression](#bonus-spell-slot-progression). Expended slots return after a Long Rest. School specialization grants no extra spell slots and does not prohibit learning or casting spells from other schools.

## Sorcerer Point Casting

Sorcerers do not use spell slots. They spend Sorcery Points, whose base daily progression is derived from the Wizard's base slot table. Each slot contributes points based on its spell level: levels 1-9 are worth 1, 2, 4, 8, 16, 32, 64, 128, and 256 points respectively. Add the point value of bonus spell slots granted by Charisma using the [bonus spell-slot progression](#bonus-spell-slot-progression). The Sorcerer's full pool returns after a Long Rest; short-rest recovery requires a specific class feature.

Sorcerers learn spell shapes and effects through class talents and combine compatible learned components freely, subject to bloodline access. Damage-size augmentation costs are documented in the [Sorcerer class](classes/base-classes/sorcerer/index.md#sorcery-point-pool).

## Scroll and Wand Activation

Activating a spell scroll or wand follows the [Use Magic Device rules](skills/use-magic-device.md#activating-scrolls-and-wands). Activating a scroll does not expend the user's spell slot; the scroll itself is consumed on successful use.

## Existing Spell Interactions

Routine spellcasting does not require a Concentration check. A specific disruption may require one; its rule sets the DC. Unless stated otherwise, failure causes the spell to fail and its spell slot to be expended. See [Concentration](skills/concentration.md).

- [Transformation Rules](game-mechanics/transformations.md) distinguishes ordinary Polymorph effects, which meld worn and carried items, from Baleful Polymorph and transformative curses, which follow the Shifter item rule.
- While mounted, casting a spell with somatic or verbal components requires a Concentration check at DC $15 +$ spell level. See [Mounted Combat](game-mechanics/mounted-combat.md).
- Entangled characters require a Concentration check at DC $15 +$ spell level to cast any spell. See [Conditions](game-mechanics/conditions.md).
- Casting under threat can provoke Attacks of Opportunity and require Concentration checks; see [Casting in Combat](#casting-in-combat).
- The Bodyguard's damage-interception feature applies to damage from spells, subject to its adjacency and area-effect rules. See [Bodyguard](classes/prestige-classes/bodyguard/index.md).
