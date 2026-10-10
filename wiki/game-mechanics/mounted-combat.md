# System Specification: Unified Mounted Combat & Player Mount Engine

This document outlines the operational rules, action economy constraints, defensive redirection arrays, and target restriction matrices applied when a character mounts a willing ally, domesticated steed, or advanced predatory form on the tactical map grid.

---

## 1. Core Mount Prerequisites & Footprint Fusion

To establish a legal Rider-Mount unit on the tactical map coordinate grid, two baseline physical constraints must be satisfied:
*   **The Size Delta:** The Mount must be **at least one size category larger** than the Rider (e.g., a Medium Human can ride a Large Wolf; a Medium Elf can ride a Huge Bear).
    * Therefore, a Small Rider can ride any Medium or larger Mount.
*   **The Footprint Fusion:** Upon mounting, the Rider’s individual token is merged entirely into the Mount's coordinate block. Spatial tracking, line of sight, and battlefield movement are resolved exclusively via the Mount's physical footprint. The Mount moves the Rider completely for free using its native action economy and land speeds.

---

## 2. Universal Mounted Penalties & Actions Taxes (The Defenses & Accuracy Maluses)

Any character actively riding a creature is subjected to a constant state of kinetic turbulence. These penalties apply globally unless explicitly neutralized via advanced feats or specialized gear.

### 2.1. Attribute & Combat Accuracy Maluses
*   **Standard Mounted Penalty:** The Rider suffers a flat **-2 penalty to all Melee/Ranged Attack Rolls (AB)** and a **-2 penalty to Armor Class (AC)** due to unstable footing.
*   **The Bestial Turbulence Multiplier:** If the creature being ridden is a wild predator, untamed monster, or shape-shifted ally form (such as a **Wolf** or **Bear**), the kinetic disruption is doubled. The Rider instead suffers a severe **-4 penalty to AB** and a **-4 penalty to AC**.

### 2.2. Spellcasting While Mounted
*   **The Concentration Tax:** Executing any spell possessing Somatic or Verbal components while mounted requires an immediate, mandatory **Concentration Check (DC = 15 + Spell Level)** due to the constant jarring motion of the steed. If this check is failed, the spell fails and its casting resource is expended.

---

## 3. Dynamic Scaling Stability Events (Getting Unseated)

A Rider must immediately execute a **Ride Skill Check** to maintain their seat and avoid being violently unseated whenever any of the following high-exertion triggers occur:

