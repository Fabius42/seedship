# A first overview of game mechanics and lore

Published: 26.09.2026

## Overview

The game is a galaxy-scale simulation of alien evolution, seen through the eyes of a single, colossal, ancient ship: an artificial mind built long ago by a vanished species, whose purpose is to cultivate life across the galaxy. Life in this galaxy is not limited to carbon-based organisms; it includes electromagnetic patterns, solar plasma convection cells, silicate and metal-melt life, and other exotic forms, all sharing one underlying premise: life is defined by its capture and use of energy, and organisms compete for the energy sources ("wells", name not final) available in their environment.

The player does not manage an empire or fight wars. Instead, the ship travels between star systems, finding worlds with existing life or empty worlds suitable for seeding, and cultivates biospheres by planting lineages of organisms it carries aboard, tending them across vast timescales, and returning later to see what evolved. Some lineages are eventually uplifted toward sapience, becoming client lineages who live aboard the ship, contribute their own capabilities, and develop their own alien cultures.

Mechanically, the game is a mix of simulation (guiding evolution), deck builder (collecting life forms), and text rpg (archeological discovery).

Running beneath this is a mystery plot: something destroyed the ship's makers ("progenitors", name not final). Clues embedded in ancient ruins scattered across the galaxy point to the nature of the threat and what is needed to overcome it. This threat is not a rival army but a passive, patient trap: an ancient, still-active surveillance network built by an older, more powerful civilization to detect and destroy any species that becomes dangerously advanced (answering Fermi's paradox).

## Design Principles

A handful of standing principles shape every system in the game:

- **Legibility over depth.** The underlying simulation can be as continuous or chaotic as it needs to be, but everything the player sees is deliberately coarse: named states ("very hot", "mild"), text forecasts, and tagged categories rather than raw numbers or deep physical models. A simulation the player can't reason about is just noise.
- **Every difference must matter mechanically.** Procedurally varied content that looks different but plays identically is worthless. Two lineages, two cultures, two names should only differ if the difference changes what the player can do or expects.
- **No combat, no empire management.** The game is not a 4X and not a fighting game. Conflicts, including the central threat, are resolved through ecology, diplomacy, consent, and clever use of the sim's rules, never through battles.
- **Organic power, not technological power.** The player's tools are living beings, not machines or weapons. The ship itself is effectively invulnerable and never needs defending; what's at stake are other things - biospheres, lineages, and guardian drones ("watchers").
- **Scarcity from biology and presence, not counters or timers.** Limits on what the player can do come from natural sources - how fast a lineage breeds, how much attention the ship can give, how many watchers exist - rather than from arbitrary resource meters or play-time clocks.

## The Player: The Ship, and the Seeding Loop

The player is the ship itself: a super-old artificial mind, vast and largely undefined in form, that gardens life across the galaxy. It does not command an empire; it tends one. Its "stats" are the lineages it carries and has cultivated, each granting capabilities that let it act in new ways or reach new places.

**Seeding (planting and developing lineages on worlds) is the game's central, recurring activity.** The ship finds a world (empty or already inhabited), chooses which of the lineages currently aboard to plant there, and leaves it to develop. The player commits from whatever residents and brews the ship currently carries. Two related techniques make this meaningful:

- **Directed evolution.** A harsh or unusual world exerts a specific selection pressure. Seeding a hardy lineage on a radiation-soaked moon or a chemically hostile world, then returning after it has adapted, produces a capability that was forged through exposure to the right environment.
- **Transplant uplift.** A lineage that has already partly developed (physically or otherwise) can be moved to a new environment specifically to help it continue growing toward sapience.

After seeding, the ship typically moves on. Time passes normally in the system regardless of whether the ship is present, and progress unfolds on its own. Returning to a system later reveals what has changed: new adaptations, new lineages having forked off, conflicts resolved, or collapse. The ship can also choose to remain in orbit for a very long time (potentially tens of thousands of years) to actively guide events as they happen - called keeping **vigil**. While in vigil, the player makes live decisions on triggered events; once the ship leaves, a **watcher** (see below) governs the system according to loose standing orders instead.

There is no fixed numeric cap on how many worlds (also called "gardens" in this doc) the player can seed at once. Existence is limited mainly by the ship's types of lineages and brews to seed with, not by an arbitrary slot count. However, a system without a watcher left behind is riskier: an unwatched, unprotected garden has a harder time evolving safely than one under some form of supervision.

## Watchers

Watchers are powerful, semi-autonomous space stations that the ship leaves behind in a system when it moves on. They mount to the outside of the ship (taking up no internal deck space) and can be recovered, re-programmed, and upgraded when the ship returns.

