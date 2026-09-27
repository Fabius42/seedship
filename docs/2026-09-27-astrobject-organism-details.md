# Details about astrobject procedural generation and species traits

Published: 27.09.2026

## Overview

Research and game design ideas about stars, systems, and orbital mechanics; astrobject types, materials, temperature, and topography; organism traits, reproduction, and mutation; alien tech/ruin flavor ideas; and the underlying data model.

## Stars, Systems & Orbits

### System-Level Structure & Star Multiplicity

**System size categories** (not yet detailed): Large System, Medium System, Small System, Exotic System.

**General tendencies:**

- Big stars are usually part of clusters or binary/ternary systems.
- Red dwarfs are almost always solitary.
- Distant binary systems are usually sun-like stars, and quite common.
- More lower-mass planets exist than higher-mass planets.
- More planets exist in large orbits than in small orbits.
- Multi-star systems have a higher likelihood of having high-mass planets.

**Close binary systems:**

- Neutron star or black hole with another (medium-large) star - an "X-ray binary."
- White dwarf with another (medium-large) star - the white dwarf itself is called a "vampiric star" or "cataclysmic variable star" in this pairing.
- Also possible: a red dwarf paired with a white dwarf or neutron star.

**Multiplicity statistics**

- Overall system multiplicity: 75:20:5 (solitary:binary:ternary).
- Mass-dependency: larger/heavier stars are more likely to come in pairs (or more), probably because they can more easily "catch" each other gravitationally.
- Example: Alpha Centauri - two central sun-like stars forming a binary pair, with a red dwarf orbiting them.

**System topology definitions:**

- **Binary System** - two stars circle around each other, and the circumbinary planets of the system orbit the shared center of gravity.
- **Ternary System** - like a binary system, but with a third star circling around the pair in a wider orbit. Planets in this system can be either circumbinary or circumstellar, depending on which star(s) they orbit.
- **Circumbinary Planet** - a planet that orbits the shared center of gravity of two stars.
- **Circumstellar Planet** - a planet with a stable orbit around a single star.

### Stellar Types & Life Cycle

**Life cycle of stars:** a star forms through gravitational accretion of a molecular cloud. If it has enough mass, it ignites and generates energy via hydrogen fusion. After a few billion years, a star usually exhausts its fuel (heavier stars burn faster, lighter ones slower). Heavy stars expand and first become giants, then eventually discard their shells and become a white dwarf. Small stars transition directly to the white dwarf phase without a giant stage. The heaviest stars become supergiants and explode in a supernova, becoming a neutron star or a black hole.

**Star type definitions:**

- **Main Sequence Star** - a white or slightly yellow star, in the middle between giants and dwarf stars in mass and brightness. The Sun is an example.
- **Red Dwarf** - a low-mass, slow-burning small star emitting faint red-orange light. The most common star type, with a very long lifespan but comparatively low temperature (burns fuel slowly). 0.01%-10% of the Sun's luminosity; frequency ~75%; color red.
- **Giant** - a late-stage star that has exhausted most of its fuel and inflated its shell by orders of magnitude. Can be blue, yellow, or red - blue giants have the highest temperature and smallest diameter, red giants the lowest temperature and largest diameter.
- **Supergiant** - a short-lived star similar to a giant, but significantly brighter and more massive.
- **White Dwarf** - an old, burnt-out star with no active fusion, very high density, emitting only faint white light from residual thermal energy.
- **Neutron Star** - an extremely small and dense, extinguished star consisting entirely of neutrons, rotating many dozens or even hundreds of times per second. Initially extremely hot after forming from a supernova, then gradually cools by emitting electromagnetic radiation in pulses.
- **Black Hole** - a body so massive that light can't escape its gravity. Grows by absorbing nearby matter; the largest black holes often form galactic centers. Can only be observed indirectly, via its interaction with nearby objects.
- **Flare Star** - a star with frequently occurring stellar flares, during which its radiation strongly increases for a short timespan. A large fraction of red dwarfs are flare stars; this behavior is less frequent in other star types.