### Event A: The Mount Attacks (Recoil Stability)
Every time the Mount executes a single attack roll or a full cascading iterative routine, the sheer violence of their muscle contraction threatens to throw the Rider.
*   **The Scaling Formula:** \[\text{Ride DC} = \text{The Mount's Highest Total Attack Roll Result for that Turn}\]

### Event B: The Mount Sustains Damage (Impact Stability)
When the Mount takes a heavy blow, they stumble, rear back, or buckle under the impact force.
*   **The Scaling Formula:** \[\text{Ride DC} = 10 + \text{Net Hit Point Damage Sustained by the Mount (Post-DR)}\]
*   **The Multi-Hit Clause:** If the Mount is struck multiple times within a single turn cycle, the Rider must roll a separate, independent Ride check against each unique damage entry that successfully pierces the Mount's Damage Reduction or Hardness.

### Event C: Severe Structural Disruptions
If the Mount suffers absolute physical displacement, the stability thresholds lock at severe baseline formulas:
*   **The Mount enters a Grappled or Pinned Gate:** \[\text{Ride DC} = 15 + \text{Mount's Strength Modifier}\]
*   **The Mount is knocked Prone or Overrun:** \[\text{Ride DC} = 20 + \text{Mount's Strength Modifier}\]

---

## 4. Stability Failure States & Equipment Core Parameters

If a Rider fails any scaling Ride Check listed above, the engine evaluates their equipped gear slot profile to determine the physical outcome of the whiplash:

### Profile A: Standard Saddle / Un-Secured Riding
The Rider is cleanly ejected from the saddle:
*   **The Crash Vector:** The Rider is thrown into a chosen adjacent 5-foot grid square, sustains `1d6` blunt falling damage, and instantly inherits the **Prone** status condition. Ground-based enemies adjacent to their landing square receive an immediate Attack of Opportunity against the fallen Rider.

### Profile B: Locking Harness / Securing Saddle (The Gear Fix)
The Rider is strapped into a heavy, reinforced framework of iron brackets and leather braces that physically prevents ejection.
*   **The Mechanical Safety:** The Rider **cannot be unseated or knocked off** via standard attack or damage stability checks. They remain locked onto the Mount's back.
*   **The Whiplash Tax:** Because their body is rigidly fused to a thrashing apex predator, their joints take the full structural trauma of the impact. The moment a Ride Check is failed, the Rider completely avoids falling off, but **instantly inherits the Staggered status condition until the start of their next turn** as they catch their breath from severe kinetic whiplash.
*   **The Emergency Trap:** If the Mount is knocked **Prone** or dies while a Rider is locked into a securing harness, the Rider cannot escape. They are automatically pinned underneath the carcass, take double blunt crushing damage (`2d6`), and require a Full-Round Action from themselves or an ally to cut the straps free.

---

### 5. Advanced Mounted Combat Feats

#### Mounted Combat (Combat Feat)
Your intensive training allows you to perfectly stabilize your center of gravity and synchronize your weapons output with your steed's movements.
*   **Prerequisites:** Ride 1 rank or Base Attack Bonus **+1**.
*   **The Benefit:** You completely and permanently eliminate the standard **-2 AB / -2 AC mounted penalty** when riding domesticated or standard mounts.

#### Cavalry Synchronization (Combat Feat)
You possess a flawless baseline muscle memory that lets you effortlessly absorb the shock and recoil of your steed's offensive movements.
*   **Prerequisites:** *Mounted Combat* feat, Base Attack Bonus **+3**.
*   **The Benefit:** When your mount executes an attack roll or a full cascading iterative routine, the scaling Ride DC required to stay seated in the saddle is permanently reduced by a flat calculation equal to **your Base Attack Bonus (BAB) + your Dexterity Modifier**.

#### Savage Cavalry / Predator Link (Advanced Animal Feat)
You have trained extensively alongside apex predators, learning how to read the muscle shifts of a wild beast's spine to maintain your lethal edge mid-frenzy.
*   **Prerequisites:** *Mounted Combat* feat, Ride 5 ranks, Base Attack Bonus **+4**.
*   **The Benefit:** You have mastered the extreme turbulence of monstrous mounts. The severe **-4 beast-riding penalty is completely and permanently removed**, reducing your mounted accuracy and defensive tax down to 0.

### Mounted Reflexes (Combat Feat)
An advanced mounted defense technique, you use your lightning reflexes to yank your steed out of harm's way, actively intercepting a blow meant for your mount.
*   **Prerequisites:** Dexterity 13, *Mounted Combat*.
*   **Action Cost:** Reaction.
*   **The Mechanic:** Once per round, when your Mount is successfully hit by a physical melee or ranged attack, you execute a **Ride Skill Check**. If your rolled total meets or exceeds the enemy's final attack roll, you successfully manipulate your mount's footing, converting the strike into an **automatic miss**.

---

### 6. Defensive Redirection & Vertical Reach Exclusion Lockouts

#### 6.1. The Ride Redirection Shield (Base Ride Capability)
*   **The Rule:** Any character trained in the Ride skill can actively use their mount's massive frame as a physical shield to deflect incoming danger. Once per round, when the *Rider* is successfully hit by a physical melee or ranged attack, they can choose to execute an immediate **Ride Skill Check (DC = Enemy's Total Attack Roll Result)**.
*   **The Outcome:** On a success, the Rider drops cleanly to the opposite side of the saddle, completely pulling themselves out of the trajectory of the blow. The incoming strike is cleanly redirected to target the **Mount** instead.
*   **The Armor Class Check:** The enemy's original attack roll result is immediately compared directly against the **Mount's Armor Class (AC)**. If the attack roll fails to meet or exceed the Mount's AC, the weapon glances harmlessly off their thick hide, natural armor plates, or barding, dealing **0 damage** to the unit. Damage is only deducted from the Mount's health pool if the redirected roll successfully pierces the Mount's defensive threshold.

### 6.2. Size Scaling Cover Matrix
The Rider gains an elevated defensive threshold based strictly on the physical size mass of the creature they are riding:
*   **Riding a Mount 1 size category: larger** Rider gains a **+2 Circumstance bonus to AC** against ground threats.
*   **Riding a Mount 2 size cateogry larger:** Rider gains a **+4 Circumstance bonus to AC** against ground threats.
*   **Riding a Mount 3+ size cateogry larger:** Rider gains a **+8 Circumstance bonus to AC** against ground threats.

### 6.3. The Vertical Reach Exclusion Lock (The Distance Rule)
To preserve strict grid physics, ground-based attackers face absolute hard-coded spatial limits when trying to strike an elevated Rider:
*   **The Lockout Rule:** A smaller ground creature (e.g., Small or Medium) **cannot target an elevated Rider with a standard melee weapon attack** if the Rider is mounted on a **Huge or larger creature**. 
*   **The Exceptions:** The ground attacker can only attempt a melee strike against the Rider if they fulfill one of three conditions:
    1.  They utilize a weapon possessing the **Reach** property (e.g., a longspear, pike, or halberd).
    2.  They are targeting the *Mount* instead of the Rider.
    3.  The ground attacker themselves is of an equal or larger size category than the Mount.