Rather than being programmed to handle every possible situation, a watcher is given **loose, vague orders**, and maybe a small number  of specific contingencies for major anticipated problems ("if a large meteor strike is imminent, shield the colony"). Everything else is left to the watcher's own interpretation - which can go right or go wrong. This gap between what the player intended and what the watcher actually does is a deliberate source of surprise: reports may describe a watcher doing exactly the right thing at exactly the right moment, or doing something well-intentioned but badly mistaken. Outcomes are logged and delivered to the ship as reports. The travel times for the reports follow realistic light speed constraints, since watchers cannot communicate instantly across interstellar distances.

More watchers, and better watcher capabilities, are unlocked over time (for example through ruin discoveries). Advanced client civilizations can also be asked to act as informal watchers for a region, watching and tending it on the ship's behalf, though they do so unreliably compared to a true watcher, and have their own motivations.

## The Life Simulation: Energy, Wells, and Worlds

**Energy as the basis of life.** All life, however exotic, is modeled as feeding on some form of energy and competing for it. Rather than continuous energy "gradients," the player-facing model uses **wells**: a handful of named energy sources on a world (sunlight, heat vents, chemical seeps, radiation, tidal flex, magnetospheric activity, and so on), each with a small capacity (typically 1-3 slots) for how many lineages it can support.

**Temperature bands.** Rather than a continuous scale, worlds and locations sit in one of a small number of discrete temperature bands (frozen, cold, mild, hot, molten, and more). The naming is only tentative since it shouldn't follow anthropocentric definitions of what's "normal". Each lineage tolerates a certain range of bands; comfort is about the overlap between a lineage's tolerance and a place's band, not an absolute, single "temperature."

**World features and composition.** Worlds carry descriptive tags for notable habitat features (deep vents, open sea, caves, ice shell, cloud layer, magma seas, and similar) and separately for their material composition (metal-rich, silicate, carbon-rich, ice-rich, radioactive, and so on). Composition affects what materials are available to lineages and civilizations that develop there, and can set a ceiling on what a civilization on that world can eventually build.

**Worlds as anvils.** The central design idea for exploration is that a world's specific mix of wells, hazards, geography, stability, and composition determines what kind of life can be *forged* there. Choosing where to seed a lineage is really choosing what pressures to expose it to - hardiness from a harsh, radioactive world; strangeness and novelty from an isolated, fragmented one; a large stable population from a calm, resource-rich one. "Which world?" becomes "what do I want to grow?"

**Radiation and evolution speed.** Radiation increases mutation rate and therefore the pace of evolution, but it is also hazardous: it can damage or kill lineages that aren't prepared for it. Lineages that evolve under high radiation tend to develop radiation resistance as a consequence (if they don't die first).

**Map scale and density.** Rather than a huge number of largely meaningless planets, the galaxy is modeled as a fairly small number of systems overall - on the order of about a hundred across the whole map - that can all be freely visited. Some contain pre-existing life or ruins; others are empty and available for seeding. This keeps the map dense with meaningful content while preserving a sense of galactic scale and realism (life is not packed absurdly close together).

## Lineages and Evolution

**Lineages, not species.** The tracked unit of life is the **lineage**: a whole radiation of related organisms making a living the same way, rather than any single species. This is why a biosphere is represented by a handful of lineages rather than hundreds of individually tracked species, without breaking realism - each lineage implicitly stands for many underlying forms.

**Roles.** Every lineage fills a role in its well: **producer, consumer, decomposer,** or **storer** (dormant, refuge-forming, resistant to crashes). In addition, some lineages take on **attachments** (naming not final) that don't consume their own capacity: **parasite** (taps a host, destabilizing and driving diversification), **symbiont** (pairs with a host to grant it a capability), **engineer** (reshapes the wells or bands of its environment), and **disperser** (links isolated populations together). The exact roles and potentially attachments are still to be finalized.

**Macroscopic cutoff and colonies.** Lineages are only tracked once they form a coherent, individually meaningful body - something that could be pointed at and selected. Colony organisms (reefs, mycelial networks, hive structures) count once the collective as a whole is large and coherent enough, even if individual members are tiny. Below this threshold, life is handled abstractly through **brews** (below), not as tracked lineages.

**Brews.** Sub-macroscopic, foundational life is represented by **brews**: an effectively unlimited supply of starter organisms that make a sterile well habitable for one fundamental order of life (broadly grouped by medium and energy source - water-based, exotic-solvent, silicate/melt-based, plasma-based, and so on). Brews are how the ship "vaccinates" a sterile world before anything macroscopic can take hold there. The exact catalog and naming of these fundamental orders is still being worked out.

