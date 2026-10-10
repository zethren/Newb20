# Product Specification: Standalone Animal Feats Pool

This document catalogs the selectable character combat feats optimized for wild, predatory, and natural-weapon-focused martial classes. 

---

## 1. Multi-Attack (Combat)
Your mastery of natural weaponry allows you to coordinate rapid, multi-limbed strikes with minimal loss of accuracy.

*   **Prerequisites:** Three or more natural attacks (granted natively by any Shifter form profile or dual-wielding framework).
*   **Mechanic:** When executing a Full Attack routine using both primary and secondary natural weapons, the global penalty applied to all of your **Secondary Natural Attacks is permanently reduced from -5 to -2**.
*   **Systemic Interaction:** Directly modifies the cascading iterative weapon chain by boosting the accuracy tracking of off-hand weapon slots 1 and 2 by +3.

---

## 2. Swallow Whole (Combat) [Revised PnP Pacing]
You can gulp down completely restrained, significantly smaller foes, trapping them inside your digestive tract to remove them from active grid coordination.

*   **Prerequisites:** *Snatch* or *Improved Grapple* class feature/feat.
*   **Target Constraint:** Target must be **at least two size categories smaller** than the initiator (e.g., a Medium human for a Huge predator, or a Small halfling for a Large predator).
*   **Action Cost:** Free Action triggered exclusively at the *start* of the initiator's turn.
*   **Trigger Condition:** The initiator must begin their turn already holding an eligible target in a persistent grapple or snatch state.

### Internal Resolution & Action Loop
*   **Stomach Containment:** The victim is given the system's standard **Pinned** status condition and removed from the active map grid. Pinned governs the victim's actions inside the stomach; the separate Restrained condition does not apply.
*   **Immunity Flag:** The predator's internal stomach cavity is completely **Immune to Sneak Attacks** and precision damage.
*   **Automated Ticking Damage:** At the start of the *victim's* turn, they **automatically sustain severe environmental trauma every single round regardless of their actions**. This damage scales dynamically based on the initiator's Strength and the Initiator's Character Level/CR:
    *   *Crushing Damage:* `1d6 + (1.5 × Initiator's Strength Modifier)` Bludgeoning damage.
    *   *Acid Damage:* `1d6` Acid damage per **4 Levels/CR of the Initiator** (Minimum 1d6).

### The Prey's Standard Action Choices
On the victim's turn, after taking the automated ticking damage, they must spend their standard action to execute one of two escape pathways:

#### Path A: The Mechanical Escape Roll (MAB / Escape Artist)
The victim attempts to physically fight against the peristaltic muscle walls and crawl back up the predator's throat.
*   **The Check:** The victim rolls an **Escape Artist Skill Check OR a Martial Ability Check (MAB)** vs. the Predator's static **Grapple MAD**.
*   **On a Success:** The victim successfully breaks the hold. The engine instantly removes the `Swallowed` status and places the victim into a chosen adjacent 5-foot grid square outside the predator's body, landing **Prone**.

#### Path B: Physical Retaliation (Attacking the Stomach)
The victim attempts to cut or claw their way to freedom by killing the predator from the inside out. Per the system constraints for the **Pinned** condition, their offensive loop is heavily restricted:
1.  *Action Lock:* They are restricted strictly to a **Single Melee Attack per round**. They cannot use Full Attacks or multi-weapon flurries.
2.  *Weapon Lock:* They can only use **Light Piercing or Slashing weapons** (e.g., daggers, shortswords, natural claws).
3.  *The Accuracy Tax:* They suffer a flat **-4 penalty to the attack roll** due to severe physical constriction.
4.  *Target Defense AC:* Attacks target the predator's **Flat-Footed AC**. The Shifter loses their Dexterity AC and Dodge AC components, but **fully retains their Natural Armor, Shield/Deflection AC, and standard Armor AC**. See [Armor Class Components](../game-mechanics/armor-class.md).

---

### Stomach Volume Capacity

