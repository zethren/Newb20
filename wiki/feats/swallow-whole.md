# Swallow Whole

**Type:** Combat Feat.

**Prerequisites:** Snatch class feature or Improved Grapple feat (not yet defined).

You can gulp down completely restrained, significantly smaller foes, trapping them inside your digestive tract to remove them from active grid coordination.

**Target Constraint:** The target must be at least two size categories smaller than you (for example, a Medium human for a Huge predator, or a Small halfling for a Large predator).

**Action:** Free Action, triggered exclusively at the start of your turn.

**Trigger:** You must begin your turn already holding an eligible target in a persistent grapple or snatch state.

## Internal Resolution and Action Loop

- **Stomach Containment:** The victim gains the system's standard Pinned status condition and is removed from the active map grid. Pinned governs the victim's actions inside the stomach; the separate Restrained condition does not apply.
- **Immunity:** Your internal stomach cavity is immune to Sneak Attacks and precision damage.
- **Automated Damage:** At the start of the victim's turn, they automatically sustain severe environmental trauma every round regardless of their actions. This damage scales based on your Strength and Character Level/CR:
  - **Crushing Damage:** `1d6 + (1.5 × your Strength modifier)` blunt damage.
  - **Acid Damage:** `1d6` acid damage per 4 of your Levels/CR (minimum 1d6).

## The Prey's Standard Action Choices

After taking the automated damage on their turn, the victim must spend their Standard Action to attempt one of these escape pathways.

### Mechanical Escape (MAB or Escape Artist)

The victim attempts to fight against the peristaltic muscle walls and crawl back up your throat.

- **Check:** The victim rolls an Escape Artist skill check or a Martial Ability Check (MAB) against your static Grapple MAD.
- **Success:** The victim breaks the hold. Remove the `Swallowed` status and place the victim in a chosen adjacent 5-foot grid square outside your body, Prone.

### Physical Retaliation (Attacking the Stomach)

The victim attempts to cut or claw their way to freedom by killing you from the inside. Under the Pinned condition, their attack is restricted as follows:

1. **Action Lock:** They are restricted to a single melee attack per round and cannot use Full Attacks or multi-weapon flurries.
2. **Weapon Lock:** They can use only light piercing or slashing weapons, such as daggers, shortswords, or natural claws.
3. **Accuracy Penalty:** They take a -4 penalty to the attack roll due to severe physical constriction.
4. **Target Defense:** Attacks target your Flat-Footed AC. You lose your Dexterity AC and Dodge AC components but retain Natural Armor, Shield/Deflection AC, and standard Armor AC. See [Armor Class Components](../game-mechanics/armor-class.md).

## Stomach Volume Capacity

Creature capacity and victim mass scale by size. See the [Stomach Volume Containment Matrix](../game-mechanics/combat-scaling.md#swallow-whole-capacity) for the shared size table (Medium victim mass = 1.0 unit).

## Ingestion and the Fed Condition

The moment you successfully ingest an organic, biological creature, you gain the **Fed** status condition, waiving the ration cost of your next upcoming rest.

## Corpses and Digestion

- **Mass Retention:** When a swallowed creature's health pool drops to 0 or below, they expire normally. Their body continues to occupy its full designated mass inside your stomach, reducing remaining capacity.
- **Digestion:** Exactly 1 hour after ingestion, a creature is fully digested and its organic mass is cleared from your volume tracking.
- **Short Rest:** A standard Short Rest advances exactly 1 hour of in-game time, satisfying the digestion window. Active digestion timers are processed and cleared when the rest completes.
- **Regurgitation:** To clear stomach volume before digestion concludes or during combat, spend a Full-Round Action to vomit up any dead, unconscious, or living targets into an adjacent grid square, where they land Prone. This consumes your Standard and Move Actions; your Free Action remains available.

## Post-Combat Humanoid Restriction

Standard, non-monstrous humanoids, such as normal player humanoids or specialized monks using external size-alteration feats, cannot maintain living or dead contents in their abdomen outside of high-adrenaline combat panic. When turn-based combat ends, any creature (living or dead) inside a non-monstrous humanoid's stomach is automatically regurgitated into an adjacent square, Prone. True monstrous or beast forms, such as Wolf and Bear, are exempt and can digest targets normally over the 1-hour window.

## Non-Digestible Equipment and Loot

- **Melting:** Muscle tissue, skin, and leather are liquefied during the 1-hour digestion cycle. Metals, gemstones, glass, and enchanted magical materials are immune to biological stomach acids.
- **Gastric Encumbrance:** After a victim is fully digested and its organic mass cleared, its equipment remains inside your gut as loose metal plates and gold.
- **Extracting Loot:** Outside combat, or as a Full-Round Action in combat, you can purge non-digestible gear into an adjacent grid square, clearing stomach capacity to zero. If the predator dies in battle, the party can spend 10 minutes field-dressing the carcass to recover all items.

**Required for:** None.

<nav aria-label="Related pages" style="display:flex;flex-wrap:wrap;gap:.5rem;margin-top:2rem;padding-top:.75rem;border-top:1px solid #aaa;">
<span style="font-weight:600;align-self:center;">Related:</span>
<a href="../index.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Game Reference</a>
<a href="../feats.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Feats</a>
<a href="../game-mechanics/armor-class.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Armor Class Components</a>
<a href="../game-mechanics/combat-scaling.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Combat Scaling</a>
<a href="still-spell.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Still Spell</a>
<a href="tail-combat.md" style="display:inline-block;padding:.35rem .65rem;border:1px solid #888;border-radius:4px;color:inherit;text-decoration:none;">Tail Combat</a>
</nav>
