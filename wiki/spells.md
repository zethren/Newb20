# Spells (Draft)

Player-character spells use spell levels 1-9. Spell level 10 is reserved for epic magic and is not currently available to player characters.

## Spell-Level Access

Full casters gain access to spell levels according to the shared progression in [Classes](classes.md#full-spell-level-progression): spell level 1 at class level 1, increasing by one every two class levels, through spell level 9 at class level 17. Class-level access does not grant every spell at that level; known spells, spellbooks, schools, bloodlines, and other class restrictions still apply.

## Bonus Spell-Slot Progression

A caster gains the bonus spell slots shown below from their spellcasting ability score. The slots apply only to spell levels the caster can cast; scores below 12 grant no bonus slots. Cantrips do not receive bonus slots.

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

Spell damage scales using the relevant caster-level formula without a maximum damage-dice cap. Unless a spell says otherwise, use levels in the class that grants the spellcasting; multiclass levels do not combine for spell damage.

## Spell Attacks and Save DCs

A spell attack bonus is **base attack bonus + spellcasting ability modifier + other applicable bonuses**. Use it for ranged spell attacks and touch spell attacks.

The recommended saving-throw DC for a spell is **10 + spell level + the caster's spellcasting ability modifier**. These spell attack and save DC formulas are recommendations pending playtest.

## Counterspell

Any spellcaster can use a Reaction when they see a creature within 60 feet begin casting a spell. To counter it, the caster must expend the same spell or a spell explicitly designated as a native counter to it. A matching spell interrupts the casting. The countering spell is expended using its normal casting resource.

Instead, a caster may expend an applicable Dispel spell to counter the casting. Resolve the attempt using the Dispel rules, which are still to be defined. A spell that counters or dispels another spell should identify that function in its description.

Cantrips known by a character are always prepared and can be cast at will without expending spell slots or Sorcery Points. They do not count against a class's prepared-spell limit. Damaging cantrips should remain short-range and low-damage.

## Wizard Spell Slots

Wizards prepare a number of distinct spells from their spellbook equal to Wizard level + Intelligence modifier (minimum 1), choosing any spell level they can currently cast. Preparation is separate from spell slots: casting a prepared spell expends a slot of its level. The [Wizard class page](classes/wizard.md#spellbook-and-daily-preparation) defines preparation; its [spell-slot table](classes/wizard.md#spellcasting) lists base daily slots by spell level. Add Intelligence bonus slots using the [bonus spell-slot progression](#bonus-spell-slot-progression). Expended slots return after a Long Rest. School specialization grants no extra spell slots and does not prohibit learning or casting spells from other schools.

## Sorcerer Point Casting

Sorcerers do not use spell slots. They spend Sorcery Points, whose base daily progression is derived from the Wizard's base slot table. Each slot contributes points based on its spell level: levels 1-9 are worth 1, 2, 4, 8, 16, 32, 64, 128, and 256 points respectively. Add the point value of bonus spell slots granted by Charisma using the [bonus spell-slot progression](#bonus-spell-slot-progression). The Sorcerer's full pool returns after a Long Rest; short-rest recovery requires a specific class feature.

Sorcerers learn spell shapes and effects through class talents and combine compatible learned components freely, subject to bloodline access. Damage-size augmentation costs are documented in the [Sorcerer class](classes/sorcerer.md#sorcery-point-pool). Spell attacks, components, duration, range, and the spell catalog remain to be defined.

## Scroll and Wand Activation

Activating a spell scroll or wand follows the [Use Magic Device rules](skills/use-magic-device.md#activating-scrolls-and-wands). Activating a scroll does not expend the user's spell slot; the scroll itself is consumed on successful use.

## Existing Spell Interactions

Routine spellcasting does not require a Concentration check. A specific disruption may require one; its rule sets the DC. Unless stated otherwise, failure causes the spell to fail and its spell slot to be expended. See [Concentration](skills/concentration.md).

- [Transformation Rules](game-mechanics/transformations.md) distinguishes ordinary Polymorph effects, which meld worn and carried items, from Baleful Polymorph and transformative curses, which follow the Shifter item rule.
- While mounted, casting a spell with somatic or verbal components requires a Concentration check at DC $15 +$ spell level. See [Mounted Combat](game-mechanics/mounted-combat.md).
- Entangled characters require a Concentration check at DC $15 +$ spell level to cast any spell. See [Conditions](game-mechanics/conditions.md).
- The Bodyguard's damage-interception feature applies to damage from spells, subject to its adjacency and area-effect rules. See [Bodyguard](classes/bodyguard.md).

These are interaction rules, not a spell catalog. Spell schools, components, saving throws, durations, and individual spells remain to be documented.