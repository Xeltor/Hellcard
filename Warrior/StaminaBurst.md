# Warrior Stamina Burst Anchor (Updated: October 2024 live build)

## One-Screen Summary
- **Win condition**: bank Stamina, trigger `Stamina Burst`, and double-tap high-impact attacks like `Whirlwind` and `Groundbreaker` while staying at full block.[1][2][6][7][8][9]
- **Difficulty**: High (12/15) – sequencing is tight, yet the burst loop can carry all 12 floors once mastered.
- **Best in**: solo or co-op frontline; excels at elite/boss control thanks to repeated taunts and AOE.
- **Key stats**: `Second Wind` refunds +2 mana and 5 Stamina, making every Armory-upgraded attack a burst candidate; two stacked bursts in a row can clear Act II waves without spending gems.[1][7]

## Core Loop
1. Generate Stamina with `Second Wind`, `Knuckle Crack`, `Stretch`, and `Deep Breath` while blocking incoming damage.[1][2][3][4][6]
2. Trigger `Stamina Burst` through natural stacking or a `Cardio` cast, then fire your biggest attack (`Whirlwind`, `Groundbreaker`, `Gut Punch`) for a double resolution.[5][7][8][9]
3. End turns with excess block so you can tank hits, immediately rebuild Stamina, and set up the next burst cycle.

## Draft Priorities
- **Stamina engine**: `Second Wind` → `Knuckle Crack` → `Stretch` → `Deep Breath`.
- **Burst payoff**: upgrade `Whirlwind` early; add `Groundbreaker` or `Gut Punch` for heavier single-target damage.[8][9]
- **Control tools**: `Taunt` and `Weakest Link` keep bosses in reach while you charge bursts.[10][3]
- **Influence**: `Cardio` is a priority legendary; `Lie in Wait` or `Padded Shield` are acceptable backups when Cardio doesn’t appear.[5][21][22]
- **Removals**: cut low-impact starters (`Sword Slash`, `Slam`) so your draw density stays on engine pieces.

## Map & Economy Routing
- **Armory**: first upgrade goes to `Whirlwind` (adds damage per swing); the second usually hits `Second Wind` for an extra card + more reliability.[1][8]
- **Hideout**: remove dud attacks, use **Plan** to pin `Second Wind` or `Cardio`, and gift gems to the Warrior until you secure Unagi or a burst payoff.[10][11]
- **Vaults**: take them only after the engine is online; empty turns before your first burst can snowball into lethal damage.

## Artifacts & Relics
- `Unagi` – start every fight with 5 Stamina so the first burst lands by turn two.[11]
- `Unripe Banana` – converts leftover mana into block, protecting Stamina stacks on slower turns.[12]
- `Sun` – +1 mana next turn after taking damage keeps the chain going even when `Second Wind` exhausts.[13]
- `Silver Spoon` – early gem injection for Armory progress and artifact purchases.[14]
- `Clam` – steady gem income in longer campaigns; combine with Hideout removals to offset forced card rewards.[15]
- Generic defensive relics (`Trowel`, `Tilted Cairn`) are fine, but prioritise anything that grants mana, Stamina, or block based on your local table in `data/artifacts.json`.

## Sequencing & Combat Micro
- Start turns with Stamina gainers before burst payoffs; this keeps random draw effects (`Deep Breath`, `Second Wind`) from whiffing due to exhausted targets.[1][4]
- `Stamina Burst` doubles only the next card – queue your biggest attack, then finish with block or taunt tools.[7]
- Keep `Taunt` available for bosses that shift lanes; a stunned or forced-near target lets `Groundbreaker` and `Gut Punch` convert burst damage efficiently.[9][10]
- Remember `Whirlwind` strains; plan your burst turns so you have enough mana (or Stamina via `Cardio`) to cover the cost increase.[5][8]

