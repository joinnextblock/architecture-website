# Architecture: Frequently Asked Questions

## What is Architecture?

Architecture is NextBlock City's building system that transforms Nostr posts into permanent structures under the [Observatory's](https://observatory.nextblock.city) Bitcoin temporal sky.

Every Nostr post becomes a building in our digital metropolis, with its physical characteristics determined by community engagement and its architectural style permanently stamped by the [Observatory's Bitcoin temporal coordinates](https://observatory.nextblock.city#how-do-i-read-observatory-dates). Instead of ephemeral social media posts that disappear into feeds, Architecture creates lasting urban infrastructure where a simple comment becomes a cottage and viral posts become towering skyscrapers.

This creates a unique digital archaeology where you can literally walk through neighborhoods and see the architectural evolution of online communities, with each building serving as a permanent monument to social interaction at specific moments in Bitcoin's timeline.

## How do engagement metrics become building dimensions?

Architecture uses four key engagement metrics to determine a building's physical characteristics:

- **Foundation/Footprint (Reposts)**: Building size on 3x3 tile lot (1-3 tiles)
- **Height (Comments)**: Number of floors using Bitcoin scarcity scaling
- **Windows (Reactions)**: Number of windows per floor (engagement visibility)
- **Greenery (Zaps)**: Amount of landscaping around building (economic appreciation)

## How does the foundation positioning system work?

Buildings are positioned using a blockchain-style sequential system where each lot's building placement depends on the previous lot's state:

### Foundation Positioning Rules
- **1-tile foundation**: Always centered (X = 1)
- **2-tile foundation**: Alternates between left-aligned (X = 0,1) and right-aligned (X = 1,2) based on previous lot
- **3-tile foundation**: Always fills entire row (X = 0,1,2)

### Complete Foundation Examples
```
1. 1→1: [   ][🏢][   ] → [   ][🏢][   ]    (center → center)
2. 1→2: [   ][🏢][   ] → [   ][🏢][🏢]    (center → right)
3. 1→3: [   ][🏢][   ] → [🏢][🏢][🏢]    (center → full)
4. 2L→1: [🏢][🏢][   ] → [   ][🏢][   ]   (left → center)
5. 2L→2: [🏢][🏢][   ] → [   ][🏢][🏢]   (left → right)
6. 2L→3: [🏢][🏢][   ] → [🏢][🏢][🏢]   (left → full)
7. 2R→1: [   ][🏢][🏢] → [   ][🏢][   ]   (right → center)
8. 2R→2: [   ][🏢][🏢] → [🏢][🏢][   ]   (right → left)
9. 2R→3: [   ][🏢][🏢] → [🏢][🏢][🏢]   (right → full)
10. 3→1: [🏢][🏢][🏢] → [   ][🏢][   ]   (full → center)
11. 3→2: [🏢][🏢][🏢] → [   ][🏢][🏢]   (full → right)
12. 3→3: [🏢][🏢][🏢] → [🏢][🏢][🏢]   (full → full)
```

This creates a deterministic but dynamic positioning system where 2-tile buildings create alternating left/right patterns, generating visual rhythm across the skyline.

## How is building height calculated?

Building heights use a Bitcoin-inspired scarcity model with exponential scaling:

### Comment-to-Floor Thresholds
- **Floors 1-10**: 10 comments per tile
- **Floors 11-21**: 100 comments per tile (exponential scarcity)
- **Foundation**: Always filled (determined by reposts)

### Height Examples by Foundation Width

**1-tile foundation:**
```
8 comments:   Foundation only
18 comments:  Foundation + 1 floor
98 comments:  Foundation + 9 floors
108 comments: Foundation + 10 floors
208 comments: Foundation + 10 floors + 1 tile of Floor 11
1108 comments: Foundation + 20 floors (rare skyscraper!)
```

**2-tile foundation:**
```
15 comments: Foundation only
25 comments: Foundation + 1 tile of Floor 1
35 comments: Foundation + 2 tiles of Floor 1 (complete floor)
215 comments: Foundation + 10 floors + 1 tile of Floor 11
2215 comments: Foundation + 20 floors (mega skyscraper!)
```

**3-tile foundation:**
```
25 comments: Foundation only
35 comments: Foundation + 1 tile of Floor 1
65 comments: Foundation + 3 tiles of Floor 1 (complete floor)
595 comments: Foundation + 10 complete floors
3595 comments: Foundation + 20 complete floors (legendary monument!)
```

### Partial Floor Filling

Individual tiles within a floor can be filled independently. For example, a 2-tile foundation with 25 comments would show:
```
[   ][   ][   ]  ← Empty Floor 2
[🏢][   ][   ]  ← Partial Floor 1 (1 tile filled)
[🏢][🏢][   ]  ← Foundation (complete)
```

This system makes viral posts into towering architectural monuments while simple interactions remain as cottages, creating a permanent visual hierarchy of community engagement.

## How is the city organized?

NextBlock City follows a hierarchical urban planning system:

- **Lot**: 3x3 tiles (1 building)
- **Block**: 4x4 lots (16 buildings)  
- **Neighborhood**: 4x4 blocks (256 buildings)
- **District**: 4x4 neighborhoods (4,096 buildings)

This systematic organization ensures buildings naturally cluster by time period and architectural style, creating coherent neighborhoods that reflect the temporal DNA of their Observatory birth moments.

## How does Observatory timing affect architecture?

Every building's architectural style is permanently determined by its [Observatory timestamp](https://observatory.nextblock.city#how-do-i-read-observatory-dates) at the moment of posting. This creates natural neighborhood cohesion and historical stratification.

### Permanent Architectural DNA (set at posting time)

- **Solar Season**: Base architectural style (Spring: Modern, Summer: Art Deco, Autumn: Craftsman, Winter: Gothic) - determined by [Observatory's solar cycle](https://observatory.nextblock.city#how-does-the-virtual-sun-cycle-work)
- **Named Moon**: Roof type (13 distinct styles: Orange Moon 🟠, Whale Moon 🐳, Lightning Moon ⚡, etc.) - based on [Observatory's Named Moons](https://observatory.nextblock.city#what-are-the-named-moons)
- **Moon Phase**: Decorative ornamentation level (Full Moon 🌕 = maximum detail, New Moon 🌑 = minimal) - follows [Observatory's moon phases](https://observatory.nextblock.city#what-are-the-moon-phases)

### Dynamic Environmental Effects (updates every ~10 minutes)

- **Atmospheric Conditions**: Network efficiency determines visibility (Clear skies ☀️ vs. Thunderstorms ⛈️) - based on [Observatory's atmospheric system](https://observatory.nextblock.city#how-does-the-observatory-determine-atmospheric-conditions)
- **Celestial Lighting**: Current moon phase and sun position create dynamic shadows
- **Eclipse Events**: Special lighting effects during mid-season [Observatory eclipses](https://observatory.nextblock.city#what-are-eclipses-and-when-do-they-happen)

**Example**: Post created at [`4|2|4|1|430 AG`](https://observatory.nextblock.city#how-do-i-read-observatory-dates)
- **Permanent Style**: Summer Art Deco base with Whale Moon roof and Full Moon ornamentation
- **Current Environment**: Changes every Bitcoin block based on network conditions

## How are buildings placed in the city?

Architecture uses the Ulam Spiral placement system, mirroring the [Observatory's solar cycle rotation](https://observatory.nextblock.city#how-does-the-virtual-sun-cycle-work). Posts are scored by total engagement and placed counterclockwise from the city center:

**Placement Direction**: West → North → East → South → (repeat outward)

## How is engagement scoring calculated?

TBD

## When does the city rebuild?

The city undergoes complete renewal every Full Moon cycle, aligning with the [Observatory's lunar rhythm](https://observatory.nextblock.city#how-does-the-virtual-moon-cycle-work).

### Full Moon Renewal (Every 4,032 blocks)

- **Urban Optimization**: All buildings repositioned using current engagement scores
- **Architectural Preservation**: Each building retains its original Observatory temporal DNA
- **Neighborhood Evolution**: New clustering patterns emerge based on accumulated engagement

This creates a living city that evolves its layout while preserving the architectural history of every structure. Buildings from different eras can become neighbors if they achieve similar engagement levels, creating fascinating temporal juxtapositions.

**Example**: A Winter Gothic post and Summer Art Deco post with similar engagement scores might become neighbors in the next renewal cycle, creating unique architectural contrast that tells the story of community interaction across different Bitcoin seasons.

## What are the seasonal architectural styles?

TBD

## What are the Named Moon roof types?

TBD

## How does Architecture work with the Observatory?

Architecture operates as the [Observatory's](https://observatory.nextblock.city) physical manifestation - where the Observatory tracks Bitcoin's celestial time, Architecture transforms that temporal data into permanent urban infrastructure. Every ~10 minutes, as Bitcoin creates new blocks, the Observatory updates the sky above NextBlock City, affecting visibility, lighting, and atmospheric conditions for all buildings below.

This creates a unique symbiosis: the Observatory provides the temporal framework that gives each building its permanent architectural DNA, while Architecture provides the physical structures that make the Observatory's time system tangible and visually meaningful.

The result is a city that serves as both a social graph and an archaeological record of Bitcoin's temporal evolution, where every building tells the story of community interaction at specific moments in our digital civilization.

---

*Learn more about NextBlock City's temporal system at [observatory.nextblock.city](https://observatory.nextblock.city)*