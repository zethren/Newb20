# Grapple, Thrash, and Throw

These rules govern grappling, thrashing, and throwing creatures. Apply the shared [Combat Scaling](combat-scaling.md) rules when a maneuver or attack depends on Size.

---

## 1. The Unified Grapple Engine (Size-Based Dominance)

When an initiator succeeds on a grapple check, the maintenance requirements and active status effects are governed completely by the **Global Size Differential**. Once a hold is successfully established, it persists automatically until the victim uses their own turn to break it. Holds started by Snatch follow the stages in [Snatch](../classes/base-classes/primal-shifter/abilities/snatch.md) instead.

### Size Comparison Matrix

| Size Comparison | Initiator Status | Victim Status | Initiator Movement | Initiator Subsequent Action Options |
| :--- | :--- | :--- | :--- | :--- |
| **Victim is Equal or Larger** | **Grappled**<br>*(Reduced AC, Immobilized)* | **Grappled**<br>*(Reduced AC, Immobilized)* | **0 ft.**<br>*(Immobilized)* | Must spend a standard action to advance or upgrade the hold (Pin, Toss, etc.). |
| **Initiator is 1 Size Larger** | **Unhindered**<br>*(Full AC, Fully Mobile)* | **Grappled**<br>*(Reduced AC, Immobilized)* | **1/2 Base Speed**<br>*(Can drag victim along)* | Full Action Economy. Can utilize standard / iterative attacks or specialized maneuvers. |
| **Initiator is 2+ Sizes Larger**| **Unhindered**<br>*(Full AC, Fully Mobile)* | **[Pinned](conditions.md#pinned)**<br>*(Flat-Footed AC, -4 AC, No Attacks or Somatic Spells)*| **Full Base Speed**<br>*(Can carry victim freely)* | Full Action Economy. Can treat victim entirely as an improvised projectile or object. |

### The Turn Rules

*   **The Initiator's Turn:** If the initiator has a size advantage, they do not need to spend an action to maintain the hold. They possess their entire action economy to move, attack the victim, strike secondary nearby targets, or spend an action to advance the hold into a Pin or Toss. Primary weapons are locked unless the initiator possesses the specific **Snag** feature.
*   **The Victim's Turn:** The victim must spend a Standard Action to attempt an Escape roll (MAB or Escape Artist vs. Initiator's static MAD). If they fail or choose not to escape, a pinned victim cannot counter-attack, and a grappled victim is limited to unarmed strikes, natural weapons, or light melee weapons.

---

## 2. Snatch Holds

Holds started by Snatch use the three-stage sequence in [Snatch](../classes/base-classes/primal-shifter/abilities/snatch.md). In that sequence, Thrash is a move action that automatically applies damage and does not require a maintenance check.

---

## 3. The Toss / Throw System (Living Projectiles)

An initiator can use a standard action to hurl a grabbed creature as an improvised ranged weapon, processing the action through a strict dual-gated system.

### Step 1: The Lift Gate (MAB vs. Victim's MAD)
The initiator attempts to launch the grabbed entity. 
*   **Failure:** The throw fails. The action is spent, and the victim remains held.
*   **Success:** The victim is successfully launched. The game opens a targeting reticle up to the maximum calculated range.

### Step 2: Distance Scaling
A successful lift allows the initiator to choose a landing point anywhere from 0 feet to the maximum range for the size comparison:

| Initiator's Size Compared to Victim | Maximum Range |
| :--- | :--- |
| Victim is larger | **10 ft.** |
| Equal size | **10 ft.** |
| Initiator is 1 size larger | **20 ft.** |
| Initiator is 2 or more sizes larger | **40 ft.** |

### Step 3: The Aim Gate (Ranged Attack vs. Secondary Target AC)
Once the creature is airborne, the initiator rolls a Ranged Attack roll against the secondary target's AC, suffering a **-4 Improvised Weapon penalty**.

*   **If the Ranged Attack HITS:**
    *   **The Flying Victim:** Takes base blunt damage (scaled to their own size tier) + initiator's Strength modifier, and is knocked **Prone**.
    *   **The Secondary Target:** Takes the exact same damage as the victim and must pass a system physical save or be knocked **Prone**.
*   **If the Ranged Attack MISSES:**
    *   **The Secondary Target:** Ducks safely, taking 0 damage and remaining unaffected.
    *   **The Flying Victim:** Still travels to the target location, smashes into the environment, takes full base blunt damage anyway, and lands **Prone**.

### Living Weapon Damage Matrix
Tossed creatures scale as heavy, blunt improvised weapons:

| Victim Size Category | Base Blunt Projectile Damage |
| :--- | :--- |
| **Small** | `1d8 + Strength modifier` |
| **Medium** | `2d6 + Strength modifier` |
| **Large** | `3d6 + Strength modifier` |

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="../index.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="../game-mechanics.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Mechanics</a>
<a href="combat-scaling.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Combat Scaling</a>
<a href="conditions.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Conditions</a>
<a href="flight.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Flight Rules</a>
<a href="health.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Health, Dying, and Recovery</a>
</nav>
