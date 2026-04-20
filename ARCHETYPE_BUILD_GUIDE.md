# Powered Cube — Per-Archetype Build Criteria

For each of the 20 archetype clusters, what cards distinguish a winning build from a losing one? Computed from within-cluster WR uplift: among decks already classified as this archetype, which cards are most/least correlated with winning?

**Methodology.** For each cluster, looked at every card played in 10-85% of cluster decks (the meaningful inclusion range — above 85% is signature/auto-include, below 10% is too rare to evaluate). Computed WR of decks that include the card vs. decks that don't, both within-cluster. Cards at the top of the uplift list are the ones that mark a properly-built deck. Cards at the bottom are the ones whose presence indicates the deck is built wrong.

**Important caveats:**

- These are *within-cluster* signals. The cluster assignment was already made based on the deck's overall card composition, so the "include" cards aren't the deck's signature cards (those are always included) — they're the *configurable* slots that distinguish well-built from poorly-built versions.
- A card showing up as "AVOID" doesn't mean the card is bad in general. It means: among decks that look like this archetype, decks that include this card win less. The card may belong in a different archetype entirely.
- Some "avoid" entries are likely **archetype confusion signals** — the card belongs in a sibling deck, and including it in this deck means the player is straddling archetypes incoherently.
- Sample sizes for niche signals may be ~150-300 decks. Treat single uplift numbers as approximate; treat overall patterns within an archetype as more reliable.

---

## Boros Aggro-Midrange (cluster 1, base WR 68.3%)

The format's best deck. Even at the tier list's top, there are configuration choices that matter.

**Include:** Phlage (+3.4%), Mox Ruby (+3.9% if you have it), Path to Exile (+2.4%), Gut, True Soul Zealot (+2.4%), Plateau (+2.2%), Ajani Nacatl Pariah (+2.2%), Mine Collapse (+2.1%), Makdee and Itla (+2.0%), Guide of Souls (+1.9%), Karakas (+1.9%), Virtue of Loyalty (+2.7%), Fear of Missing Out (+1.8%)

**Avoid:** Enduring Innocence (-3.2%), Flame Slash (-3.1%), Hellrider (-2.7%), Ademi of the Silkchutes (-2.6%), Cori-Steel Cutter (-2.6%), Intrepid Adversary (-2.5%), Fury (-2.3%), Burst Lightning (-2.2%)

**What this is telling you.** The well-built version is the **midrange version** with planeswalkers, removal, and Phlage. The "avoid" list is dominated by **aggressive cards that belong in the Mono-R / Boros Aggro shell instead**: Cori-Steel Cutter, Hellrider, Burst Lightning, Intrepid Adversary, and Fury are all Mono-R aggro staples. **The data is telling you not to mix aggressive R-side cards into the midrange version.** If you have Phlage + Ajani + Adeline, lean into the controlling shell — don't try to also be a fast aggro deck.

---

## Boros Skies / Showdown (cluster 4, base WR 66.5%)

The other dominant Boros variant. Wants different supporting cards than Boros Aggro-Midrange.

**Include:** Mox Pearl (+5.5% if available), Mox Ruby (+3.2%), Ajani Nacatl Pariah (+3.2%), Goblin Bombardment (+3.0%), Fable of the Mirror-Breaker (+2.7%), Death-Greeter's Champion (+2.6%), Flame Slash (+2.5%), Comet Stellar Pup (+2.4%), Parallax Wave (+2.3%), Laelia (+2.3%), Ocelot Pride (+2.3%), Swords to Plowshares (+2.1%)

**Avoid:** Yera and Oski, Weaver and Guide (-5.3%), Mana Tithe (-3.9%), Virtue of Loyalty (-3.5%), Splitskin Doll (-2.7%), Unholy Heat (-2.6%), Grim Lavamancer (-2.3%), Skullclamp (-2.2%), Galvanic Discharge (-2.2%)

**Notable:** Flame Slash is +2.5% in Skies but -3.1% in Boros Aggro-Mid. Same card, different role. In Skies it's removal that clears fliers' blockers; in Aggro-Mid it's redundant with better burn options. This is a reminder that "is this card good in Boros" depends on which Boros.

---

## Boros Goodstuff / Solitude variant (cluster 19, base WR 63.3%)

