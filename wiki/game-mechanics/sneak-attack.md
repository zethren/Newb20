# System Specification: Global Limitation on Precision and Sneak Attack (Revised)

To preserve a distinct mechanical boundary between combat-focused martial classes and utility-focused skill classes, the execution of precision damage is split into independent Damage and Status tracking loops.

## 1. Universal Primary Weapon Restriction (Raw Damage)
*   **The Damage Law:** Sneak Attack damage dice can **only be evaluated and added to attack rolls executed using a character's designated Primary Weapon slot.**
*   **Secondary Slot Suppression:** Any attack rolls executed using an Off-Hand weapon slot, a secondary natural weapon slot, or an automated bonus strike trigger (such as the *Rend* feat) **deal 0 bonus precision damage dice**. These strikes resolve utilizing baseline weapon dice and static attributes only.

## 2. Universal Off-Hand Retention (Utility & Debuff Triggers)
*   **The Exception Clause:** While secondary and off-hand strikes are completely stripped of raw precision damage dice, they **fully retain the ability to check for Sneak Attack positioning conditions (Flanked / Flat-Footed) to deliver conditional class talents.**
*   **The Status Loop:** If an off-hand or secondary natural weapon strike successfully hits an eligible target, it triggers all associated riders, modifications, and debilitations exactly as if precision damage had landed. This includes, but is not limited to:
    *   *Crippling Strike:* Inflicts attribute damage (e.g., -2 Strength).
    *   *Bleeding Attack:* Inflicts ongoing bleed damage tracking conditions.
    *   *Sickening Sneak:* Inflicts the system's **Sickened** status condition.

## 3. Systemic Operational Summary
This split framework transforms the tactical execution of multi-attack archetypes across your engine:
1.  **The Rogue (The Utility Saboteur):** A dual-wielding Rogue’s off-hand strikes no longer generate broken, encounter-trivializing damage spikes. Instead, they act as highly targeted delivery vectors for debilitating status conditions, maintaining the Rogue's identity as a high-utility combat tactician.
2.  **The Feline Shifter (The Apex Burst Predator):** Natively capitalizes on their high-BAB track to land maximum raw damage triggers on their primary weapon chain, while their secondary natural attacks focus on critical-hit generation and physical tearing mechanics.