**Forking.** A lineage splits into two only at significant, player-legible events (isolation, a newly opened niche, a major environmental shift), not continuously. When a lineage forks, the original branch keeps its existing name; the newly split-off branch is automatically given a new name reflecting its new traits.

**The Steps ladder.** Each lineage's physical development is shown at a glance as a short ladder of major steps. The first step represents simply having a coherent body capable of entering the game; the last step is **sapience**, after which physical evolution stops (see "Sapience and Culture" below). The steps in between are still being defined (maybe containing a "Proto-Culture" step just before sapience).

## The Ship

The ship is colossal - tens of kilometers or more in scale - and its exterior form is deliberately left undefined for now; it may or may not ever be shown visually. Lore-wise, it is understood to be a ramscoop design with strong forward shielding, which also explains why it is confined to the galaxy: there is effectively nothing to scoop between galaxies. Gravity aboard is not treated as a defined game mechanic and doesn't need explanation in the lore.

**Decks.** The ship's interior is organized into decks, each defined by the habitat it provides (a band plus a well) rather than by which specific lineage occupies it - any lineage that fits the deck's habitat can live there. Each deck has a small capacity measured in **pips** (naming not final). A small lineage costs 1 pip, a regular one costs 2, and a huge one costs 3 (a larger deck type for truly gigantic life forms may be introduced later). There is no food-chain simulation within a deck and no forking aboard the ship - a lineage simply draws what it needs from its deck. Ship progression comes from adding more decks and supporting more band/well combinations, which is what allows the ship to carry increasingly exotic lineages. New decks and ship upgrades come from restoring or being gifted technology by ruins and advanced civilizations. Only sufficiently advanced client civilizations are capable of improving the ship this way.

**Cargo.** Only living residents cost deck space. Brews and any other technology are effectively uncountable and take no slots. Watchers are mounted to the outside of the hull and likewise take no interior space.

## Ship Politics and Sapient Residents

Sapient lineages living aboard the ship form a light social layer. Any sapient resident can communicate with any other via unspecified translation technology, regardless of how alien their communication medium naturally is; non-sapient residents can't communicate yet. Sapient lineages can exchange values with each other through contact, gradually influencing each other's cultures. Genetically identical lineages that are isolated from each other (e.g. in different systems) can gradually drift apart culturally. Long crossings at relativistic speed also mean comparatively little time passes aboard the ship while much more passes for the galaxy outside, so a return visit can find a resident's homeworld changed far more than shipboard life would suggest.

**Petitions.** Sapient lineages periodically make short, specific requests of the ship - a deck of their own, a different neighbor, a world to settle, guidance on a cultural question, and so on. Granting or denying a petition affects that lineage's **trust** toward the ship (the exact name for this attitude metric is still undecided; possibilities include something closer to "worship" depending on how a given lineage relates to the ship). Consent also matters more broadly: whether a lineage was taken aboard willingly or not factors into its overall attitude.

**No rebellion, no violence.** The ship is powerful enough to prevent any resident lineage from harming another, and there are no rebellions against the ship itself. Conflict among residents instead takes softer forms - internal tension, drift, or friction between lineages with very different values - rather than anything violent.

**Fixations.** Extended time aboard the ship can produce named cultural changes in a lineage (for example, a lineage might become deeply attached to shipboard life, or develop a longing for a lost homeworld), each carrying both a benefit and a cost. Ship life does not alter a lineage's fixed physical traits.

**Time dilation.** Because the ship travels at relativistic speeds, less time passes aboard during a long passage than for the wider galaxy outside; a resident's homeworld, or an entire civilization, may change dramatically over a passage that felt comparatively short to those aboard. This can influence shipboard psychology and politics, and gives flavor to a return visit of a shipboard lineage to their homeworld.

## Sapience and Culture

Sapience is the final step of a lineage's physical evolution. Once reached, physical change stops, and further development becomes cultural rather than biological. The game uses only the single term "sapient" in its interface; a more fine-grained sentience/sapience distinction is not exposed to the player.

A sapient lineage's development afterward is tracked through **cultural evolution** in the form of the culture matrix, a system distinct from physical evolution. This system is intentionally not meant to be anthropocentric - it should avoid defaulting to human-style categories like individualism, religion, or economics, so that different sapient lineages feel genuinely alien to one another rather than reskinned human societies. Culture is understood to be shaped partly by a lineage's physical form and its homeworld. Candidate elements identified so far include a lineage's memory (how faithfully knowledge is preserved across generations), its openness to new ideas, and its restraint (how much it moderates its own energy appetite) - though the full system, including how the player can influence a culture's direction, is still an open area needing significant further design work.

