# Conditions

Conditions describe effects that change a creature's actions, defenses, or capabilities.

## Base Condition Rules

* **No Self-Stacking:** A named condition applies only once to a creature, even when multiple sources apply it. Its penalties and restrictions are not multiplied by repeated applications.
* **Repeated Applications:** Use the longest remaining duration for the condition; do not add durations together.
* **Replacement:** Within a progression, the most advanced condition replaces the earlier stages. Applying an earlier stage cannot downgrade the current condition. Each condition's description states its effects in full; it does not inherit additional effects from earlier stages.
* **Progression:** Reapplying a condition does not automatically advance it. An effect or a specific progression rule must apply the later stage.
* **Other Conditions:** Conditions from different progressions, and conditions outside a progression, can apply together.

### Condition Progressions

| Progression | Earlier to later |
| --- | --- |
| Grappling | [Grappled](#grappled) -> [Pinned](#pinned) |
| Fatigue | [Fatigued](#fatigued) -> [Exhausted](#exhausted) |
| Sickness | [Sickened](#sickened) -> [Nauseated](#nauseated) |
| Fear | [Shaken](#shaken) -> [Fear](#fear) |
| Incapacitation | [Staggered](#staggered) -> [Dazed](#dazed) -> [Stunned](#stunned) -> [Paralyzed](#paralyzed) |

---

## Grapple Conditions

### Grappled
The initial capture state. Both the initiator and the target are locked in close-quarters wrestling.
* **Movement Limit:** Base movement speed is reduced to 0 feet.
* **Defensive Effects:** The target cannot execute Attacks of Opportunity. They lose their Dexterity AC and Dodge AC components against all external threats, but fully retain them against the initiator. See [Armor Class Components](armor-class.md).
* **Offensive Lock:** The target can still execute standard attacks and Full Attack routines, but is restricted strictly to Unarmed Strikes, Natural Weapons, or Light Melee Weapons.
* **Casting Gate:** Casting any spell requires a Concentration check with a DC equal to the grappler's CMD. On a failure, the spell fails and its casting resource is expended.

### Pinned
The initiator has successfully leveraged their mass to pin the target's primary limbs. **This is the active baseline state for any creature trapped inside a stomach cavity via Swallow Whole.**
* **Replaces:** [Grappled](#grappled).
* **Movement Limit:** Base movement speed is 0 feet.
* **Defensive Effects:** The target loses their Dexterity AC and Dodge AC components against *all* attackers, completely exposing their **Flat-Footed AC**. They suffer an additional flat **-4 penalty to their static AC** against external attackers.
* **Action Lock:** The target can take only mental and verbal actions, plus break attempts. It cannot make attack rolls and cannot cast spells with somatic components.
* **Casting Gate:** Casting any spell requires a Concentration check with a DC equal to the pinner's CMD. On a failure, the spell fails and its casting resource is expended.

### Helpless
A character is Helpless when bound, hog-tied, or otherwise unable to move or defend themselves.
* **Action Lock:** The target is completely immobilized. They **cannot execute any physical actions, attack rolls, or somatic spellcasting components** whatsoever.
* **Defensive Failure:** The target's effective Dexterity score drops to 0 (applying a permanent -5 modifier to AC). They are entirely vulnerable to Coup de Grace execution actions.

### Restrained
The target is completely bound, hog-tied, or physically locked in an inescapable mechanical structure. A Restrained target is [Helpless](#helpless).

---

## Physical and Positional Conditions

### Prone
The character is knocked flat on the ground or underwater floor.
* **Movement Limit:** The character cannot move normally. They must spend a Move Action to stand up, which automatically provokes Attacks of Opportunity from adjacent threats. They can crawl at a rate of 5 feet per Move Action.
* **Melee Attack Penalty:** The character suffers a flat **-4 penalty on all melee attack rolls**.
* **Defensive Matrix:** The character suffers a flat **-4 penalty to AC against melee attacks**, but gains a **+4 bonus to AC against ranged attacks** due to a minimized physical silhouette.

### Entangled
The character is ensnared by vines, nets, sticky resins, or localized magical bonds.
* **Movement Limit:** The character moves at half speed and cannot execute a Charge action.
* **Attack Penalty:** The character suffers a flat **-2 penalty on all attack rolls**.
* **Dexterity Penalty:** The character suffers a flat **-4 penalty to their effective Dexterity score**, reducing their AC and Reflex saves by 2.
* **Casting Gate:** Casting any spell requires a Concentration Check (`DC = 15 + spell level`). On a failure, the spell fails and its casting resource is expended.

### Fatigued
The character is physically exhausted from overexertion or environmental hazards.
* **Action Lock:** The character cannot execute a Run or Charge action.
* **Ability Penalties:** The character suffers a flat **-2 penalty to Strength and Dexterity**.
* **Progression:** If a fatigued character is subjected to another effect that causes fatigue, they become [Exhausted](#exhausted).

### Exhausted
The character is completely physically spent.
* **Replaces:** [Fatigued](#fatigued).
* **Movement Limit:** The character can only move at half speed. They cannot Run or Charge.
* **Ability Penalties:** The character suffers a severe **-6 penalty to Strength and Dexterity**.

---

## Action-Inhibiting and Cognitive Conditions

### Berserk
The creature has lost control to a violent compulsion.
* **Action Compulsion:** On each of its turns, the creature must move toward and attack the nearest creature, regardless of whether that creature is friend or foe. It uses the shortest available route and makes an attack if it can reach a target; if it cannot, it continues moving toward the nearest creature.
* **Control Loss:** The creature cannot choose a different target or take a different action while Berserk.
* **Duration:** The effect that caused Berserk determines when it ends.

### Nauseated
The character is experiencing severe physical trauma, stomach sickness, or chemical distress. **This status condition instantly overrides and forces a predator to regurgitate any swallowed targets.**
* **Replaces:** [Sickened](#sickened).
* **Penalties:** The character suffers a flat **-2 penalty on all attack rolls, weapon damage rolls, saving throws, skill checks, and ability checks**.
* **Action Lock:** The character is heavily incapacitated. They **cannot attack, cast spells, concentrate, or execute standard actions** of any kind.
* **Action Allocation:** The character is restricted strictly to a **Single Move Action per turn** (allowing them to retreat or reposition).

### Sickened
A minor threshold variant of nausea. The character is physically unwell but functional.
* **Penalties:** The character suffers a flat **-2 penalty on all attack rolls, weapon damage rolls, saving throws, skill checks, and ability checks**.

### Shaken
The character is unnerved by fear or intimidation.
* **Penalties:** The character suffers a **-2 penalty on attack rolls, saving throws, and skill checks**.

### Fear
The character is terrified of a specific source, the creature that applied this condition.
* **Replaces:** [Shaken](#shaken).
* **Penalties:** The character suffers a **-4 penalty on attack rolls, saving throws, and skill checks**.
* **Source Restriction:** The character cannot make attacks against its source.
* **Approach Restriction:** The character cannot take any action that moves it closer to its source.
* **Duration:** The effect that applied Fear determines when it ends.

### Staggered
The character is unsteady, critically wounded, or mechanically slowed.
* **Action Allocation:** The character can only execute **either a single Standard Action OR a single Move Action per turn**, plus Free Actions and Reactions. They cannot perform Full-Round Actions or Full Attacks.

### Dazed
The character is momentarily disoriented.
* **Replaces:** [Staggered](#staggered).
* **Action Lock:** The character **cannot execute any actions or take Reactions**.
* **Defenses:** The character retains their full visual awareness and standard defense parameters. They do not lose their Dexterity AC or Dodge AC components and do not provoke attacks of opportunity.

### Stunned
The character has sustained massive neural or physical shock.
* **Replaces:** [Staggered](#staggered) and [Dazed](#dazed).
* **Action Lock:** The character drops everything held in their hands, falls prone if airborne, and **cannot execute any actions or take Reactions** whatsoever.
* **Defensive Effects:** The character loses their Dexterity AC and Dodge AC components (exposing their Flat-Footed AC) and drops their guard, granting all attackers a flat **-2 penalty to the character's static AC**.

### Paralyzed
The character’s muscles are entirely locked by magic, toxin, or structural nerve failure.
* **Replaces:** [Staggered](#staggered), [Dazed](#dazed), and [Stunned](#stunned).
* **Action Lock:** The character is frozen in place and **cannot move or execute any physical actions** whatsoever. They are locked into a sub-state of the [Helpless](#helpless) condition.
* **Cognitive Freedom:** The character retains full mental awareness. They can execute purely mental actions (such as psychic triggers or purely verbal/thought-based spellcasting) if the game engine allows.
* **Defensive Failure:** The character's Dexterity score drops to 0 (-5 AC modifier).

---

## Sensory Conditions

### Blinded
The character cannot see their surroundings due to darkness, magical curses, or ocular trauma.
* **Movement Limit:** The character moves at half speed. They suffer a flat -4 penalty on most Strength and Dexterity-based skill checks.
* **Accuracy Effects:** All opponents gain **Total Concealment (50% miss chance)** against the blinded character's attack rolls. The blinded character automatically fails all visual Perception checks.
* **Defensive Effects:** The character loses their Dexterity and Dodge bonuses to AC. Furthermore, external attackers gain a flat **+2 bonus on attack rolls** executed against the blinded target.

### Deafened
The character cannot perceive acoustic frequencies.
* **Sensory Effects:** The character automatically fails all sound-based Perception checks and suffers a flat -4 penalty on Initiative checks.
* **Casting Gate:** Any spell cast that includes a verbal component faces a flat **20% spell failure chance**, rolled on a d100 at the moment of execution.

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="../index.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="../game-mechanics.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Mechanics</a>
<a href="armor-class.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Armor Class Components</a>
<a href="combat-scaling.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Combat Scaling</a>
<a href="flight.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Flight Rules</a>
<a href="grapple-and-throw.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Grapple, Thrash, and Throw</a>
</nav>