The third Boros variant — the "play the best evasive whites + reactive cards" build, less aggressive than Aggro-Mid.

**Include:** Ragavan (+3.6%), Fury (+3.5%), Mox Pearl (+3.5%), Umezawa's Jitte (+3.1%), Lightning Bolt (+3.0%), Chrome Mox (+2.8%), Flickerwisp (+2.5%), Parallax Wave (+2.4%), Swords to Plowshares (+2.3%), Lightstall Inquisitor (+2.1%), Chandra Torch of Defiance (+2.0%), Abrade (+2.0%)

**Avoid:** Fear of Missing Out (-3.8%), Splitskin Doll (-3.1%), Unholy Heat (-3.0%), The Wandering Emperor (-3.0%), Descendant of Storms (-3.0%), Galvanic Discharge (-2.5%), Robber of the Rich (-2.1%), Portable Hole (-2.0%)

**Reading this:** the Goodstuff build wants **older-format reactive cards** (Fury, Jitte, Bolt, Chrome Mox, Solitude implied). The avoid list is mostly recent-set aggressive 1-drops/2-drops (Robber, Descendant of Storms, Splitskin Doll, Galvanic) — those belong in the more aggressive Boros builds. The lesson: when building this version of Boros, lean into the older premium cards, not the new aggressive ones.

---

## Mono-R / Boros Aggro (cluster 16, base WR 64.4%)

The aggressive R-focused build.

**Include:** Scalding Tarn (+5.1%), Pyrogoyf (+4.2%), Swords to Plowshares (+4.1% — splash white), Laelia (+4.0%), Mox Ruby (+3.9%), Fury (+3.8%), Prismatic Vista (+3.7%), Broadside Bombardiers (+3.3%), Karakas (+3.2%), Unholy Heat (+3.2%), Monastery Swiftspear (+3.1%), Arena of Glory (+2.9%)

**Avoid:** Goldspan Dragon (-4.4%), Voice of Victory (-3.4%), Ademi of the Silkchutes (-3.1%), Glorybringer (-2.8%), Galvanic Discharge (-2.4%), Kari Zev (-2.2%), Bonecrusher Giant (-2.2%), Abrade (-2.0%)

**Counterintuitive findings:** **Goldspan Dragon, Glorybringer, Bonecrusher Giant, and Kari Zev are ALL avoid-tier here** despite being premium red cards. The pattern: these are 4-mana threats. Aggro Boros wants to be killing the opponent on turn 4-5, not casting a 4-mana creature for the first time. **Top-end red threats are the trap in red aggro decks.** The deck wants to cap out at 3 mana with burn for the kill. Voice of Victory is white but same issue — costs too much.

This is a real and important lesson — aggro decks consistently mis-include "good" 4-drops because players see them as "premium cards." Splash white for Swords to Plowshares is +4.1%, but adding 4-cost finishers is -2 to -4%.

---

## Mono-W / Bant Aggro (cluster 18, base WR 64.4%)

The dedicated white aggro shell.

**Include:** Lightstall Inquisitor (+4.2%), Mox Sapphire (+4.0% — implies Bant splash), Arid Mesa (+3.8%), Phelia, Exuberant Shepherd (+2.9%), Winds of Abandon (+2.9%), Serra Paragon (+2.8%), Elspeth Storm Slayer (+2.6%), Guide of Souls (+2.5%), Solitude (+2.2%), Touch the Spirit Realm (+2.0%), Blade Splicer (+2.0%), Smuggler's Copter (+1.9%)

**Avoid:** Plateau (-4.5%), Sunbillow Verge (-3.6%), Sacred Foundry (-3.2%), Path to Exile (-2.6%), Yera and Oski (-2.4%), Gut, True Soul Zealot (-2.4%), Witch Enchanter (-2.3%), The Wandering Emperor (-1.8%)

**Reading this:** **Splashing red kills the deck.** Plateau / Sunbillow Verge / Sacred Foundry are all R/W lands and they're trap-tier. The Mono-W build that wins is mono-W or W-with-blue-splash (Mox Sapphire +4.0%, Arid Mesa +3.8%). The minute you start adding R duals, your deck stops being efficient mono-W and starts being a worse Boros deck. Yera and Oski (a UW card) being -2.4% suggests even blue splash should be sparing; the deck wants to be tight and aggressive.

