# Combat Scaling

This page contains the size and natural-weapon rules used throughout the handbook.

## Size Modifiers

Apply these modifiers for a creature's current size, whether it is natural or caused by an effect. An effect may specify additional adjustments.

| Size | Steps from Medium | Attack and AC | MAB and MAD | Strength | Dexterity | Constitution | Stealth | Reach | Base land speed | 5-ft square sharing |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Diminutive | -3 | +4 | -4 | -4 | +4 | +0 | +12 | 0 ft. | 10 ft. | One partner of any size |
| Tiny | -2 | +2 | -2 | -2 | +2 | +0 | +8 | 0 ft. | 15 ft. | One partner of any size |
| Small | -1 | +1 | -1 | -2 | +2 | +0 | +4 | 5 ft. | 20 ft. | One partner of any size |
| Medium | 0 | +0 | +0 | +0 | +0 | +0 | +0 | 5 ft. | 30 ft. | One Small-or-smaller partner |
| Large | +1 | -1 | +1 | +4 | -2 | +0 | -4 | 10 ft. | 40 ft. | One Small-or-smaller partner |
| Huge | +2 | -2 | +2 | +8 | -4 | +0 | -8 | 15 ft. | 50 ft. | One Small-or-smaller partner |
| Gargantuan | +3 | -4 | +4 | +12 | -4 | +0 | -12 | 15 ft. | 60 ft. | One Small-or-smaller partner |
| Colossal | +4 | -8 | +8 | +16 | -4 | +0 | -16 | 30 ft. | 70 ft. | One Small-or-smaller partner |

The Strength, Dexterity, and Constitution entries are Size adjustments to ability scores. Apply them before calculating ability modifiers; they are not separate Racial bonuses.

The Size modifier to Stealth applies to all Stealth checks and is calculated as `-4 x Steps from Medium`. This yields a bonus for smaller sizes and a penalty for larger sizes.

### Sharing a 5-Ft Square

A 5-ft grid square can contain up to two creatures without a crowding penalty if at least one is Small or smaller. This includes a Medium-or-larger creature sharing with one Small-or-smaller creature, or two Small-or-smaller creatures sharing. A square without a Small-or-smaller creature can contain only one creature. Large and larger creatures occupy multiple squares; apply this limit separately to each square in their footprint.

## Size-Dependent Utility

| Size | Daily ration factor | Weight factor for creature and carried items |
| --- | ---: | ---: |
| Diminutive | 1/8 | 1/27 |
| Tiny | 1/4 | 1/9 |
| Small | 1/2 | 1/3 |
| Medium | 1 | 1 |
| Large | 2 | 3 |
| Huge | 4 | 9 |
| Gargantuan | 8 | 27 |
| Colossal | 16 | 81 |

- Apply the ration factor to daily requirements and to ration amounts listed for rests.
- For game purposes, weight scales by a factor of 3 per size step: `3^(Steps from Medium)`. This is a size-category abstraction rather than an exact doubling or halving of every linear dimension. Apply the weight factor to the creature and all carried items for encumbrance and when another creature carries or lifts them.
- Ration requirements scale by a factor of 2 per size step: `2^(Steps from Medium)`.
- A mount must be at least one size category larger than its rider; therefore, a Small rider can ride a Medium or larger mount. See [Mounted Combat](mounted-combat.md).
- Smaller creatures can fit into spaces too small for larger creatures and are easier for allies to carry or assist. The Stealth benefit is represented by the Size modifier above.

## Natural Weapon Properties

- Natural weapon attacks have a 19-20 / x2 critical threat profile.
- If an attack lists multiple physical damage types, it counts as all of those types simultaneously. The types do not multiply damage; they determine which damage-reduction rules the attack can bypass.
- A bite is treated as a two-handed weapon, adds 1.5 times the Strength modifier to damage, and deals blunt, piercing, and slashing damage.
- A claw is treated as a light, Weapon Finesse-compatible weapon and deals piercing and slashing damage. It adds the full Strength modifier in the main-hand slot and half the Strength modifier in an off-hand slot.

See [Damage Types](../game-mechanics.md#damage-types) for the standard type names and their effects.

## Weapon Damage by Size

For a weapon sized appropriately to its wielder, use the column for the wielder's current size and the row matching the weapon's Medium-size base damage. Medium is the reference column, centered between the smaller and larger sizes. This table applies to natural and manufactured weapons alike; weapon type does not change the size progression.

| Diminutive | Tiny | Small | Medium | Large | Huge | Gargantuan | Colossal |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | 1 | 1 | 1 | 1d2 | 1d3 | 1d4 | 1d6 |
| 1 | 1 | 1 | 1d2 | 1d3 | 1d4 | 1d6 | 1d8 |
| 1 | 1 | 1d2 | 1d3 | 1d4 | 1d6 | 1d8 | 2d6 |
| 1 | 1d2 | 1d3 | 1d4 | 1d6 | 1d8 | 2d6 | 3d6 |
| 1d2 | 1d3 | 1d4 | 1d6 | 1d8 | 2d6 | 3d6 | 4d6 |
| 1d3 | 1d4 | 1d6 | 1d8 | 2d6 | 3d6 | 4d6 | 6d6 |
| 1d4 | 1d6 | 1d8 | 1d10 | 2d8 | 3d8 | 4d8 | 6d8 |
| 1d6 | 1d8 | 1d10 | 1d12 | 3d6 | 4d6 | 6d6 | 8d6 |
| 1d3 | 1d4 | 1d6 | 2d4 | 2d6 | 3d6 | 4d6 | 6d6 |
| 1d4 | 1d6 | 1d8 | 2d6 | 3d6 | 4d6 | 6d6 | 8d6 |

The listed rows cover the normal d20 weapon damage values. Damage for smaller-than-Minimum results is floored at 1.

## Swallow Whole Capacity

Stomach capacity uses a base Medium victim mass of 1.0 unit. The [Swallow Whole feat](../feats/swallow-whole.md) uses this matrix to limit the size and number of contained creatures.

| Creature size | Predator volume capacity | Victim mass | Maximum containment examples |
| --- | ---: | ---: | --- |
| Small | 0.2 | 0.25 | Cannot swallow targets. |
| Medium | 0.5 | 1.00 | Cannot swallow targets natively. |
| Large | 1.0 | 2.00 | Up to 4 Small victims (4 x 0.25). |
| Huge | 2.0 | 4.00 | 2 Medium victims (2 x 1.0) or 8 Small victims. |
| Gargantuan | 4.0 | 8.00 | 1 Large (2.0) + 2 Medium (2.0), or 4 Medium victims. |
| Colossal | 8.0 | 16.00 | 1 Gargantuan (8.0), or 2 Large + 4 Medium victims. |

Form profiles specify their natural attacks and Medium base damage; use the shared rules above to determine their properties and adjust damage by Size.

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="../index.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="../game-mechanics.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Mechanics</a>
<a href="mounted-combat.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Mounted Combat</a>
<a href="../feats/swallow-whole.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Swallow Whole</a>
<a href="armor-class.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Armor Class Components</a>
<a href="conditions.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Conditions</a>
</nav>
