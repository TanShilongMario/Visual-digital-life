---
name: digital-life-visual
description: Transform supplied photographs or scenes into a restrained “Digital Life / 数字人生” visual system that preserves the source reality while selectively revealing CAD/Rhino/SketchUp-style raw models, wireframe/X-ray geometry, semantic technical annotations, localized glitch seams, and sparse editorial typography. Use when users ask for 数字人生, Digital Life, AR与现实混合, 数字孪生视觉, 建模视图叠化, Rhino/SU素模过渡, virtual-real poster, computational reality, or a real photograph that should gradually transition from editable 3D model to rendered reality without becoming generic cyberpunk or game HUD.
---

# Digital Life Visual / 数字人生视觉转译

> Core principle: **Reality remains the subject. The digital layer reveals how reality could be measured, modeled, indexed, and edited.**
>
> Default spatial grammar: **RAW MODEL → EDGE / WIREFRAME → RENDER → REALITY**.

## Workflow

Track this sequence:

- [ ] 1. Confirm the source image or scene exists; if editing a supplied image, use it as the master reference.
- [ ] 2. Lock composition, camera, perspective, object placement, and recognizable scene anchors.
- [ ] 3. Read foreground / midground / background and select only a few objects for digital transformation.
- [ ] 4. Make the closest selected objects the most model-like; taper the effect with depth.
- [ ] 5. Add sparse semantic annotations only where they contribute information.
- [ ] 6. Add at most one large contextual typography intervention on a suitable architectural surface; omit it if no meaningful wording exists.
- [ ] 7. Place glitch only at reality/model seams, edges, or local transition zones.
- [ ] 8. Generate or edit the image.
- [ ] 9. Inspect against the quality gates; retry if the result becomes generic cyberpunk, game HUD, full wireframe, or typography-heavy.

## Interaction

- Prefer an input image. If none is supplied and the user explicitly asks for a new scene, create one using the same visual grammar.
- When an image is supplied and the user says “直接做”, “默认”, “你来判断”, or equivalent, execute without unnecessary questions.
- If the user asks for a prompt, Skill, direction, or plan only, do not generate the image.
- Ask at most one question, and only when a missing decision would materially change the result.
- Treat follow-up scope as a hard edit mask. Use the latest approved image as the master and preserve all unmentioned composition, objects, typography, model transitions, colors, and annotations.
- For image editing, use an image-edit tool that receives the actual source image. Do not reconstruct from prose when the source is available.

## Analyze the source internally

Identify without narrating every point unless asked:

- **Camera:** crop, lens feel, horizon, vanishing points, camera height, perspective convergence.
- **Scene anchors:** main architecture, road geometry, vehicles, people, furniture, products, vegetation, signage, or other masses required for recognition.
- **Depth:** nearest 10–25% of visual depth, middle transition zone, distant photographic zone.
- **Candidate digital objects:** objects whose geometry reads clearly and benefits from model conversion.
- **Semantic surfaces:** façades, billboards, glazing, screens, walls, vehicle panels, or other surfaces that can legitimately carry one large typographic intervention.
- **Existing text:** preserve meaningful source signage unless the requested treatment explicitly replaces it.

## Default visual system

Use these defaults unless the user specifies otherwise:

```yaml
source_lock: high
composition_lock: strict
perspective_lock: strict
photographic_reality_share: 60_to_75_percent
model_layer_share: 15_to_30_percent
graphic_layer_share: 5_to_15_percent
foreground_digitization: strong
midground_digitization: medium
background_digitization: light
foreground_model_style: rhino_sketchup_raw_viewport
foreground_material: pale_clay_or_untextured
foreground_outline: bold_model_edges
internal_wireframe_density: low_to_medium
xray: selective
transition: continuous_depth_fade
annotation_density: low
hero_typography_count: 0_to_1
road_hero_typography: off
generic_future_slogans: prohibited
glitch_coverage: 5_to_15_percent
palette: source_led_neutral
cyberpunk_neon: off
hud_style: restrained_industrial_information_design
```

Read `references/visual-system.md` for detailed layer behavior.

## Preserve reality first

- Keep the original composition, camera position, perspective, road/building geometry, and major object placement recognizable.
- Default target: **roughly 60–85% of the source remains visually legible as the original reality**.
- Do not redesign the city, room, product, vehicle, or scene merely to make it more futuristic.
- Do not add flying vehicles, hologram billboards, robots, speculative skyscrapers, or unrelated sci-fi props unless explicitly requested.
- Preserve source-led lighting and color. The digital layer should coexist with the photograph rather than recolor the entire image.

## Build the depth-based model transition

The digital effect must obey depth, not distribute evenly.

### Foreground

The closest selected object should read like a **Rhino / SketchUp / CAD viewport object**, not merely a transparent wireframe overlay.

Use:

- pale gray / off-white / source-tinted clay surfaces
- simplified or untextured materials
- smooth CAD-like surfaces or planar modeling logic
- **strong outer contour and feature-edge lines**
- sparse construction edges or section lines
- selective transparency or X-ray only where useful
- visible “editable model” character

Prefer the feeling of a model still open inside design software.

Avoid:

- dense all-over polygon cages
- photoreal PBR on the most digital foreground object
- neon hologram outlines
- mechanical exploded-view complexity unless the source calls for it

### Midground

Blend model and reality rather than switching abruptly.

A single object may progress through:

`clay surface → outlined render → sparse wireframe / x-ray → photographic material`

Possible devices:

- partial material restoration
- wireframe fading
- edge-line fade
- section/X-ray windows
- construction lines
- bounding frames
- anchor points

### Background

Keep the background mostly photographic. Allow only light computational traces such as:

- building edge recognition
- a few target circles
- sparse coordinates or object labels
- faint wireframe fragments
- localized glitch at boundaries

The hierarchy must remain readable at a glance: **model-heavy foreground, hybrid midground, real background**.

## Use semantic information graphics

The interface layer should feel closer to **industrial documentation, architectural annotation, transit information, Braun-like information design, scientific instruments, and engineering drawings** than to a videogame HUD.

Use sparingly:

- thin leader lines
- circles / target points
- crosshair markers
- dimensions
- object IDs
- route or direction data
- building height / floor count when contextually useful
- distance / speed / coordinate snippets
- small boxed labels
- restrained monospaced / DIN-like / printer typography

Read `references/annotation-language.md` before building dense annotations.

## Semantic text rule

Every visible word should earn its place.

Do **not** add generic words merely to announce the aesthetic. Avoid large or repetitive use of:

- SCAN / SCANNING
- VIRTUAL / REALITY
- FUTURE
- DIGITAL
- AI
- XR / AR
- METAVERSE
- SYSTEM ONLINE
- ANALYZING

The picture already communicates those concepts.

Prefer scene-specific content such as:

- actual place / district / building / route names when known
- existing source signage
- contextual object IDs
- dimensions or distances
- directional or transit information
- concise designed metadata

If the necessary information is unknown, either use clearly synthetic technical identifiers quietly or omit the text. **Never fill empty space with fake techno-copy.**

## Large typography rule

Large type is an **editorial poster layer**, not the UI layer.

- Default: **0–1 major typography intervention per image**.
- Prefer an architectural carrier: façade, billboard, wall, glazing, large transport surface, screen, or other believable planar surface.
- Match the exact perspective and surface orientation.
- Prefer meaningful place names, building names, route names, dates, or project-specific terms.
- **Do not place major typography on the road by default.**
- If no meaningful large text exists, use none.
- Do not repeat the same concept in both large typography and small UI labels.

## Glitch as a seam, not a filter

Glitch represents disagreement between physical and computational reality.

Use only where layers intersect:

- object silhouette transitions
- building edges
- model-to-photo seams
- people or vehicles in motion
- image borders
- local occlusion boundaries

Allowed devices:

- RGB separation
- short horizontal tearing
- local frame displacement
- scanline break
- pixel fragmentation
- compression-like block interruption

Keep glitch sparse, directional, and localized. Do not coat the full image in VHS noise or chromatic aberration.

## Keep three layers unequal

Aim approximately for:

- **Photography:** 60–70%
- **Model:** 20–30%
- **Graphic / text / glitch:** 10–15%

These are visual weights, not literal pixel masks. The image should first read as a photograph, then reveal the model layer, then reward inspection with information graphics.

## Avoid generic cyberpunk

The following are failure modes unless explicitly requested:

- purple/cyan neon grading across the whole image
- rain-soaked Blade-Runner-like atmosphere added to an unrelated source
- full-screen HUD frames
- dense telemetry everywhere
- holographic floating panels
- sci-fi props not present in the source
- full-scene wireframe conversion
- glowing edge outlines on every object
- meaningless coordinate/data wallpaper
- repeated “future / virtual / scan” slogans

Target instead:

**contemporary photography × CAD/model viewport × industrial information design × editorial poster × localized digital failure**.

## Build prompts in this order

When preparing an image-edit prompt, follow this sequence:

1. **Source lock** — specify what must remain unchanged.
2. **Depth map** — name foreground / midground / background behavior.
3. **Foreground model language** — Rhino/SU clay + bold modeling edges.
4. **Transition behavior** — model → render → reality.
5. **Semantic annotation layer** — sparse and useful.
6. **Hero typography** — 0–1, contextual, surface-bound.
7. **Localized glitch** — only at seams.
8. **Negative constraints** — no road slogans, no generic techno-copy, no game HUD, no cyberpunk takeover.

Use `references/prompt-blueprint.md` for reusable prompt structures.

## Quality gates

Do not accept the result until all relevant gates pass:

- **SOURCE:** Is the original scene still immediately recognizable?
- **PERSPECTIVE:** Do all model geometry, annotations, and typography obey the source camera?
- **DEPTH:** Is digitization strongest near camera and progressively weaker with distance?
- **MODEL:** Does the closest object feel like Rhino / SketchUp / CAD clay modeling, with strong model edges rather than only a thin wireframe skin?
- **TRANSITION:** Does the model gradually become rendered reality instead of cutting abruptly?
- **TEXT:** Is there at most one major type zone, no unnecessary road typography, and no generic futuristic slogans?
- **ANNOTATION:** Are small labels sparse, contextual, and visually subordinate?
- **GLITCH:** Is glitch a local seam rather than an all-over filter?
- **POSTER:** Is there a clear hierarchy instead of equal-strength overlays everywhere?
- **ANTI-CYBERPUNK:** Would the image still make sense without neon sci-fi clichés?

If any gate fails, use `references/quality-and-recovery.md` and retry the smallest necessary scope.

## Output behavior

- If the user asked for an image, return the edited/generated image with minimal extra prose.
- If the user asked for a prompt or Skill application recipe, return the prompt rather than generating.
- If the user asks to refine one dimension, modify only that dimension and preserve the rest of the latest approved image.