**Stellar Composition:** active (fusing) stars are spheres of hot plasma, powered by nuclear fusion in their core. They have a layered shell that transmits heat via thermal radiation and convection upward to the photosphere, from which energy is emitted as electromagnetic radiation across a wide spectrum, including light, infrared, and X-rays.

**Luminosity:** stars emit electromagnetic radiation across a wide spectrum, from infrared to ultraviolet and beyond. Luminosity varies strongly between star types and strongly influences orbiting bodies, which receive energy, heat, and ionizing radiation from it.

**Star luminosity by type** (relative to the Sun = 1):

- Supergiant (Betelgeuse) - 75,000 -> x100,000
- Giant (Aldebaran) - 150 -> x100
- Main Sequence (Sun) - 1
- White Dwarf (Sirius B) - 0.05 -> /100
- Red Dwarf (Proxima Centauri) - 0.00005 -> /100,000
- Neutron Star - 0.0000005 (only visible in X-ray spectrum) -> /10,000,000

**Ionizing radiation:** ultraviolet light, X-rays, and gamma rays are radiation types with enough energy to change the atoms and molecules they hit. Emitted by stars and radioactive elements; can cause mutations and death in some lifeforms.

**Transient/violent stellar events:**

- **Solar flare**
- Star quake on neutron stars, possibly related to gamma-ray bursts.
- **Gamma-ray Burst** - the most powerful type of explosion, emitting extremely strong radiation for a brief time. Occurs during supernovas, and from the merger of binary neutron stars.
- **Supernova** - a powerful explosion of a massive star, emitting strong cosmic rays and expelling large amounts of matter at a fraction of the speed of light.

**Also to think about:** Heliosphere, Heliopause, Solar Wind - not yet detailed.

### Orbital Mechanics

- **Hill Sphere** - the maximum distance at which an astrobject still holds gravitational influence over smaller astrobjects. This is the maximum stable orbit; going beyond it, the smaller astrobject is lost.
- **Roche Limit** - the minimum distance at which an astrobject can orbit a larger one without being ripped apart by tidal forces. This is the minimum stable orbit; going closer, the smaller astrobject disintegrates.
- **Tidal Heating** - when an astrobject has an elliptical orbit, the gravity of the larger astrobject pushes and pulls the smaller one. This orbital energy creates friction, which generates heat in the smaller astrobject. (A large moon close to its planet experiences vastly more tidal heating than a small moon farther away.)

**Orbit tightness categories:** Roche Limit, Tight, Moderate, Wide.

## Astrobject Types

### Astrobject Types & Size Scale

**On moons:** everything from large planets to asteroids can orbit another, larger astrobject and thereby be its moon - this is useful information, but has little to do with the orbiting body's own size class.

**List of Astrobjects by Diameter** (size class, name, approximate real diameter, example body):

- 11 - Supergiant - ~600,000,000 km (e.g. Betelgeuse)
- 10 - Giant - ~60,000,000 km (e.g. Aldebaran)
- 9 - Main Sequence Star - ~1,500,000 km (e.g. Sun)
- 8 - Red Dwarf - ~200,000 km (e.g. Proxima Centauri)
- 7 - Gas Giant - ~150,000 km (e.g. Jupiter)
- 6 - Small Gas Giant - ~25,000 km (e.g. Neptune)
- 5 - Large Planet - ~20,000 km (e.g. "Super Earth" Phobetor)
- 4 - White Dwarf - ~12,000 km (e.g. Sirius B)
- 4 - Planet - ~12,000 km (e.g. Earth)
- 3 - Dwarf Planet - ~2,500 km (e.g. Pluto)
- 2 - Large Asteroid - ~1,000 km (e.g. Ceres)
- 1 - Asteroid - ~20 km (e.g. Eros)

For a more even gameplay experience, real-world size differences between planets, suns, and asteroids could be compressed via a roughly logarithmic relationship between actual size and in-game size.

### Planetary Body Types