---

## Rakdos Midrange (cluster 3, base WR 62.6%)

The BR midrange/aggro shell.

**Include:** Black Lotus (+5.7% if available), Pyrogoyf (+4.2%), Cori-Steel Cutter (+3.8%), Screaming Nemesis (+3.7%), Mana Crypt (+3.7%), Restless Vents (+3.6%), Ivora, Insatiable Heir (+3.5%), Takenuma (+3.3%), Detective's Phoenix (+3.3%), Inti, Seneschal of the Sun (+3.1%), Murderous Cut (+3.0%), Dragon's Rage Channeler (+2.8%)

**Avoid:** Bitter Triumph (-2.7%), Duress (-2.4%), Savai Triome (-2.3%), Elegy Acolyte (-2.2%), Mine Collapse (-2.2%), Minsc & Boo, Timeless Heroes (-2.1%), Gut, True Soul Zealot (-2.1%), Voldaren Epicure (-1.9%)

**Notable:** **Duress, Bitter Triumph, and Elegy Acolyte all underperform** — these are slow black cards. Rakdos Midrange wants the aggressive overlap of red (Cori-Steel, Pyrogoyf, Phoenix, DRC) plus efficient black removal (Murderous Cut), not the reactive black tools. The Minsc & Boo penalty (-2.1%) is weird and worth noting — it's a strong card in Gruul/Jund (where it's a +3% inclusion) but in pure Rakdos it pulls you toward the wrong game plan.

---

## Gruul/Jund Midrange (cluster 5, base WR 60.6%)

**Include:** Ketria Triome (+5.3%), Sol Ring (+5.0%), Screaming Nemesis (+5.0%), Smuggler's Copter (+4.7%), Chain Lightning (+3.9%), Lightning Bolt (+3.4%), Arena of Glory (+3.2%), Tersa Lightshatter (+3.2%), Wrenn and Six (+3.1%), Strip Mine (+3.1%), Fiery Confluence (+3.0%), Goblin Rabblemaster (+3.0%)

**Avoid:** Chandra Torch of Defiance (-3.9%), Elder Gargaroth (-3.3%), Avacyn's Pilgrim (-3.3%), Prismatic Vista (-2.8%), Savannah (-2.8%), Icetill Explorer (-2.7%), Omnath Locus of Creation (-2.7%), Nadu (-2.6%)

**Reading this:** the well-built version is **aggro-leaning Gruul/Jund** — Lightning Bolt, Chain Lightning, Smuggler's Copter, Goblin Rabblemaster. The avoid list is full of value-creature/ramp pieces (Avacyn's Pilgrim, Elder Gargaroth, Omnath, Nadu) — these belong in Green Ramp / Lands cluster decks. **Chandra Torch of Defiance being -3.9% is striking** — a 4-cost planeswalker is too slow even in this midrange shell. The format is fast enough that Gruul wants to be a creature deck with reach, not a control-leaning planeswalker shell.

---

## Orzhov/Abzan Midrange (cluster 14, base WR 60.4%)

**Include:** Serra Paragon (+5.5%), Preacher of the Schism (+5.2%), Portable Hole (+5.1%), Mox Emerald (+5.0%), Guide of Souls (+4.9%), Barrowgoyf (+4.6%), Thraben Inspector (+4.6%), Mox Jet (+4.5%), Go for the Throat (+4.3%), Elspeth Storm Slayer (+4.3%), Sanguine Evangelist (+3.9%), Karakas (+3.8%)

**Avoid:** Mind Twist (-6.1%), Tundra (-5.2%), Dismember (-4.4%), Umezawa's Jitte (-4.4%), Prismatic Vista (-4.1%), Sorin of House Markov (-4.0%), Library of Alexandria (-3.2%), Fire Covenant (-3.2%)

**Striking observation:** **Umezawa's Jitte is -4.4% in Orzhov.** Same card that's +3.1% in Boros Goodstuff. Jitte wants tons of cheap creatures to equip; Orzhov Midrange runs more 3-4 mana cards than 1-drops, so Jitte sits in hand. The lesson: **Jitte isn't context-free good — it's only good if your deck has enough early creatures**.