Creature capacity and victim mass scale by size. See the [Stomach Volume Containment Matrix](../game-mechanics/combat-scaling.md#swallow-whole-capacity) for the shared size table (Medium victim mass = 1.0 unit).

### The Ingestion Flash & The "Fed" Condition Output
* **Immediate Buff Acquisition:** The moment an organic, biological creature is successfully ingested via the Swallow Whole action, the predator instantly acquires the **Fed** status condition flag. This completely waives the ration cost of their next upcoming rest.

### The Corpses & 1-Hour Digestion Rule
* **The Mass Retention Lock:** When a swallowed creature's health pool drops to 0 or below, they expire normally. However, their physical body continues to occupy its full designated Mass Weight inside the stomach cavity, reducing the remaining capacity buffer.
* **Digestion State Clearance:** Exactly 1 hour after the initial timestamp of ingestion, a creature is considered fully digested, instantly purging the creature's organic mass from the predator's volume tracking array.
* **The Short Rest Time Jump (+1 Hour):** Because a standard **Short Rest executes exactly 1 hour of in-game time advancement**, taking a Short Rest automatically satisfies and concludes the 1-hour digestion window. Any active digestion timers are natively processed and cleared upon completing the rest.
* **The Regurgitation Override:** To clear stomach volume mid-combat or before the 1-hour digestion cycle naturally concludes, the predator can spend a **Full-Round Action** to vomit up any dead, unconscious, or living targets into an adjacent grid square, where they land **Prone**. This consumes the character's Standard and Move Actions; their Free Action remains available.

### The Post-Combat Humanoid Gating Rule
* **The Restriction:** Standard, non-monstrous humanoids (such as normal player humanoids or specialized monks utilizing external size alteration feats) do not possess the throat or gut anatomy to maintain living or dead contents inside their abdomen outside of high-adrenaline combat panic.
* **The Enforcement:** The moment turn-based combat officially concludes and the encounter ends, **any creature (living or dead) currently held within a Non-Monstrous Humanoid's stomach matrix is automatically and instantly regurgitated** into an adjacent square, landing **Prone**. True monstrous/beast forms (like the Wolf and Bear) are exempt from this restriction and can digest targets normally over the 1-hour window.

### Non-Digestible Equipment & Loot Retention
* **The Melting Law:** While muscle tissue, skin, and leather are completely liquefied during the 1-hour digestion cycle, **Metals, Gemstones, Glass, and Enchanted Magical Materials are 100% immune to biological stomach acids.** 
* **Gastric Encumbrance Tax:** Once a victim is fully digested and their organic mass is cleared, their heavy equipment remains inside the predator's gut as a loose pool of metal plates and gold.
* **Extracting the Loot:** The Shifter can choose to empty the non-digestible gear from their stomach at any time outside of combat (or via a Full-Round Action in combat) by actively purging their stomach. A steaming pile of loose gold coins, weapons, and armor plates is deposited into an adjacent grid square, completely freeing the volume capacity back to zero. If the predator dies in battle, the party can spend 10 minutes field-dressing the carcass to perfectly recover all items.

---

## 4. Gore Squeeze (Combat)
You use raw, suffocating kinetic pressure to crush the life out of a target while systematically warping and buckle their equipped armor plating.

*   **Prerequisites:** Large size category or larger, *Snatch* or *Snag* capability.
*   **Action Cost:** Standard Action.
*   **Target Gate:** The initiator must currently have a target secured in a persistent grapple or snatch state.
*   **Resolution Check:** The initiator rolls an offensive **MAB vs. the Target's MAD**.

### Execution & Resolution Loop
On a successful check, the engine resolves two events simultaneously:
1.  **The Victim's Health:** The victim automatically takes standard natural weapon squeeze damage (per the safe path grapple rules).
2.  **The Item's Integrity:** The automatic squeeze damage is also applied directly to the opponent's equipped armor or held weapon. The item subtracts its flat **Hardness** rating from the damage, and the leftover value is deducted directly from the item's structural Hit Points. 
3.  **The Magic Override:** If the targeted item is magical, the damage can reduce it down to a minimum floor of 1 HP (triggering the *Broken* condition rules), but the item will never drop to 0 HP or be permanently vaporized.

---

## 5. Rend (Combat)
Your claws latch onto the target's flesh from opposite directions and violently pull outward, tearing their muscular structure apart.

*   **Prerequisites:** Two or more Claw natural attacks, Base Attack Bonus **+4**.
*   **Type:** Passive Combat Trigger.
*   **Action Cost:** None (Triggers automatically as part of a Full Attack or Pounce action).
*   **The Trigger:** The character must successfully land at least **two claw attacks** against the exact same target creature within a single turn.

### Damage Resolution Math
*   **Automated Bonus Damage:** The moment the second claw attack confirms a successful hit on the target, they instantly take bonus tearing damage calculated as:
    \[\text{Rend Damage} = \text{Base Claw Damage Dice} + \left( 1.5 \times \text{Your Strength Modifier} \right)\]
*   **Operational Limitation:** You can only inflict Rend damage **once per turn against any individual target**. It triggers on the second successful hit and cannot fire again on subsequent claw hits that round.

---

## 6. Primal Awareness (Combat)
Your primal instincts allow you to translate scent data and microscopic acoustic cues into a perfect physical map, rendering physical invisibility completely useless once a target has been located.

*   **Prerequisites:** Scent class feature, Blind-Fight.
*   **Engine Code Override Flag:** `Scent_Pierces_Invisibility = True`

### Technical Outputs
*   **Miss Chance Overrides:** Once an unseen target's exact location is flagged by the engine through a successful Sniff check, a creature with this feat **completely ignores the 50% total concealment miss chance**. Melee natural weapons strike the target as if they were fully visible.
*   **Defensive Stasis:** You natively retain your dynamic Uncanny Dodge protection against melee attacks executed by that target, ensuring your defense never drops within your active Scent tracking field.

---

## 7. Blood Frenzy (Combat)
The metallic aroma of deep trauma triggers a primal surge, sharpening your accuracy against wounded prey.

*   **Prerequisites:** Scent class feature, Base Attack Bonus **+4**.
*   **Trigger Condition:** The target must be beneath **50% of their maximum health** and actively **detectable by your scent radius**.
*   **The Modifier:** You gain a flat **+2 Circumstance bonus to all Attack Rolls (AB) and Martial Ability Bonus (MAB) checks** executed against that specific target.

---

## 8. Giant Killer (Combat)
You use your low center of gravity and high speed to slide under the guard of massive foes, striking at their vulnerabilities and deforming their footing.

*   **Prerequisites:** Base Attack Bonus **+1**.
*   **Trigger Condition:** The target must be at least **one size category larger** than you (e.g., a Medium shifter striking a Large orc, or a Large wolf striking a Huge giant).
*   **The Modifier:** You gain a flat **+2 Circumstance bonus to all Attack Rolls (AB) and Martial Ability Bonus (MAB) checks** executed against that larger target.

---

## 9. Apex Predator (Combat)
You leverage your superior physical mass to overwhelm smaller threats, pinning them down and breaking through their desperate attempts to evade you.

*   **Prerequisites:** Base Attack Bonus **+1**.
*   **Trigger Condition:** The target must be at least **one size category smaller** than you (e.g., a Huge bear striking a Medium human, or a Large wolf striking a Small halfling).
*   **The Modifier:** You gain a flat **+2 Circumstance bonus to all Attack Rolls (AB) and Martial Ability Bonus (MAB) checks** executed against that smaller target.

---

## 10. Trample (Combat)
You leverage your superior physical mass and momentum to plow straight through lines of smaller enemies on the battlefield, crushing them underfoot and leaving them flattened in your wake.

*   **Prerequisites:** Base Attack Bonus **+4**.
*   **Action Cost:** Full-Round Action.
*   **Movement Constraint:** As part of this action, you move up to your full maximum land speed. You are permitted to move directly through the map grid squares of any enemy creatures.
*   **Opportunity Tax:** This trampling movement does not provoke standard Attacks of Opportunity from the targets you are actively running over.

### Resolution Loop (Ability vs. Defense)
The moment your physical avatar enters a grid square occupied by an eligible smaller target, the movement momentarily pauses to resolve the collision:
*   **The Roll:** You execute a single **Martial Ability Check** utilizing your **Martial Ability Bonus (MAB)** score (`d20 + MAB`).
*   **The Defenses:** The target evaluates your roll against their static **Martial Ability Defense (MAD)** score.

### Execution States
*   **Success State (Plowed Over):** If your Martial Ability roll meets or exceeds the target's Martial Ability Defense (MAD), the target automatically takes crushing blunt damage equal to your **Main Hand natural weapon damage code + 1.5 × your Strength modifier**. The target instantly inherits the **Prone** status condition, and your character continues their remaining movement path seamlessly into the next square.
*   **Failure State (The Wall):** If your Martial Ability roll falls below the target's Martial Ability Defense (MAD), the target manages to brace or evade. They take **0 damage** and are not knocked prone. Your movement path is instantly terminated, and your character is locked into the grid square directly *adjacent* to the target who blocked you.
*   **Operational Limitations:** You can trample multiple different targets along your movement path, but you can only attempt to run over any **individual creature once per turn**. If your path is blocked by a creature of your same size category or larger, or by impassable terrain, your Trample action ends immediately in the adjacent square.

---

## 12. Leaping Pounce (Combat)
You use a high vertical leap to skyrocket completely over frontline blockades and difficult terrain, using your downward momentum to drop straight into an explosive attack loop.

*   **Prerequisites:** *Pounce* capability, Acrobatics 4 ranks, Base Attack Bonus **+4**.
*   **Action Cost:** Full-Round Action (Replaces your standard Charge maneuver).
*   **The Execution:** You execute a standard tactical Charge, but your path occurs entirely in the air via an Acrobatics check. You completely ignore all ground obstacles, difficult terrain, and hazards along your trajectory, allowing you to soar directly over the heads of intervening enemies.
*   **The Drop-In Combo:** To land successfully, your landing square must be directly adjacent to your targeted foe. Upon landing, you immediately unleash your full cascading iterative full-attack routine (per the *Pounce* rules) against that target.
