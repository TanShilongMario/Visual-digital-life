# First-Person UI Reference

## Goal

Create the feeling that the viewer is inside an augmented first-person system.

The reference point is high-end cinematic sci-fi game interface design: clear mission hierarchy, spatial navigation, object understanding, status feedback, and layered depth. The system may evoke the general experience of titles such as Death Stranding or Cyberpunk 2077, but must remain visually original.

Do not copy exact layouts, logos, proprietary icons, branded typefaces, or recognizable HUD assets.

## Recommended module set

Choose 2–4 modules, not all of them.

### 1. Objective panel

Place in an upper corner.

Structure:

ACTIVE TASKS / OBJECTIVES
- active task
- secondary task
- optional third task

Rules:

- derived from visible content
- text large enough to read
- one active state
- 2–4 tasks maximum
- no dramatic lore unless user asks

### 2. Minimap / local map

Place in a separate corner.

Use:

- simplified floor / street / route geometry
- viewer marker
- active target
- one or two contextual points

Do not imply survey accuracy unless source data supports it.

### 3. Object dossier

Use for the focal object.

Content can include:

- object name
- ID
- category
- material
- volume / dimensions
- location
- confidence

Keep it compact.

### 4. Status module

Examples:

- connection
- focus
- route progress
- scan / sync progress tied to a specific task
- battery / local time if relevant

Use one module only unless the composition has ample negative space.

### 5. Reticle / scan bracket

Use around the main object or active target.

Prefer:

- simple corner brackets
- one central reticle
- controlled ring / crosshair

Avoid weapon-like targeting language unless the scene calls for it.

## Layout logic

The interface should preserve a readable center.

- Keep the focal object mostly free of large panels.
- Put panels in corners or negative-space zones.
- Let primary leaders cross into the image only when they terminate clearly.
- Use one dominant corner, one secondary corner, then stop.

## Readability

Mission titles and primary object labels should be visibly larger than metadata.

Do not rely on tiny glyphs for atmosphere.

Large, clear UI creates more virtual presence than dozens of unreadable lines.

## Color

Use source-led colors plus one or two accents.

Good:

- white / off-white structure
- cool cyan / mint / pale blue for passive UI
- warm yellow / orange / red for active task or warning
- subtle black translucent backing when necessary

Avoid full-frame neon grading.

## Motion feeling in a still image

Suggest time and update cycles through:

- short motion trails
- shifted duplicates
- partial RGB split
- scanline interruptions
- progress segments
- pulsing-looking node halos
- directional ghost images

Keep these local.

## AR attachment

Virtual elements should feel spatially located.

Use:

- perspective matching
- soft projected shadow
- slight depth offset
- parallax-like duplication
- local occlusion
- luminous edge separation
- contact point markers

This is especially important for hero typography.

## Failure modes

Too weak:
- tiny annotations only
- no objective hierarchy
- no clear spatial module
- no bold focal UI

Too strong:
- every edge framed
- multiple minimaps
- full border chrome
- dozens of panels
- exact imitation of a known game HUD

Target the middle: confident, readable, spatial, and selective.
