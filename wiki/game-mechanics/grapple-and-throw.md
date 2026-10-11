# Grapple, Thrash, and Throw

This document outlines the unified, size-based grapple, thrash, and throwing mechanics designed for a pure-martial shifting Druid class/archetype and global game engine integration.

---

## 1. The Unified Grapple Engine (Size-Based Dominance)

When an initiator succeeds on a grapple check, the maintenance requirements and active status effects are governed completely by the **Global Size Differential**. Once a hold is successfully established, it persists automatically until the victim uses their own turn to break it. The **All-In Thrash** pathway is the sole exception: its follow-up MAB check is a risk gate specific to that multi-attack action.

### Size Comparison Matrix

| Size Comparison | Initiator Status | Victim Status | Initiator Movement | Initiator Subsequent Action Options |
| :--- | :--- | :--- | :--- | :--- |
| **Victim is Equal or Larger** | **Grappled**<br>*(Reduced AC, Immobilized)* | **Grappled**<br>*(Reduced AC, Immobilized)* | **0 ft.**<br>*(Immobilized)* | Must spend a standard action to advance or upgrade the hold (Pin, Toss, etc.). |
| **Initiator is 1 Size Larger** | **Unhindered**<br>*(Full AC, Fully Mobile)* | **Grappled**<br>*(Reduced AC, Immobilized)* | **1/2 Base Speed**<br>*(Can drag victim along)* | Full Action Economy. Can utilize standard / iterative attacks or specialized maneuvers. |
| **Initiator is 2+ Sizes Larger**| **Unhindered**<br>*(Full AC, Fully Mobile)* | **[Restrained](conditions.md#restrained)**<br>*(Severe AC Penalty, [Helpless](conditions.md#helpless))*| **Full Base Speed**<br>*(Can carry victim freely)* | Full Action Economy. Can treat victim entirely as an improvised projectile or object. |

### The Turn Rules

*   **The Initiator's Turn:** If the initiator has a size advantage, they do not need to spend an action to maintain the hold. They possess their entire action economy to move, attack the victim, strike secondary nearby targets, or spend an action to advance the hold into a Pin or Toss. Primary weapons are locked unless the initiator possesses the specific **Snag** feature.
*   **The Victim's Turn:** The victim must spend a Standard Action to attempt an Escape roll (MAB or Escape Artist vs. Initiator's static MAD). If they fail or choose not to escape, any counter-attacks they attempt suffer heavy system penalties due to being grappled/restrained.

---

## 2. Post-Snatch Combat Pathways

Once a target is secured in a grapple, an unhindered initiator can resolve their combat turn via two distinct mechanical pathways.

### Pathway A: The All-In Thrash (The Multi-Attack Gambler)
*   **Action Cost:** Full Attack Action.
*   **The Roll:** Multiple iterative attack rolls against the target's lowered AC using claws, paws, or secondary natural weapons. (The primary grabbing limb cannot target anyone else).
*   **The Risk/Reward Gate:**
    1.  The initiator must hit with **at least one** attack in the routine to deal damage.
    2.  If at least one attack hits, the initiator **MUST roll an MAB vs. MAD check** to maintain the grapple.
    3.  If all attacks in the routine miss, OR if the follow-up MAB check fails, the hold breaks instantly and the victim slips free into an adjacent square.

### Pathway B: The Secured Crush (The Reliable MAB Attack)
*   **Action Cost:** Standard Action.
*   **The Roll:** A single **MAB vs. MAD** roll to crush, slam, or squeeze the target.
*   **The Resolution:** If the MAB check is successful, it is an **automatic hit**. The target takes baseline natural weapon damage plus size/strength scaling, and the hold is securely maintained without any further rolls.

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
| **Small** | $1\text{d}8 + \text{Str}$ |
| **Medium** | $2\text{d}6 + \text{Str}$ |
| **Large** | $3\text{d}6 + \text{Str}$ |