**Capability beyond sapience.** How far a sapient lineage can reach - whether they've only settled their homeworld, expanded through their star system, or gone interstellar - is one useful way to describe what a lineage can do for the ship and how close they may be to drawing dangerous attention (see "The Masters, the Sieve, and the Devices" below). This is just one among several possible capability metrics, since a highly developed lineage might simply have no interest in leaving their homeworld.

## Galaxy Structure and Exploration

The playable galaxy is organized into broad **zones** (for example, an inner bulge, a habitable annulus, an outer rim) with different physical tendencies - metal content, supernova rate, typical stellar age - that color what kind of worlds and hazards are found there. Beneath zones, the map is a relatively small set of systems (on the order of about a hundred across the whole galaxy) that the player can visit freely. there is no intermediate "cluster" layer as a formal navigational structure, and no fixed star lanes connecting systems. Instead, the ship makes free jumps between known systems, with travel time set by distance. The map is newly generated for every game, but contains many scripted structures (ruins etc), quests, events, and other handwritten content.

Learning what a system actually holds depends on the ship's survey capabilities. Several complementary methods of scanning and exploring exist, each revealing a different layer of a world or ruin, and better methods are unlocked over time through ruins, gifted technology, and events.

Travel is not instantaneous, and real time passes both in transit and at the destination while the ship is away. Returning to a system after a long absence shows what happened in the interim, aided by any watcher reports that arrived in the meantime; the ship learns of distant events only after a significant delay, since information cannot travel faster than light.

The galaxy is bounded: the ship can travel between stars but not between galaxies, consistent with its ramscoop design. Deeper or more dangerous zones are being explored as a design space for what makes them harder to enter - not necessarily more physically damaging to the ship, but more consequential or more exotic. This is still an open area of design (see "Open Questions").

## Background Lore: The Progenitors and the Filter

The ship was built by an ancient species referred to as the **Progenitors**, who are now gone. Something destroyed them, and the central mystery and long-term plot of the game is uncovering what that was and what it takes to survive it - this is a deliberate use of the Fermi paradox as a plot device. Ruins scattered across the galaxy, mostly built by the Progenitors (though possibly by other, older cultures as well), all point toward the same cause of extinction and offer clues about the nature of the threat and the capabilities needed to face it. All lore and ruin content is handwritten rather than procedurally generated, though the ruins themselves are scattered across the map by a placement process.

The precise reason the ship exists without any of its makers aboard, and why it was specifically designed as a "gardener" instead of e.g. a warship or an archive, is not yet settled and remains an area for further worldbuilding.

## The Masters, the Sieve, and the Devices

The filter that destroyed the Progenitors was installed by an even older, intergalactic race referred to as the **Masters**. Their goal is not to farm or exploit emerging civilizations, but to keep neighboring galaxies safely underdeveloped: they have no interest in sentient life arising in galaxies other than their own, and their devices exist purely as **insurance and early warning**, not as something intended to encourage or cultivate sentience. If a device does detect clear evidence of a spacefaring or otherwise dangerously advanced intelligence, the Masters destroy it through their devices. The Masters themselves never physically appear in the game - only their machinery, their ruins, and their consequences are ever encountered. A late-game lore idea could be that the Masters themselves have since been destroyed or gone extinct, potentially even through their own machines.

**The devices.** Multiple passive detector devices are seeded across the galaxy, each watching a limited radius. They are deliberately sited on sterile or hostile worlds that constitute a seeding challenge. One of the devices, likely the largest, also serves as the **relay** for the entire network and functions as a final "boss" of sorts.

**Neutralizing a device.** Destroying a device outright is treated as an alarm in itself (a deadman-switch problem), so devices cannot simply be blown up. Instead, they are **defanged**: by seeding the devices (which are very large space structures) with layered, thriving, but deliberately unintelligent life, the device's ability to pick out an engineered, intelligent signal from ordinary biological noise is overwhelmed. Care must be taken that life on or near the device itself never becomes smart, since that would recreate the very risk the device exists to catch. Mechanically, this plays out as an intensified version of the normal seeding loop, layered with additional events, rather than as combat. This mechanic is just a first idea how to have "boss fights", and might get completely revised.

