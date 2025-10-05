# Warrior Stamina Burst Anchor (Updated: October 2024 live build)

## One-Screen Summary
- **Win condition**: bank Stamina, trigger [`Stamina Burst`][card-stamina-burst], and double-tap high-impact attacks like [`Whirlwind`][card-whirlwind] and [`Groundbreaker`][card-groundbreaker] while staying at full block.
- **Difficulty**: High (12/15) – sequencing is tight, yet the burst loop can carry all 12 floors once mastered.
- **Best in**: solo or co-op frontline; excels at elite/boss control thanks to repeated taunts and AOE.
- **Key stats**: [`Second Wind`][card-second-wind] refunds +2 mana and 5 Stamina, making every Armory-upgraded attack a burst candidate; two stacked bursts in a row can clear Act II waves without spending gems.

## Core Loop
1. Generate Stamina with [`Second Wind`][card-second-wind], [`Knuckle Crack`][card-knuckle-crack], [`Stretch`][card-stretch], and [`Deep Breath`][card-deep-breath] while blocking incoming damage.
2. Trigger [`Stamina Burst`][card-stamina-burst] through natural stacking or a [`Cardio`][card-cardio] cast, then fire your biggest attack ([`Whirlwind`][card-whirlwind], [`Groundbreaker`][card-groundbreaker], `Gut Punch`) for a double resolution.
3. End turns with excess block so you can tank hits, immediately rebuild Stamina, and set up the next burst cycle.

## Draft Priorities
- **Stamina engine**: [`Second Wind`][card-second-wind] → [`Knuckle Crack`][card-knuckle-crack] → [`Stretch`][card-stretch] → [`Deep Breath`][card-deep-breath].
- **Burst payoff**: upgrade [`Whirlwind`][card-whirlwind] early; add [`Groundbreaker`][card-groundbreaker] or `Gut Punch` for heavier single-target damage.
- **Control tools**: [`Taunt`][card-taunt] and `Weakest Link` keep bosses in reach while you charge bursts.
- **Influence**: [`Cardio`][card-cardio] is a priority legendary; [`Lie in Wait`][card-lie-in-wait] or [`Padded Shield`][card-padded-shield] are acceptable backups when Cardio doesn’t appear.
- **Removals**: cut low-impact starters (`Sword Slash`, `Slam`) so your draw density stays on engine pieces.

## Map & Economy Routing
- **Armory**: first upgrade goes to [`Whirlwind`][card-whirlwind] (adds damage per swing); the second usually hits [`Second Wind`][card-second-wind] for an extra card + more reliability.
- **Hideout**: remove dud attacks, use **Plan** to pin [`Second Wind`][card-second-wind] or [`Cardio`][card-cardio], and gift gems to the Warrior until you secure Unagi or a burst payoff.
- **Vaults**: take them only after the engine is online; empty turns before your first burst can snowball into lethal damage.

## Artifacts & Relics
- [`Unagi`][card-unagi] – start every fight with 5 Stamina so the first burst lands by turn two.
- [`Unripe Banana`][card-unripe-banana] – converts leftover mana into block, protecting Stamina stacks on slower turns.
- [`Sun`][card-sun] – +1 mana next turn after taking damage keeps the chain going even when [`Second Wind`][card-second-wind] exhausts.
- [`Silver Spoon`][card-silver-spoon] – early gem injection for Armory progress and artifact purchases.
- [`Clam`][card-clam] – steady gem income in longer campaigns; combine with Hideout removals to offset forced card rewards.
- Generic defensive relics (`Trowel`, `Tilted Cairn`) are fine, but prioritise anything that grants mana, Stamina, or block based on your local table in `data/artifacts.json`.

## Sequencing & Combat Micro
- Start turns with Stamina gainers before burst payoffs; this keeps random draw effects ([`Deep Breath`][card-deep-breath], [`Second Wind`][card-second-wind]) from whiffing due to exhausted targets.
- [`Stamina Burst`][card-stamina-burst] doubles only the next card – queue your biggest attack, then finish with block or taunt tools.
- Keep [`Taunt`][card-taunt] available for bosses that shift lanes; a stunned or forced-near target lets [`Groundbreaker`][card-groundbreaker] and `Gut Punch` convert burst damage efficiently.
- Remember [`Whirlwind`][card-whirlwind] strains; plan your burst turns so you have enough mana (or Stamina via [`Cardio`][card-cardio]) to cover the cost increase.