- **Gas Giant** - a massive, layered planet consisting mostly of hydrogen and helium. A molten metallic core is surrounded by a layer of liquid hydrogen, with an exterior gaseous shell on top.
- **Small Gas Giant** - unlike its more massive relative, this large layered planet consists mostly of water and methane, plus some heavier elements as well as hydrogen and helium (also has oxygen, carbon, nitrogen).
- **Gas Giant Weather** - heat from the gas giant's interior fuels thunderstorms with electrical discharges and powerful winds that swirl perpetually over parts of the surface.

**Other planet-type names to develop:** Chthonian planet, Carbon planet, Coreless planet, Iron planet, Lava planet.

Also think about rings of gas giants and giant planets as habitats.

### Asteroids & Small Bodies

- **Stony asteroid** - S-type (siliceous) asteroids have high density, consisting of varying amounts of silicate, iron, and magnesium. Occurrence: ~20%.
- **Carbon asteroid** - C-type (carbonaceous) asteroids have low density, consisting of large amounts of carbon with some silicate and water. Occurrence: ~75%.
- **Iron asteroid** - M-type (metallic) asteroids have extremely high density, consisting of iron, nickel, and some silicate. Occurrence: ~5%.

**Dust ponds** - dry pockets of dust that accumulate via electrostatic transport in surface craters of astronomical objects without an atmosphere.

## Materials, Temperature & Topography

### Materials & Elemental Composition

The types of materials are, in effect, the same materials existing at different temperatures. In-game, that means these material "types" don't make sense as fixed categories - materials should be referred to only by their name and their current temperature-related state.

**Solids** (temperature states: 0-2 Solid [Regolith], 3-7 Solid [Massive], 8 Liquid, 9 Plasma): Silicate, Carbon, Uranium (radioactive), Iron, Aluminum, Magnesium, Nickel.

**Gases** (temperature states: 0 Solid, 1 Liquid, 2-8 Gaseous, 9 Plasma): Hydrogen, Helium, Nitrogen, Oxygen, Methane, Radon (radioactive).

**Liquids:**

- Water (temperature states: 0-2 Solid [Ice], 3-6 Liquid, 7-8 Gaseous [Water Vapor], 9 Plasma).
- Mercury (temperature states: 0-1 Solid, 2-7 Liquid, 8 Gaseous, 9 Plasma).

**Silicate** - a stone-like, hard material consisting of silicon and oxygen. Found in granite, cement, or glass.

**Example descriptive sentences:**

- A tranquil sea of liquid hydrogen.
- A mountain range of solid carbon.
- A thin nitrogen atmosphere.
- A turbulent field/area of iron plasma.

**Exclusions:** some elements don't go with others, and would make for not-possible or unrealistic planets - e.g. Carbon and Water together.

### Temperature & Physical-State Scales

**Range of Temperatures** (0-9):

- 0 - Absolute Zero
- 1 - Stone-Shattering
- 2 - Freezing
- 3 - Cold
- 4 - Mild
- 5 - Warm
- 6 - Hot
- 7 - Boiling
- 8 - Stone-Melting
- 9 - Plasma-Inducing

**Range of Physical States** (0-4, each with its possible temperature range):

- 0 - Vacuum (0-9)
- 1 - Solid (0-7)
- 2 - Liquid (3-8)
- 3 - Gaseous (1-8)
- 4 - Plasma (9)

### Topography, Areas & Zones

An astrobject's topography type is generated first based on its location in the solar system, its elemental composition, and randomness.

**List of topography factors** (each possibly on its own ordinal scale, similar to temperature):

- Jaggedness (planar / hilly / mountainous / cratered)
- Dryness (dry / lakes / oceans / sea cover)
- Temperature (see Temperature & Physical-State Scales above)
- Denseness (caves vs. no caves)
- Gravity (scale from no-g to extreme gravity, like inside a sun)
- Seismically active vs. non-active (influences volcanic energy, earthquakes)

