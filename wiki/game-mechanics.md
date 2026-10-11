# Game Mechanics

This section is the home for shared rules and system-wide tables. Combat, Equipment, and Exploration pages act as additional topic indexes into these mechanics.

## Resolution Terms

- **AB:** Attack Bonus.
- **AD:** Attack Damage, the damage dealt by a successful attack.
- **AC:** Armor Class.
- **BAB:** Base Attack Bonus.
- **MAB:** Martial Ability Bonus, used for special maneuver checks.
- **MAD:** Martial Ability Defense, the target number such checks must meet or exceed.

For a maneuver check, roll `d20 + MAB` and compare the result with the target's static MAD. Calculate the scores as follows:

- **MAB:** `BAB + Strength modifier + size modifier + miscellaneous modifiers`.
- **MAD:** `10 + BAB + Strength modifier + Dexterity modifier + size modifier + miscellaneous modifiers`.

Use ability modifiers, not raw ability scores. Apply size modifiers from the [Combat Scaling](game-mechanics/combat-scaling.md#size-modifiers) table. Apply any other modifiers specified by the relevant effect. A feat may explicitly allow a character to substitute a different ability modifier for Strength when calculating MAB; such a substitution does not add to Strength unless the feat says otherwise.

Against a fixed Difficulty Class (DC), a check succeeds if its total meets or exceeds the DC. In a contested check, compare the participants' totals; the higher total succeeds, and the defender wins ties. This also applies to Attack Bonus (AB) checks against Armor Class (AC) and saving throws against a DC.

## Damage Types

Damage has one or more types. A type determines which resistances, vulnerabilities, and other effects apply; it does not by itself determine which creatures are harmed or healed. Use these standard names throughout the handbook:

| Type | Meaning |
| --- | --- |
| Acid | Corrosive damage. |
| Cold | Freezing damage. |
| Electric | Electrical damage, including lightning. |
| Fire | Heat and flame damage. |
| Sonic | Sound and pressure-wave damage. |
| Positive energy | Vital energy; it restores HP to living creatures and damages undead. |
| Negative energy | Entropic energy; it damages living creatures and restores HP to undead. |
| Holy | Sacred damage that can harm living and undead creatures; it does not restore HP. |
| Corrupt | Profane or entropic damage that can harm living and undead creatures; it does not restore HP. |
| Poison | Toxic damage. |
| Psychic | Damage that directly harms the mind. |
| Blunt | Impact damage; also called bludgeoning damage. |
| Piercing | Damage from puncturing or impaling. |
| Slashing | Damage from cutting. |
| Magic | Direct magical force; also called force damage. |

Older terms map to the standard type as follows: electricity or lightning to Electric, thunder to Sonic, radiant or divine to Holy, necrotic to Corrupt, force to Magic, and bludgeoning to Blunt. Use the standard type names in new rules. Elemental damage means Acid, Cold, Electric, Fire, or Sonic damage. Physical attacks can have multiple physical types simultaneously, as described in [Combat Scaling](game-mechanics/combat-scaling.md#natural-weapon-properties).

An effect's own rules specify its targets, amount, and any saving throw. Holy and Corrupt damage are distinct from Positive and Negative energy and have no automatic healing interaction.

## Energy Resistance

Energy Resistance X reduces each instance of matching energy damage by X, to a minimum of 0. Energy Resistance 5 also allows comfortable existence in environments of that energy type without environmental hazard damage or associated penalties.

## Basic Action Economy

On their turn, a character has one **Standard Action**, one **Move Action**, and one **Free Action**. Actions have the following hierarchy: **Standard > Move > Free**. A character may give up one action to take one additional action of a lower tier: a Standard Action can be exchanged for one additional Move or Free Action, and a Move Action can be exchanged for one additional Free Action.

A **Full-Round Action** consumes the character's Standard and Move Actions for the turn, but leaves their Free Action available. A **Full Attack Action** is a Full-Round Action unless a feature or feat says otherwise.

A **Reaction** is a separate response outside the three-action allotment. A character can take one Reaction between the start of their turn and the start of their next turn; this allowance refreshes at the start of their turn. Effects that grant additional Reactions increase this limit for that interval. An Attack of Opportunity uses one Reaction.

### Attacks of Opportunity from Movement

Unless an effect says otherwise, a creature provokes an Attack of Opportunity from each enemy able to take one when it moves out of a square that enemy threatens. The attacker resolves the attack before the creature leaves that square. A hit does not stop or reduce the movement. Each attack spends one Reaction. See [Mobility](feats/mobility.md) and [Attacks of Opportunity from Casting](spells.md#casting-in-combat).

A single movement provokes no more than one Attack of Opportunity from the same enemy, even if the creature leaves more than one square that enemy threatens.

### Ranged Attacks in Melee

Making a ranged weapon attack while within an enemy's reach provokes an Attack of Opportunity from that enemy if it can take one. Resolve the Attack of Opportunity before the ranged attack roll; being hit does not by itself interrupt the attack. [Point Blank Shot](feats/point-blank-shot.md) prevents this provocation when its target is within 30 feet.

### Defensive Combat Options

A character may choose to fight defensively while making attacks on their turn. Until the start of their next turn, they gain a +2 Circumstance bonus to Dodge AC and take a -4 penalty on attack rolls. [Combat Expertise](feats/combat-expertise.md) and [Improved Combat Expertise](feats/improved-combat-expertise.md) modify these benefits and penalties.

As a Full-Round Action, a character may take Total Defense. Until the start of their next turn, they gain a +4 Circumstance bonus to Dodge AC and take a -8 penalty on attack rolls, including attacks made as Reactions. They cannot make attacks on their turn while taking Total Defense. Combat Expertise and Improved Combat Expertise modify these benefits and penalties.

### Flanking

You and an ally flank a creature when you both threaten it with melee attacks and occupy positions on opposite sides of it. Flanking grants no benefit by itself; feats and features may use it as a requirement.

## Movement and Encumbrance

Base land speed is determined by current size in the [Combat Scaling table](game-mechanics/combat-scaling.md#size-modifiers); an ancestry trait can set a different base speed. Heavy armor reduces a 30-foot speed to **20 feet**. Encumbrance halves movement speed; a heavily encumbered character cannot move at all. An ancestry trait can negate speed reductions from armor or encumbrance, but does not negate the inability to move while heavily encumbered.

## Tables

- [Combat Scaling](game-mechanics/combat-scaling.md): global size modifiers, 5-ft square sharing, size-based utility, and weapon damage scaling.
- [Damage Types](#damage-types): standard damage type names and terminology.

## Rules Catalog

### Combat

- [Conditions](game-mechanics/conditions.md)
- [Health, Dying, and Recovery](game-mechanics/health.md)
- [Armor Class Components](game-mechanics/armor-class.md)
- [Grapple, Thrash, and Throw](game-mechanics/grapple-and-throw.md)
- [Martial Maneuvers](game-mechanics/maneuvers.md): shared maneuver rules, Trip, and maneuver-specific defensive modifiers.
- [Mounted Combat](game-mechanics/mounted-combat.md)
- [Sneak Attack](game-mechanics/sneak-attack.md)

### Other Rules

- [Item Durability](game-mechanics/item-durability.md)
- [Magic Item Enchantments](game-mechanics/magic-item-enchantments.md)
- [Resting and Combat Stamina](game-mechanics/resting.md)
- [Scent and Tracking](game-mechanics/scent.md)
- [Swimming](game-mechanics/swimming.md)
- [Transformation Rules](game-mechanics/transformations.md)

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="index.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="combat.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Combat</a>
<a href="equipment.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Equipment</a>
<a href="spells.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Spells</a>
</nav>