Tundra and Library of Alexandria being trap-tier suggests the **3+ color "Esper-pile" version of Orzhov underperforms vs. the focused 2-color WB version**. Splashing for the powerful blue cards weakens the deck.

---

## UW(x) Control (cluster 8, base WR 60.5%)

**Include:** Time Walk (+7.2% if available), Ancestral Recall (+5.8% if available), Tamiyo Inquisitive Student (+4.3%), Thraben Inspector (+4.0%), Quantum Riddler (+3.6%), Mana Leak (+2.6%), Miscalculation (+2.5%), Malcolm, Alluring Scoundrel (+2.5%), Karakas (+2.5%), Thundertrap Trainer (+2.5%), Ajani Nacatl Pariah (+2.3%), Containment Priest (+2.2%)

**Avoid:** Godless Shrine (-5.9%), Brainstorm (-4.0%), Lingering Souls (-3.3%), Consider (-2.9%), Leyline Binding (-2.7%), Portable Hole (-2.4%), Counterspell (-2.2%), Swords to Plowshares (-2.2%)

**Wait, Counterspell and Swords to Plowshares are AVOID in UW Control??** That's the kind of result that makes me want to dig in. The interpretation isn't "Counterspell is bad" — it's that **decks that include Counterspell in this cluster are doing other things wrong**. The most successful UW Control builds run **Mana Leak / Miscalculation / No More Lies** as their counter package — soft counters that cost less mana. Counterspell at UU is too restrictive in 3-color piles. Swords to Plowshares at -2.2% is similar — the well-built version uses **Tamiyo, Inquisitive Student** for card advantage rather than spot removal at all (they have Wraths). 

Also: **Brainstorm at -4.0%** is wild. Brainstorm + fetchlands is the classic UW Control package. The data is telling you that decks playing Brainstorm here have mana base or library shuffle issues. Could be selection effect (Brainstorm decks are over-greedy with fetchland counts), but it's a flag.

**Splashing black hurts:** Godless Shrine -5.9%, Lingering Souls -3.3%. Stay 2-color or splash blue/red, not WB.

---

## UB Tempo / Psychic Frog (cluster 12, base WR 58.6%)

**Include:** Ancestral Recall (+7.0%), Qarsi Revenant (+5.2%), Emperor of Bones (+3.9%), Otawara Soaring City (+3.9%), Thieving Skydiver (+3.7%), Harvester of Misery (+2.9%), Psychic Frog (+2.8%), Abhorrent Oculus (+2.6%), Fractured Identity (+2.4%), Cryptic Command (+2.4%), Subtlety (+2.3%), Thirst for Discovery (+2.3%)

**Avoid:** Blazemire Verge (-6.8%), Hullbreacher (-3.5%), Jace, the Mind Sculptor (-3.0%), Dig Through Time (-2.9%), Consider (-2.8%), Enduring Curiosity (-2.7%), Collective Brutality (-2.7%), Library of Alexandria (-2.6%)

**Notable findings:** **Jace, the Mind Sculptor is -3.0% in UB Tempo.** Jace is one of the most powerful cards in Magic but in a tempo deck, you don't have time to set up a 4-mana planeswalker that needs to survive. Tempo decks want their threats to attack immediately.

**Hullbreacher at -3.5%** is interesting — Hullbreacher is good in slower blue decks but in Tempo it competes for the 2-mana slot with Psychic Frog (which is the better card here). Tempo decks need creature threats, not stax pieces.

**Dig Through Time at -2.9%** — even instant-speed card draw is too slow when the format wants you tapping out for threats.

The lesson is that UB Tempo is **NOT a value deck** — it's a tempo deck. Don't include the value-engine cards that look like they belong.

---

## UR Spells (cluster 6, base WR 58.6%)

**Include:** Time Walk (+6.6% if available), Dack Fayden (+4.5%), Comet Stellar Pup (+4.0%), Aether Spellbomb (+4.0%), Mox Sapphire (+3.9% if available), Counterspell (+3.5%), Mox Diamond (+3.5%), Force of Will (+3.5% if available), Broadside Bombardiers (+3.4%), Dismember (+3.1%), Miscalculation (+3.1%), Subtlety (+3.0%)

