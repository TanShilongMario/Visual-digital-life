# Quality and Recovery

## Gate 1: Source drift

Failure:
The scene is newly invented or the original camera/composition is lost.

Recovery:
Increase source/composition/perspective lock. Remove new architecture and props. Reassert original object positions and occlusion.

## Gate 2: Foreground is only wireframe

Failure:
The near object looks like a transparent mesh cage rather than a Rhino/SU model.

Recovery:
Replace dense wireframe with pale solid clay surfaces, stronger outer/crease edges, fewer internal lines, and clearer massing.

## Gate 3: Model looks too photorealistic

Failure:
Foreground no longer reads as editable CAD.

Recovery:
Flatten materials, reduce PBR/reflection, simplify shading, increase neutral clay surface, strengthen model-edge display, expose a few construction features.

## Gate 4: Hard cut between model and photo

Failure:
Model and photo meet at a straight seam.

Recovery:
Use multiple intermediate states:
clay → edge render → sparse wireframe/X-ray → restored material → photo.

## Gate 5: Digital layer feels too weak

Failure:
The image looks like a normal photo with tiny annotations.

Recovery:
Add one stronger first-person module:
- mission panel
- minimap
- reticle / scan bracket
- stronger hero typography
- more obvious foreground model state

Do not add all of them at once.

## Gate 6: HUD is too cluttered

Failure:
Many tiny panels, micro lines, and labels compete equally.

Recovery:
Remove 30–60% of UI.
Keep one dominant corner, one secondary corner, and 3–6 important callouts.
Enlarge important text.
Use thicker primary leaders and finer secondary guides.

## Gate 7: Mission list is generic

Failure:
Tasks say things like SYSTEM ONLINE, ENTER FUTURE, ANALYZE WORLD.

Recovery:
Rewrite tasks from visible scene content:
specific object, place, table, route, product, building, person, or waypoint.

## Gate 8: Minimap invents geography

Failure:
The map looks precise even though the source does not provide exact layout.

Recovery:
Make it schematic and local.
Show only viewer, target, and a few nearby scene elements.
Label it as a local / floor / area map.

## Gate 9: Hero typography feels printed

Failure:
Large text is perspective-aligned but flat, like ordinary graphic design pasted onto the image.

Recovery:
Add slight surface offset, contact/projected shadow, local luminous edge, subtle RGB split, and short directional motion ghosting. Allow local occlusion.

## Gate 10: Hero typography is meaningless

Failure:
Large FUTURE, VIRTUAL, DIGITAL CITY, or other generic techno-copy appears.

Recovery:
Replace with a scene-specific object, place, route, dish, product, table, room, event, or project name. If no meaningful wording exists, remove hero type.

## Gate 11: Lines are too thin and messy

Failure:
Everything uses the same hairline weight and overlaps.

Recovery:
Promote 3–6 important leaders to medium/bold.
Reduce micro-grid contrast.
Shorten connector routes.
Increase label spacing.
Delete decorative lines.

## Gate 12: Glitch becomes a filter

Failure:
RGB split/noise covers the whole image.

Recovery:
Restrict glitch to model/photo seams, hero type, UI attachment points, silhouettes, and borders.

## Gate 13: Exact game imitation

Failure:
The result reproduces a recognizable game HUD layout, logo, or icon system.

Recovery:
Keep the high-level first-person information architecture but redesign layout, shapes, typography, icons, colors, and module distribution.

## Gate 14: Flat hierarchy

Failure:
Every object is equally digitized and annotated.

Recovery:
Choose one foreground hero model, one or two hybrid secondary objects, one dominant UI area, and one optional hero type zone.

## Final acceptance test

A successful Digital Life image should answer yes to most of these:

1. Is the source photograph still immediately recognizable?
2. Does the nearest digital object feel editable rather than merely holographic?
3. Is there a clear model-to-reality depth progression?
4. If immersive mode is active, are the mission items contextual and readable?
5. If a minimap exists, is it useful and clearly schematic?
6. Are key leader lines stronger than secondary guides?
7. Does large typography have a contextual reason to exist?
8. Does hero type feel attached to space through shadow / glow / glitch / ghosting?
9. Can the viewer find the focal object quickly?
10. Does glitch mark transitions instead of decorating everything?
11. Does the UI feel premium and game-like without copying a specific game?
12. Does the image still read as reality first, system second?
