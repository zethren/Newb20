# System Specification: Constitution-Scaled Combat Stamina

## 1. The Dynamic Round Accumulator

To prevent mechanical fatigue from interfering with open-world exploration or social roleplay, physical stamina degradation is calculated exclusively from turn-based combat rounds.

### The Tracking Metrics
The engine tracks a persistent integer per character: `Combat_Rounds_Accumulated`.
* **The Active Windows:** This variable increments by +1 at the conclusion of every turn-based round of combat the character actively participates in.
* **The Rest Windows:** Outside of active combat turn cycles, the counter freezes entirely.

---

## 2. Constitution-Based Degradation Thresholds

The round thresholds required to trigger physical status conditions scale directly with a character's native **Constitution (CON) Score** at a rate of 2 rounds per point.

### Threshold 1: The Fatigue Boundary
The number of combat rounds a character can endure before suffering temporary muscles strain is calculated as:

\[\text{Rounds to Fatigue} = \text{Character's Constitution Score} \times 2\]

*   **The Trigger:** When `Combat_Rounds_Accumulated` reaches this value, the character instantly inherits the **Fatigued** status condition.
*   **The Reset:** Spending a **1-Hour Short Rest** (consuming 0.5 rations for a Medium creature, adjusted by the creature's [size-based ration factor](combat-scaling.md#size-dependent-utility), or the `Fed` flag) completely wipes away the Fatigued condition and resets `Combat_Rounds_Accumulated` back to exactly 0.

### Threshold 2: The Exhaustion Boundary
If the character continues to force themselves to fight through consecutive encounters without executing a Short Rest, their physical state hits a critical cellular ceiling at three times their fatigue limit:

\[\text{Rounds to Exhaustion} = \text{Rounds to Fatigue} \times 3\]

*   **The Trigger:** When `Combat_Rounds_Accumulated` reaches this hard ceiling, the condition automatically scales up to **Exhausted** (-6 Strength/Dexterity, base movement speed halved).
*   **The System Lockout:** Per the master conditions framework, a Short Rest provides **zero mechanical relief to an Exhausted target**. The round counter is locked at this stage. The character can only clear these severe penalties by setting up a full camp and executing a full **8-Hour Long Rest** (consuming 1.0 ration for a Medium creature, adjusted by the creature's [size-based ration factor](combat-scaling.md#size-dependent-utility), or the `Fed` flag), which resets the master counter back to 0.