**Avoid:** Goben, Gene-Splice Savant (-5.6%), Skullclamp (-4.7%), Goldspan Dragon (-4.3%), Sleight of Hand (-3.6%), Polluted Delta (-3.5%), Grim Lavamancer (-3.3%), Thundertrap Trainer (-3.3%), Burst Lightning (-3.3%)

**Sleight of Hand at -3.6%** is unexpected — it's a classic blue cantrip. The pattern: UR Spells decks that play Sleight of Hand are typically mis-built versions trying to be like Storm. Real UR Spells leans on Expressive Iteration and Dack Fayden for card advantage, not 1-mana cantrips.

**Polluted Delta at -3.5%** suggests UR Spells decks shouldn't be UB-leaning — stay UR or splash white, not black.

---

## UR Artifacts / Urza (cluster 0, base WR 57.0%)

**Include:** Sol Ring (+6.8%), Tezzeret Cruel Captain (+5.0%), Mox Emerald (+4.9% if available), Candelabra of Tawnos (+4.8%), Mox Sapphire (+4.8%), Tolarian Academy (+4.8%), Lotus Petal (+4.7%), Ugin Eye of the Storms (+4.1%), Mox Opal (+3.7%), Timetwister (+3.7%), Urza Lord High Artificer (+3.6%), Urza's Saga (+3.4%)

**Avoid:** Broadside Bombardiers (-5.0%), Talisman of Conviction (-3.3%), Scalding Tarn (-3.1%), Mishra's Bauble (-2.9%), Expressive Iteration (-2.3%), Riverpyre Verge (-2.3%), Chromatic Star (-2.1%), Talisman of Impulse (-2.1%)

**The pattern is clear:** UR Artifacts wants **fast mana** (Sol Ring, Lotus Petal, Mox Opal/Emerald/Sapphire) — every fast-mana card in the cube is in the include list. The avoid list is **the slower / midrange UR shells** — Expressive Iteration belongs in UR Spells, Talisman of Conviction is too slow for the artifact deck. **Mishra's Bauble at -2.9%** is interesting — looks like an artifact synergy card but doesn't actually accelerate or threaten.

---

## UW(x) Tinker / Big Artifact (cluster 17, base WR 56.4%)

**Include:** Staff of the Storyteller (+6.6%), Phyrexian Metamorph (+5.5%), Tolarian Academy (+5.4%), Mana Drain (+5.1%), Retrofitter Foundry (+5.0%), No More Lies (+4.5%), Marsh Flats (+4.3%), Sol Ring (+4.3%), Soul-Guide Lantern (+4.2%), Urza's Saga (+4.2%), Chromatic Star (+4.1%), Golos Tireless Pilgrim (+4.1%)

**Avoid:** Talisman of Hierarchy (-9.5%), The Mightstone and Weakstone (-4.3%), Talisman of Indulgence (-3.8%), Coalition Relic (-3.5%), Urza Lord High Artificer (-3.2%), Sundering Titan (-2.9%), Memory Jar (-2.9%), Talisman of Unity (-2.8%)

**Wait — Urza, Lord High Artificer is -3.2% in the Tinker cluster?** This is a clean signal of two distinct archetypes that share cards. Urza belongs in cluster 0 (UR Artifacts), not cluster 17 (UW Tinker). When you put Urza in Tinker, you're confusing two archetypes — Urza wants tons of artifacts to tap for mana; Tinker wants Portal to Phyrexia. Different game plans.

**Talisman of Hierarchy at -9.5%** is the most extreme avoid signal in the entire dataset. WB-fixing in a UW deck just doesn't make sense. The pattern of bad talismans (Hierarchy, Indulgence, Unity) shows that **any UW Tinker deck splashing for a third color is a trap**.

The well-built UW Tinker deck has **counter magic backup** (Mana Drain +5.1%, No More Lies +4.5%) — Tinker as a finisher needs to make it to turn 5-6 alive.

---

## UB Reanimator (cluster 2, base WR 58.1%)

**Include:** Watery Grave (+5.2%), Library of Alexandria (+4.4%), Psychic Frog (+4.4%), Force of Will (+4.2%), Ertai Resurrected (+4.1%), Force of Negation (+4.1%), Quantum Riddler (+4.0%), Qarsi Revenant (+3.7%), Polluted Delta (+3.4%), Grave Titan (+3.3%), Otawara (+3.1%), Mystic Confluence (+3.1%)