## Sample Deck Shell / Flex Slots
| Card | Cost / Rarity | Role | Notes |
| --- | --- | --- | --- |
| [`Second Wind`][card-second-wind] ×2 | 1 / Rare | Core Stamina + draw | +5 Stamina, +2 mana; exhausts but refunds tempo. |
| [`Knuckle Crack`][card-knuckle-crack] | 1 / Rare | Stamina generator | +5 Stamina with Strain – play on burst setup turns.
| [`Stretch`][card-stretch] | 1 / Common | Cheap Stamina | +2 (or +5) Stamina when hand lacks swords; great vs tight mana. |
| [`Deep Breath`][card-deep-breath] | 1 / Rare | Stamina + block | +2 Stamina, draw 2, gain 4 block for safe setup. |
| [`Cardio`][card-cardio] | 0 / Legendary | Instant burst | Gives [`Stamina Burst`][card-stamina-burst] with Strain; only fire when payoff is ready. |
| [`Whirlwind`][card-whirlwind] | 1 / Rare | AOE payoff | Burst to double the cone; manage Strain costs. |
| [`Groundbreaker`][card-groundbreaker] or `Gut Punch` | 1 / Rare/Legendary | Single-target payoff | Excellent for elites/bosses; benefits from stun/block synergies. |
| [`Taunt`][card-taunt] | 1 / Rare | Position control | Pulls priority targets into your near section and fetches an Attack. |
| Flex slot 1 | Varies | Influence | [`Lie in Wait`][card-lie-in-wait], [`Padded Shield`][card-padded-shield], or [`Vigor`][card-vigor] depending on burst consistency. |
| Flex slot 2 | Varies | Defense | [`Readiness`][card-readiness], [`Parry`][card-parry], or [`Shield Bite`][card-shield-bite] to sustain block between bursts. |

## Gem Damage Benchmarks
- [`Whirlwind`][card-whirlwind]: 5 base damage per enemy; with burst, expect 10 (plus upgrades). Plan to stack Stamina before Strain pushes cost to 2+.
- [`Groundbreaker`][card-groundbreaker]: 12 base damage in a wide cone; burst converts to 24, enough to clear Act II bar sizes.
- `Gut Punch`: 5 + Stamina (often 10+) doubled under burst, easily cracking boss block.

## Co-op & Boss Notes
- Funnel early gems and mana relics to the Warrior so bursts come online before Act II elites.
- Coordinate taunts with ally AOE: burst [`Whirlwind`][card-whirlwind] clears near lanes while teammates finish far lanes.
- Bosses with multi-hit attacks (e.g., Bone Hydra) fuel block-based artifacts ([`Unripe Banana`][card-unripe-banana], [`Sun`][card-sun]) – let the Warrior take aggro to exploit them.

## Common Pitfalls
- Overusing [`Cardio`][card-cardio] without a payoff queued wastes bursts; wait until the hand holds [`Whirlwind`][card-whirlwind]/[`Groundbreaker`][card-groundbreaker].
- Forgetting Strain on [`Whirlwind`][card-whirlwind]/[`Knuckle Crack`][card-knuckle-crack] – track costs so you aren’t short on burst turns.
- Leaving Stamina unused while ending the turn at zero block; chip damage erases stacks and delays the loop.

## Changelog
- 2025-03-02 – Initial release (Codex).

---

[card-second-wind]: https://hellcard.fandom.com/wiki/Second_Wind "Second Wind | Hellcard Wiki"
[card-knuckle-crack]: https://hellcard.fandom.com/wiki/Knuckle_Crack "Knuckle Crack | Hellcard Wiki"
[card-stretch]: https://hellcard.fandom.com/wiki/Stretch "Stretch | Hellcard Wiki"
[card-deep-breath]: https://hellcard.fandom.com/wiki/Deep_Breath "Deep Breath | Hellcard Wiki"
[card-cardio]: https://hellcard.fandom.com/wiki/Cardio "Cardio | Hellcard Wiki"
[card-stamina]: https://hellcard.fandom.com/wiki/Effects#Stamina "Stamina | Hellcard Wiki"
[card-stamina-burst]: https://hellcard.fandom.com/wiki/Effects#Stamina_Burst "Stamina Burst | Hellcard Wiki"
[card-whirlwind]: https://hellcard.fandom.com/wiki/Whirlwind "Whirlwind | Hellcard Wiki"
[card-groundbreaker]: https://hellcard.fandom.com/wiki/Groundbreaker "Groundbreaker | Hellcard Wiki"
[card-taunt]: https://hellcard.fandom.com/wiki/Taunt "Taunt | Hellcard Wiki"
[card-unagi]: https://hellcard.fandom.com/wiki/Unagi "Unagi | Hellcard Wiki"
[card-unripe-banana]: https://hellcard.fandom.com/wiki/Unripe_Banana "Unripe Banana | Hellcard Wiki"
[card-sun]: https://hellcard.fandom.com/wiki/Sun "Sun | Hellcard Wiki"
[card-silver-spoon]: https://hellcard.fandom.com/wiki/Silver_Spoon "Silver Spoon | Hellcard Wiki"
[card-clam]: https://hellcard.fandom.com/wiki/Clam "Clam | Hellcard Wiki"
[card-lie-in-wait]: https://hellcard.fandom.com/wiki/Lie_in_Wait "Lie in Wait | Hellcard Wiki"
[card-padded-shield]: https://hellcard.fandom.com/wiki/Padded_Shield "Padded Shield | Hellcard Wiki"
[card-vigor]: https://hellcard.fandom.com/wiki/Vigor "Vigor | Hellcard Wiki"
[card-readiness]: https://hellcard.fandom.com/wiki/Readiness "Readiness | Hellcard Wiki"
[card-parry]: https://hellcard.fandom.com/wiki/Parry "Parry | Hellcard Wiki"
[card-shield-bite]: https://hellcard.fandom.com/wiki/Shield_Bite "Shield Bite | Hellcard Wiki"
