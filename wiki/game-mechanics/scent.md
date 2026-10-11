# Core Game Mechanic: Scent System

## 1. Passive Detection Loop
Each creature's Scent trait specifies its range. Both passive detection and active tracking use that range.

* **Trigger Condition:** Any hidden, stealthing, or invisible entity enters within the Scent range of a creature possessing the trait.
* **UI Feedback:** The system immediately fires a localized user interface notification alert: *"You catch an unfamiliar scent..."*
* **Systemic State Modification:** The engine applies a target-specific **Uncanny Dodge** condition to the tracking creature. 
* **Mechanical Protection:** The tracking creature natively retains their full Dexterity bonus to Armor Class (AC) and **cannot be caught Flat-Footed** or subjected to precision/sneak attack modifiers by that specific unseen attacker, effectively breaking the ambush state.

## 2. Active Tracking Loop (Sniff)
* **Action Cost:** **Move Action**. A Primal Shifter with [Swift Tracker](../classes/base-classes/primal-shifter/abilities/swift-tracker.md) can instead use a **Free Action**.
* **Range Requirement:** The target must be within the creature's listed Scent range. The check is still required at point-blank / adjacent (5 feet); no automatic square flagging is permitted.
* **Resolution Check:** A contested **Survival Skill Check vs. Target's Survival Skill Check** (representing the target's active wilderness capability to mask their biological footprint via masking agents, wind angles, or water crossings).
* **Success State:** The engine flags the exact 5-foot map grid square that the hidden or invisible target occupies.

## 3. Baseline Concealment Tax
* **The Rule:** Pinpointing a target's grid square via a successful active Sniff check provides location data but does not grant visual clarity.
* **The Penalty:** All physical attack rolls targeting an invisible entity's verified square automatically inherit a flat **50% Total Concealment miss chance** until overridden by explicit feats or advanced capabilities.