**Avoid:** Souls of the Lost (-6.5%), Mind Twist (-5.5%), Woodfall Primus (-5.3%), Thirst for Discovery (-3.8%), Sheoldred's Edict (-3.5%), Torsten, Founder of Benalia (-3.3%), Murderous Cut (-3.2%), Darkslick Shores (-2.1%)

**Big picture:** **Reanimator wants counter magic.** Force of Will, Force of Negation, Mystic Confluence all show up as +4% inclusions. This makes sense — your enabler (Entomb) is a sorcery, your threats are uncastable fatties — without counters, the opponent kills you while you set up. The well-built version is more like a UB Control deck with a reanimation kill plan.

**Library of Alexandria at +4.4%** is one of those cards-that-just-belong-in-control shells. The Reanimator decks that include it are properly building.

**Souls of the Lost at -6.5%** is a recurring trap — it's been on every reanimator list as the worst common include. People keep including it because "discard outlet creature" sounds like a synergy piece. It isn't.

---

## BR(x) Reanimator / Etali shell (cluster 7, base WR 59.5%)

**Include:** Archon of Cruelty (+6.2%), Barrowgoyf (+4.6%), Inti Seneschal of the Sun (+4.5%), Crabomination (+3.7%), Fury (+3.4%), Bloodtithe Harvester (+3.1%), Ragavan (+3.0%), Atraxa (+3.0%), Bloodstained Mire (+2.8%), Animate Dead (+2.6%), Unholy Heat (+2.6%), Broadside Bombardiers (+2.4%)

**Avoid:** **Torsten, Founder of Benalia (-6.5%)** — bad in every reanimator shell, BR included; Virtue of Persistence (-5.7%), Flash (-5.1%), Scalding Tarn (-4.9%), Tersa Lightshatter (-3.6%), Currency Converter (-3.5%), Gut, True Soul Zealot (-3.4%), Grave Titan (-3.1%)

**Notable:** **Grave Titan is -3.1% in BR Reanimator** despite being +3.3% in UB Reanimator. The interpretation: BR Reanimator is faster, with Etali / Bloodtithe Harvester as alternative threats. Grave Titan is a 6-mana value threat — too slow for the BR speed band, fine for the slower UB build.

**Flash at -5.1% in BR Reanimator** is interesting — Flash is a legitimate enabler but not in this archetype. The pattern is "stay focused on your archetype's enablers; don't try to do everything."

---

## Sneak & Show / Flash (cluster 10, base WR 56.7%)

**Include:** Verdant Catacombs (+6.8%), Ancestral Recall (+6.4%), Mana Leak (+6.2%), Remand (+5.4%), Watery Grave (+5.2%), Atraxa (+4.9%), Mana Drain (+4.8%), Flash (+4.8%), Spell Pierce (+4.7%), Sleight of Hand (+4.5%), Marsh Flats (+4.1%), Consult the Star Charts (+4.1%)

**Avoid:** Life // Death (-6.8%), Wheel of Fortune (-6.1%), Inquisition of Kozilek (-5.2%), Frantic Search (-5.2%), Xander's Lounge (-4.8%), Pentad Prism (-4.6%), Taiga (-4.5%), Griselbrand (-4.1%)

**Big finding:** **Sneak & Show wants counter magic and selection cantrips**, not just enablers and fatties. The +6 to +5 inclusions are Mana Leak, Remand, Spell Pierce, Mana Drain, Sleight of Hand, Consult the Star Charts. The deck's job isn't just "enabler + fatty" — it's "protect the enabler with counters, find it with cantrips."

**Griselbrand at -4.1%** continues the pattern from the enabler analysis — Griselbrand is mediocre as a Sneak/Show target compared to Atraxa/Archon. Players keep including it because of legacy/vintage Storm associations.

**Wheel of Fortune at -6.1%** — Wheel + Sneak Attack is a popular combo but the data flatly says it's a trap. Refilling your hand also refills opponent's; against the fast Boros decks you can't afford to give them more cards.

---

## Storm / Underworld Breach (cluster 11, base WR 55.1%)

