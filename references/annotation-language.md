# Annotation Language

## Purpose

Annotations should make the scene feel computationally understood without becoming unreadable UI confetti.

The system now supports both restrained industrial annotation and stronger first-person mission UI.

## Hierarchy

Use four text levels:

1. Mission / panel title
2. Primary object label
3. Metadata
4. Micro data

Only level 1 should be large. Level 4 is optional.

## Line-weight hierarchy

Do not use one thin weight everywhere.

### Primary leaders

Use for 3–6 important targets.

- medium-to-bold weight
- simple angular routing
- clear circle / node at target
- short enough to read instantly
- enough spacing from nearby text

### Secondary leaders

Use for less important objects.

- regular weight
- fewer nodes
- no decorative complexity

### Micro guides

Use for grids, rulers, construction lines, or perspective helpers.

- fine weight
- lower contrast
- never compete with the focal object

## Preferred information

Use when contextually relevant:

- object identifier
- dimension
- distance
- direction
- speed
- route
- floor or level
- coordinate snippet
- material / component / part code
- volume / temperature / state
- table / room / seat / zone ID
- confidence or progress when it represents a scene-specific operation

## Mission language

Contextual action verbs are allowed when tied to a specific scene target.

Good:

SCAN HK MILK TEA
IDENTIFY ICE / STRAW / GLASS
INSPECT VEHICLE 07
ROUTE TO EXIT B
COMPARE MATERIAL A / B
LOCATE TABLE A3

Weak:

SCANNING...
SYSTEM ONLINE
ANALYZING REALITY
ENTER THE FUTURE

Use 2–4 tasks. Highlight at most one active task.

## Typography

Prefer:

- monospaced, DIN-like, grotesk, or technical sans
- larger panel titles than previous versions
- readable body text
- short lines
- strong alignment
- generous negative space

Avoid microtext soup.

If text cannot be read at the expected output size, remove it or enlarge it.

## UI panels

A strong immersive composition may contain:

- one mission panel
- one minimap
- one object data panel
- one status module

Do not automatically use all four.

## Minimap labels

Keep simple:

- YOU
- TARGET
- EXIT
- TABLE / ROOM / STOP / PLATFORM
- COUNTER / ELEVATOR / VEHICLE / WAYPOINT

Use schematic geometry when exact geography is unknown.

## Hero typography

Hero type is not ordinary annotation.

Good content:

- actual place / district / station / building / product / dish name
- project name supplied by user
- one meaningful route or room identifier
- concise context-specific phrase

Weak content:

- DIGITAL CITY
- FUTURE LIFE
- VIRTUAL WORLD
- SYSTEM ONLINE

Hero type may use stronger glitch, shadow, projection, or ghosting than ordinary labels.

## Truth vs designed metadata

When exact factual values are known, use them.

When they are unknown:

- use clearly designed IDs
- use approximate neutral metadata only when harmless
- keep uncertain numbers visually subordinate
- use schematic spatial panels instead of fake precise maps
- do not present invented values as factual claims in accompanying prose
