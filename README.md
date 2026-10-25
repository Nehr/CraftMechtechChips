# CraftMechtechChips
RimWorld mod for Biotech to craft high mechtech chips.

## ![About](images/rimworld-about.png)

Craft Signal chips, Powerfocus chips and Nano structuring chips.

Unlock the power to craft mechtech chips through research once you've analyzed the chips. Instead of repeatedly battling the same bosses to obtain mechtech chips, this mod offers you the alternative to craft them yourself.

Additionally, this mod introduces a research project for Mechlink crafting.

This mod can be added to existing saves. Before removing it, back up your save and finish or cancel any active crafting jobs and bills added by this mod.

This mod is tailored for end-game progression, offering experienced players an alternative pathway to enhance their technological capabilities. It aims to offer a supplementary method for advancing within the game.

### ![How to](images/rimworld-howto.png)

![How to](images/rw-mod-strip.png)

1. Analyze the chip.
2. Unlock the crafting ability through research in the Mechtech crafting tab.
3. Fabricate the mechtech chip at a fabrication bench.

### ![Features](images/rimworld-features.png)

Additionally, this mod introduces a research project for Mechlink crafting.

The ability to craft
	- Signal chip
	- Powerfocus chip
	- Nano chip
	- Mechlink

### ![Compatibility](images/rimworld-compatibility.png)

#### AlphaMechs support

Now compatible with the AlphaMechs mod, allowing you to craft Hyper-linkage chips, Stellar processing chips, and Quantum matrix chips! (Ensure this mod is loaded after AlphaMechs for proper functionality.)

## In-game values (RimWorld 1.6 / 1.7)
### Base research cost
Requires Multi analyzer for Powerfocus, Nano structuring, and Mechlink research.
- Signal chip: 2000
- Powerfocus chip: 2500
- Nanostructuring chip: 3000
- Mechlink: 6000
### Crafting costs
Requires Fabrication bench.
#### Signal chip
- Basic subcore (1)
- Advanced component (4)
- Plasteel (30)
#### Powerfocus chip
- Signal chip (2)
- Standard subcore (1)
- Advanced component (6)
- Plasteel (40)
#### Nano structuring chip
- Powerfocus chip (2)
- High subcore (1)
- Plasteel (50)
- Advanced component (8)
- Uranium (10)
#### Mechlink
- High subcore (2)
- Integrator headset (1)
- AI persona core (1)
- Advanced component (16)
### Skills needed to craft
- Signal chip: 9 crafting (can be crafted by fabricators)
- Powerfocus chip: 10 crafting (can be crafted by fabricators)
- Nano structuring chip: 10 crafting, 14 intellectual (must be crafted by a colonist)
- Mechlink: 10 crafting, 18 intellectual (must be crafted by a colonist)
### Work amount
- Signal chip: 8000
- Powerfocus chip: 10000
- Nano structuring chip: 12000
- Mechlink: 18000
## In-game values for AlphaMechs (RimWorld 1.6 / 1.7)
### Base research cost
Requires Multi analyzer.
- Hyper-linkage chip: 3000
- Stellar processing chip: 3000
- Quantum matrix chip: 3000
### Crafting costs
Requires Fabrication bench.
#### Hyper-linkage chip
- Nano structuring Chip (2)
- High subcore (1)
- Advanced component (8)
- Uranium (10)
#### Stellar processing chip
- Hyper-linkage chip (2)
- High subcore (2)
- Advanced component (8)
- Uranium (10)
#### Quantum matrix chip
- Stellar processing chip (2)
- High subcore (3)
- Advanced component (10)
- Uranium (10)
### Skills needed to craft (must be crafted by a colonist)
- Hyper-linkage chip: 10 crafting, 15 intellectual
- Stellar processing chip: 10 crafting, 16 intellectual
- Quantum matrix chip: 10 crafting, 18 intellectual
### Work amount
- Hyper-linkage chip: 14000
- Stellar processing chip: 16000
- Quantum matrix chip: 18000
## Patch notes
### CMC build 1.7
- Updated for Rimworld 1.7
- Updated README values to match existing recipes and research costs
### CMC build 1.6
- Updated for Rimworld 1.6
- Restructured folders and stuff
- Lowered Nano structuring chip crafting intellect requirement from 16 to 14
- Lowered costs again, the amount of raw plasteel needed was a bit too high when crafting from scratch. I still want this to be a part of the end game and not feel like you're cheating, but considering we're getting more things that will need plasteel in Odyssey I think lowering the costs a bit is fair. New raw plasteel costs:
  - Signal chip: 110 -> 70
  - Powerfocus chip: 135 -> 100
  - Nano structuring chip: 200 -> 130
