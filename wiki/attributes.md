# Attributes

The game uses six attributes. Each rule or character option specifies which attribute it uses. Starting scores use the 20-point-buy method below.

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

## Ability Damage

Ability damage reduces an ability score directly; recalculate its modifier and all derived values from the reduced score. Temporary ability damage recovers by 1 point per damaged ability score after a Long Rest. Long-Term Care does not speed this recovery. Permanent ability damage does not recover through rest or care, but restorative magic can remove it. Damage from separate effects accumulates, and restoration cannot raise a score above its undamaged value.

## Bonus Types and Stacking

For ability scores, add bonuses to the base score before calculating the modifier. For checks and other statistics, add applicable bonuses to the base value. A base score is not a bonus type. Bonus type—not the source that grants a bonus—determines stacking. Different bonus types stack unless a rule below says otherwise. See [Transformation Rules](game-mechanics/transformations.md) for how an active form replaces ancestry-based racial traits and bonuses.

| Bonus type | Applies to | Stacks with different types? | Same-type stacking |
| --- | --- | --- | --- |
| Size | The current-size adjustment to relevant scores, checks, or AC from [Combat Scaling](game-mechanics/combat-scaling.md#size-modifiers), or an explicitly named Size bonus. | Yes. | Size bonuses to the same value do not stack; use the applicable current-size adjustment or the highest explicit Size bonus. |
| Racial | An ancestry's or active form's racial ability-score or skill bonus. | Yes. | Use only the active ancestry/form package; multiple Racial bonuses to the same value within that package do not stack. |
| Enhancement | Magical effects such as *Bull's Strength*, *Mass Bull's Strength*, or a bonus to a creature's Size category. | Yes. | Enhancement bonuses to the same value do not stack; use the highest. |
| Armor | An Armor bonus to AC granted by worn armor. | Yes. | Armor bonuses do not stack; a creature can wear only one suit of armor. |
| Shield | A Shield bonus to AC granted by a wielded shield. | Yes. | Shield bonuses do not stack; a creature can benefit from only one wielded shield. |
| Natural Armor | A Natural Armor bonus to AC from a creature's hide or an effect. | Yes. | Natural Armor bonuses stack. |
| Dodge | A Dodge bonus to AC from evasion, movement, or a defensive effect. | Yes. | Dodge bonuses stack. |
| Ioun Stone | Persistent bonuses granted by Ioun Stones. | Yes, including with a non-Ioun bonus of the same usual type. | Bonuses from multiple Ioun Stones to the same statistic, saving throw, check, or AC component do not stack; use the highest. |
| Teamwork | Benefits granted by teamwork feats. | Yes. | Teamwork bonuses to the same statistic or check do not stack unless a feat explicitly says otherwise; use the highest. |
| Class Skill | The +3 bonus for a skill designated as a class skill. | Yes. | Applies once to a skill check, even if multiple classes designate that skill as a class skill. |
| Circumstance | A specific favorable situation or distinct effect; may apply to checks or an identified AC component. | Yes. | Distinct effects stack. Repeated instances of the same effect do not stack. |
| Morale | Effects explicitly granting a Morale bonus to a score, check, attack, save, or other statistic. | Yes. | Morale bonuses to the same value do not stack; use the highest. |
| Competence | Effects explicitly granting a Competence bonus to a score, check, or other statistic. | Yes. | Competence bonuses to the same value do not stack; use the highest. |
| Luck | Effects explicitly granting a Luck bonus to a score, check, attack, save, or AC component. | Yes. | Luck bonuses to Luck AC stack. Luck bonuses to the same non-AC value do not stack; use the highest. |
| Deflection | Effects explicitly granting a Deflection bonus, usually to Deflection AC. | Yes. | Deflection bonuses to the same AC component or statistic do not stack; use the highest. |
| Synergy | The +2 bonus from a skill with at least 5 ranks to a specific related skill check. | Yes. | Bonuses from different source skills stack. A source skill grants its linked bonus only once. |
| Supernatural | Effects explicitly granting a Supernatural bonus; use this type when a rule labels a bonus Supernatural. | Yes. | Supernatural bonuses stack with one another and with other types. |

An effect may name a bonus type that differs from its source: for example, a spell can grant an Enhancement bonus. New effects should state their bonus type; if an existing effect does not, treat its bonus as Supernatural unless its source is already defined as another type here. For AC, the **AC component** identifies where the modifier applies, while its **bonus type** determines stacking; see [Armor Class Components](game-mechanics/armor-class.md). Dodge AC, Armor AC, Shield AC, and similar components are not bonus types. Do not add a separate Size bonus to a skill check when its effect is already included in the relevant ability modifier.

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="index.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="skills.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Skills</a>
<a href="game-mechanics.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Mechanics</a>
<a href="game-mechanics/combat-scaling.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Combat Scaling</a>
</nav>
