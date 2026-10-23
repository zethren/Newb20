# Mounted Combat

These rules govern mounting, mounted penalties, Ride checks, and the effects of failing a check.

---

## Mounting and Space

To establish a legal Rider-Mount unit on the tactical map coordinate grid, two baseline physical constraints must be satisfied:
*   **The Size Delta:** The Mount must be **at least one size category larger** than the Rider (e.g., a Medium Human can ride a Large Wolf; a Medium Elf can ride a Huge Bear).
    * Therefore, a Small Rider can ride any Medium or larger Mount.
*   **The Footprint Fusion:** Upon mounting, the Rider’s individual token is merged entirely into the Mount's coordinate block. Spatial tracking, line of sight, and battlefield movement are resolved exclusively via the Mount's physical footprint. The Mount moves the Rider completely for free using its native action economy and land speeds.

---

## Mounted Penalties

Any character actively riding a creature is subjected to a constant state of kinetic turbulence. These penalties apply globally unless explicitly neutralized via advanced feats or specialized gear.

### Attack and AC Penalties
*   **Standard Mounted Penalty:** The Rider suffers a flat **-2 penalty to all Melee/Ranged Attack Rolls (AB)** and a **-2 penalty to Armor Class (AC)** due to unstable footing.
*   **The Bestial Turbulence Multiplier:** If the creature being ridden is a wild predator, untamed monster, or shape-shifted ally form (such as a **Wolf** or **Bear**), the kinetic disruption is doubled. The Rider instead suffers a severe **-4 penalty to AB** and a **-4 penalty to AC**.

### Spellcasting
*   **Concentration Check:** Executing any spell possessing Somatic or Verbal components while mounted requires an immediate, mandatory **Concentration Check (DC = 15 + Spell Level)** due to the constant jarring motion of the steed. If this check is failed, the spell fails and its casting resource is expended.

---

## Ride Checks to Stay Mounted

A Rider must immediately execute a **Ride Skill Check** to maintain their seat and avoid being violently unseated whenever any of the following high-exertion triggers occur:

### The Mount Attacks
Every time the Mount executes a single attack roll or a full cascading iterative routine, the sheer violence of their muscle contraction threatens to throw the Rider.
*   **The Scaling Formula:** `Ride DC = the mount's highest total attack roll result for that turn`

### The Mount Takes Damage
When the Mount takes a heavy blow, they stumble, rear back, or buckle under the impact force.
*   **The Scaling Formula:** `Ride DC = 10 + net Hit Point damage the mount sustains after Damage Reduction`
*   **The Multi-Hit Clause:** If the Mount is struck multiple times within a single turn cycle, the Rider must roll a separate, independent Ride check against each unique damage entry that successfully pierces the Mount's Damage Reduction or Hardness.

### The Mount Is Restrained or Displaced
If the Mount suffers absolute physical displacement, the stability thresholds lock at severe baseline formulas:
*   **The Mount enters a Grappled or Pinned Gate:** `Ride DC = 15 + the mount's Strength modifier`
*   **The Mount is knocked Prone or Overrun:** `Ride DC = 20 + the mount's Strength modifier`

---

## Failing a Ride Check

If a Rider fails any scaling Ride Check listed above, the engine evaluates their equipped gear slot profile to determine the physical outcome of the whiplash:

### Standard Saddle
The Rider is cleanly ejected from the saddle:
*   **The Crash Vector:** The Rider is thrown into a chosen adjacent 5-foot grid square, sustains `1d6` blunt falling damage, and instantly inherits the **Prone** status condition. Ground-based enemies adjacent to their landing square receive an immediate Attack of Opportunity against the fallen Rider.

### Locking Harness
The Rider is strapped into a heavy, reinforced framework of iron brackets and leather braces that physically prevents ejection.
*   **The Mechanical Safety:** The Rider **cannot be unseated or knocked off** via standard attack or damage stability checks. They remain locked onto the Mount's back.
*   **Whiplash Effect:** Because their body is rigidly fused to a thrashing apex predator, their joints take the full structural trauma of the impact. The moment a Ride Check is failed, the Rider completely avoids falling off, but **instantly inherits the Staggered status condition until the start of their next turn** as they catch their breath from severe kinetic whiplash.
*   **The Emergency Trap:** If the Mount is knocked **Prone** or dies while a Rider is locked into a securing harness, the Rider cannot escape. They are automatically pinned underneath the carcass, take double blunt damage (`2d6`), and require a Full-Round Action from themselves or an ally to cut the straps free.

---

## Related Feats

#### Mounted Combat (Combat Feat)
See the standalone [Mounted Combat feat](../feats/mounted-combat.md).

#### Cavalry Synchronization (Combat Feat)
See the standalone [Cavalry Synchronization feat](../feats/cavalry-synchronization.md).

#### Savage Cavalry / Predator Link (Advanced Animal Feat)
See the standalone [Savage Cavalry feat](../feats/savage-cavalry.md).

### Mounted Reflexes (Combat Feat)
See the standalone [Mounted Reflexes feat](../feats/mounted-reflexes.md).

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

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="../index.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="../game-mechanics.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Mechanics</a>
<a href="../feats/mounted-combat.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Mounted Combat</a>
<a href="../feats/cavalry-synchronization.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Cavalry Synchronization</a>
<a href="../feats/savage-cavalry.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Savage Cavalry</a>
<a href="../feats/mounted-reflexes.html" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Mounted Reflexes</a>
</nav>