- Cut research times a bit for each:
  - Signal chip: 3000 -> 2000
  - Powerfocus chip: 4000 -> 2500
  - Nano structuring chip: 5000 -> 3000
- Some small changes and tweaks for crafting the AlphaMechs chips:
  - Cut all research times by half (from 6000 to 3000 for each)
  - Lowered Hyper-linkage chip crafting crafting requirement from 12 to 10
  - Lowered Hyper-linkage chip crafting intellect requirement from 18 to 15
  - Lowered Stellar processing chip crafting intellect requirement from 18 to 16
  - Lowered Stellar processing chip crafting cost:
    - Advanced components: 12 -> 8
    - High subcore: 4 -> 2
  - Lowered Quantum matrix chip crafting crafting requirement from 12 to 10
  - Lowered Quantum matrix chip crafting intellect requirement from 20 to 18
    - Lowered Quantum matrix chip crafting cost:
      - Advanced components: 16 -> 10
      - High subcore: 6 -> 3
### CMC build 1.5
- Added description and title to the research tab
- Added steam page images
- Updated git readme
### CMC build 1.4
- Updated to support Rimworld version 1.5
- Fixed ResearchProjects defs renamed from "studied" to "analyzed"
- Removed MultiAnalyzer from requirements on signal chip crafting research
- Updated preview image
### CMC build 1.3
- Changed some costs for crafting the chips, so it needs less raw resources and are utilizing advanced components instead. The total costs are slightly cheaper for the first two chips, slightly more expensive for the third one - but the raw amount of plasteel needed are the same or less. 
- New raw plasteel costs:
  - Signal chip: 125 -> 110
  - Powerfocus chip: 150 -> 135
  - Nano structuring chip: no change
- New raw gold costs:
  - Signal chip: 0 -> 18
  - Powerfocus chip: 0 -> 18
  - Nano structuring chip: 0 -> 24
- Nano structuring chip crafting research time lowered slightly: 6000 -> 5000
- Signal chip crafting research time increased slightly: 2000 -> 3000
- Added a 'Mechtech crafting' tab in the research menu
- Initial support for the mod AlphaMechs (https://github.com/juanosarg/AlphaMechs/tree/main) I may need to tweak some numbers though.
- Added Mechlink crafting. It's not cheap though, it's pretty expensive as it's supposed to be an end-game thing.
### CMC build 1.2
- I find that by end-game my subcore crafting bench and scanners just sit there which is quite boring. So I removed steel and gold cost from crafting the chips and replaced it with subcores to utilize them more. So the chips need one subcore from the respective tier. The actual cost for the chips are about the same, but it requires less different stuff but more streamlined ingredients.
  - Signal chip: Basic subcore
  - Powerfocus chip: Standard subcore
  - Nano structuring chip: High subcore
- Increased workAmount even more
  - Signal chip: 5200 -> 8000
  - Powerfocus chip: 6000 -> 10000
  - Nano structuring chip: 6800 -> 12000
- Reduced plasteel costs considering the cost for subcores
  - Powerfocus chip: 200 -> 150
  - Nano structuring chip: 250 -> 200

Crafting a Nano structuring chip from scratch is now an even 1000 plasteel. But requires some additional work and resources with the addition of subcores.
### CMC build 1.1
  - Decreased overall cost of plasteel by 200 when crafting a Nano structuring chip from scratch
    - Signal chip plasteel cost 150 -> 125
    - Powerfocus chip plasteel cost 225 -> 200
    - Nano structuring chip plasteel cost 300 -> 250
  - Removed Intellectual requirement of crafting Signal chips and Powerfocus chips, so now your fabricators are able to craft them
  - Increased workAmount by a small amount for each chip
