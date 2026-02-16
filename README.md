# Pupique's Power Rebalance Patch

## Purpose

Even though this patch's name refers to a general rebalance for power generation, for now it's contained to patching fuel consumption for both Wood and Chemfuel generators. The name was left in its current generic form on purpose since it may be expanded to overhaul other power sources in the future as well.

> [!NOTE]
> This patch also applies to Vanilla Furniture Expanded - Power but it is not required as a dependency.

> [!NOTE]
> Since it merely adjusts a few variables, it is relatively safe to add and remove this mod mid-game.

## Patches

### Fuel Consumption

I was genuinely appalled by the Vanilla fuel consumption for both Wood- and Chemfuel-powered generators. I don't usually have them in my bases since I generally avoid having non-renewable power sources but the consumption for them is so low that they are infinitely better than their non-renewable counterparts with are usually more expensive to build, occupy more space and are more inconsistent overall.

Therefore, this patch aims to rectify that by adding more impact to these generators' power consumption. The power output was left as it is.

#### Chemfuel

The chemfuel consumption rate was the most surprising one of them all: merely 4.5 units per day for every type of generator, from portable to industrial. Even though industrial-grade generators indeed should be more efficient when producing energy, it shouldn't be so much so that they consume the same amount of resources than their smaller counterparts while producing much more energy.

In overall, Chemfuel generators consume much more power than before. Naturally, your settlement's chemfuel generation should be much higher now in order to sustain them, meaning it'd be adequate to get a mod that allows you to extract it on an industrial scale if your base solely relies on it to generate power, but biofuel alternatives still are valid since they produce a reasonable amount of chemfuel whilst not consuming that much raw resources.

| Generator | Output | Old Daily Consumption | New Daily Consumption | Old W/fuel | New W/fuel | Old Fuel Capacity | New Fuel Capacity |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VFEP - Portable Chemfuel | 500W | 4.5 | 10 | 111.11W | 50.00W | 30 | 30 |
| Chemfuel Generator | 1000W | 4.5 | 18 | 222.22W | 55.56W | 30 | 100 |
| VFEP - Industrial Chemfuel | 2400W | 4.5 | 36 | 533.33W | 66.67W | 60 | 400 |

#### Wood

Wood-powered generators have the same issue as the chemfuel ones: all three tiers consume the same amount of it, and likewise consume too little albeit not in the same intensity as the chemfuel generators. Wood generators indeed should be less efficient than their chemfuel counterparts since chemfuel isn't usually readily available in nature and the wood-to-chemfuel biofuel recipe consumes 2 wood for every 1 chemfuel produced.

At the same time, it should be more interesting to use wood-powered generators than the basic fueled stove for instance in order to reward the technological advances, adding more relevance to electricity even if no better power source than wood is available. Therefore, even though wood consumption is in general higher, it shouldn't be so much so to make it completely useless, being a valid fallback option in the case of an emergency.

| Generator | Output | Old Daily Consumption | New Daily Consumption | Old W/fuel | New W/fuel | Old Fuel Capacity | New Fuel Capacity |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VFEP - Portable Wood | 500W | 22 | 35 | 22.73W | 14.29W | 75 | 75 |
| Wood Generator | 1000W | 22 | 60 | 45.45W | 16.67W | 75 | 150 |
| VFEP - Industrial Wood | 2400W | 22 | 120 | 109.09W | 20.00W | 150 | 350 |

## Disclaimers

Since this mod considerably inceases the consumption of generators and you do agree with this hike in consumption, auxiliary mods for fuel extraction are recommended. This mod was made based on my own observations with the mod list that I have so it may not be adequate for a vanilla experience.

### Credits

Credits go to the Vanilla Expanded team for creating the original generators that are patched by this mod.

#### Referenced Repositories
Vanilla Furniture Expanded - Power: https://github.com/Vanilla-Expanded/VanillaFurnitureExpanded-Power

### License
This mod falls under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