**Include:** Black Lotus (+9.0%), Brain Freeze (+8.8%), Ancestral Recall (+7.0%), Flame Slash (+6.0%), Sink into Stupor (+5.4%), Unholy Heat (+4.8%), Thundering Falls (+4.7%), Consult the Star Charts (+4.6%), Remand (+4.3%), Hullbreacher (+4.1%), Stock Up (+3.9%), Underworld Breach (+3.9%)

**Avoid:** Blackcleave Cliffs (-6.7%), Mox Opal (-5.5%), Talisman of Indulgence (-5.2%), Fire Covenant (-5.2%), Sleight of Hand (-4.9%), Wooded Foothills (-4.7%), Timetwister (-4.5%), Blazemire Verge (-4.4%)

**Surprising findings worth highlighting:**

1. **Storm wants removal**, specifically Flame Slash (+6.0%) and Unholy Heat (+4.8%). The well-built Storm deck includes red removal to clear the board against aggro. Storm without removal dies to Boros before assembling combo. Combine this with Remand (+4.3%), Stock Up (+3.9%), Hullbreacher (+4.1%) — the deck wants to play **interaction**, not just dig and combo.

2. **Mox Opal is -5.5%** — fast mana you'd think Storm wants. The pattern: Mox Opal in Storm signals an artifact-heavy build that doesn't have the right mana base. Storm wants UR mana, not UR-artifact mana.

3. **Sleight of Hand is -4.9%** in Storm. Same as in UR Spells. Either Sleight of Hand is genuinely worse than Ponder/Preordain (which it is, though all are 1-mana cantrips), or Sleight-Storm decks are mis-built versions trying to maximize cantrip count over impactful spells.

4. **Wheel of Fortune isn't on the avoid list** here (compare to Sneak & Show where it's -6.1%). In Storm, refill effects are part of the combo — you wheel after you've committed your hand, then continue. In Sneak & Show, you don't have a need to refill mid-combo.

5. **Splashing black for Tendrils kills you.** Blackcleave Cliffs / Talisman of Indulgence / Fire Covenant / Blazemire Verge — every B/X land or rock is on the avoid list. The well-built Storm is **Mono-U or UR**, not UB or URB.

---

## Sultai/Bant Oko-Uro Midrange (cluster 9, base WR 57.4%)

**Include:** Ancestral Recall (+5.1%), Shifting Woodland (+5.0%), Time Walk (+4.3%), Savannah (+4.3%), Oko Thief of Crowns (+4.0%), Noble Hierarch (+3.6%), Misty Rainforest (+3.6%), Otawara (+3.5%), Dismember (+3.5%), Hushwood Verge (+3.4%), Jace the Mind Sculptor (+3.4%), Esika's Chariot (+3.3%)

**Avoid:** Fastbond (-5.0%), Arid Mesa (-4.6%), Stomping Ground (-3.7%), Thundering Falls (-3.7%), Malcolm Alluring Scoundrel (-3.3%), Taiga (-3.2%), Spara's Headquarters (-3.0%), Flooded Strand (-2.7%)

**Reading this:** **Stay UG/BG/UB; don't splash red.** Stomping Ground / Taiga / Arid Mesa / Spara's Headquarters are all R-fixing; they're avoid-tier. The well-built Bant Oko deck is GU+W with Savannah, Hushwood Verge — not 4-color.

**Fastbond at -5.0%** is interesting — Fastbond is a powerful card that belongs in Lands. Including it in Sultai/Bant Oko means you're trying to be a Lands hybrid, which doesn't work.

**Jace the Mind Sculptor at +3.4%** — JTMS works here because Bant Oko is a slow control-leaning deck that can protect a 4-cost planeswalker. Compare to UB Tempo where JTMS is -3% (too slow).

---

## Lands / Ramunap (cluster 15, base WR 57.8%)

**Include:** Ketria Triome (+5.1%), Loot the Pathfinder (+4.4%), Restless Vinestalk (+4.2%), Mox Emerald (+4.1%), Malevolent Rumble (+4.1%), Ancestral Recall (+3.9%), Lush Portico (+3.9%), Nadu (+3.7%), Tropical Island (+3.6%), Oko (+3.5%), Birds of Paradise (+3.4%), Prismatic Vista (+3.2%)

