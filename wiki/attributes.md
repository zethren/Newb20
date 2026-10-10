# Attributes

The game uses six attributes. Current specifications use Strength, Dexterity, Constitution, and Wisdom modifiers in combat and class features; mechanical uses for Intelligence and Charisma are not yet documented. Starting scores use the 20-point-buy method below; attribute advancement rules are not yet defined.

| Attribute | Documented interactions |
| --- | --- |
| Strength (STR) | Shifter form adjustments; natural-weapon damage; grapple-related damage; several feat and maneuver effects. See [Primal Shifter](classes/primal-shifter.md), [Grapple and Throw Rules](game-mechanics/grapple-and-throw.md), and [Animal Feats](feats/animal-feats.md). |
| Dexterity (DEX) | Shifter form adjustments, AC, attack prerequisites, and conditions that remove or penalize Dexterity. See [Primal Shifter](classes/primal-shifter.md), [Conditions](game-mechanics/conditions.md), and [Mounted Combat](game-mechanics/mounted-combat.md). |
| Constitution (CON) | Bear form adjustments and the combat-round thresholds for Fatigue and Exhaustion. See [Primal Shifter](classes/primal-shifter.md) and [Resting](game-mechanics/resting.md). |
| Intelligence (INT) | No mechanical interactions are specified in the current rules. |
| Wisdom (WIS) | Ability modifier in the Wolf's Alpha's Howl save DC. See [Primal Shifter](classes/primal-shifter.md). |
| Charisma (CHA) | No mechanical interactions are specified in the current rules. |

The [Primal Shifter specification](classes/primal-shifter.md) also contains a global size-adjustment table. Size adjustments are not attribute-generation rules.

## Starting Ability Scores

Before applying ancestry, form, or other bonuses, assign each of the six attributes a score from 8 to 18 using a **20-point buy**. Add the costs for all six scores; the total cannot exceed 20. A score of 8 refunds 2 points relative to a score of 10.

| Score | Point cost |
| ---: | ---: |
| 8 | -2 |
| 9 | -1 |
| 10 | 0 |
| 11 | 1 |
| 12 | 2 |
| 13 | 3 |
| 14 | 5 |
| 15 | 7 |
| 16 | 10 |
| 17 | 13 |
| 18 | 17 |

For example, scores of **18, 13, 10, 10, 10, and 10** use all 20 points.

## Ability Modifiers

Calculate an ability modifier as `floor((score - 10) / 2)`. Apply all relevant ability-score bonuses and penalties before calculating the modifier. For example, a score of 8 gives a -1 modifier, 10 gives +0, and 18 gives +4.

## Bonus Types and Stacking

For ability scores, add applicable bonuses to the base score, then calculate its modifier. For skill checks, add applicable bonuses to the check total. Bonus type—not the source that grants it—determines stacking. See [Transformation Rules](game-mechanics/transformations.md) for how an active form replaces ancestry-based racial traits and bonuses.

| Type | Sources and application | Stacking |
| --- | --- | --- |
| Base score | The character's starting ability score and permanent increases. This is not a bonus. | Not applicable; add applicable bonuses to it. |
| Size | The current-size adjustment from the [Combat Scaling](game-mechanics/combat-scaling.md#size-modifiers) table, or an explicit Size bonus from an effect. Apply only when the rule for the ability or check makes size relevant. | Size bonuses to the same ability or check do not stack. Use whichever is higher: the current-size table value or the explicit Size bonus. |
| Racial | An ancestry's or active form's racial ability or skill bonus. An active transformation replaces the ancestry's racial package with the form's package. | Ancestry racial bonuses are inactive while transformed. Multiple Racial bonuses to the same ability or check from the active racial package do not stack; use the highest. |
| Enhancement | Magical effects such as *Bull's Strength* and *Mass Bull's Strength*. | Enhancement bonuses to the same ability or check do not stack; use the highest. |
| Class Skill | The bonus for a skill designated as a class skill by a class. | The +3 bonus applies once to a skill check, even if multiple classes designate that skill as a class skill. |
| Circumstance | A bonus granted by a specific favorable condition, situation, or distinct effect. | Circumstance bonuses from distinct effects stack, including when they modify the same AC component. Repeated instances of the same effect do not stack. |
| Morale | Effects that explicitly grant a Morale bonus. | Morale bonuses to the same ability or check do not stack; use the highest. |
| Competence | Effects that explicitly grant a Competence bonus. | Competence bonuses to the same ability or check do not stack; use the highest. |
| Luck | Effects that explicitly grant a Luck bonus. | Luck bonuses to the same ability or check do not stack; use the highest. |
| Synergy | The +2 bonus from a skill with at least 5 ranks to a specific related skill check. | Synergy bonuses from different source skills stack. A source skill grants its linked bonus only once; it does not increase with additional ranks. |
| Supernatural | Bonuses from feats, class features, DM rewards, and special items are Supernatural by default unless the effect names another type. | Supernatural bonuses stack with one another and with bonuses of other types. |

An effect may name a bonus type that differs from its source: for example, a spell can grant an Enhancement bonus. Every bonus must have a type so the game can apply these stacking rules consistently. Do not add a separate Size bonus to a skill check when its effect is already included in the relevant ability modifier.