---
name: digital-life-visual
description: Transform supplied photographs or scenes into the “Digital Life / 数字人生” visual system: preserve the source reality while selectively revealing Rhino/SketchUp/CAD-style raw models, wireframe/X-ray geometry, contextual AR information, first-person mission UI, schematic minimaps, perspective-bound hero typography, and localized glitch seams. Use for 数字人生, Digital Life, digital twin visuals, AR/现实混合, first-person futuristic UI, computational reality, virtual-real poster design, or real photographs that should feel measurable, editable, game-like, and spatial without becoming generic cyberpunk.
---

# Digital Life Visual / 数字人生视觉转译

Core principle: Reality remains the subject. The digital layer reveals how reality can be measured, modeled, indexed, navigated, and edited.

Primary spatial grammar:

RAW MODEL → EDGE / WIREFRAME → RENDER → REALITY

Primary interface grammar:

SCENE → OBJECT / SPACE UNDERSTANDING → CONTEXTUAL TASKS → SPATIAL UI

The result may range from restrained editorial information design to immersive first-person game-like AR. Choose the intensity from the image and user request instead of forcing one fixed HUD template.

## Workflow

- [ ] 1. Use the supplied image as the master reference and lock composition, camera, perspective, lighting, and major object placement.
- [ ] 2. Read foreground / midground / background and select a small number of objects for digital transformation.
- [ ] 3. Make the nearest selected objects the most model-like; taper the effect toward photographic reality with depth.
- [ ] 4. Choose an interface mode: restrained editorial, immersive first-person HUD, or adaptive hybrid.
- [ ] 5. Replace generic branding with scene-specific objectives, object data, route information, or spatial status.
- [ ] 6. Add a schematic minimap only when the scene benefits from spatial navigation.
- [ ] 7. Add one strong perspective-bound hero type zone when a meaningful phrase or object name exists.
- [ ] 8. Use a clear line-weight hierarchy: a few thicker primary leaders, fewer fine secondary guides.
- [ ] 9. Add glitch, shadow, and motion ghosting mainly where virtual elements attach to physical surfaces or where model and photo disagree.
- [ ] 10. Inspect against the quality gates and patch only the failing layer.

## Interaction

- Prefer an input image. If none is supplied and the user explicitly asks for a new scene, create one using the same visual grammar.
- When the user says “直接做”, “默认”, “你来判断”, or equivalent, execute without unnecessary questions.
- If the user asks for a prompt, Skill, direction, or plan only, do not generate the image.
- Ask at most one question, only when a missing decision would materially change the result.
- Treat follow-up scope as a hard edit mask. Use the latest approved image as the master and preserve all unmentioned composition, objects, typography, model transitions, colors, and UI.
- For image editing, use the actual source image. Do not reconstruct from prose when the source is available.

## Analyze the source internally

Identify:

- Camera: crop, horizon, vanishing points, camera height, lens feel, perspective convergence.
- Scene anchors: major architecture, furniture, vehicles, people, products, signage, vegetation, road/table/floor planes.
- Depth: nearest model-heavy zone, middle hybrid zone, distant real zone.
- Candidate digital objects: clear geometry that benefits from raw model conversion.
- Spatial carriers: façades, tabletops, walls, floors, signs, screens, vehicle panels, product surfaces.
- Objective candidates: what a first-person system could plausibly ask the viewer to inspect, reach, identify, compare, or interact with.
- Map candidates: whether the scene contains enough spatial logic for a schematic minimap.

## Default visual system

Use these defaults unless the user specifies otherwise:

source_lock: high
composition_lock: strict
perspective_lock: strict
photographic_reality_share: 50_to_70_percent
model_layer_share: 15_to_30_percent
ui_graphic_share: 15_to_25_percent
foreground_digitization: strong
midground_digitization: medium
background_digitization: light
foreground_model_style: rhino_sketchup_raw_viewport
foreground_material: pale_clay_or_untextured
foreground_outline: bold_model_edges
internal_wireframe_density: low_to_medium
xray: selective
transition: continuous_depth_fade
interface_mode: adaptive_hybrid
primary_leader_weight: medium_to_bold
secondary_guide_weight: fine
annotation_density: low_to_medium
mission_panel: contextual_optional
minimap: contextual_optional
hero_typography_count: 0_to_1
hero_typography_surface: scene_bound
hero_typography_ar_depth: subtle
glitch_coverage: 5_to_15_percent
palette: source_led_with_limited_ui_accents
exact_game_ui_copy: prohibited

