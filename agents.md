# Hellcard Guide Authoring Playbook

## Purpose
- Keep every build guide readable, current, and actionable for Hellcard players.
- Capture the logic behind recommendations so updates stay easy when balance patches land.
- Provide a single reference for voice, structure, and sourcing so future guides stay consistent.

## Voice & Tone
- Write like a high-level teammate: direct, confident, never smug.
- Lead with the “why” behind each pick before the “how to execute”.
- Default to present tense and active voice; avoid passive phrasing and filler adjectives.
- Use short paragraphs and 1-line bullets for scanability; reserve callout boxes only when absolutely necessary.

## Canonical Guide Layout
1. **Header**: build title + patch (e.g., `Patch 1.0.12`).
2. **One-screen summary**: core win condition, difficulty, solo/co-op viability.
3. **Core Loop**: the repeatable turn pattern that actually wins fights.
4. **Draft Priorities**: pickups & skips with quick reasoning; separate by rarity when relevant.
5. **Map & Economy Routing**: Armory vs Hideout priorities, event usage, gem/mana management.
6. **Artifacts & Relics**: ranked list with synergy notes and anti-picks.
7. **Sequencing & Combat Micro**: turn order, positioning, etc.
8. **Sample Deck Shell / Flex Slots**: 8–12 card template, labelled must-haves vs flex.
9. **Co-op / Boss / Floor Notes**: targeted adjustments; keep concise tables when data heavy.
10. **Common Pitfalls**: mistakes that implode the build (draw bricking, over-spending gems, etc.).
11. **Changelog**: bullet list of the last edits with patch/date for traceability.

## Content Rules
- Name cards, artifacts, enemies, and map nodes in backticks (e.g., `Shakedown`) for consistency.
- When stating numbers (damage, mana, thresholds), cite a verifiable source or include the patch note.
- Call out when a strategy is experimental or reliant on RNG so readers can gauge risk.
- Use footnotes for external references; link the smallest page that verifies the claim.
- Validate that every build can execute as written in the live game; no speculative combos without proven runs or patch confirmations.
- Reach for the local datasets in `data/` (`cards.json`, `artifacts.json`, `effects.json`) before opening the wiki; only hit online sources when the offline snapshot lacks what you need.
- Keep `README.md` as a browsable index—update it whenever guides or datasets move so newcomers can navigate the repo quickly.
- When updating the index, group builds by class and list them from lowest to highest difficulty, including the difficulty label beside each entry.
- Each new build must highlight a distinct gameplan—different damage engine, resource economy, or control approach—so we never publish near-duplicates of guides already in the repo.
- Any time you pull fresh details from the web, capture them in a local dataset (or refresh the existing JSON) before moving on so the next edit can stay offline.
- Tag every guide with a difficulty label derived from this rubric (always considering how reliably the build clears a full 12-floor campaign):
  * **Sequencing Complexity** – 1 (simple rotation), 2 (occasional tricky order), 3 (constant precise sequencing).
  * **Core Card/Artifact Dependency** – 1 (commons/early finds), 2 (mix of rarities), 3 (needs specific rares or relics).
  * **Survivability Management** – 1 (self-sustaining), 2 (needs some planning), 3 (frequent HP risk or tight block numbers).
  * **Coordination Requirements** – 1 (solo friendly), 2 (some ally help), 3 (relies heavily on teammates).
  * **Routing Pressure** – 1 (flexible map), 2 (prefers certain nodes), 3 (strict upgrade/event path).
Sum the scores:
  * 5–7 → **Difficulty: Low**
  * 8–11 → **Difficulty: Medium**
  * 12–15 → **Difficulty: High**
Record the label in the guide’s one-screen summary so readers see it immediately.
When scoring, judge each axis by how it holds up over the full 12-floor run (early stability, midgame scaling, and late-game survivability).

## Data Collection & Verification
- **Pre-write checklist**: confirm the current game build, note any balance hotfixes in the last 7 days, and scan official Discord announcements.
- **Testing**: log at least two full runs or seeded practice arenas; record screenshots or VOD timestamps if numbers differ from published data.
- **Validation**: after drafting, re-check any numeric tables against primary sources before publishing.

## Source Library (keep updating)
- [1] **Official Patch Notes (Steam News Hub)** – primary source for card/stat changes, event tweaks, bug fixes.
- [2] **Hellcard Wiki** – card text, artifact effects, location rules, unlock paths. Cross-check images when describing UI.
- [3] **Hellcard Discord #guides / #patch-notes** – early info on hotfixes, datamined drop rates.
- [4] **"If You Are Struggling" Steam guide** – curated card evaluations, encounter notes, and economy tips collected from high-win players.
- [5] **Rogue tips mega-thread (Steam Discussions)** – long-form community testing on gem economy, artifact synergy, and map routes.
- [6] **Steam Community guides index** – discovery hub for newly published tech; great for spotting emerging strategies to verify.

## Workflow for New Guides
1. Define the build goal (class, archetype, solo/co-op focus).
2. Gather fresh data: card pool, artifact synergies, agent behaviour if applicable.
3. Outline using the canonical layout; fill notes under each heading before writing prose.
4. Draft sections in priority order (Core Loop → Draft → Map → Artifacts → Micro → Pitfalls).
5. Insert inline citations as you go; don’t wait until the end.
6. Run a self QA pass: spell check, confirm tone, ensure bullets stay concise.
7. Update the changelog and commit with a meaningful message referencing the patch.

## Maintenance Cadence
- After every official patch: audit all guides within 48 hours; mark untouched guides with “Pending revalidation” until checked.
- For hotfixes: skim patch note; if the change affects a featured card or artifact, append a quick note or update stats immediately.
- Quarterly: prune dead links, refresh source library, archive outdated spreadsheets.

## Style Quick Reference
- Headings use Title Case; sub-bullets avoided unless data tables demand nesting.
- Tables: prefer Markdown tables for encounter timelines or reward breakpoints; keep ≤5 columns.
- Numbers: write `10 mana` not `10 Mana`; pluralize gems/mana normally.
- Terminology: `Hideout`, `Armory`, `Plan`, `Gem`, `Mana`, `Stun`, `Strain` follow in-game capitalization.
- Footnotes: numeric order, placed at the end of the file; reuse numbers only when referencing the exact same source.

## Change Tracking Template
```
## Changelog
- 2025-03-02 – Updated for Patch 1.0.12 (author)
```
Include this block at the end of every guide and keep the newest entry on top.

---

[1]: https://store.steampowered.com/news/app/1201540 "HELLCARD Steam News"
[2]: https://hellcard.fandom.com/wiki/Hellcard_Wiki "HELLCARD Wiki"
[3]: https://discord.gg/hellcard "Hellcard Official Discord"
[4]: https://steamcommunity.com/sharedfiles/filedetails/?id=2940088889 "If you are struggling – Steam Guide"
[5]: https://steamcommunity.com/app/1201540/discussions/0/3776868105346454307/ "Rogue Tips? – Steam Discussions"
[6]: https://steamcommunity.com/app/1201540/guides/ "Steam Community Guides"