## Sample Deck Shell / Flex Slots
| Card | Cost / Rarity | Role | Notes |
| --- | --- | --- | --- |
| `Second Wind` ×2 | 1 / Rare | Core Stamina + draw | +5 Stamina, +2 mana; exhausts but refunds tempo.[1] |
| `Knuckle Crack` | 1 / Rare | Stamina generator | +5 Stamina with Strain – play on burst setup turns.[2]
| `Stretch` | 1 / Common | Cheap Stamina | +2 (or +5) Stamina when hand lacks swords; great vs tight mana.[3] |
| `Deep Breath` | 1 / Rare | Stamina + block | +2 Stamina, draw 2, gain 4 block for safe setup.[4] |
| `Cardio` | 0 / Legendary | Instant burst | Gives `Stamina Burst` with Strain; only fire when payoff is ready.[5][7] |
| `Whirlwind` | 1 / Rare | AOE payoff | Burst to double the cone; manage Strain costs.[8] |
| `Groundbreaker` or `Gut Punch` | 1 / Rare/Legendary | Single-target payoff | Excellent for elites/bosses; benefits from stun/block synergies.[9] |
| `Taunt` | 1 / Rare | Position control | Pulls priority targets into your near section and fetches an Attack.[10] |
| Flex slot 1 | Varies | Influence | `Lie in Wait`, `Padded Shield`, or `Vigor` depending on burst consistency.[21][22][23] |
| Flex slot 2 | Varies | Defense | `Readiness`, `Parry`, or `Shield Bite` to sustain block between bursts.[24][25][26] |

## Gem Damage Benchmarks
- `Whirlwind`: 5 base damage per enemy; with burst, expect 10 (plus upgrades). Plan to stack Stamina before Strain pushes cost to 2+.[8]
- `Groundbreaker`: 12 base damage in a wide cone; burst converts to 24, enough to clear Act II bar sizes.[9]
- `Gut Punch`: 5 + Stamina (often 10+) doubled under burst, easily cracking boss block.[9]

## Co-op & Boss Notes
- Funnel early gems and mana relics to the Warrior so bursts come online before Act II elites.
- Coordinate taunts with ally AOE: burst `Whirlwind` clears near lanes while teammates finish far lanes.
- Bosses with multi-hit attacks (e.g., Bone Hydra) fuel block-based artifacts (`Unripe Banana`, `Sun`) – let the Warrior take aggro to exploit them.

## Common Pitfalls
- Overusing `Cardio` without a payoff queued wastes bursts; wait until the hand holds `Whirlwind`/`Groundbreaker`.
- Forgetting Strain on `Whirlwind`/`Knuckle Crack` – track costs so you aren’t short on burst turns.[2][8]
- Leaving Stamina unused while ending the turn at zero block; chip damage erases stacks and delays the loop.

## Changelog
- 2025-03-02 – Initial release (Codex).

---

[1]: https://hellcard.fandom.com/wiki/Second_Wind "Second Wind | Hellcard Wiki"
[2]: https://hellcard.fandom.com/wiki/Knuckle_Crack "Knuckle Crack | Hellcard Wiki"
[3]: https://hellcard.fandom.com/wiki/Stretch "Stretch | Hellcard Wiki"
[4]: https://hellcard.fandom.com/wiki/Deep_Breath "Deep Breath | Hellcard Wiki"
[5]: https://hellcard.fandom.com/wiki/Cardio "Cardio | Hellcard Wiki"
[6]: https://hellcard.fandom.com/wiki/Effects#Stamina "Stamina | Hellcard Wiki"
[7]: https://hellcard.fandom.com/wiki/Effects#Stamina_Burst "Stamina Burst | Hellcard Wiki"
[8]: https://hellcard.fandom.com/wiki/Whirlwind "Whirlwind | Hellcard Wiki"
[9]: https://hellcard.fandom.com/wiki/Groundbreaker "Groundbreaker | Hellcard Wiki"
[10]: https://hellcard.fandom.com/wiki/Taunt "Taunt | Hellcard Wiki"
[11]: https://hellcard.fandom.com/wiki/Unagi "Unagi | Hellcard Wiki"
[12]: https://hellcard.fandom.com/wiki/Unripe_Banana "Unripe Banana | Hellcard Wiki"
[13]: https://hellcard.fandom.com/wiki/Sun "Sun | Hellcard Wiki"
[14]: https://hellcard.fandom.com/wiki/Silver_Spoon "Silver Spoon | Hellcard Wiki"
[15]: https://hellcard.fandom.com/wiki/Clam "Clam | Hellcard Wiki"
[21]: https://hellcard.fandom.com/wiki/Lie_in_Wait "Lie in Wait | Hellcard Wiki"
[22]: https://hellcard.fandom.com/wiki/Padded_Shield "Padded Shield | Hellcard Wiki"
[23]: https://hellcard.fandom.com/wiki/Vigor "Vigor | Hellcard Wiki"
[24]: https://hellcard.fandom.com/wiki/Readiness "Readiness | Hellcard Wiki"
[25]: https://hellcard.fandom.com/wiki/Parry "Parry | Hellcard Wiki"
[26]: https://hellcard.fandom.com/wiki/Shield_Bite "Shield Bite | Hellcard Wiki"