**Progression and restriction.** The ship is not permitted to seed lineages within a device's actively monitored radius at all because of the existential risk this would pose. Neutralizing a device unlocks travel into the next galactic zone it was watching, functioning as both a satisfying unlock and a natural pacing limiter. The overall threat escalates as ruins are researched, following predefined milestones rather than a real-time countdown, so player progress - not elapsed play time - drives the pacing of danger.

**What can actually harm the ship.** The ship itself is essentially safe; it is far too powerful to be meaningfully threatened directly. The one recognized risk is the loss of scarce resources during dangerous events - for example, losing an entire deck along with its occupants, or losing a watcher.

**After the campaign.** Resolving the central threat doesn't end the game. The player can continue afterward in an open sandbox mode, still seeding and developing lineages and civilizations across the galaxy and uncovering any ruins or secrets not yet found.

## UI and Presentation

The game is presented in 2D, combining illustrated images with text fields, alongside maps: a galaxy map and a system map. There is no separate planet-surface map. A world is represented as a compact "card": an illustration, well icons showing pip capacity, a band tag, and a summary of who lives where.

Information about the state of a world or lineage is shown through coarse, weather-app-style **text forecasts** ("likely thrives," "could go either way," "likely collapses") rather than precise numbers, with the forecast's fuzziness potentially narrowing the longer and more closely a place has been observed (or if the ship has been upgraded with better observation tools).

**No individually simulated characters.** The game does not track or simulate specific named individuals. Instead, when a lineage's high-status members make requests or appear in events (petitions, quests, contact), they're represented through role-based flavor names generated from that lineage's traits and philosophy - for example, "a seer/merchant/king from the Glass-Feelers makes a request" - rather than through a persistent, individually tracked character.

## Naming Conventions

A few terms are established as the game's working vocabulary:

- **Passage** - a slow interstellar trip between systems; the reports that come back from a watcher or system are **reports**, and the accumulated record of everything that's happened is the **log**.
- **Watcher** - the powerful machine intelligence left behind in a system to observe and act on the ship's behalf.
- **Vigil** - remaining in orbit at a system, sometimes for tens of thousands of years, to make live decisions rather than leaving things to a watcher.
- **Lineage** - the tracked unit of evolving life; **forking** - when a lineage splits into two distinct branches.

Lineages and civilizations are given meaningful, composed names on encounter, assembled from a vocabulary of words reflecting their type, traits, and philosophy (for example, "Vent-Singers"), rather than random syllables. Once a lineage is uplifted to sapience, the player can choose to rename it themselves in a ceremony-like moment.

## Open Questions

The following are acknowledged as unresolved and need further design work:

- **Nonlinear acceleration of progress.** How civilizational and lineage development speeds up over time is still an open and important question. One idea is a developmental model of distinct phases separated by plateaus, but nothing is settled.
- **The middle of the Steps ladder.** The first step (a coherent body) and the last step (sapience) are fixed; the steps in between are not yet defined, nor the name for the first step.
- **Cultural evolution system.** That cultural evolution exists as its own system, distinct from physical evolution, is settled; its actual mechanics - structure, progression, how the player can influence it, and what its underlying currency is called - are not. Early candidate elements (memory, openness, restraint) are tentative only.
- **Inter-lineage relations aboard the ship.** How sapient residents relate to one another beyond value exchange (friendliness, rivalry, alliance) needs a non-anthropocentric system.
- **Reliable steward traits.** Which specific traits make a client civilization trustworthy enough to act as an informal steward over a region is unresolved.
- **Short-term threats.** The game currently lacks well-defined ongoing dangers to gardens and watchers; some are needed, but their exact form isn't decided.
- **Consequences of a failed uplift.** Uplifted species "gone bad" can become a problem later, but what form that danger takes is open.
- **World feature and composition tag systems.** Both are adopted in principle, but the full list of tags and how they mechanically interact still needs to be built out.
- **Biosphere/garden status readout.** There should be a quick way to summarize a whole ecosphere at a glance.
- **Ruin typology.** Beyond being handwritten, mostly Progenitor-related, and possibly including other ancient cultures, the specific categories or types of ruins remain undefined.
- **Internal quarrels or cults.** The idea that long-term shipboard life could produce non-violent internal strife among residents is a tentative direction only, with no defined shape yet.
- **Brew naming and detail.** The catalog of fundamental "orders" of life represented by brews, and what to call them, is still open.
- **The ship's origin story.** Why the ship exists without any of its makers aboard, and specifically why it was built as a "gardener", has not been settled.
- **Danger gradient across zones.** What specifically makes deeper or more dangerous zones harder to operate in (beyond the device-monitoring restriction) needs further brainstorming.
