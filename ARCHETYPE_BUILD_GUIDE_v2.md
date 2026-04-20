# Powered Cube — Per-Archetype Build Criteria (v2)

This is a revision of the previous build guide, with three improvements based on critique:

1. **Distinguishes AUTO-INCLUDES from FLEX SLOTS.** The previous guide showed "WR uplift when included," which made signature cards like Minsc & Boo look unimportant in their home archetype because they're already baked into the cluster definition. The new structure is: (a) the core cards everyone plays in this archetype, (b) the configurable choices that distinguish well-built from poorly-built versions, (c) cards that signal you're building the deck wrong.

2. **Categorizes AVOID cards by mechanism.** Some "AVOID" findings are real "this card is bad here" signals. Others are markers of a sub-archetype that loses (the card itself may be fine; the deck pattern around it isn't). The two require different responses.

3. **Honest uncertainty.** Where the data can't distinguish "card is bad" from "card-includers are also doing other things wrong," I say so.

---

## How to read this guide

Each archetype gets four sections:

- **Core (signature cards):** Played in 40%+ of cluster decks. These define the deck. Include them by default.
- **Flex slots — INCLUDE:** Played in 10–40% of decks, with positive WR uplift. These are configurable choices that mark a well-built version.
- **Flex slots — AVOID:** Played in 10%+ of decks, with negative WR uplift. Each is annotated:
  - **Genuine trap** = card hurts the deck in this role.
  - **Sub-archetype marker** = card signals a coherent build that just doesn't work in this format.
  - **Likely selection effect** = card may be fine, but its includers are also doing other things wrong.
- **Verdict** = honest summary of what to take from this.

---

## Boros Aggro-Midrange (cluster 1, base WR 68.3%)

**Core (40%+ play rate):** Guide of Souls (55%), Ajani Nacatl Pariah (52%), Mother of Runes (50%), Phlage (48%), Voice of Victory (46%), Luminarch Aspirant (45%), Inspiring Vantage (45%), Adeline Resplendent Cathar (45%), Plateau (45%), Ocelot Pride (44%), Giver of Runes (43%), Sunbillow Verge (42%).

This is the densest core of any archetype — these 12 cards are essentially auto-includes. The deck works because every Boros card slots together.

**Flex slots — INCLUDE:** Mox Ruby (+3.9% if in pool), Phlage (+3.4% — listed twice because it's both core and a meaningful uplift), Path to Exile (+2.4%), Gut True Soul Zealot (+2.4%), Mine Collapse (+2.1%), Makdee and Itla (+2.0%).

**Flex slots — AVOID:**
- **Cori-Steel Cutter** (-2.6%) — *Sub-archetype marker.* Cori-Steel decks correlate with Sunbaked Canyon (+8%), Figure of Destiny (+8%), Goblin Bombardment (+7%), Burst Lightning (+5%), Kumano (+6%) — that's the **Mono-R Aggro shell trying to be Boros**. The card is fine in Mono-R; it's a sign you're trying to be two archetypes at once.
- **Hellrider** (-2.7%), **Burst Lightning** (-2.2%), **Fury** (-2.3%), **Intrepid Adversary** (-2.5%) — same pattern. Mono-R aggro creatures in a midrange shell.
- **Enduring Innocence** (-3.2%) — likely a *genuine trap*. White value enchantment that doesn't help Boros's tempo plan.
- **Flame Slash** (-3.1%) — same card is +2.5% in Boros Skies. Here it's redundant with the burn you already have. *Genuine trap in this version.*
- **Ademi of the Silkchutes** (-2.6%) — *likely selection effect.* Plays in 26% of cluster but lower-WR decks.

**Verdict:** Don't mix Mono-R aggro creatures into the midrange version. The "include" flex slots are smaller boosts than the avoid penalties — i.e., the upside of perfect tuning is +2-3%, the downside of mixing aggressive R cards is -2-3%. Avoidance matters more than optimization here.

---

## Boros Skies / Showdown (cluster 4, base WR 66.5%)

**Core:** Sanguine Evangelist (55%), Showdown of the Skalds (54%), Death-Greeter's Champion (50%), Hired Claw (46%), Glimmer Lens (43%), Luminarch Aspirant (43%), Draconautics Engineer (43%), Sage of the Skies (41%).

The Skies build is more committed to a specific direction than Boros Aggro-Midrange — every signature card is a flier or a "pump fliers" piece.

**Flex slots — INCLUDE:** Mox Pearl (+5.5% if available), Mox Ruby (+3.2%), Ajani Nacatl Pariah (+3.2%), Goblin Bombardment (+3.0%), Fable of the Mirror-Breaker (+2.7%), Flame Slash (+2.5%), Comet Stellar Pup (+2.4%), Parallax Wave (+2.3%), Laelia (+2.3%), Ocelot Pride (+2.3%), Swords to Plowshares (+2.1%).

**Flex slots — AVOID:**
- **Yera and Oski** (-5.3%), **Mana Tithe** (-3.9%), **Virtue of Loyalty** (-3.5%) — *likely sub-archetype markers* for the slower Bant/UW-leaning version. Wants different supporting cast than Skies.
- **Splitskin Doll** (-2.7%), **Grim Lavamancer** (-2.3%), **Galvanic Discharge** (-2.2%), **Skullclamp** (-2.2%), **Unholy Heat** (-2.6%) — *genuine traps*. These are go-wide / sacrifice / midrange-burn cards that don't synergize with the "play threats with evasion + pump them" plan.

**Verdict:** Skies is more focused than Aggro-Mid; stay aggressive and evasive. Don't dilute with go-wide/grindy cards.

---

## Boros Goodstuff / Solitude variant (cluster 19, base WR 63.3%)

**Core:** No card breaks 40% — this cluster is more diffuse than the other Boros variants.

**Flex slots — INCLUDE:** Ragavan (+3.6%), Fury (+3.5%), Mox Pearl (+3.5%), Umezawa's Jitte (+3.1%), Lightning Bolt (+3.0%), Chrome Mox (+2.8%), Flickerwisp (+2.5%), Parallax Wave (+2.4%), Swords to Plowshares (+2.3%), Lightstall Inquisitor (+2.1%), Chandra Torch of Defiance (+2.0%), Abrade (+2.0%).

This deck wants the **older premium reactive Boros toolkit** — Fury, Bolt, Jitte, Solitude (implied), Chrome Mox.

**Flex slots — AVOID:**
- **Fear of Missing Out** (-3.8%), **Splitskin Doll** (-3.1%), **Descendant of Storms** (-3.0%), **Robber of the Rich** (-2.1%) — *sub-archetype markers* for the more-aggressive Boros build. Goodstuff wants reactive premium spells, not aggressive 1- and 2-drops.
- **The Wandering Emperor** (-3.0%) — *genuine trap.* 4-mana planeswalker that's too slow.
- **Unholy Heat** (-3.0%), **Galvanic Discharge** (-2.5%), **Portable Hole** (-2.0%) — *genuine traps* for this version. Better burn/removal options exist.

**Verdict:** This is the controlling Boros build. Don't mix in the aggressive 1- and 2-drops; those want their own (different) Boros shell.

---

## Mono-R / Boros Aggro (cluster 16, base WR 64.4%)

**Core:** Death-Greeter's Champion (44%) — slightly above 40%; otherwise no cards above the threshold.

**Flex slots — INCLUDE:** Scalding Tarn (+5.1%), Pyrogoyf (+4.2%), Swords to Plowshares (+4.1% — splash white), Laelia (+4.0%), Mox Ruby (+3.9%), Fury (+3.8%), Prismatic Vista (+3.7%), Broadside Bombardiers (+3.3%), Karakas (+3.2%), Unholy Heat (+3.2%), Monastery Swiftspear (+3.1%), Arena of Glory (+2.9%).

**Flex slots — AVOID — this is where the most surprising findings live:**
- **Goldspan Dragon** (-4.4%) — *real trap with a clear deckbuilding signal.* Goldspan-Mono-R decks correlate with Seasoned Pyromancer (+20%), Mana Crypt (+14%), Mox Diamond (+12%), Seething Song (+8%), Fireblast (+16%) — that's a **fast-mana ritual-storm-style deck pretending to be aggro**. The deck is trying to do too much. Goldspan is the marker, but the strategy is the problem: aggro decks can't afford 4-mana topdecks AND ritual mana, so they end up fragile.
- **Glorybringer** (-2.8%), **Bonecrusher Giant** (-2.2%) — *genuine traps.* Premium 4-mana threats that compete for too much mana.
- **Voice of Victory** (-3.4%) — *sub-archetype marker.* Voice belongs in Boros Aggro-Mid and signals you're trying to splash white for midrange tools.
- **Kari Zev, Skyship Raider** (-2.2%) — surprising. *Possibly selection effect* — Kari Zev appears in 36% of cluster decks but its WR-with is 0.629 vs WR-without 0.652. Hard to say if she's actively bad or just played in worse builds.
- **Galvanic Discharge** (-2.4%), **Abrade** (-2.0%) — *genuine traps.* Worse burn options than Bolt/Chain Lightning/Unholy Heat which all show up as positive.

**Verdict:** **The single biggest mistake in Mono-R is including premium 4-mana threats.** Goldspan, Glorybringer, Bonecrusher, Voice of Victory — all "good cards" that don't belong. Aggro tops out at 3 mana.

---

## Mono-W / Bant Aggro (cluster 18, base WR 64.4%)

**Core:** Giver of Runes (44%), Phelia (44%), Mother of Runes (44%), Guide of Souls (43%), Ocelot Pride (42%), Voice of Victory (42%), Adeline (41%), Sanguine Evangelist (41%), Glimmer Lens (41%), Parallax Wave (40%).

**Flex slots — INCLUDE:** Lightstall Inquisitor (+4.2%), Mox Sapphire (+4.0%), Arid Mesa (+3.8%), Winds of Abandon (+2.9%), Serra Paragon (+2.8%), Elspeth Storm Slayer (+2.6%), Solitude (+2.2%), Touch the Spirit Realm (+2.0%), Blade Splicer (+2.0%), Smuggler's Copter (+1.9%).

**Flex slots — AVOID — splashing red is the dominant pattern:**
- **Plateau** (-4.5%), **Sunbillow Verge** (-3.6%), **Sacred Foundry** (-3.2%) — *clear sub-archetype marker.* These are R/W lands. The Mono-W shell that wins is mono-W or W-with-blue-splash. R-splash builds are a worse Boros deck.
- **Gut True Soul Zealot** (-2.4%) — *sub-archetype marker.* Belongs in Mono-R / Boros Aggro.
- **Path to Exile** (-2.6%) — surprising. *Probably genuine trap here.* Mono-W Aggro typically wants Swords to Plowshares (which IS in the cluster's signature card pool) — Path is redundant and maybe signals over-removal at the cost of threats.
- **Yera and Oski** (-2.4%), **The Wandering Emperor** (-1.8%) — *genuine traps.* Slower 4-mana cards that don't fit.
- **Witch Enchanter** (-2.3%) — *uncertain.* Could be selection.

**Verdict:** Stay tight on color. Mono-W or W-blue, not WR. Don't dilute with slow 4-drops.

---

## Rakdos Midrange (cluster 3, base WR 62.6%)

**Core:** Bloodtithe Harvester (44%), Fire Covenant (44%).

**Flex slots — INCLUDE:** Black Lotus (+5.7% if available), Pyrogoyf (+4.2%), Cori-Steel Cutter (+3.8%), Screaming Nemesis (+3.7%), Mana Crypt (+3.7%), Restless Vents (+3.6%), Ivora (+3.5%), Takenuma (+3.3%), Detective's Phoenix (+3.3%), Inti (+3.1%), Murderous Cut (+3.0%), Dragon's Rage Channeler (+2.8%).

**Flex slots — AVOID:**
- **Bitter Triumph** (-2.7%), **Duress** (-2.4%), **Elegy Acolyte** (-2.2%) — *genuine traps*. These are slow black cards. Rakdos here is an aggressive R-leaning shell, not a black grindy shell.
- **Minsc & Boo, Timeless Heroes** (-2.1%) — *sub-archetype marker.* M&B is a strong card, but its presence here implies you're trying to splash green and be Jund. The 3-color version of this deck loses to the 2-color.
- **Mine Collapse** (-2.2%), **Voldaren Epicure** (-1.9%), **Gut True Soul Zealot** (-2.1%), **Savai Triome** (-2.3%) — *sub-archetype markers* for greedier or more-fast-aggro variants.

**Verdict:** Rakdos wins by being efficient red threats + black removal, not by being slow black or by splashing.

---

## Gruul/Jund Midrange (cluster 5, base WR 60.6%)

**Core:** Minsc & Boo (56%), Taiga (44%). M&B is the signature card — and yes, it's a top auto-include. The previous version of the guide buried this; here I'm calling it out explicitly.

**Flex slots — INCLUDE:** Ketria Triome (+5.3%), Sol Ring (+5.0%), Screaming Nemesis (+5.0%), Smuggler's Copter (+4.7%), Chain Lightning (+3.9%), Lightning Bolt (+3.4%), Arena of Glory (+3.2%), Tersa Lightshatter (+3.2%), Wrenn and Six (+3.1%), Strip Mine (+3.1%), Fiery Confluence (+3.0%), Goblin Rabblemaster (+3.0%).

**Flex slots — AVOID:**
- **Chandra Torch of Defiance** (-3.9%) — *genuine trap.* 4-mana planeswalker too slow.
- **Avacyn's Pilgrim** (-3.3%), **Nadu** (-2.6%), **Omnath Locus of Creation** (-2.7%), **Elder Gargaroth** (-3.3%) — *sub-archetype markers* for ramp-leaning Green Ramp / Lands variants. These belong in different clusters.
- **Prismatic Vista** (-2.8%), **Savannah** (-2.8%), **Icetill Explorer** (-2.7%) — *sub-archetype markers.* Suggest 4-color or Lands-hybrid builds that underperform.

**Verdict:** Gruul/Jund wants to be aggressive midrange (Bolt, Smuggler's Copter, Goblin Rabblemaster), not slow ramp. M&B is the auto-include centerpiece; the configurable choices are about staying aggressive.

---

## Orzhov/Abzan Midrange (cluster 14, base WR 60.4%)

**Core:** Scrubland (44%).

**Flex slots — INCLUDE:** Serra Paragon (+5.5%), Preacher of the Schism (+5.2%), Portable Hole (+5.1%), Mox Emerald (+5.0%), Guide of Souls (+4.9%), Barrowgoyf (+4.6%), Thraben Inspector (+4.6%), Mox Jet (+4.5%), Go for the Throat (+4.3%), Elspeth Storm Slayer (+4.3%), Sanguine Evangelist (+3.9%), Karakas (+3.8%).

**Flex slots — AVOID:**
- **Umezawa's Jitte** (-4.4%) — *genuine trap here.* Orzhov-Jitte decks correlate with Lingering Souls (+12%), Stoneforge Mystic (+10%), Reprieve (+9%), Splitskin Doll (+9%) — that's a **token / equipment go-wide build** that doesn't have enough cheap creatures to actually hold the Jitte. The card is great with cheap aggro creatures (which is why it's +3% in Boros Goodstuff). In a midrange shell that lacks 1-drops, it sits in hand.
- **Mind Twist** (-6.1%), **Library of Alexandria** (-3.2%), **Tundra** (-5.2%) — *sub-archetype markers* for the **3+ color "Esper-pile"** version. The data flatly says: stay 2-color WB or splash light green for Abzan, don't try to play Esper.
- **Dismember** (-4.4%), **Fire Covenant** (-3.2%) — *probably genuine traps.* Removal that costs life or stretches mana, redundant with better black removal.
- **Sorin of House Markov** (-4.0%) — *uncertain*; could be either bad card or sub-archetype signal.
- **Prismatic Vista** (-4.1%) — *sub-archetype marker* for greedy mana bases.

**Verdict:** Stay 2-color. Don't include Jitte unless you have the cheap creatures to hold it. The format penalizes splashing for power cards.

---

## UW(x) Control (cluster 8, base WR 60.5%)

**Core:** Teferi Time Raveler (46%), No More Lies (45%).

**Flex slots — INCLUDE:** Time Walk (+7.2% if available), Ancestral Recall (+5.8% if available), Tamiyo Inquisitive Student (+4.3%), Thraben Inspector (+4.0%), Quantum Riddler (+3.6%), Mana Leak (+2.6%), Miscalculation (+2.5%), Malcolm (+2.5%), Karakas (+2.5%), Thundertrap Trainer (+2.5%), Ajani Nacatl Pariah (+2.3%), Containment Priest (+2.2%).

**Flex slots — AVOID — this is where I overstated my conclusions before:**
- **Counterspell** (-2.2%) — *honest answer: I don't know.* The interpretation I gave previously ("UU is too restrictive") wasn't supported by the data. The correlation analysis shows Counterspell-decks are actually well-built in many ways: more Cryptic Command (+8%), more Celestial Colonnade (+7%), more Remand (+7%), more Stock Up (+6%). These are good cards. So the -2.2% delta is likely a **player-tendency selection effect** — hard counterspell players may be over-running expensive blue spells (Cryptic, Stock Up) and under-running threats. **My previous "Counterspell is bad here" framing was too strong.** The honest take: Counterspell is probably fine, but it correlates with a more spell-heavy build pattern that isn't winning. If you include it as part of a balanced curve, it's likely good. If it's the 4th expensive blue card in your deck, the signal is more concerning.
- **Brainstorm** (-4.0%) — *similar story but stronger.* Brainstorm-decks have more Force of Will (+11%), Cryptic Command (+8%), Karakas (+8%), Sink into Stupor (+11%), Faerie Mastermind (+8%) — these are spell-heavy, expensive-blue builds. **Brainstorm signals a "do all the blue things" deck that loses to Boros.** Probably less the card and more the strategy. If you build a balanced UW deck and include Brainstorm with proper fetch density, it's likely fine.
- **Godless Shrine** (-5.9%), **Lingering Souls** (-3.3%) — *sub-archetype markers.* Splashing black. The Esper-version of UW Control underperforms.
- **Consider** (-2.9%), **Leyline Binding** (-2.7%), **Portable Hole** (-2.4%), **Swords to Plowshares** (-2.2%) — *uncertain.* Some of these may be selection effects. Swords to Plowshares being negative is a particularly strong sign that the methodology has a blind spot — it's universally regarded as the best removal spell in white. The pattern across these "premium card is negative" findings is that they correlate with spell-heavy / removal-heavy builds that are underweight on threats and tempo.

**Verdict:** The data is less prescriptive for UW Control than I claimed. The robust findings are: **Time Walk and Ancestral are huge, splashing black is bad, Tamiyo is excellent.** The "avoid" list of premium cards (Counterspell, Brainstorm, Swords) is probably picking up player-tendency selection effects, not telling you the cards are bad. Trust your fundamentals here over the data.

---

## UB Tempo / Psychic Frog (cluster 12, base WR 58.6%)

**Core:** Psychic Frog (42%).

**Flex slots — INCLUDE:** Ancestral Recall (+7.0%), Qarsi Revenant (+5.2%), Emperor of Bones (+3.9%), Otawara (+3.9%), Thieving Skydiver (+3.7%), Harvester of Misery (+2.9%), Abhorrent Oculus (+2.6%), Fractured Identity (+2.4%), Cryptic Command (+2.4%), Subtlety (+2.3%), Thirst for Discovery (+2.3%).

**Flex slots — AVOID:**
- **Jace, the Mind Sculptor** (-3.0%) — *genuine trap here.* JTMS-Tempo decks correlate with Brazen Borrower (+9%), Zagoth Triome (+9%), Sol Ring (+8%) — slower, splashier builds. JTMS is a control card; Tempo wants threats with immediate impact, not 4-mana planeswalkers that need to survive.
- **Hullbreacher** (-3.5%) — *genuine trap here.* Stax piece that competes with Psychic Frog for the 2-mana slot. Frog is just the better card in tempo.
- **Dig Through Time** (-2.9%), **Library of Alexandria** (-2.6%), **Enduring Curiosity** (-2.7%), **Consider** (-2.8%) — *sub-archetype markers* for value-engine / control-leaning UB. Tempo doesn't want to set up; it wants to attack.
- **Blazemire Verge** (-6.8%) — splashing red.
- **Collective Brutality** (-2.7%) — *probably genuine trap.* 2-mana sorcery-speed reactive spell isn't tempo's speed.

**Verdict:** UB Tempo is genuinely sensitive to "do I include this or not" choices. The deck wants creatures + cheap interaction, not value engines or planeswalkers.

---

## UR Spells (cluster 6, base WR 58.6%)

**Core:** No card breaks 40%.

**Flex slots — INCLUDE:** Time Walk (+6.6%), Dack Fayden (+4.5%), Comet Stellar Pup (+4.0%), Aether Spellbomb (+4.0%), Mox Sapphire (+3.9%), Counterspell (+3.5%), Mox Diamond (+3.5%), Force of Will (+3.5%), Broadside Bombardiers (+3.4%), Dismember (+3.1%), Miscalculation (+3.1%), Subtlety (+3.0%).

(Notably: Counterspell IS a positive include here, even though it's negative in UW Control. Different decks, different roles.)

**Flex slots — AVOID:**
- **Goben** (-5.6%), **Skullclamp** (-4.7%), **Goldspan Dragon** (-4.3%) — *genuine traps.* Don't fit the spell-focused plan.
- **Sleight of Hand** (-3.6%) — *uncertain selection effect.* Cantrips themselves should be fine in a spells deck; the negative may be picking up the same pattern as Storm where Sleight-of-Hand-includers are over-cantripping at the cost of impactful spells.
- **Polluted Delta** (-3.5%) — *sub-archetype marker.* Splashing black.
- **Grim Lavamancer** (-3.3%), **Burst Lightning** (-3.3%), **Thundertrap Trainer** (-3.3%) — *genuine traps* in this version.

**Verdict:** UR Spells wants impactful spells (Dack, Comet, Iteration, Counterspell) and the best fast mana, not piles of cantrips. Stay UR; don't splash black.

---

## UR Artifacts / Urza (cluster 0, base WR 57.0%)

**Core:** Tolarian Academy (62%), Urza (44%), Mox Opal (42%), Retrofitter Foundry (42%), Kappa Cannoneer (41%), Pinnacle Emissary (40%).

**Flex slots — INCLUDE:** Sol Ring (+6.8%), Tezzeret Cruel Captain (+5.0%), Mox Emerald (+4.9%), Candelabra of Tawnos (+4.8%), Mox Sapphire (+4.8%), Lotus Petal (+4.7%), Ugin Eye of the Storms (+4.1%), Timetwister (+3.7%), Urza's Saga (+3.4%).

**Flex slots — AVOID:**
- **Mishra's Bauble** (-2.9%) — *sub-archetype marker.* Bauble-decks correlate with Chromatic Star (+11%), Brainstorm (+7%) — that's a **cantrip-heavy "draw cards" build** that doesn't generate enough mana or pressure. The card itself is fine in dedicated artifact decks, but in this cluster it's a marker for the lower-impact build.
- **Broadside Bombardiers** (-5.0%), **Talisman of Conviction** (-3.3%), **Talisman of Impulse** (-2.1%) — *sub-archetype markers* for the splashier 3-color version.
- **Expressive Iteration** (-2.3%) — *sub-archetype marker.* Belongs in UR Spells.
- **Chromatic Star** (-2.1%), **Riverpyre Verge** (-2.3%), **Scalding Tarn** (-3.1%) — *sub-archetype markers* for fixing-heavy builds.

**Verdict:** UR Artifacts wants tight UR (or mono-U with red splash for finishers), maximum fast mana, big artifact threats. The avoid list is mostly markers of decks that wandered into being other archetypes.

---

## UW(x) Tinker / Big Artifact (cluster 17, base WR 56.4%)

**Core:** Tinker (41%).

**Flex slots — INCLUDE:** Staff of the Storyteller (+6.6%), Phyrexian Metamorph (+5.5%), Tolarian Academy (+5.4%), Mana Drain (+5.1%), Retrofitter Foundry (+5.0%), No More Lies (+4.5%), Marsh Flats (+4.3%), Sol Ring (+4.3%), Soul-Guide Lantern (+4.2%), Urza's Saga (+4.2%), Chromatic Star (+4.1%), Golos Tireless Pilgrim (+4.1%).

**Flex slots — AVOID:**
- **Urza, Lord High Artificer** (-3.2%) — *clear sub-archetype marker.* Urza-Tinker decks correlate with Talisman of Creativity (+7%), Hullbreacher (+7%), Counterspell (+6%), Library of Alexandria (+6%), Path to Exile (+5%) — that's a **UW Tinker deck trying to be UR Artifacts at the same time**. Urza wants tons of artifacts to tap; Tinker wants Portal to Phyrexia. Different game plans, same color base. Including Urza implies you're doing both poorly.
- **Talisman of Hierarchy** (-9.5%) — *clear sub-archetype marker.* WB-fixing in a UW deck.
- **The Mightstone and Weakstone** (-4.3%), **Coalition Relic** (-3.5%), **Sundering Titan** (-2.9%), **Memory Jar** (-2.9%) — *genuine traps.* Slow artifact threats that don't enable Tinker or finish the game.
- **Talisman of Indulgence** (-3.8%), **Talisman of Unity** (-2.8%) — *sub-archetype markers* for splashing.

**Verdict:** UW Tinker has clear lanes: Tinker + Portal + counter magic + acceleration. Don't try to also be UR Artifacts (drop Urza), don't splash black/green for talismans.

---

## UB Reanimator (cluster 2, base WR 58.1%)

**Core:** Entomb (52%), Archon of Cruelty (46%), Animate Dead (45%), Reanimate (44%), Necromancy (42%).

**Flex slots — INCLUDE:** Watery Grave (+5.2%), Library of Alexandria (+4.4%), Psychic Frog (+4.4%), Force of Will (+4.2%), Ertai Resurrected (+4.1%), Force of Negation (+4.1%), Quantum Riddler (+4.0%), Qarsi Revenant (+3.7%), Polluted Delta (+3.4%), Grave Titan (+3.3%), Otawara (+3.1%), Mystic Confluence (+3.1%).

**Flex slots — AVOID:**
- **Souls of the Lost** (-6.5%) — *genuine trap with clear deckbuilding signal.* Souls-decks correlate with Persist (+19%), Triplicate Titan (+13%), Torsten (+9%), Damn (+9%), Restless Fortress (+7%) — that's a **slow, value-engine reanimator build with too many redundant threats**. Souls is a 4-mana 3/3 with discard-when-it-dies — it's a discard outlet that competes for slots with better discard outlets and doesn't add to the win condition.
- **Mind Twist** (-5.5%), **Sheoldred's Edict** (-3.5%) — *probably genuine traps.* Slow disruption when the deck wants tempo.
- **Woodfall Primus** (-5.3%), **Torsten** (-3.3%) — *sub-archetype markers* for "include any big creature as a target" builds. Reanimator wants Archon and Atraxa specifically.
- **Thirst for Discovery** (-3.8%) — *probably genuine trap.* 3-mana sorcery that doesn't help vs aggro.
- **Murderous Cut** (-3.2%) — *genuine trap.* Conflict with the graveyard plan (delve).

**Verdict:** UB Reanimator wants to be a **UB Control deck with a reanimation kill**. Counter magic + value creatures + the right targets. Don't add weak fatties or weak black disruption.

---

## BR(x) Reanimator / Etali shell (cluster 7, base WR 59.5%)

**Core:** Necromancy (47%), Bloodtithe Harvester (45%), Archon of Cruelty (44%), Animate Dead (43%), Entomb (41%), Reanimate (41%).

**Flex slots — INCLUDE:** Archon (+6.2%), Barrowgoyf (+4.6%), Inti (+4.5%), Crabomination (+3.7%), Fury (+3.4%), Bloodtithe Harvester (+3.1%), Ragavan (+3.0%), Atraxa (+3.0%), Bloodstained Mire (+2.8%), Animate Dead (+2.6%), Unholy Heat (+2.6%), Broadside Bombardiers (+2.4%).

**Flex slots — AVOID:**
- **Torsten** (-6.5%) — *genuine trap.* Same finding as elsewhere.
- **Virtue of Persistence** (-5.7%) — *genuine trap.* Slow value enchantment.
- **Flash** (-5.1%) — *sub-archetype marker.* Flash is an enabler from a different archetype; including it here means you're trying to do both Sneak/Show AND BR Reanimator, and neither well.
- **Scalding Tarn** (-4.9%) — *sub-archetype marker.* Splashing blue.
- **Tersa Lightshatter** (-3.6%), **Currency Converter** (-3.5%), **Gut True Soul Zealot** (-3.4%) — *sub-archetype markers* for aggro-leaning Rakdos builds.
- **Grave Titan** (-3.1%) — interesting *role mismatch.* Same card is +3.3% in UB Reanimator. BR Reanimator is faster, with Etali / Bloodtithe as alternative threats; Grave Titan is too slow for the BR speed band.

**Verdict:** BR Reanimator is faster than UB. Stay 2-color, focus on Archon, and don't try to also be Sneak & Show.

---

## Sneak & Show / Flash (cluster 10, base WR 56.7%)

**Core:** Flash (73%), Sneak Attack (49%), Torsten (46% — interesting; signature card but mediocre), Worldspine Wurm (44%).

**Flex slots — INCLUDE:** Verdant Catacombs (+6.8%), Ancestral Recall (+6.4%), Mana Leak (+6.2%), Remand (+5.4%), Watery Grave (+5.2%), Atraxa (+4.9%), Mana Drain (+4.8%), Spell Pierce (+4.7%), Sleight of Hand (+4.5%), Marsh Flats (+4.1%), Consult the Star Charts (+4.1%).

**Flex slots — AVOID:**
- **Life // Death** (-6.8%) — *sub-archetype marker.* Belongs in BR Reanimator. Including it means you're confused about which deck you're building.
- **Wheel of Fortune** (-6.1%) — *genuine trap.* Refilling both players' hands favors Boros.
- **Inquisition of Kozilek** (-5.2%), **Frantic Search** (-5.2%), **Xander's Lounge** (-4.8%) — *sub-archetype markers* for the BR Reanimator hybrid.
- **Pentad Prism** (-4.6%), **Taiga** (-4.5%) — *sub-archetype markers* for green-splash builds.
- **Griselbrand** (-4.1%) — *genuine trap.* The format-wide finding that Griselbrand underperforms Atraxa/Archon as a cheat target.

**Verdict:** Sneak & Show wants to be a **focused UB-or-Bant tempo-control deck** with the Flash/Sneak win condition, plus counter magic to protect it. Atraxa is the right target. Don't dilute with BR Reanimator pieces.

---

## Storm / Underworld Breach (cluster 11, base WR 55.1%)

**Core:** Brain Freeze (70%), Underworld Breach (70%), Lion's Eye Diamond (60%).

**Flex slots — INCLUDE:** Black Lotus (+9.0%), Brain Freeze (+8.8%), Ancestral Recall (+7.0%), Flame Slash (+6.0%), Sink into Stupor (+5.4%), Unholy Heat (+4.8%), Thundering Falls (+4.7%), Consult the Star Charts (+4.6%), Remand (+4.3%), Hullbreacher (+4.1%), Stock Up (+3.9%).

**Flex slots — AVOID:**
- **Sleight of Hand** (-4.9%) — *sub-archetype marker with strong evidence.* Sleight-Storm decks correlate with Consider (+10%), Mystical Tutor (+8%), Multiversal Passage (+8%), Frantic Search (+8%), Thirst for Discovery (+8%), Goben (+6%) — that's a **cantrip-heavy "dig for combo" build that's UB-leaning** (Multiversal Passage, Thirst for Discovery, Goben). The deck pattern is "spend mana on cantrips → eventually find Breach → win." The pattern that wins instead is "spend mana on interaction → survive → assemble engine → win." The card itself isn't bad; the strategy of over-cantripping is.
- **Mox Opal** (-5.5%) — *sub-archetype marker* for artifact-base mana.
- **Talisman of Indulgence** (-5.2%), **Blackcleave Cliffs** (-6.7%), **Fire Covenant** (-5.2%), **Wooded Foothills** (-4.7%), **Blazemire Verge** (-4.4%) — *sub-archetype markers* for splashing black to play Tendrils. The well-built Storm is mono-U or UR.
- **Timetwister** (-4.5%) — *probably genuine trap here.* Symmetric refill helps Boros.

**Verdict:** Well-built Storm is leaner than people build it. Mono-U or UR. Interaction over cantrips. Engine + restart spells (Wheel, Echo of Eons, Memory Jar) over cantrips. **Don't splash black for Tendrils.**

---

## Sultai/Bant Oko-Uro Midrange (cluster 9, base WR 57.4%)

**Core:** No card above 40%.

**Flex slots — INCLUDE:** Ancestral Recall (+5.1%), Shifting Woodland (+5.0%), Time Walk (+4.3%), Savannah (+4.3%), Oko (+4.0%), Noble Hierarch (+3.6%), Misty Rainforest (+3.6%), Otawara (+3.5%), Dismember (+3.5%), Hushwood Verge (+3.4%), Jace the Mind Sculptor (+3.4%), Esika's Chariot (+3.3%).

**Flex slots — AVOID:**
- **Fastbond** (-5.0%) — *sub-archetype marker.* Belongs in Lands.
- **Arid Mesa** (-4.6%), **Stomping Ground** (-3.7%), **Taiga** (-3.2%), **Spara's Headquarters** (-3.0%), **Flooded Strand** (-2.7%), **Thundering Falls** (-3.7%) — *sub-archetype markers* for greedy 4-color or wrong-color combinations. Stay GU/BG/UB; don't splash red.
- **Malcolm Alluring Scoundrel** (-3.3%) — *probably genuine trap*; doesn't fit the planeswalker-value plan.

**Verdict:** Stay 2-3 colors with green base. Avoid red splash. Oko + counter magic + planeswalkers + value creatures.

---

## Lands / Ramunap (cluster 15, base WR 57.8%)

**Core:** Titania (44%).

**Flex slots — INCLUDE:** Ketria Triome (+5.1%), Loot the Pathfinder (+4.4%), Restless Vinestalk (+4.2%), Mox Emerald (+4.1%), Malevolent Rumble (+4.1%), Ancestral Recall (+3.9%), Lush Portico (+3.9%), Nadu (+3.7%), Tropical Island (+3.6%), Oko (+3.5%), Birds of Paradise (+3.4%), Prismatic Vista (+3.2%).

**Flex slots — AVOID — most of these turned out to be sub-archetype markers, not bad cards:**
- **Misty Rainforest** (-3.1%) — *sub-archetype marker, not a bad card.* Misty-Lands correlates with Scythecat Cub (+12%), Island (+10%), Nadu (+6%), Bristly Bill (+7%), JTMS (+6%) — that's the **UG/Bant tempo-Lands variant**. Not all fetches are negative — Bloodstained Mire (+2.8%), Marsh Flats (+2.4%), Wooded Foothills (+1.5%), Verdant Catacombs (+1.3%) all positive. The data is telling you: **the BG/RG-leaning version of Lands wins more than the UG version.** Misty isn't bad; the UG-Lands archetype underperforms in this format.
- **Scalding Tarn** (-2.3%) — *similar.* Correlates with Mountain (+21%), Titania (+14%), Breeding Pool (+13%), Ketria Triome (+13%) — a **4+ color splashy Lands deck**. Stretching to 4 colors is the problem.
- **Channel** (-5.4%) — *genuine trap.* Channel belongs in dedicated Channel deck, not Lands.
- **Worldspine Wurm** (-3.4%), **Vaultborn Tyrant** (-2.8%), **Woodfall Primus** (-4.3%) — *genuine traps.* Big creature finishers in a tempo-deck — too slow.
- **Zagoth Triome** (-4.4%) — *sub-archetype marker* for greedy mana bases.
- **Explore** (-3.6%), **Shifting Woodland** (-2.4%) — *probably genuine traps.* Slow ramp pieces.

**Verdict:** **The data is NOT saying "don't include fetches in Lands."** It's saying the UG-Lands and 4-color-Lands variants underperform. If you're building BG/RG/G-with-WG-splash Lands, the right fetches are positive. The format's Lands deck wants to be tempo (Loot, Birds, Nadu, planeswalkers) more than slow ramp (Worldspine Wurm, Channel, Explore).

---

## Golgari/Sultai Grist (cluster 13, base WR 56.5%)

**Core:** No card above 40%.

**Flex slots — INCLUDE:** Fastbond (+6.1%), Sheoldred's Edict (+5.2%), Demonic Tutor (+5.0%), Fanatic of Rhonas (+4.9%), Wight of the Reliquary (+4.9%), Underground Sea (+4.6%), Bloodstained Mire (+4.4%), Thoughtseize (+4.1%), Vampiric Tutor (+4.0%), Bayou (+4.0%), Green Sun's Zenith (+3.7%), Deep-Cavern Bat (+3.7%).

**Flex slots — AVOID:**
- **Multiversal Passage** (-7.6%), **Indatha Triome** (-4.3%) — *sub-archetype markers* for 4-color piles.
- **Tireless Tracker** (-5.2%), **Sentinel of the Nameless City** (-4.0%), **Sowing Mycospawn** (-4.0%), **Virtue of Persistence** (-3.6%), **Birds of Paradise** (-3.5%), **Takenuma** (-4.2%) — *probably sub-archetype markers* for slow value-creature builds. Grist wants tight BG with discard, removal, and tutors.

**Verdict:** Stay 2-color BG. Discard + removal + tutors. Don't drift into ramp/value-creature land.

---

## Cross-archetype patterns (revised)

After the deeper analysis, here are the patterns I'm most confident in:

1. **The format penalizes greedy mana bases.** Across nearly every archetype, splashing for a 3rd or 4th color shows up as a sub-archetype marker for losing decks. Stay 2-color when you can; splash carefully when you can't.

2. **Aggressive decks should not include premium 4-mana threats.** Goldspan Dragon, Glorybringer, Bonecrusher Giant, Voice of Victory, Chandra TOD — all show up as avoid-tier in aggressive shells. Top out at 3 mana.

3. **Combo / control decks need MORE interaction than people are running.** Storm wants Flame Slash and Unholy Heat. Sneak & Show wants Mana Leak and Spell Pierce. Reanimator wants Force of Will and Mystic Confluence. The Boros-dominated meta squeezes glass-cannon decks; combo decks with interaction packages do much better.

4. **Same card, archetype-specific value.** Counterspell is +3.5% in UR Spells, -2.2% in UW Control. Jitte is +3.1% in Boros Goodstuff, -4.4% in Orzhov. Grave Titan is +3.3% in UB Reanimator, -3.1% in BR Reanimator. **Stop first-picking generically-strong cards without an archetype plan.**

5. **Avoid lists are often archetype-confusion signals.** Cori-Steel in Boros Aggro-Mid means you're trying to be Mono-R. Urza in UW Tinker means you're trying to be UR Artifacts. Life//Death in Sneak/Show means you're trying to be BR Reanimator. The data is telling you to commit.

6. **Souls of the Lost is a recurring trap in reanimator shells.** It looks like a synergy card; it isn't.

7. **Torsten, Founder of Benalia is a recurring trap in reanimation/cheat shells** (-3.3% in UB Reanimator, -6.5% in BR Reanimator, -3.3% in BR Reanimator). It rewards you for *finding* creatures and lands, but you usually want spells (interaction) more than the next creature.

8. **Honest uncertainty:** For UW Control specifically, the avoid list (Counterspell, Brainstorm, Swords to Plowshares) is probably picking up player-tendency selection effects rather than telling you the cards are bad. The format's UW Control optimum may not be radically different from other formats; the data is just noisier in that cluster.

**Things to be skeptical about when reading this guide:**

- **Single-card uplift numbers below ±3% should be taken loosely.** Many of these will not replicate with more data.
- **"AVOID" cards that show up in only one cluster** are weaker signals than ones that appear consistently across related archetypes.
- **The data fundamentally cannot distinguish "card is bad" from "card-includers are also doing other things wrong."** When the includers' build pattern is identifiable and coherent (Misty → UG-Lands, Sleight of Hand → cantrip-Storm, Souls of the Lost → over-stuffed reanimator), I've called it a sub-archetype marker. When it isn't (Counterspell in UW Control), I'm honest about not knowing.
