# Annotation Language

## Purpose

Annotations should suggest that the scene is being understood by a computational system, while still behaving like serious information design.

## Preferred information types

Use only when contextually relevant:

- object identifier: `VEH_012`, `BLDG_027`, `OBJ_A14`
- dimension: `L 4.72 M`, `H 68.0 M`
- distance: `DIST 4.2 M`
- direction: `DIR NNE`
- speed: `8 KM/H`
- route: `ROUTE 6`, `WESTBOUND`
- floor or level: `FLOORS 18`, `LEVEL 04`
- coordinate snippet when geography matters
- material / component / part code for products
- camera or spatial reference values when composition benefits

## Typography

Prefer:

- monospaced or DIN-like families
- small caps or uppercase
- short lines
- strong alignment
- generous negative space
- 1–4 data lines per callout

## Linework

- 1-pixel-like thin leaders
- simple circles at target points
- small crosshairs
- restrained rectangles
- avoid ornate sci-fi brackets
- avoid glowing UI borders

## Truth vs designed metadata

When exact factual values are known from the user/source, use them.

When exact values are not known but a label is visually useful:

- use clearly designed object IDs or approximate neutral metadata
- keep it small
- do not present invented values as real-world claims in accompanying prose
- omit instead of fabricating if the number itself would carry factual importance

## Banned filler

Do not use the following merely as decoration:

`SCANNING`, `ANALYZING`, `REALITY`, `VIRTUAL`, `FUTURE`, `AI`, `XR`, `METAVERSE`, `SYSTEM ONLINE`, `TARGET LOCKED`.

## Hero typography

Good:

- actual district / station / building / project name
- event title supplied by user
- one meaningful code or date central to the project

Weak:

- DIGITAL CITY
- FUTURE LIFE
- REAL / VIRTUAL
- SCAN TRAFFIC

If only weak options exist, omit hero type.