Different zones of an astrobject - suited to organism types that are "airborne," "land-dwelling"/"seaborne," and "cave-dwelling"/"diggers" - are composed of different elements (e.g. a nitrogen atmosphere, a silicate ground cover, and iron rock below) that influence organism behavior and survival chances.

**Other things to consider when creating a planetary body:**

- Topography (smooth vs. scraggly, cavernous, impact-craters, etc.).
- Weather - fast winds, lots of condensation (moisture) in the "air."

### Energy Sources

An area can have the following energy sources:

- Solar Energy (if it's near a sun, and not on a dark, tidally locked side)
- Thermal Energy (if it's seismically active - volcanism, deep sea vents, etc.)
- Organic Energy (micro-organisms, prey, carrion)
- Gravitational Energy (if there's a significant planet/moon mass nearby)
- Radioactive Energy (if there are radioactive elements nearby)
- Wind Energy
- ... (more possible categories, not yet identified)

## Atmosphere & Habitability

### Atmosphere & Magnetic Field

Whether a planet can keep its atmosphere depends on its mass (whether it "holds on" to the gases) and its magnetic field (which helps protect the atmosphere against solar wind pushing it away). Gas giants are better at keeping their atmosphere because they're so massive; dwarf planets and smaller bodies can't hold an atmosphere because they're too light.

Moons can potentially be protected by their planet's magnetic field.

Tidally locked bodies, or bodies with less mass, tend to have a weak to non-existent magnetic field.

**Ozone layer** - noted as a concept, not yet detailed.

**Atmosphere as data fields:** atmosphere thickness (thick / thin / vacuum) and atmosphere composition (one or two elements the atmosphere is made from).

### Habitability & Life-Related Notes

**Water viability:** astrobjects containing water: in very hot temperature orbits, water would simply boil away; if the astrobject doesn't have much mass, the resulting water vapor also escapes rather than forming an atmosphere.

**Potential different forms of life** (name ideas, not yet detailed): Energy Beings, Nonconventional Lifeforms, Species with Indeterminate Biochemistry, Alternative Forms of Life.

**Geological activity:**

- Earthquake, vulcanism, asteroid impact (with several possible degrees of severity, and the potential to seed life) - not yet detailed.
- The smallest astrobject that can be geologically active (i.e. have vulcanism / interior heat) is a dwarf planet.

## Alien Tech / Ruin Flavor Ideas

A list of exotic structure ideas.

- Sun solar panels surrounding it.
- A perfect diamond sphere planet - slightly rough and dusty on the surface from past impacts, with elaborate 3D capillary-like canals in the interior (a computer?).
- A death-star-like guardian dwarf planet that can be activated and then kills life in the system via radiation or similar.
- A gigantic fleet of alien spaceships (needs a description of how they look and what material they're made from - maybe diffractive, so they're very hard to see, or only visible via their occlusion of stars behind them).
- A large asteroid with a hostile-looking, spiky structure that signifies danger, protecting an equivalent of a nuclear waste deposit (substance still undecided) that might be dangerous to the player's life cargo.
- A hollowed-out dwarf planet with interior reinforcements to avoid self-collapse - maybe a camouflaged hangar for spaceships, or something else entirely.

## Data Model & UI

**List of properties of a non-star astrobject:**

- Distance to star (several distance classes -> orbits)
- Amount of light received per area, on an ordinal scale (depends on the star's strength and its distance)
- Size
- Eccentricity of the orbit
- `is_tidally_locked`: bool
- Composition: which elements the astrobject is made of
- Atmosphere thickness: thick / thin / vacuum
- Atmosphere composition: one or two elements the atmosphere is made from
- Areas: list of areas that the astrobject consists of
- `is_geologically_active`: bool (or maybe a small-scale/graded value?)
- `has_magnetic_field`: bool (or maybe a small-scale/graded value?)
- `instable_orbit`: bool (a small chance that the astrobject crashes into the larger one)

**UI idea for an astrobject overview screen** (example data for an MVP version):

- Name: "Cleisthenes" (needs more default names)
- Size Class: "3 - Dwarf Planet"
- Composition: "Silicate / Iron"
- Special properties: "Vulcanic / Magnetic field" (no atmosphere)
- Short info text: "Sterile, craggy dwarf planet with a hot core"
- Longer info text - not yet written
- List of areas, with short info texts on hover, including atmosphere where present:
  - Low orbit / Atmosphere (depending on whether it has one)
  - Plane
  - Mountain chain
  - Craters - "Torn up terrain full of ring-shaped scars from asteroid impacts"
  - Dense mantle
  - Iron core
- List of lineages that live on/in/around the astrobject: currently "None" in the example

## Traits & Reproduction

### Reproduction

Candidate reproduction models a lineage could use (no decision made yet on which exist, or whether multiple coexist):

- Male-female model
- Male-inter-female model
- Two-hermaphrodite model
- Self-fertilization model
- Spore vs. "physical" transmission

### Trait System: Taxonomy

Traits are binary - either present or not (for example, predatory). Trait tags regulate how an organism behaves in a given world: they can gate which areas can be traversed, what food can be eaten, and what actions can be taken.

Two categories of traits are distinguished:

- **Access traits** - binary, and govern where a species can settle, what it can hunt, and similar access questions.
  - Example: whether another species can even hunt it (an airborne organism can fly away from a land-dwelling one).
  - Example: whether it can be eaten at all (a poisonous species can only be eaten by a poison-resistant species).
- **Complex traits** - binary, but influence and change deep gameplay effects and patterns.
  - Example: how a species survives in an area over time (hibernation).
  - Example: how a species makes decisions and evolves its civilization (swarm-intelligence).
  - Example: how a species appears to others (changeling).

### Trait Catalog

**Trait tag ideas:**

- Metabolism
- More resilient
- Poisonous
- Cunning
- Predatory
- Plant-eater
- Is a plant
- Flying
- Swimming
- Is a gas
- Is completely dry (stone-like)
- Is information / electricity (no "body")
- Short-lived
- Parasitic
- Swarm-intelligence (individuals merging)
- Changeling
- Incapable of moving (stationary)
- Can move
- Hibernate (reduced metabolism with no actions)
- Hide (difficult to find by predators / shielded from nature)
- Camouflage (e.g. color, patterns)
- Good Senses (e.g. audio, visuals, smell)
- Body Armor (e.g. plates, scales, thick skin)
- Fangs, Claws

**Access traits, worked examples:**

- **Poisonous** - won't be hunted by species that aren't resistant to poison.
- **Poison-Resistant** - can hunt and eat carrion from species that are poisonous.
- **Immobile** (can be in water, air, or on land - just means it can't influence where it goes, like spores)
  - strongly reduced CATCH & FLEE
  - strongly reduced metabolic cost
- **Mobile** - improved CATCH & FLEE.
- **Airborne** (floating, gliding) - can move through air or other gases.

**Complex traits, worked examples:**

- **Starvation-Resistant** - lower threshold for starving (in %).
- Cunning
- Flying
- Swimming
- Parasitic
- Swarm-intelligence (individuals merging)
- Changeling
- Hibernate (reduced metabolism with no actions)
- Traits related to amount of offspring.
- Traits related to threshold of dying, in % (lower is better).

**Start traits** - potential traits a lineage could begin with when it first enters the game:

- Tiny body
- Soft tissue
- Immobile
- Some form of eating trait, in rudimentary form

## Habitat & Mutation Pressures

### Habitats & Niche Specialization

Usually, a species needs a substance to live in (its "habitat"), though there may be an exception for vacuum. A habitat can be a specific element at a specific physical state at a specific temperature or temperature range, or something more broad, like "burrows in solid elements," "swims in liquids," or something in the middle, like "breathes nitrogen."

Expected emergent story: if a species population lives at the fringe of another habitat it can't yet settle, over time a useful mutation will occur that, by luck, lets the mutants settle the new area and grow in numbers. Over time, the old habitat's trait might mutate away, both because being an "allrounder" (e.g. land dweller and sea dweller at once) carries a higher metabolic cost (two traits required), and because the population no longer needs access to the old habitat. The result is two species with different habitats (land and sea) that will likely diverge further over time.

### Mutation Rate & Radiation

The amount of mutation in organisms depends on the amount of radiation they receive in an area. Total radiation in an area is a combination of:

- **Cosmic Radiation** - high (3) if there's no magnetosphere, otherwise low (1).
- **Solar Radiation** - low to high (1-3) if there's a sun nearby, depending on distance to the sun; only occurs in an area that isn't in permanent shadow (e.g. due to tidal locking), otherwise none (0).
- **Other Radiation** - high (3) if there are radioactive elements nearby, varying area by area (and potentially even by layer within an area), otherwise none (0); can also come from (uplift) technology.

Total radiation therefore ranges from 1 (a planet or big asteroid with a magnetosphere, no nearby sun, no radioactive elements) to 9 (a planet or asteroid without a magnetosphere, near a sun, with radioactive elements).

## Simulation & Data Notes

### Simulation / Turn Processing (Engine-Level)

Undecided ideas on how to implement action/turn processing:

It makes sense to handle turns sequentially by Area, since most interactions tend to be local. Then, after those local interactions resolve, the more macro-level ones can be resolved: first migration between different Areas, and then - for a later stage of the game - intra- and inter-species politics, and movement between planets and star systems.

### Species Data Model: Odds and Ends

Miscellaneous notes on what a species/lineage record needs to track:

- **Size** - add a size category (e.g. micro, nano, small, large, macro, giga).
- **Ancestor** - add an ancestor field storing only a single id; the whole ancestry tree can be reconstructed later from that chain, rather than being stored directly.
- **Sociality** - some species might not be "social" (on the values/philosophy/type of consciousness level).
- **Monadic species** - there might be a species that doesn't communicate at all, or is maybe even unaware that anybody exists except the Individuum (i.e. unaware of other individuals or of a wider society at all).

## Open Questions

### General Factual Research

- When does an astrobject (e.g. a gas giant) have rings?
- Do asteroids form groups (i.e. "orbiting" each other)?
- How does mass influence what orbits what, and at what distance from the sun (orbit-clearing? minimum stable orbit for a given astrobject size)?
- When can tidal locking occur?
- Can an astrobject have an electric field without a liquid metal core? (Ganymede might have a subsurface ocean consisting of electrically conductive material.)
- Which star types and orbits would lead to which colors in photosynthesizing organisms, for optimal energy absorption? Color ideas: red, orange, purple.
- Can there be water on a body without a magnetic field protecting it from the sun?
- Look into magma caused by tidal heating (as with Io).
- Look into subsurface oceans as a concept generally.

### Game Design Decisions

- What should the likelihood be for each astrobject/system-size category to appear in a generated star system?
- Should "Double Planet" be treated as a distinct astrobject category?
- Should "Minor Planet" be used instead of "Dwarf Planet" as the category name?
- Should "rubble pile" and "contact binary" be adopted as descriptive terms for some asteroid types?
- Should orbit types be categorized by temperature and distance (temperature zones) and based on the strength of the star?
- Should Aphelion and Eccentricity of the orbit play a role?
- Should the game treat solar wind as an "area" of a sun, the same way planets have areas?
- Should elements be distributed across different areas of an astrobject? Or should we just list a bunch of labels for that astrobject card?
- Should "Wind Energy" be included as an energy-source type?
- What naming convention should default astrobject names follow (e.g. Greek names for planet-like bodies, Latin for suns)?
- Should "breathing" (oxygen breather, methane breather, etc.) be a modeled concept at all?
- Can traits be removed by mutation, not just added?
- Should we have metabolic cost as a concept? If yes, how should we calculate it, and what role does it play?
- How does the 0-9 radiation scale translate into a practical (%) mutation rate? Or maybe we should just simplify this scale into something shorter, like a 3-5 item scale?
- How does a species' size influence its required energy intake?