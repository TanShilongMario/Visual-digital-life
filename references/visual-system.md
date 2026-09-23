# Visual System Reference

## 1. Concept

Digital Life is not a science-fiction skin. It treats ordinary reality as something partially exposed to computation: measurable, editable, modeled, indexed, and occasionally unstable.

The visual tension comes from **different ontological states occupying one photograph**:

1. photographic reality
2. editable 3D model
3. technical representation
4. information layer
5. digital failure / glitch

Do not make every object pass through every state.

## 2. Depth grammar

### Near field: editable model

Best candidates:

- cars / bicycles / furniture / products
- rails, barriers, street hardware
- architectural fragments close to camera
- foreground props with clear geometry

Treatment:

- pale clay or source-tinted neutral surface
- bold silhouette and crease edges
- sparse internal modeling lines
- smooth Rhino/NURBS or simple SketchUp planar character
- AO/contact shadow retained enough to anchor it in the scene
- optional light transparency revealing simple internal volumes

A foreground model should still occupy the physical scene. It must cast/receive plausible light and respect occlusion.

### Middle field: hybrid rendering

Mix states inside one object or across adjacent objects. Useful methods:

- 30–60% material restoration
- wireframe only on one panel or side
- partial X-ray window
- fading edge display
- visible registration points / bounding corners
- subtle rendered-to-photo gradient

### Far field: recognition traces

Use almost no clay conversion. Prefer:

- edge detection on one building
- one or two technical labels
- thin perspective guides
- subtle geometry ghosting

## 3. Modeling aesthetics

### Rhino-like

- smooth NURBS surfaces
- continuous pale body
- strong naked/feature edges
- clean technical geometry
- no dense triangulation
- object feels designed, not simulated

### SketchUp-like

- slightly more planar surfaces
- explicit silhouette edges
- readable crease/feature lines
- minimal material complexity
- architectural massing feel

### CAD/X-ray accent

Use as a secondary state, not the main foreground look:

- thin white/gray construction lines
- transparent structural regions
- section lines
- sparse control geometry

## 4. Graphic hierarchy

Three scales of graphic language:

### A. Hero typography

0–1 zone. Large. Site-specific. Surface-bound. Poster-like.

### B. Object annotation

A few medium labels tied to selected objects.

### C. Micro data

Tiny coordinates / IDs / dimensions. Optional texture, never the main event.

If A exists, reduce B and C.

## 5. Color

Default to source colors. Digital layers should be mostly:

- off-white
- graphite
- cool gray
- transparent pale gray
- occasional source-derived accent

Small warm/red/cyan registration artifacts are allowed for glitch but should not become a cyberpunk palette.

## 6. Human subjects

When people are present:

- preserve identity-relevant visible characteristics and broad action
- avoid turning all people into anonymous holograms
- digitize only one local part if helpful: clothing outline, silhouette registration, accessory, bounding marker, skeletal pose hint, or partial clay treatment
- keep faces readable unless the requested concept specifically obscures them

## 7. Products / interiors / nature

The same grammar works outside cities.

### Product
Foreground product can be split into clay CAD + rendered material + real photographed portion. Use dimensions and part labels rather than city telemetry.

### Interior
Furniture near camera can become SketchUp/Rhino models; room architecture remains photographed. Hero type may sit on a wall only if meaningful.

### Nature
Digitize selected rocks, trunks, terrain contours, or man-made objects. Avoid converting organic nature into a generic polygon world. Use contour, survey, point/mesh, or measurement logic sparingly.