Read references/visual-system.md and references/first-person-ui.md for detailed behavior.

## Preserve reality first

- Keep the original composition, camera position, perspective, scene geometry, lighting, and major object placement recognizable.
- Default target: roughly 55–80% of the source should remain legible as the original reality.
- Do not redesign the city, room, café, product, vehicle, or landscape merely to make it futuristic.
- The digital layer may be visually strong, but it should feel attached to the source rather than replacing it.

## Build the depth-based model transition

### Foreground

The closest selected object should read like a Rhino / SketchUp / CAD viewport object, not merely a transparent wireframe skin.

Use:

- pale gray / off-white / source-tinted clay surfaces
- simplified or untextured materials
- smooth CAD-like or planar modeled surfaces
- strong silhouette, crease, naked-edge, or feature-edge display
- sparse construction lines
- selective X-ray or transparent volume
- retained AO/contact shadow so the model still sits in the physical scene

The near object can be strongly virtual. It should feel editable.

### Midground

Blend model and reality continuously:

clay surface → outlined render → sparse wireframe / X-ray → restored material → photographic detail

Useful devices:

- partial material restoration
- edge-line fade
- section / X-ray windows
- registration points
- bounding corners
- light grid overlays
- local glitch seams

### Background

Keep the background mostly photographic. Use only light computational traces:

- recognition outlines
- sparse target circles
- faint wireframe fragments
- route markers
- restrained UI anchors
- small localized glitches

## Choose an interface mode

### Mode A: Editorial / Instrument

Use when the user wants quieter design, product visualization, architecture, or poster restraint.

Characteristics:

- few object labels
- small information panels
- minimal border chrome
- no permanent HUD frame
- no minimap unless spatially useful
- hero typography may be the strongest graphic element

### Mode B: First-person / Immersive

Use when the user wants a stronger digital, virtual, game-like, or AR-goggles feeling.

Use high-level interface qualities associated with premium first-person sci-fi games such as Death Stranding or Cyberpunk 2077: mission hierarchy, navigation, reticles, status modules, spatial overlays, and readable modular UI. Translate those qualities into an original system. Never copy exact branded layouts, logos, icons, or proprietary interface assets.

Characteristics:

- one contextual task / objective panel in an upper corner
- one schematic minimap or spatial radar in another corner when useful
- one or two status modules
- larger, readable interface type
- stronger scan brackets or reticles around the focal object
- a few bold primary leader lines
- controlled neon or luminous accents drawn from the source
- no decorative microtext wallpaper

### Mode C: Adaptive Hybrid

Default when the user does not specify intensity.

Combine the model-depth grammar with one or two immersive elements, usually:

- contextual task list
- optional minimap
- one hero type zone
- a few technical callouts

Do not use every module simultaneously.

## Contextual task panel instead of branding

Do not place “数字人生 / DIGITAL LIFE” as a default title in the top-left or top-right corner.

Prefer a scene-specific objective panel whose wording is generated from the actual image.

Examples of structure:

ACTIVE TASKS
- Inspect / identify / compare / locate a specific scene object
- Analyze a specific table, building, route, product, person, or area
- Reach or mark a visible destination
- Sync or confirm one context-specific state

Rules:

- task titles should be larger than micro annotations and legible at final output size
- 2–4 tasks are usually enough
- one task may be highlighted as active
- verbs such as SCAN or IDENTIFY are allowed only when attached to a specific real object or mission, not as generic decoration
- do not invent dramatic story stakes unless the source or user suggests them

## Virtual minimap

Add a minimap only when it improves the first-person spatial reading.

Good uses:

- café / room: current table, counter, exit, seat, target object
- street: current block, route, intersection, transit stop
- building: floor, room, elevator, destination
- landscape: trail, waypoint, terrain contour

Rules:

- use a schematic scene-derived map when exact geography is unknown
- label it as a local map / floor map / area map rather than pretending to be surveyed truth
- show only a few markers
- place it in a corner and keep the focal subject unobstructed
- use one clear player / viewer marker and one active target when helpful

## Information and line hierarchy

The interface should be readable before it is intricate.

Use three line weights:

1. Primary leaders: medium-to-bold, used for 3–6 important object callouts.
2. Secondary leaders / brackets: regular weight, used sparingly.
3. Micro grids / construction guides: fine and low contrast.

Avoid a field of equally thin lines.

Primary leader lines should feel deliberate, with clear circular nodes or joints. Reduce overlapping callouts and give labels breathing room.

Typography hierarchy:

