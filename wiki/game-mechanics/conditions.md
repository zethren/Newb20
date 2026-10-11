# Conditions

Conditions describe effects that change a creature's actions, defenses, or capabilities.

---

## Grapple Conditions

### Grappled
The initial capture state. Both the initiator and the target are locked in close-quarters wrestling.
* **Movement Limit:** Base movement speed is reduced to 0 feet.
* **Defensive Tax:** The target cannot execute Attacks of Opportunity. They lose their Dexterity AC and Dodge AC components against all external threats, but fully retain them against the initiator. See [Armor Class Components](armor-class.md).
* **Offensive Lock:** The target can still execute standard attacks and Full Attack routines, but is restricted strictly to Unarmed Strikes, Natural Weapons, or Light Melee Weapons. 

### Pinned
The initiator has successfully leveraged their mass to pin the target's primary limbs. **This is the active baseline state for any creature trapped inside a stomach cavity via Swallow Whole.**
* **Movement Limit:** Base movement speed remains 0 feet. 
* **Defensive Tax:** The target loses their Dexterity AC and Dodge AC components against *all* attackers, completely exposing their **Flat-Footed AC**. They suffer an additional flat **-4 penalty to their static AC** against external attackers.
* **Offensive Lock:** The target cannot execute Full Attacks or iterative flurries. They are limited strictly to a **Single Melee Attack per round** using a Light Piercing or Slashing weapon, executed at a flat **-4 circumstance penalty** due to severe constriction.

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
* **Melee Tax:** The character suffers a flat **-4 penalty on all melee attack rolls**. 
* **Defensive Matrix:** The character suffers a flat **-4 penalty to AC against melee attacks**, but gains a **+4 bonus to AC against ranged attacks** due to a minimized physical silhouette.

### Entangled
The character is ensnared by vines, nets, sticky resins, or localized magical bonds.
* **Movement Limit:** The character moves at half speed and cannot execute a Charge action.
* **Accuracy Tax:** The character suffers a flat **-2 penalty on all attack rolls**.
* **Defensive Tax:** The character suffers a flat **-4 penalty to their effective Dexterity score**, reducing their AC and Reflex saves by 2.
* **Casting Gate:** Casting any spell requires a Concentration Check ($DC = 15 + \text{Spell Level}$). On a failure, the spell fails and its casting resource is expended.

### Fatigued
The character is physically exhausted from overexertion or environmental hazards.
* **Action Lock:** The character cannot execute a Run or Charge action.
* **Attribute Tax:** The character suffers a flat **-2 penalty to Strength and Dexterity**.
* **Escalation Flag:** If a fatigued character is subjected to another effect that causes fatigue, they instantly escalate to the **Exhausted** condition.

### Exhausted
The character is completely physically spent.
* **Movement Limit:** The character can only move at half speed. They cannot Run or Charge.
* **Attribute Tax:** The character suffers a severe **-6 penalty to Strength and Dexterity**.

---

## Action-Inhibiting and Cognitive Conditions

### Berserk
The creature has lost control to a violent compulsion.
* **Action Compulsion:** On each of its turns, the creature must move toward and attack the nearest creature, regardless of whether that creature is friend or foe. It uses the shortest available route and makes an attack if it can reach a target; if it cannot, it continues moving toward the nearest creature.
* **Control Loss:** The creature cannot choose a different target or take a different action while Berserk.
* **Duration:** The effect that caused Berserk determines when it ends.

### Nauseated
The character is experiencing severe physical trauma, stomach sickness, or chemical distress. **This status condition instantly overrides and forces a predator to regurgitate any swallowed targets.**
* **Action Lock:** The character is heavily incapacitated. They **cannot attack, cast spells, concentrate, or execute standard actions** of any kind.
* **Action Allocation:** The character is restricted strictly to a **Single Move Action per turn** (allowing them to retreat or reposition).

### Sickened
A minor threshold variant of nausea. The character is physically unwell but functional.
* **Universal Tax:** The character suffers a flat **-2 penalty on all attack rolls, weapon damage rolls, saving throws, skill checks, and ability checks**.

### Shaken
The character is unnerved by fear or intimidation.
* **Fear Tax:** The character suffers a **-2 penalty on attack rolls, saving throws, and skill checks**.
* **Repeated Effects:** Multiple Shaken effects do not stack. Apply the longest remaining duration.

### Staggered
The character is heavily dazed, critically wounded, or mechanically slowed.
* **Action Allocation:** The character can only execute **either a single Standard Action OR a single Move Action per turn**, plus Free Actions and Reactions. They cannot perform Full-Round Actions or Full Attacks.

### Stunned
The character has sustained massive neural or physical shock.
* **Action Lock:** The character drops everything held in their hands, falls prone if airborne, and **cannot execute any actions or take Reactions** whatsoever.
* **Defensive Tax:** The character loses their Dexterity AC and Dodge AC components (exposing their Flat-Footed AC) and drops their guard, granting all attackers a flat **-2 penalty to the character's static AC**.

### Paralyzed
The character’s muscles are entirely locked by magic, toxin, or structural nerve failure.
* **Action Lock:** The character is frozen in place and **cannot move or execute any physical actions** whatsoever. They are locked into a sub-state of the [Helpless](#helpless) condition.
* **Cognitive Freedom:** The character retains full mental awareness. They can execute purely mental actions (such as psychic triggers or purely verbal/thought-based spellcasting) if the game engine allows.
* **Defensive Failure:** The character's Dexterity score drops to 0 (-5 AC modifier).

### Dazed
The character is momentarily disoriented.
* **Action Lock:** The character **cannot execute any actions** but retains their full visual awareness and standard defense parameters. They do not lose their Dexterity bonus to AC and do not provoke attacks of opportunity.

---

## Sensory Conditions

### Blinded
The character cannot see their surroundings due to darkness, magical curses, or ocular trauma.
* **Movement Limit:** The character moves at half speed. They suffer a flat -4 penalty on most Strength and Dexterity-based skill checks.
* **Accuracy Tax:** All opponents gain **Total Concealment (50% miss chance)** against the blinded character's attack rolls. The blinded character automatically fails all visual Perception checks.
* **Defensive Tax:** The character loses their Dexterity and Dodge bonuses to AC. Furthermore, external attackers gain a flat **+2 bonus on attack rolls** executed against the blinded target.

### Deafened
The character cannot perceive acoustic frequencies.
* **Tactical Tax:** The character automatically fails all sound-based Perception checks and suffers a flat -4 penalty on Initiative checks.
* **Casting Gate:** Any spell cast that includes a verbal component faces a flat **20% spell failure chance**, rolled on a d100 at the moment of execution.