**Avoid:** Channel (-5.4%), Zagoth Triome (-4.4%), Woodfall Primus (-4.3%), Explore (-3.6%), Worldspine Wurm (-3.4%), Misty Rainforest (-3.1%), Vaultborn Tyrant (-2.8%), Shifting Woodland (-2.4%)

**Lands wants tempo, not Eldrazi/big-spell endgame.** The avoid list (Channel, Worldspine Wurm, Vaultborn Tyrant, Woodfall Primus) is all big-spell finishers. The include list is **mana acceleration + planeswalkers + Nadu**. The well-built Lands deck is Bant tempo with land manipulation, not a green ramp deck.

**Zagoth Triome at -4.4%** suggests black splash is the trap — stay GUW.

---

## Golgari/Sultai Grist (cluster 13, base WR 56.5%)

**Include:** Fastbond (+6.1%), Sheoldred's Edict (+5.2%), Demonic Tutor (+5.0%), Fanatic of Rhonas (+4.9%), Wight of the Reliquary (+4.9%), Underground Sea (+4.6%), Bloodstained Mire (+4.4%), Thoughtseize (+4.1%), Vampiric Tutor (+4.0%), Bayou (+4.0%), Green Sun's Zenith (+3.7%), Deep-Cavern Bat (+3.7%)

**Avoid:** Multiversal Passage (-7.6%), Tireless Tracker (-5.2%), Indatha Triome (-4.3%), Takenuma Abandoned Mire (-4.2%), Sentinel of the Nameless City (-4.0%), Sowing Mycospawn (-4.0%), Virtue of Persistence (-3.6%), Birds of Paradise (-3.5%)

**Reading this:** Grist wants to be a tight BG deck with discard, tutors, and removal. The avoid list (Multiversal Passage, Indatha Triome, Sentinel of the Nameless City, Sowing Mycospawn) is **3+ color piles**. **Birds of Paradise at -3.5%** is interesting — in this archetype the 1-mana mana dorks are slowing you down rather than ramping you. The deck wants efficient interaction, not ramp.

---

## Cross-archetype patterns worth internalizing

A few rules emerged across multiple archetypes:

1. **Stay 2-color when possible.** Almost every archetype's avoid list includes lands/fixers that imply a 3rd-color splash. Tundra in Orzhov, Stomping Ground in Sultai, Plateau in Mono-W, Zagoth Triome in Lands, Multiversal Passage in Grist. **The format penalizes greedy mana bases** more than the public 17Lands data suggested.

2. **Cards have archetype-specific value, even great cards.** Jitte is +3% in Boros Goodstuff but -4% in Orzhov. Jace TMS is +3.4% in Bant Oko but -3% in UB Tempo. Grave Titan is +3.3% in UB Reanimator but -3.1% in BR Reanimator. **The same card can be exactly right or exactly wrong depending on context.** Don't first-pick a generically-strong card without thinking about what deck you're enabling.

3. **The "avoid" cards are often signals of archetype confusion.** Cori-Steel Cutter in Boros Aggro-Mid (-2.6%) is a Mono-R card. Urza in UW Tinker (-3.2%) is a UR Artifacts card. Brainstorm in UW Control (-4.0%) signals over-greedy fetchland counts. The data flags decks that are trying to be two archetypes at once, and they lose.

4. **Most archetypes want more interaction than people are running.** Storm wants Flame Slash and Unholy Heat. Sneak & Show wants Mana Leak and Spell Pierce. Reanimator wants Force of Will and Mystic Confluence. The pattern: in a 65%-WR-Boros meta, **non-Boros decks need extra removal/counters to stabilize before executing their plan.** Glass-cannon combo decks lose to Boros; combo decks with interaction packages win.

5. **Avoid 4-cost finishers in aggro decks.** Goldspan Dragon, Glorybringer, Bonecrusher Giant, Voice of Victory, Chandra Torch of Defiance — all show up as avoid-tier in aggressive shells. Aggressive decks want their curve to top out at 3.

6. **The Eldrazi-as-cheat-target pattern from the enabler analysis recurs here.** Worldspine Wurm is -3.4% in Lands, Vaultborn Tyrant is -2.8% in Lands. Big creatures in slow-grindy decks underperform the format speed.
