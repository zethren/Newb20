# Game Mechanics

This section is the home for shared rules and system-wide tables. Combat, Equipment, and Exploration pages act as additional topic indexes into these mechanics.

## Core Resolution Terms

- **AB:** Attack Bonus.
- **AC:** Armor Class.
- **BAB:** Base Attack Bonus.
- **MAB:** Martial Ability Bonus, used for special maneuver checks.
- **MAD:** Martial Ability Defense, the target number such checks must meet or exceed.

For a maneuver check, roll `d20 + MAB` and compare the result with the target's static MAD. Calculate the scores as follows:

- **MAB:** `BAB + Strength modifier + size modifier + miscellaneous modifiers`.
- **MAD:** `10 + BAB + Strength modifier + Dexterity modifier + size modifier + miscellaneous modifiers`.

Use ability modifiers, not raw ability scores. Apply size modifiers from the [Combat Scaling](game-mechanics/combat-scaling.md#size-modifiers) table. Miscellaneous modifiers include applicable bonuses such as [Pack Tactics](classes/abilities/shifter/pack-tactics.md) and [Bear's Maneuvering Stance](classes/abilities/shifter/bear-maneuvering-stance.md). A feat may explicitly allow a character to substitute a different ability modifier for Strength when calculating MAB; such a substitution does not add to Strength unless the feat says otherwise.

Against a fixed Difficulty Class (DC), a check succeeds if its total meets or exceeds the DC. In a contested check, compare the participants' totals; the higher total succeeds, and the defender wins ties. This also applies to Attack Bonus (AB) checks against Armor Class (AC) and saving throws against a DC.

## Basic Action Economy

On their turn, a character has one **Standard Action**, one **Move Action**, and one **Free Action**. Actions have the following hierarchy: **Standard > Move > Free**. A character may give up one action to take one additional action of a lower tier: a Standard Action can be exchanged for one additional Move or Free Action, and a Move Action can be exchanged for one additional Free Action.

A **Full-Round Action** consumes the character's Standard and Move Actions for the turn, but leaves their Free Action available. A **Full Attack Action** is a Full-Round Action.

A **Reaction** is a separate response outside the three-action allotment. A character can take at most one Reaction between the start of their turn and the start of their next turn; this allowance refreshes at the start of their turn.

## Movement and Encumbrance

Base land speed is determined by current size in the [Combat Scaling table](game-mechanics/combat-scaling.md#size-modifiers); an ancestry trait can set a different base speed. Heavy armor reduces a 30-foot speed to **20 feet**. Encumbrance halves movement speed; a heavily encumbered character cannot move at all. An ancestry trait can negate speed reductions from armor or encumbrance, but does not negate the inability to move while heavily encumbered.

## Universal Tables

- [Combat Scaling](game-mechanics/combat-scaling.md): global size modifiers, 5-ft square sharing, size-based utility, and weapon damage scaling.

## Rules Catalog

### Combat

- [Conditions](game-mechanics/conditions.md)
- [Health, Dying, and Recovery](game-mechanics/health.md)
- [Armor Class Components](game-mechanics/armor-class.md)
- [Grapple, Thrash, and Throw](game-mechanics/grapple-and-throw.md)
- [Martial Maneuvers](game-mechanics/maneuvers.md): shared maneuver rules, Trip, and maneuver-specific defensive modifiers.
- [Mounted Combat](game-mechanics/mounted-combat.md)
- [Sneak Attack](game-mechanics/sneak-attack.md)

### Other Shared Rules

- [Item Durability](game-mechanics/item-durability.md)
- [Resting and Combat Stamina](game-mechanics/resting.md)
- [Scent and Tracking](game-mechanics/scent.md)
- [Swimming](game-mechanics/swimming.md)
- [Transformation Rules](game-mechanics/transformations.md)