- task / panel title: large and immediately readable
- primary object label: medium
- metadata: smaller but still legible
- micro coordinates / IDs: optional

## Semantic text rule

Every visible word should earn its place.

Avoid generic slogans merely announcing the aesthetic:

FUTURE, METAVERSE, DIGITAL CITY, SYSTEM ONLINE, AI WORLD, VIRTUAL FUTURE.

Contextual verbs such as SCAN, ANALYZE, IDENTIFY, TRACK, ROUTE, or SYNC are acceptable inside a specific task or object panel when they describe an action tied to the image.

Prefer:

- actual place / object / route / building / dish / product names
- table / seat / room / floor identifiers
- dimensions, materials, volumes, temperatures
- directions, distances, route data
- concise mission language tied to visible content

## Hero typography

Hero type is a poster layer plus an AR layer.

- Default: 0–1 major typography zone.
- It may sit on any believable perspective carrier: façade, billboard, wall, glazing, tabletop, floor, product plane, screen, transport surface, or other scene-bound surface.
- Match the exact perspective and local surface orientation.
- Prefer scene-specific names, object names, district names, route names, event names, table/room identifiers, or concise meaningful phrases.
- Avoid generic words that merely repeat “future / virtual / digital”.
- Road text is not automatically banned, but it should be omitted when it has no contextual reason.

To create AR attachment / hovering depth:

- offset the type slightly above the carrier plane
- add a soft contact or projection shadow
- add restrained luminous edge separation
- use localized RGB split or scan displacement
- add a short directional motion ghost / temporal trail
- allow slight occlusion by real objects when perspective demands it

The type should feel anchored and hovering at the same time.

## Glitch as a seam

Glitch represents disagreement between physical and computational layers.

Good locations:

- model-to-photo transitions
- hero typography edges
- object silhouettes
- occlusion boundaries
- UI attachment points
- image borders

Allowed devices:

- RGB separation
- short horizontal tearing
- local frame displacement
- scanline break
- pixel fragmentation
- temporal ghosting
- brief motion-trail duplication

Keep glitch directional and local. Do not coat the full image with noise.

## UI palette

Stay source-led.

Good default:

- white / off-white / graphite for structure
- one cool luminous accent
- optionally one warm active-state accent
- source-derived highlight colors

Game-like does not mean neon everywhere. Keep accents sparse enough that the photograph still matters.

## Avoid exact game imitation

Do not reproduce exact HUD layouts, logos, iconography, proprietary fonts, or branded visual assets from specific games.

Use only high-level qualities:

- readable mission hierarchy
- modular status panels
- spatial navigation
- reticles / brackets
- layered depth
- animated-feeling AR projection
- clean first-person information architecture

## Build prompts in this order

1. Source lock.
2. Depth map.
3. Foreground model language.
4. Model-to-reality transition.
5. Interface mode.
6. Task / objective panel.
7. Optional minimap.
8. Object annotations with line-weight hierarchy.
9. Hero typography with AR depth.
10. Local glitch and motion ghosting.
11. Negative constraints against clutter and exact game-copy.

Use references/prompt-blueprint.md for reusable structures.

## Quality gates

- SOURCE: Is the original scene immediately recognizable?
- PERSPECTIVE: Do model geometry, typography, minimap logic, and callouts respect the scene?
- DEPTH: Is digitization strongest near camera and progressively weaker with distance?
- MODEL: Does the near object feel like editable Rhino / SketchUp / CAD rather than a thin mesh cage?
- UI MODE: Does the chosen interface intensity match the user request?
- TASKS: Are the mission items specific to the visible scene, readable, and limited in number?
- MAP: If a minimap exists, is it schematic, useful, and unobtrusive?
- LINES: Are important leaders thicker and clearer than micro guides?
- TEXT: Is hero type meaningful, perspective-bound, and free of generic future slogans?
- AR DEPTH: Does large type or UI feel attached to space through shadow, glow, ghosting, and occlusion rather than simply pasted on?
- GLITCH: Is glitch local and functional?
- CLUTTER: Can the eye still find the focal object quickly?
- ORIGINALITY: Does the interface feel game-like without copying a specific game UI?

If a gate fails, use references/quality-and-recovery.md and retry only the failing layer.

## Output behavior

- If the user asked for an image, return the edited/generated image with minimal extra prose.
- If the user asked for a prompt or Skill application recipe, return the prompt rather than generating.
- If the user asks to refine one dimension, modify only that dimension and preserve the rest of the latest approved image.
